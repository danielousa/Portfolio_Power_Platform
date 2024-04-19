# Portfolio_Power_Automate

 Analytic_Avengers_Flow_Authorizing_of_Leaving


The flow consists of the following steps:

Trigger: The flow is triggered by a button press.
Create an Approval: An approval is created with the title "Sair mais cedo" (Leave early), assigned to "iefp220@alunos.ipca.pt", and with the details "Posso sair mais cedo?" (Can I leave early?). Notifications and reassignment are enabled.
Post Card to Conversation: A card containing the approval details is posted to a specific channel in Microsoft Teams.
Wait for an Approval: The flow waits for the approval to be completed.
Send Email V2: An email is sent to "iefp220@alunos.ipca.pt" with the subject "Pedido para sair mais cedo" (Request to leave early) and the body "<p>Resposta submetida</p>" (Response submitted). The email has high importance.

 ![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/6bfb080f-5394-48d9-b9f3-56b3978a7755)

Analytic_Avengers_Flow_Purchase_Approval


The flow starts with a trigger that subscribes to a webhook. It listens for a message with specific entity name and scope.

Next, it checks if the value of "cr9f8_preco" in the trigger output is greater than 500. If it is, it starts an approval process using the "StartAndWaitForAnApproval" action. The approval is assigned to two email addresses and includes details from the trigger output.

If the outcome of the approval is "Approve", it updates a record in the "cr9f8_requisicaodecompras" entity, setting the value of "cr9f8_escolha" to 1. Otherwise, it sets the value to 0.

If the value of "cr9f8_preco" is not greater than 500, it starts a basic approval process without waiting for it to complete. The approval is assigned to two email addresses and includes the "cr9f8_justificativa" from the trigger output.

If the outcome of this approval is "Approve", it updates the same record as before, setting the value of "cr9f8_escolha" to 1. Otherwise, it sets the value to 0.

![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/62932749-5919-473f-b628-df8b43d27424)

Analytic_Avengers_Flow_Sharepoint_New_File

The flow consists of the following steps:

GetOnUpdatedFileItems: This action retrieves the details of the updated file items from a SharePoint dataset.
StartAndWaitForAnApproval: This action starts an approval process and waits for it to be completed. It creates an approval with the title, assigned user, details, item link, and enables notifications and reassignment.
If statement: Checks if the outcome of the approval is "Approve".
SendEmailV2: Sends an email notification to the assigned user if the approval outcome is "Approve". It includes the name of the file in the email body.
Else statement: Executes if the approval outcome is not "Approve".
DeleteFile: Deletes the file from the SharePoint dataset.
SendEmailV2: Sends an email notification to the assigned user if the approval outcome is not "Approve". It notifies the user that the file request has been rejected.

![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/83894187-2b78-475d-bb45-fe7a6896bac6)

Analytic_Avengers_Flow_Sharepoint_New_Item

![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/3f542ec1-6331-4ba9-853c-49ab05786ac9)

Analytic_Avengers_atualize_projeto1_power_automate

![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/6c990c59-d4e5-4d67-9832-a1a018acaadd)










 


 
