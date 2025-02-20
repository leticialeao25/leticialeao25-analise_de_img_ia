Passo a passo para extrair texto de imagens usando o Azure Vision

1️⃣ Criar uma conta
Antes de começar, é necessário criar uma conta no Azure.
2️⃣ Acessar o portal
Após criar a conta, acesse o portal do Azure AI Services, que é a página principal para a configuração do serviço.

3️⃣ Criar um recurso
No portal, clique na opção "Criar um Recurso", localizada no menu à esquerda, no topo da página.
Na próxima página, à esquerda, você verá a seção "Categoria", onde são listados os tipos de grupos disponíveis. Escolha "IA + Machine Learning" (primeira opção abaixo de "Categorias").

![image](https://github.com/user-attachments/assets/ec88b11f-3c17-4130-b177-1daa15a75600) 


![image](https://github.com/user-attachments/assets/658a7c63-ac74-4c9a-a896-d3fad21ba8e7)



 ![image](https://github.com/user-attachments/assets/0865ecf4-2587-4170-ae1d-fd3b6e813357)

 


 ![image](https://github.com/user-attachments/assets/2ce66b40-baa5-4787-be12-64336a079851)

 
4️⃣ Configurar o Serviço de Linguagem

Após selecionar "IA + Machine Learning", no centro da página aparecerão várias seções com recursos dessa categoria.
Em "Serviço de Linguagem", clique na opção "Criar".
Na parte inferior da página, clique em "Continue to create your resource", que iniciará a criação do laboratório.


5️⃣ Finalizando a configuração

Após a criação do laboratório, você será redirecionado para outra aba para concluir o processo.

6️⃣ Acessando o Serviço Criado
Após a criação do laboratório, você será redirecionado para o painel do recurso. Agora, siga os passos abaixo para configurar e testar a extração de texto:

![image](https://github.com/user-attachments/assets/aab82c7f-2fd3-4d92-84d2-bdeb7fe4b584)


No menu à esquerda, clique em "Chaves e Endpoint".
Anote a chave da API e o endpoint, pois eles serão necessários para utilizar o serviço.

7️⃣ Testando a Extração de Texto no Portal
O Azure Vision permite testar a extração de texto diretamente no portal antes de integrá-lo ao código.

Acesse o Azure Vision OCR Demo.
Clique em "Upload" e selecione uma imagem contendo texto.
O serviço processará a imagem e exibirá o texto extraído.


