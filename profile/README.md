# 🌱 AgroMart - Comunidades que Sustentam a Agricultura

Bem-vindo à organização do **AgroMart**! 

O AgroMart é uma solução tecnológica em software, de código aberto (Open Source), focada na agricultura familiar. Nosso objetivo principal é conectar pequenos produtores rurais a consumidores (chamados de coagricultores) utilizando o modelo de negócio das **Comunidades que Sustentam a Agricultura (CSAs)**. 

A plataforma visa descentralizar a gestão das CSAs, oferecendo um ambiente próprio para que os agricultores possam escoar suas produções, gerenciar assinaturas de cestas agroecológicas, controlar seus estoques e organizar pagamentos digitais, além de fornecer um aplicativo móvel direto e prático para o cliente final. Originalmente nascido em um *hackathon* da Universidade de Brasília (UnB) em 2020.

---

## 📂 Repositórios

O ecossistema do Agromart é dividido em múltiplos repositórios e serviços. Abaixo está a finalidade de cada um deles em nossa organização:

*   📱 **[mobile-client](https://github.com/AgroMart/mobile-client)**: O aplicativo móvel oficial do Agromart voltado para os coagricultores (consumidores). Desenvolvido em React Native e TypeScript, ele permite que os usuários encontrem sua CSA, assinem planos de cestas, comprem produtos avulsos e gerenciem seus pedidos.
*   💻 **[interface-web](https://github.com/AgroMart/interface-web)**: Uma interface web moderna, acessível e responsiva desenvolvida em Vue.js. Criada com foco no baixo letramento digital, ela substitui a interface nativa do Strapi, permitindo que os agricultores administrem a sua CSA de forma intuitiva.
*   ⚙️ **[api](https://github.com/AgroMart/api)**: O servidor *back-end* principal do sistema. Construído com o CMS *Headless* Strapi (Node.js/JavaScript), ele abriga as regras de negócios da CSA, como a gestão de produtos, assinantes, módulos de pagamento e extratos.
*   🚀 **[deploy-automatico](https://github.com/AgroMart/deploy-automatico)**: Repositório contendo os *scripts* em Python responsáveis por automatizar e agilizar a criação e a implantação (deploy) de novos ambientes de infraestrutura para novas CSAs aderentes à plataforma.
*   📖 **[docs](https://github.com/AgroMart/docs)** e **[Documentacao](https://github.com/AgroMart/Documentacao)**: Repositórios destinados à hospedagem da documentação técnica oficial da plataforma. Eles englobam manuais técnicos, diagramas arquiteturais e histórico de tomadas de decisão.
*   🆘 **[ajuda-agromart](https://github.com/AgroMart/ajuda-agromart)**: Uma página de tutoriais e suporte dedicada aos usuários finais (agricultores), ajudando-os a navegar pelas funcionalidades da plataforma.
*   📦 **[agromart-web](https://github.com/AgroMart/agromart-web)**: Repositório público arquivado (*archive*), que continha o código de iterações iniciais de antigas interfaces web.
*   🔀 **[api-dicionario](https://github.com/AgroMart/api-dicionario)**: Repositório público arquivado (*archive*), que continha a API de roteamento criada para permitir a descentralização. O gerenciamento de URLs e o roteamento para os ambientes individualizados de cada CSA foram migrados para um modelo Serverless / FaaS (Function as a Service).
*   🌐 **[.github](https://github.com/AgroMart/.github)**: Repositório de perfil com os padrões de saúde da comunidade, informações de organização e este arquivo de apresentação `README.md`.

---

## 🎓 Evolução do Projeto: Resumo dos TCCs

O Agromart vem sendo desenvolvido de maneira colaborativa e contínua pelos alunos de Engenharia de Software da UnB-FCTE ao longo dos anos. A evolução do projeto se divide nos seguintes marcos:

### Inovações tecnológicas na agricultura familiar : Agromart
**Autores:** *Lucas Siqueira Rodrigues e Lucas Pereira de Andrade Macêdo* <br>
**Resumo:** A agricultura familiar é responsável por grande parte dos alimentos consumidos no Brasil,
ela é focada em produzir tipos variados de produtos orgânicos e artesanais. Este trabalho
de conclusão de curso tem como objetivo desenvolver uma solução tecnológica denominada
Agromart que foca facilitar a relação entre os pequenos agricultores e os consumidores.
A solução engloba uma interface web para os agricultores e um aplicativo mobile multi-
plataforma para os consumidores, com o propósito de proporcionar ao pequeno agricultor
uma maior garantia para o escoamento de sua produção e ajudar pessoas que buscam
uma alimentação mais saudável e de qualidade a encontrar seus produtos <br>
🔗 **[Disponível aqui](https://bdm.unb.br/handle/10483/30718)**

### Uma evolução do projeto Agromart : open source, meios de pagamento e gestão de co-agricultores
**Autores:** *Byron Kamal Barreto Corrêa e Igor Guimarães Veludo* <br>
**Resumo:** O projeto Agromart nasceu a partir de um evento de competição de programação (hackathon) realizado pela Faculdade do Gama (FGA), da Universidade de Brasília (UnB) no qual, em uma das categorias, o objetivo era o desenvolvimento de um software que facilitasse a conexão entre agricultores e consumidores. Após o evento, o projeto tornou-se um Trabalho de Conclusão de Curso (TCC) e contou com a parceria de uma Comunidade que Sustenta a Agricultura (CSA) do Distrito Federal. As CSAs são comunidades formadas por agricultores de produtos orgânicos ou agroecológicos e co-agricultores (consumidores) que investem mensalmente em um sistema sustentável de produção. O objetivo deste trabalho foi continuar o desenvolvimento do projeto bem como da solução tecnológica legada, que engloba por um lado um sistema web para os agricultores realizarem o gerenciamento de co-agricultores e de interação por mensagens com estes e, por outro lado, um aplicativo mobile multi-plataforma para os co-agricultores receberem notificações e realizarem suas assinaturas de cestas. Para o desenvolvimento dos projetos web e mobile foram empregadas as metodologias ágeis Scrum, Kanban e XP. Foram empregas também as técnicas de entrevistas com os clientes e o estudo das regras de negócio do funcionamento de uma CSA para levantamento das novas funcionalidades. <br>
🔗 **[Disponível aqui](https://bdm.unb.br/handle/10483/33850)**

### Uma evolução do projeto Agromart : implantação individualizada e automatizada de um ambiente de CSA
**Autores:** *André Aben-Athar de Freitas e Pedro Vítor de Salles Cella* <br>
**Resumo:** Este trabalho tem como objetivo apresentar a evolução do software Agromart, com foco em sua característica Open Source. A proposta é explorar como o software poderá ser modificado em seu código mobile React-Native e CMS Strapi, a fim de torná-lo personalizado e automatizado para cada CSA. O objetivo principal é permitir que cada CSA possa gerenciar sua própria aplicação através de um admin Strapi, otimizando a gestão de seus produtos e serviços. Para isso, o trabalho abordará as modificações necessárias no software, bem como a criação de uma documentação detalhada (que se encontra em <https://agromart.github.io/docs/>) para facilitar a utilização e o processo de implantação da aplicação da CSA. O trabalho é relevante para a agricultura sustentável e a gestão de produtos locais, trazendo uma solução moderna e eficiente para as CSAs. A partir deste trabalho, espera-se que outras CSAs possam utilizar o software Agromart de forma mais eficiente e personalizada, contribuindo para o fortalecimento da agricultura sustentável e para o desenvolvimento da economia local. <br>
🔗 **[Disponível aqui](https://bdm.unb.br/handle/10483/35945)**

### Módulo de integração de pagamento e manutenção do software Agromart
**Autores:** *Giovanna Borges Bottino e Felipe Boccardi Silva Agustini* <br>
**Resumo:** O AgroMart é um software que serve para auxiliar comercialização de cestas de produtos agroecológicos cultivados por agricultores familiares. Ele visa facilitar a relação entre os pequenos agricultores e os co-agricultores com uma interface web para os agricultores e um aplicativo mobile multiplataforma. Esta proposta pretende fazer a manutenção e a criação de um módulo de integração de pagamentos para o AgroMart. A manutenção refere-se a melhoria da segurança através da atualização dos pacotes encontrados na API feita em Strapi CMS. Já o módulo de integração de pagamento, um serviço em Node Express que se comunicará com os gateways de pagamento Mercado Pago, PagSeguro e PayPal escolhidos por uma matriz de decisão. Assim espera-se contribuir para AgroMart com evolução, manutenção e documentação. <br>
🔗 **[Disponível aqui](https://bdm.unb.br/handle/10483/39189)**

### Associação para aplicações Agromart de uma CSA em cloud
**Autores:** *Abner Filipe Cunha Ribeiro e Rafael Leão Teixeira de Magalhães* <br>
**Resumo:** O AgroMart é um software que tem como proposta auxiliar o escoamento da produção dos agricultores, promovendo um ambiente propício para as Comunidades que Sustentam a Agricultura por meio de uma interface web e um aplicativo mobile. Este trabalho tem como objetivo a associação de aplicações AgroMart de uma Comunidade que sustenta Agricultura na Cloud por meio de serviços como o AWS Lambda, o DynamoDB e o Amazon SES reduzindo, assim, os custos de mantimento de alguns serviços por parte da Universidade de Brasília(UnB). Com este trabalho, espera-se contribuir para o AgroMart com evolução, manutenção, documentação e redução de custos. <br>
🔗 **[Disponível aqui](https://bdm.unb.br/handle/10483/39809)**

### Agromart : integração e publicação do aplicativo para agricultura familiar
**Autores:** *Christian Fleury Alencar Siqueira e Thiago Siqueira Gomes* <br>
**Resumo:** O Agromart é uma solução tecnológica com o objetivo de conectar produtores da agricultura familiar e consumidores de produtos orgânicos, por meio de um aplicativo que possibilita a compra e venda desses produtos. A ideia dessa aplicação surgiu em um Hackathon realizado na FGA no ano de 2020, desde então o seu desenvolvimento foi continuado por alunos da UnB-FGA ao longo de cinco trabalhos de conclusão de curso. A solução atualmente consiste em um aplicativo móvel para os consumidores, um servidor com uma API principal para cada CSA e uma API dicionário que conecta os consumidores ao servidor de cada CSA listada. Por se tratar de um trabalho desenvolvido por várias mãos diferentes ao longo do tempo sem seguir uma metodologia específica para conectar cada um dos trabalhos, a aplicação carece de documentação e uma política clara para orientar o desenvolvimento e dar unidade aos trabalhos desenvolvidos. Neste contexto, o presente trabalho de conclusão de curso em um trabalho de reengenharia, organizou os repositórios, documentou as funcionalidades, e integrou tudo que foi desenvolvido em um único ponto de convergência, para dar unidade ao projeto Agromart. Como efeito, este buscou viabilizar a publicação do Agromart, e possibilitou que o desenvolvimento de novas funcionalidades futuramente sigam essa mesma unidade. <br>
🔗 **[Disponível aqui](https://bdm.unb.br/handle/10483/40098)**

### Da análise à implementação: migração da infraestrutura de IaaS para FaaS com foco na redução de custos no AgroMart
**Autores:** *Kalebe Lopes da Cunha e Murilo Schiler Lopes Santana* <br>
**Resumo:** O AgroMart é um aplicativo que conecta produtores rurais e consumidores por meio do modelo de Comunidades que Sustentam a Agricultura (CSAs). Essas comunidades permitem a comercialização direta de alimentos, promovendo um consumo mais sustentável e aproximando os consumidores dos produtores locais. Na arquitetura de implantação atual, o agricultor arca com custos em dólares para manter sua CSA em funcionamento, pois o Agromart está implantado em uma arquitetura tradicional de IaaS. Como buscamos tornar essa solução acessível ao maior número possível de agricultores, não podemos impor custos a eles pela escolha do Agromart. Portanto, é essencial analisar a viabilidade de uma alternativa de implantação que seja sempre gratuita e acessível ao agricultor e, caso exista, implementá-la. Este Trabalho de Conclusão de Curso (TCC) propõe a migração da API de dicionário e do backend STRAPI da aplicação, que atualmente operam sob o modelo de Infraestrutura como Serviço (IaaS) utilizando instâncias Amazon Elastic Compute Cloud (EC2), para uma arquitetura baseada no paradigma de computação serverless, especificamente Função como Serviço (FaaS), através da AWS Lambda. A pesquisa abordará a viabilidade técnica e econômica dessa migração, investigando se a infraestrutura pode operar dentro dos limites do plano gratuito da AWS, reduzindo custos operacionais. Além disso, será analisada a capacidade das APIs de ultrapassar os limites da camada gratuita e as implicações de custos adicionais, bem como a necessidade de modificações na aplicação para garantir uma migração eficiente, sem impactos negativos na experiência do usuário. A adoção de computação serverless oferece benefícios como redução de custos com infraestrutura, escalabilidade automática e menor complexidade operacional. Este trabalho documenta todas as etapas envolvidas na transição de arquiteturas tradicionais para serverless. <br>
🔗 **[Disponível aqui](https://bdm.unb.br/handle/10483/43566)**

### Redesign Responsivo da Interface Web do Agromart: Uma Proposta de Acessibilidade Digital para Agricultores
**Autores:** *Guilherme Nishimura da Silva e Matheus Costa Gomes* <br>
**Resumo:** O Agromart é uma plataforma de gerenciamento que surgiu em meados de 2020, desenvolvida para apoiar pequenos agricultores, especialmente aqueles vinculados a Comunidades que Sustentam a Agricultura (CSA), na divulgação de seus produtos. No entanto, a interface nativa do Sistema Gerenciador de Conteúdo (Content Management System- CMS) Strapi, utilizada originalmente, apresenta barreiras de usabilidade para esse público-alvo. Diante desse cenário, este trabalho objetivou o desenvolvimento de uma nova camada de apresentação feita com o framework Vue.js, focada em proporcionar uma experiência mais intuitiva através de uma interface mais responsiva, acessível e de fácil compreensão em comparação à interface do Strapi. A metodologia adotada fundamentou-se no paradigma desacoplado, em que a nova interface consome os dados gerenciados pelo CMS por meio de uma API REST. Como resultado, apresenta-se a solução final através das telas implementadas, que demonstram uma evolução significativa na acessibilidade e na facilidade de interação em comparação à solução anterior. <br>
