Desafio-AISearch-DIO
Azure Cognitive Search: Utilizando AI Search para indexação e consulta de Dados.

Passo-a-passo
Para realizar a indexação e consulta de dados, é necessário seguir o seguinte passo-a-passo:

Criar um recurso de search no Azure AI Search;
Ferramenta de busca;
Criar recurso de inteligência artifical em AI Machine Learning;
Responsável pelas automações;
Criar conta de armazenamento (Storage Account);
Armazenamento dos arquivos;
Com o storage account criado e pronto, seguir com os passos:
realizar o upload dos arquivos no storage;
De volta no recurso Azure AI Search, é necessário fazer:
em "Import data", selecionar o Azuere Blob Storage e preencher os detalhes do armazenamento para realizar a conexão com o storage;
adicionar os campos de enriquecimento;
escolher a storage account criada anteriormente ao selecionar uma conexão existente para conectar;
personalizar o indice de destino;
criar o indexador;
selecione enviar, para realizar a criação da fonte de dados, conjunto de habilidades, indice e indexador;
Por fim, utilize o Search Explorer para escrever e testar suas consultas.
Exemplo: search=locations:'chicago' - retornará todas as reviews associadas a localização Chicago.
Com essas ferramentas é possível realizar automações e consultas de forma mais prática e rápida, além da possibilidade de realizar as buscas direto pelo Search Explorer, é possível desenvolver essas ferramentas para utilização em aplicações. A aplicabilidades dessas ferramentas são infinitas e podem auxiliar em diversas áreas, como no exemplo, na gestão de reviews de produtos e serviços, onde com essas buscas precisas e rápidas, é possivel verificar constantemente e de forma atualizada a opinião do público e desenvolver ações com base nessa informações.
