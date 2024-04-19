# Portfolio_Power_Automate

 Analytic_Avengers_Flow_Authorizing_of_Leaving

 O fluxo começa com um gatilho de botão. Em seguida, é criada uma aprovação básica com título, destinatário, detalhes e notificações habilitadas. Depois, um cartão é postado em um canal de equipe. O fluxo aguarda a aprovação e, em seguida, envia um e-mail com uma resposta submetida e alta importância.

 ![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/6bfb080f-5394-48d9-b9f3-56b3978a7755)

Analytic_Avengers_Flow_Purchase_Approval

The flow starts with a trigger that subscribes to a webhook. It listens for a message with specific entity name and scope.

Next, it checks if the value of "cr9f8_preco" in the trigger output is greater than 500. If it is, it starts an approval process using the "StartAndWaitForAnApproval" action. The approval is assigned to two email addresses and includes details from the trigger output.

If the outcome of the approval is "Approve", it updates a record in the "cr9f8_requisicaodecompras" entity, setting the value of "cr9f8_escolha" to 1. Otherwise, it sets the value to 0.

If the value of "cr9f8_preco" is not greater than 500, it starts a basic approval process without waiting for it to complete. The approval is assigned to two email addresses and includes the "cr9f8_justificativa" from the trigger output.

If the outcome of this approval is "Approve", it updates the same record as before, setting the value of "cr9f8_escolha" to 1. Otherwise, it sets the value to 0.

![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/62932749-5919-473f-b628-df8b43d27424)

Analytic_Avengers_Flow_Sharepoint_New_File

![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/83894187-2b78-475d-bb45-fe7a6896bac6)

Analytic_Avengers_Flow_Sharepoint_New_Item

![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/3f542ec1-6331-4ba9-853c-49ab05786ac9)

Analytic_Avengers_atualize_projeto1_power_automate

![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/6c990c59-d4e5-4d67-9832-a1a018acaadd)










 


 
