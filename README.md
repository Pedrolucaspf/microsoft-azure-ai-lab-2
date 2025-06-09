# microsoft-azure-ai-lab-2
Repositório do lab "Azure Cognitive Search: Utilizando AI Search para indexação e consulta de Dados" da DIO

Neste lab, foi explicada brevemente a mineração de conhecimento, processo no qual uma IA utiliza um mecanismo de pesquisa a partir palavras-chave ou frases-chave para encontrar informações específicas em bases de dados muito grandes.

No Azure, existem diferentes soluções de pesquisa cognitiva: desde ingestão de dados com Blob (pode receber qualquer tipo de arquivo) até  o enriquecimento da IA a partir do uso de uma indexação específica do conteúdo, de acordo com o tipo de consulta que será feito com mais frequência. É feita então a pesquisa, cujos dados costumam ser informados no formato JSON. 

Para fazer o uso do serviço de AI Search, devemos criar um novo recurso do tipo Azure AI Search no portal. Ele possuirá diferentes Tiers de preço, que afetam a quantidade de dados que a IA poderá receber, além da quantidade de unidades de pesquisa.

Após isso, é criado um novo recurso do tipo Azure AI Services, e também uma Storage Account. Após ter sido criada a Storage Account, é necessária a criação de um Container dentro dela para o armazenamento dos dados.

De volta ao AI Search, deve-se ir na aba 'Import Data', onde o usuário deverá selecionar o container da Storage Account criada. A partir disso, pode ser feita a pesquisa por meio do serviço, levando em conta todos os arquivos do container.
