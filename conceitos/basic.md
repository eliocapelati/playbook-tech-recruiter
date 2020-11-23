## **Aprendendo um pouco sobre tecnologia**

### Algoritmo

Um algoritmo nada mais é do que uma sequência de ações. É uma receita que mostra passo a passo os procedimentos necessários para a resolução de uma tarefa.
Exemplo: fazer um macarrão.

### Design Pattern
Padrões de Projeto (Design Patterns) são práticas criadas por desenvolvedores experientes com o objetivo de definir soluções para problemas conhecidos que se repetem durante ciclos de desenvolvimento de software. Utilizar padrões de projeto traz o benefício de seguir práticas que já foram aplicadas com sucesso em diversos projetos até se tornarem um padrão. Quanto mais padrões o desenvolvedor conhecer, mais possibilidades ele terá de resolver problemas comuns com mais eficácia, reduzindo a necessidade de pensar em uma nova solução para um problema que já é conhecido em engenharia de software.

### Lógica de programação

É o modo como se escreve um programa de computador.

### Linguagem de programação

É um meio de comunicação entre humanos e computadores.
É uma linguagem formal que especifica um conjunto de instruções e regras utilizadas para gerar programas (softwares). Esse software pode ser desenvolvido para rodar via Desktop, Web e via Mobile (aplicativos).

O que é linguagem de mais baixo nível?
É aquela que se aproxima mais da linguagem da máquina. Exemplo: Assembly.

O que é linguagem de mais alto nível?
A sintaxe se aproxima mais da nossa linguagem. O desenvolvedor (dev) escreve menos e realiza mais. Exemplo: PHP, Python, C#, Java.

### Sistemas operacionais

É um programa ou um conjunto de programas cuja função é gerenciar os recursos do sistema, fornecendo uma interface entre o computador e o usuário.

#### Sistemas Operacionais mais comuns:

Microsoft Windows: O Windows vem instalado na maioria dos computadores novos. Isto faz com que ele seja um dos sistemas operativo mais populares.

MacOS: Este é o sistema operacional desenvolvido pela Apple Inc. Ele vem instalado em todos os computadores Mac.

Linux: é um termo popularmente empregado para se referir a sistemas operativos ou sistemas operacionais que utilizam o Kernel Linux.
Exemplos de sistemas que utilizam Kernel Linux: Ubuntu, Manjaro, Fedora, Linux Mint, entre muitos outros.

### Mobile - Sistema Operacional Móvel

Sistema operacional ou operativo móvel é um tipo de sistema operacional desenvolvido especificamente para smartphones, tablets, PDAs ou outros dispositivos móveis.

Exemplos:

Android: é um sistema operativo móvel que roda sobre o núcleo Linux, embora por enquanto seja ainda desenvolvido numa estrutura externa ao núcleo Linux.

iOS: é o sistema operativo móvel da Apple. Desenvolvido originalmente para o iPhone, também é usado em iPod Touch, iPad e Apple TV. A Apple não permite o sistema operativo rodar em hardware de outras marcas.

#### Nativo x Híbrido

Nativo: aplicações nativas são aquelas desenvolvidas com linguagem específica para cada plataforma. Seja Swift e Objective-C para iOS ou Java para Android. O modelo mais conhecido, mas nunca ortodoxo ou antiquado.

Híbrido: aplicações híbridas são aplicações multiplataforma. Elas permitem, por exemplo, que você construa um produto iOS e Android simultaneamente, em vez de desenvolver duas vezes usando a linguagem nativa de cada plataforma.

### Front-end

Podemos classificar como a parte visual, aquilo que conseguimos interagir. Lida com a interface do usuário.
Quem trabalha com o Front-end é responsável por desenvolver uma interface gráfica, normalmente com as tecnologias base da Web (mas poderíamos pensar em Front-end de aplicações desktop/mobile).

Principais linguagens, bibliotecas e frameworks:

- JavaScript
- HTML
- CSS
- React
- Vue
- vAngular

### Back-end

O desenvolvedor Back-end trabalha na parte de “trás” da aplicação. Ele é o responsável, de forma geral, pela implementação da regra do negócio e gestão dos dados através de um banco de dados.
Hoje em dia é muito comum que o desenvolvedor Back-end disponibilize uma API que será consumida pelo Frontend.
Algumas linguagens, frameworks e banco de dados:
JavaScript, Python, C#, Java (Linguagens)
Express, Django, Hapi, Nest (Frameworks para construção de APIs)
MySQL, PostgreSQL, SQL Server,MariaDB, MongoDB, Cassandra (Banco de dados)
Vídeo explicativo: Diferenças entre Frontend e Backend

### Banco de dados

É o armazenamento permanente para os dados do seu aplicativo. Normalmente o backend fará uma consulta no Banco de dados durante uma chamada de API. Existem dois tipos de banco de dados comuns: o Banco de dados relacional e o não relacional.

**Banco de dados relacional:** É aquele que modela os dados em forma de tabelas. Essas tabelas podem opcionalmente se relacionar entre si.
Ex: MySl, SQL Server, Oracle, Postgres
Atenção MySql e SQL Server não são iguais. Um é da Microsoft e o outro é Open Source.

**Banco de dados não relacional:** É usado para situações nas quais as tabelas dos bancos relacionais não se adequam muito bem ao caráter variável da estrutura de dados.
Ex: MongoDB, Redis, Cassandra.

### Full-stack

