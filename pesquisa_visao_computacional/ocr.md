# Serviços de Inteligência Artificial Azure - OCR

* Abra o [portal do Azure](https://portal.azure.com/):
* Acesse Mais Recursos  e depois IA + Machine Learning
* Clique em Azure AI services para criar recursos do Serviços Cognitivos.

![alt text](inputs/image.png)

* Crie um Grupo de Recursos, caso ainda não tenha
* Atribua um nome ao Grupo de Recursos

![alt text](inputs/image-1.png)

![alt text](inputs/image-2.png)

* Importante:
     - Adicionar uma região para o recurso
     - nomear o recurso
     - Escolher o tipo de preço **Standard S0**
     - Deixar a caixa "Ao marcar essa caixa, confirmo que li e compreendi todos os termos abaixo" - como **checada**
     - Depois Clique em Revisar e Criar e Criar novamente

![alt text](inputs/image-3.png)

Depois de criar os Serviços Cognitivos - acesse o [portal Vision](https://portal.vision.cognitive.azure.com/):
 
 * Não esqueça de confirmar se está logado com a mesma conta

 ![alt text](inputs/image-4.png)

 * Clique em ver todos recursos

 ![alt text](inputs/image-5.png)

 * Selecione o recurso e marque como padrão

 ![alt text](inputs/image-6.png)

 * Feche - voltando para página principal
 * Encontre o recurso: Face - Detect faces in an image

![alt text](inputs/inputs/image-11.png)

 * Marque a caixa: I acknowledge that this demo will incur usage to my Azure account.
 * Para testar basta selecionar uma das imagens ou escolher uma imagem do computador ou tirar uma foto

 ![alt text](inputs/image-10.png)

 # Referências
 
 * [OCR para imagens](https://learn.microsoft.com/pt-br/azure/ai-services/computer-vision/concept-ocr)
 * [Guia de início rápido: Análise de Imagem](https://learn.microsoft.com/pt-br/azure/ai-services/computer-vision/quickstarts-sdk/image-analysis-client-library-40?tabs=visual-studio%2Clinux&pivots=programming-language-rest-api)