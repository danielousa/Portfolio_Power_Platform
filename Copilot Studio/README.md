# Portfolio_Copilot_Studio

Buy a product flow

This flow show to the customer the available products. Permit his selection and the purchase.
The customer receive the feedback on the chatbot and by email.

This is an OnRecognizedIntent node named main. It's triggered when one of the specified intents (Quero comprar um produto, produtos, Produtos, produto ginasio) is recognized.
This is the first action inside the main node. It asks the user whether they want to know about your products. Depending on their response, it leads to different branches of the dialog.

![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/6013fd07-6f19-47d0-92c7-0f8830d6b07f)

This is a conditional branching node. It checks the response from the first question and directs the flow accordingly.
This is another question node inside the first condition group. It asks the user to choose their city.


![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/1e1f1ea8-27ff-4b71-8891-eafdaacbc054)

This action sets the value of a variable Topic.Var3 to the selected city. This action invokes another flow based on the selected city. This action invokes another flow based on the selected city.

![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/b6c36992-b59a-4a23-9bf4-88e118ef6390)

This is another question node asking if the user wants to continue with the purchase. Another conditional branching node based on the user's response to the previous question.

![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/fb9a81cc-46ae-4b4e-a7e4-2887988ad508)

This question node asks for the product code if the user chooses to continue with the purchase. This question node asks for the quantity of the product.

![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/d14bb198-4513-4619-b8eb-35ae2b811f04)

This question node asks for the user's email. This action invokes another flow, possibly to process the purchase details.

![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/b9b47fff-b2d5-4644-b3bf-c09262b4f920)

This action sends a confirmation message to the user.  This question node asks if the user wants to continue shopping.

![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/2ae65a55-6f7c-48e6-8744-f201bacdcc9c)

Another conditional branching node based on the user's response. This action sends a thank you message to the user if they choose not to continue shopping. This action ends the conversation.

![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/b3099517-5d15-404e-b8a7-5cade76298c9)



Opening hours flow

This flow let know the customer now the horary of our gym, by city, and receive the overall schedule of ours activities.

This is an OnRecognizedIntent node named main. It's triggered when one of the specified intents (Qual é o horário de funcionamento do ginásio?, horario funcionamento, horario, horário) is recognized. This is the first action inside the main node. It asks the user for the city they're interested in.

![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/43885018-b79e-4be8-a65d-af8e1cce304a)

This is a conditional branching node. It checks the user's response about the city and directs the flow accordingly.  This question node asks the user for their preferred activity, such as yoga, cycling, or weightlifting.

![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/fde0817e-a2a2-4100-b288-faafbf2cf1e2)

 This is another conditional branching node based on the user's activity preference.  This action sets the value of variables Topic.Var11 and Topic.Var12 to the selected activity and city, respectively.

![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/6cd5100f-87e1-4c27-8681-66d20dd950e8)

This action invokes another flow based on the selected activity and city. This action sends a message to the user with the output from the invoked flow, which likely contains the gym's operating hours.

![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/2c03796c-da34-444c-92dc-e6dbbfa1f612)

 This question node asks if the user wants to receive the gym's schedule via email. Another conditional branching node based on the user's email preference.

![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/6b52ad51-e41a-4261-87c5-238855fc23c3)
![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/1fdbbdbe-b929-46dc-93f3-ea1801377b2f)
![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/6603f556-6053-469b-9cde-0f77cb929bd0)