Desenvolvedor Fullstack é aquele que atua em várias frentes (back-end, front-end, banco de dados) e para isso pode usar várias tecnologias.
Cada empresa classifica essa pessoa com requisitos que fazem sentido ao seu produto. Mas basicamente é um profissional que consegue trabalhar em uma aplicação de ponta a ponta.

### Framework

Framework é um template ou um conjunto de bibliotecas com diversas funções que podem ser usadas pelo desenvolvedor. Uma analogia interessante é a uma caixa de ferramentas. Um framework disponibiliza um formato padrão para desenvolver e implantar aplicações.
O framework possui 3 características marcantes:
Inversão do controle: Diferente de bibliotecas o controle do fluxo de execução não é feito pelo programador mas pelo próprio framework.
Extensibilidade: O programador estende ou sobrescreve comportamentos padrão
Não modificável: Via de regra o programador não deveria interagir ou alterar diretamente o código do framework
Vídeo explicativo: O que é um Framework

### Library

Uma biblioteca é uma coleção de subprogramas. Em geral podem ser vistas como um conjunto de funcionalidade modular que pode ser reutilizado para resolver um problema.
Bibliotecas podem ser muitos grandes ou pequenas e simples.
Exemplos:
Biblioteca para fazer regressão linear
Biblioteca para construir interfaces (React uhul!)
Hoje utilizamos React para criar interfaces!
React é uma biblioteca JavaScript para construir interfaces para usuários e pode ser usada como base no desenvolvimento de páginas web.
No geral é necessária a utilização de bibliotecas adicionais para gerenciar estado da aplicação, rotas e outros.

### API

API é um conjunto de rotinas e padrões de programação para acesso a um aplicativo de software ou plataforma baseado na Web. A sigla API refere-se ao termo em inglês "Application Programming Interface" que significa em tradução para o português "Interface de Programação de Aplicativos".
É criada quando uma empresa de software tem a intenção de que outros criadores de software desenvolvam produtos associados ao seu serviço.
Através das APIs, os aplicativos podem se comunicar uns com os outros sem conhecimento ou intervenção dos usuários.

Exemplos: Google Maps APIs, Mercado Pago API, IBGE API, etc.

### Git

O Git é um sistema de controle de versão muito popular atualmente. Com ele podemos criar e navegar por todo histórico de alterações no código do nosso projeto. É essencial para equipes trabalhando em um mesmo projeto.
Exemplo1:
Um dev na empresa está trabalhando em um mesmo projeto com 5 outros. Cada um trabalha em uma parte do problema e algumas dessas partes tem que comunicar uma com a outra.
Como juntar esse código em um único código final? Usando o Git!
Exemplo 2:
Um dev acabou fazendo um modificação que faz todo o sistema parar de funcionar!
Como podemos reverter? Usando o Git!

### Github

O GitHub é uma empresa com fins lucrativos que disponibiliza um serviço de hospedagem de repositório Git baseado em nuvem. De forma sucinta, faz com que pessoas singulares e equipes usem de forma muito mais simples o Git para o controle de versão e colaboração.
CONCEITOS IMPORTANTES EM TECNOLOGIA

### DDD

O Domain-Driven Design (DDD), conceito criado em 2003 por Erick Evans em seu livro “Domain-Driven Design: Tackling Completixy in the Heart of Software” diz respeito a uma abordagem focada no design de softwares, o qual abarca uma série de protocolos, conceitos e técnicas para garantir um design mais eficiente no desenvolvimento de soluções. Sua importância é trazer as abordagens necessárias para realizar esse tipo de aplicação, mantendo o foco no Domínio de Software, ou seja, para cumprir o propósito que a aplicação deve atender. Afinal, não adianta ter um bom design, mas não cumprir a função para o qual a solução foi criada.

### TDD

O Test-Driven Development (TDD ou, em português, Desenvolvimento Orientado a Testes) é uma abordagem cujo objetivo é a realização de um sistema com 100% de cobertura de testes. O sistema de testes é fundamental para verificar se há qualquer tipo de falha que pode comprometer a usabilidade e funcionalidade da solução antes que seja entregue ao cliente final ou aplicada em seu negócio. Seu objetivo é buscar a qualidade total do código, por meio de 100% de cobertura de testes.

### BDD

O Behavior Driven Development (BDD, ou, em português, Desenvolvimento Guiado por Comportamento ou, ainda, Desenvolvimento Orientado a Comportamento) é um modelo criado em 2003, por Dan North, como uma espécie de resposta à criação do DDD. O Behavior Drive Development tem como principal característica a criação de códigos que sejam baseados nas descrições do comportamento que determinada funcionalidade da solução deva ter. Sendo assim, ele deve descrever, sem o uso de informação técnica, exatamente como ela deve se comportar e qual a resposta esperada da funcionalidade. Por exemplo, se você está montando um aplicativo baseado em gamification, deverá registrar como será um sistema de pontuação, demonstrando o que deverá ocorrer nos momentos em que os usuários ganham e perdem pontos.

### ATDD

O Acceptance Test-Driven Development (ATDD), ou "Desenvolvimento Orientado a Testes de Aceitação", é uma prática de obtenção de requisitos de forma colaborativa aplicada por equipes ágeis, onde exemplos concretos e testes automatizados são utilizados para especificar os requisitos, tornando-os mais claros, com o objetivo de criar especificações executáveis. Eles são gerados em sessões de criação do backlog do produto, com a participação da equipe, Product Owner, além dos demais interessados.

### Clean Code (Código Limpo)

É uma filosofia de desenvolvimento de softwares que consiste em aplicar técnicas simples que facilitam a escrita e a leitura de um código. Tornando-o, assim, de fácil compreensão.
