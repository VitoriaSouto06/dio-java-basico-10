# dio-java-basico-10
# Desafio de projeto 1

Inteligência artificial

A inteligência artificial é como um cérebro que aprender a fazer tarefas que normalmente apenas pessoas conseguiria fazer, como entender o que uma pessoa fala, identificar rostos, ou até fazer recomendações de músicas, filmes e etc. Ela funciona analisando dados e encontrando padrões para tomar decisões com base neles, dois exemplos são o chat gpt e a alexa.


Machine Learning

É um tipo de inteligência artificial que faz as maquinas aprenderem sem ter serem programadas para cada detalhe, elas analisam frande quantidade de dados e encontram padrões para tomar decisões e aprendem com essas decisões.


Visão computacional

É uma parte da IA que ensina as maquinas a identificarem imagens ou vídeos, assim como nós fazemos, isso é muito usado em reconhecimento facial de celulares, filtros em redes sociais, diagnósticos médicos por imagens e etc.


Processamento de linguagem neural

É uma parte da inteligência artificial que é muito usada nos bots pois ela tem a função de identificar uma fala, texto de um ser humano interpretar a entonação daquela conversa e responder de acordo com o que a pessoa está solicitando.


Inteligência de documentos

Nessa área a inteligência artificial é responsável por ajudar as maquinas a entender, processar e extrair informações de documentos como PDFs, notas fiscais, contratos e etc.


Mineração de conhecimento 

É o processo de descobrir informações uteis e padrões em grandes quantidades de dados, é muito usado para entender comportamento dos clientes, prever tendencias de mercado e detectar fraudes. 


IA Generativa

É a IA responsável por criar coisas novas, como textos, imagens, vídeos invés de apenas analisar dados existentes, como é o caso da IA preditiva, o chat gpt é um bom exemplo de IA Generativa.


Imparcialidade 

A imparcialidade na inteligência artificial é responsável por garantir que os sistemas tomem decisões justas sem favorecer ou prejudicar certos grupos de pessoas


Confiabilidade e Segurança

Confiabilidade é quando a IA tem que gerar resultados consistentes e corretos, sem erros ou decisões incoerente, para isso os modelos devem ser testados e monitorados, assim evitamos falhas e vieses. Segurança se refere à proteção contra ataques cibernéticos, manipulação de dados e acessos não autorizados. Sistemas de IA devem ser projetados para evitar que sejam enganados ou explorados por hackers.


Privacidade e Segurança

A privacidade é a parte responsável por proteger informações pessoais e garantir que a LGPD esteja sendo aplicada, e a segurança é sobre prevenir ataques e acessos não autorizados.


Inclusão e transparência

A inclusão em IA é quando nenhum grupo está sendo excluído, temos que garantir que os sistemas atendam diversos grupos de pessoas independente de origem, gênero, idade ou condição social. E a transparência é deixar claro a forma como os sistemas com IA tomam as decisões e sempre deixar claro ao usuário que ele está usando um sistema IA


Responsabilidade

É a necessidade dos desenvolvedores, organizações e governos assumirem o papel de garantir que as IAs sejam usadas de maneira ética e responsável, e evitando que a IA cause danos ou tome decisões erradas e que isso impacte negativamente o usuário.


Processamento de Linguagem Natural e Conversacional no Azure

Analise de sentimento e resposta a perguntas 

É a uma série de serviços e ferramentas oferecidas pela Microsoft para permitir que os sistemas compreendam, interpretem e respondam seres humanos. A analise de sentimentos no Azure é realizada pelo Azure Cognitive Services - Text Analytics, ele permite que os textos sejam analisados e identifique a entonação, os sentimentos por trás daquele texto e o que aquela pessoa quis falar. Já a parte de respostas de perguntas  é feito pelo o Azure Cognitive Services - QnA Maker que permite que você crie um sistema de perguntas e respostas automatizado, essa ferramenta junto com o Azure Bots Services permite que você crie bons chat bots que realmente entenda as perguntas e traga respostas assertivas.


Fala

São ferramentas que permitem que as máquinas compreendam e gerem linguagem falada. Isso é possível por meio dos Azure Cognitive Services. Esses serviços podem ser usados para transcrever fala em texto, traduzir fala, ou até gerar respostas de fala a partir de texto. O Azure Speech Service pode converter fala em texto em tempo real, isso é útil para transcrição de áudio, como em reuniões, chamadas telefônicas ou gravações e também permite que você converta texto em fala. Isso é útil para criar respostas automatizadas ou interações de voz em chatbots, assistentes virtuais ou dispositivos inteligentes, você pode personalizar tom, ritmo, e o estilo de fala.


Tradução

O Azure Speech Translation permite que você traduza fala de um idioma para outro em tempo real. Isso pode ser útil para conferências multilíngues ou sistemas de atendimento ao cliente que atendem a uma base de usuários global. 


# Desafio Projeto 2

A IA de Documentos do Azure é uma tecnologia da Microsoft que ajuda empresas a ler e entender documentos automaticamente. Em vez de alguém precisar digitar informações de faturas, contratos ou formulários manualmente, essa inteligência artificial escaneia o documento, extrai os dados importantes e organiza tudo de forma automática.

Ela funciona como um "leitor inteligente" que identifica textos, tabelas e até assinaturas em arquivos como PDFs e imagens. Isso economiza tempo e reduz erros, tornando o trabalho mais rápido e eficiente.

Passo a passo do laboratório para usar essa tecnologia 

Precisamos criar uma search service, dar um nome e selecionar o offering basic e vamos para overview.

Depois precisamos ir em create a resource, e selecionar create azure AI services, selecionar um resource group e adicionar um pricing tier e selecionar o standard e marcar o check box abaixo.

Depois temos que ir em storage account, adicionar o resource group, storage account name,  escolher a performance, e escolher o redundancy selecionando locally redundant storage e podemos ir em review.

Precisamos fazer algumas configurações o storage, a primeira é deixando como enable a opção de allow blob anonymous acess e salvamos essa configuração.

Vamos criar um novo container, e adicionar em upload os arquivos da documentação, agora temos que ir no AI Search e no importar dados vamos selecionar o container e temos que apontar onde estão os documentos e que tipo de informação eu quero buscar nesses documentos, e podemos filtrar algumas informações que precisamos.












