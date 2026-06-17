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
**Autores:** *Lucas Siqueira Rodrigues e Lucas Pereira de Andrade Macêdo*
🔗 **[Disponível aqui](https://bdm.unb.br/handle/10483/30718)**

### Uma evolução do projeto Agromart : open source, meios de pagamento e gestão de co-agricultores
**Autores:** *Byron Kamal Barreto Corrêa e Igor Guimarães Veludo*
🔗 **[Disponível aqui](https://bdm.unb.br/handle/10483/33850)**

### Uma evolução do projeto Agromart : implantação individualizada e automatizada de um ambiente de CSA
**Autores:** *André Aben-Athar de Freitas e Pedro Vítor de Salles Cella*
🔗 **[Disponível aqui](https://bdm.unb.br/handle/10483/35945)**

### Módulo de integração de pagamento e manutenção do software Agromart
**Autores:** *Giovanna Borges Bottino e Felipe Boccardi Silva Agustini*
🔗 **[Disponível aqui](https://bdm.unb.br/handle/10483/39189)**

### Associação para aplicações Agromart de uma CSA em cloud
**Autores:** *Abner Filipe Cunha Ribeiro e Rafael Leão Teixeira de Magalhães*
🔗 **[Disponível aqui](https://bdm.unb.br/handle/10483/39809)**

### Agromart : integração e publicação do aplicativo para agricultura familiar
**Autores:** *Christian Fleury Alencar Siqueira e Thiago Siqueira Gomes*
🔗 **[Disponível aqui](https://bdm.unb.br/handle/10483/40098)**

### Da análise à implementação: migração da infraestrutura de IaaS para FaaS com foco na redução de custos no AgroMart
**Autores:** *Kalebe Lopes da Cunha e Murilo Schiler Lopes Santana*
🔗 **[Disponível aqui](https://bdm.unb.br/handle/10483/43566)**
