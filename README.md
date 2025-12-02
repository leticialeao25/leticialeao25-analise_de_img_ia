Passo a passo para extrair texto de imagens usando o Azure Vision

1️⃣ Criar uma conta
Antes de começar:

 é necessário criar uma conta no Azure https://azure.microsoft.com/pt-br/products/ai-services/

2️⃣ Acessar o portal

Após criar a conta, acesse o portal do Azure AI Services, que é a página principal para a configuração do serviço. https://portal.azure.com/#home

No portal, clique na opção "Criar um Recurso", localizada no menu à esquerda, no topo da página.
![image](https://github.com/user-attachments/assets/e9de80ce-d0e9-4e76-b603-11742fccbb8a)






3️⃣ 
 Você verá a seção "Categoria", onde são listados os tipos de grupos disponíveis. Escolha "IA + Machine Learning" (primeira opção abaixo de "Categorias").

Após selecionar "IA + Machine Learning", no centro da página aparecerão várias seções com recursos dessa categoria.
Em "Serviço de Linguagem", clique na opção "Criar".

![image](https://github.com/user-attachments/assets/658a7c63-ac74-4c9a-a896-d3fad21ba8e7)

4️⃣ Configurar o Serviço de Linguagem


Na parte inferior da página, clique em "Continue to create your resource", que iniciará a criação do laboratório.
 ![image](https://github.com/user-attachments/assets/0865ecf4-2587-4170-ae1d-fd3b6e813357)
 



5️⃣ Configurando o Serviço no Azure

1️⃣ Preencher as Informações do Recurso

Na tela de criação do recurso, preencha os seguintes campos:

Subscription: Selecione a assinatura ativa (se for uma conta gratuita, escolha "Free Trial").

Resource Group: Clique em "Create new"  e dê um nome ao grupo de recursos (por exemplo, meu-grupo-de-recursos).

Region(Região): Escolha a região mais próxima ou recomendada.

Name(Nome): Escolha um nome para o recurso (exemplo: meu-servico-de-visao).

Pricing Tier: Selecione o plano adequado (para testes, escolha o F0 - Free se disponível).

![image](https://github.com/user-attachments/assets/e1086675-1f25-4e89-9d91-ed65bc5408af)




Obs.: não esqueça de flegar a caixa de confirmação de aceite de termos(na parte inferior da página). Caso essa opção não esteja flegada o serviço não vai ser concluído. 
![image](https://github.com/user-attachments/assets/41adb3f9-818f-4f55-af41-3858b7121ffa)






6️⃣  Finalizando a configuração

Após a criação do laboratório, você será redirecionado para outra aba para concluir o processo.

 ![image](https://github.com/user-attachments/assets/2ce66b40-baa5-4787-be12-64336a079851)

 7️⃣ Clicar na opção ir para "Recurso"



 ![image](https://github.com/user-attachments/assets/eb808789-7201-4708-9141-f06cb5826f1d)



 
Veja se o Laboratório foi criado. Caso sim aparecerá em "Recursos" e "Registros".
![image](https://github.com/user-attachments/assets/ecd9df91-e947-4b0b-b3a1-f84dbf370ece)


 8️⃣ Acessando o Serviço Criado

Após a criação do laboratório, você será redirecionado para o painel do recurso. Agora, siga os passos abaixo para configurar e testar a extração de texto: 

Na última opção em "Language Studio" clique no link "Get started with Language Studio" que o levará para o site https://language.cognitive.azure.com/home

![image](https://github.com/user-attachments/assets/b022dcd2-86f3-41d4-850b-d290879555a8)


Escolher a Ferramenta de Extração de Texto

No painel principal, clique em "Experimentar" (Try It).
Selecione "Extração de Texto"

![image](https://github.com/user-attachments/assets/065b515b-e815-42a7-95f5-dbc841262e15)





 9️⃣ Inserir o Texto para Extração

Clique na caixa de entrada de texto.

Digite um texto manualmente ou cole um trecho de um documento.

Se quiser testar com uma imagem ou PDF, veja se há a opção de upload (algumas versões podem não suportar).

![image](https://github.com/user-attachments/assets/b1d2e2a5-c3dc-4bf9-9011-d9fd05ed02e4)


Conclusão

✅ O Azure retorna os dados extraídos no formato JSON.

✅ Ele organiza o texto em regiões, linhas e palavras.

✅ Você pode processar esse JSON em qualquer linguagem de programação para utilizar os resultados.



