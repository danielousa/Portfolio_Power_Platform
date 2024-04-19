# Portfolio_Power_Automate

 Analytic_Avengers_Flow_Authorizing_of_Leaving

 O fluxo começa com um gatilho de botão. Em seguida, é criada uma aprovação básica com título, destinatário, detalhes e notificações habilitadas. Depois, um cartão é postado em um canal de equipe. O fluxo aguarda a aprovação e, em seguida, envia um e-mail com uma resposta submetida e alta importância.

 ![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/6bfb080f-5394-48d9-b9f3-56b3978a7755)

Analytic_Avengers_Flow_Purchase_Approval

O fluxo começa com um gatilho de assinatura de webhook para a entidade "cr9f8_requisicaodecompra". Em seguida, é verificado se o valor do campo "cr9f8_preco" é maior que 500. Se for, é iniciada uma aprovação básica aguardando todas as aprovações, com detalhes sobre o item, justificativa e preço. Se a aprovação for aprovada, é atualizada uma linha no registro da entidade "cr9f8_requisicaodecompras" com o valor 1 no campo "cr9f8_escolha". Caso contrário, o valor 0 é atualizado no mesmo campo. Se o valor do campo "cr9f8_preco" for menor ou igual a 500, é iniciada uma aprovação básica, com detalhes apenas sobre a justificativa. Novamente, se a aprovação for aprovada, é atualizada uma linha no registro da entidade "cr9f8_requisicaodecompras" com o valor 1 no campo "cr9f8_escolha". Caso contrário, o valor 0 é atualizado no mesmo campo.

![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/62932749-5919-473f-b628-df8b43d27424)

Analytic_Avengers_Flow_Sharepoint_New_File

![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/83894187-2b78-475d-bb45-fe7a6896bac6)

Analytic_Avengers_Flow_Sharepoint_New_Item

![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/3f542ec1-6331-4ba9-853c-49ab05786ac9)

Analytic_Avengers_atualize_projeto1_power_automate

![image](https://github.com/danielousa/Portfolio_Power_Platform/assets/159817085/6c990c59-d4e5-4d67-9832-a1a018acaadd)










 


 
