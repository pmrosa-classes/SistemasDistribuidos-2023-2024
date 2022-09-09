# Trabalhos Práticos (65%)

Os alunos que preferirem Avaliação Continua V1 terão que efetuar um trabalho prático que valerá 65% da classificação final. Nesses casos o teste final apenas vale 35%.
É uma solução para os alunos que preferem uma abordagem mais prática à cadeira. Será ao mesmo tempo uma forma de avaliação mais vocacionada para a auto-formação que dá mais liberdade aos alunos mas também mais responsabilidade para com as decisões que vão tomando (preferencialmente de acordo com o Docente sendo que para essa interação haverão aulas de apoio).

São propostos alguns temas de trabalhos. A primeira entrega será uma proposta mais descritiva, do que os enunciados seguintes, sobre o que será o trabalho prático e terá que ser entregue **até dia 4 de março** (poderá sofrer alterações posteriromente). O template para a Proposta está disponível na página de [Documentação](https://github.com/pmrosa-classes/SistemasDistribuidosEI/blob/main/TrabsP/Documentacao.md) do Projeto

Todos os trabalhos terão que abordar a temática da **Tolerância a Faltas** em conjunto com outros assuntos estudados.

Os alunos podem usar qualquer tecnologia, infraestrutura, framework ou linguagem que entenderem. Nas aulas não haverá suporte direto a essas componente, apenas aos conceitos envolvidos.

---


## 1. Sistema de sensores para trânsito automovel 


## 2. Sistema de registo de jogadores de jogos on-line


## 3. Sistema peer-to-peer para transferência de ficheiros

## 1. Sistema de Votação On-Line Distribuído

Os sistemas de votação *on-line* comecam timidamente a aparecer. Um dos motivos que atrasa a sua implementação é a confiança necessária à sua utilização.
O que se pretende é um sistema de votação *on-line*, que deverá obviamente contar com estações de voto (sugere-se uma app na web ou apps Android em alternativa) e servidores de gestão da votação e de armazenamento de dados (bases de dados). Os serviços devem estar replicados em mais que uma máquina; as bases de dados devem estar replicadas em mais que uma máquina e cifradas. Toda a comunicação entre clientes e servidores deve ser cifrada (https).
A implementação exata e seu contexto fica ao critério do aluno que terá que o descreverá na sua proposta de trabalho.

***Interessante e Relevante:*** *se dois grupos colaborarem e juntarem este trabalho com o Sistema de 2FA, cada grupo pode libertar-se de uma parte do projeto e mesmo assim terem a mesma percentagem da nota. Portanto sugere-se colaboração estreita entre grupos para a elaboração de um sistema unico.*

## 2. Repositório de Ficheiros Distribuído on-line

A necessidade de acesso facilitado a ficheiros fez surgir um grande número de serviços como a DropBox, GoogleDrive, OneDrive, etc.
Estes serviços são fornecidos em ambientes de Cloud e alem da facilidade e ubiquidade no seu acesso, estão configurados em alta disponibilidade.
O que se pretende é a elaboração de um sistema deste tipo, com acesso facilitado através de uma página web (como opcional através de uma app Android) e que suporte um ambiente de alta disponibilidade com replicação e preferencialmente encriptação de dados.

***Interessante e Relevante:*** *se dois grupos colaborarem e juntarem este trabalho com o Sistema de 2FA, cada grupo pode libertar-se de uma parte do projeto e mesmo assim terem a mesma percentagem da nota. Portanto sugere-se colaboração estreita entre grupos para a elaboração de um sistema unico.*

## Sistema de Auto-Reposição de ficheiros / Anti-Ransomware

Uma modificação não autorizada de um sistema de ficheiros é algo que se deseja evitar, seja devido a ataques de Ransomware ou outra causa.
O que se pretende é criar um sistema que detete alterações não autorizadas de ficheiros armazenados e os reponha, caso se detete que foram acessos não autorizados. Os alunos devem iniciar o trabalho por propor a forma de deteção.

***Interessante e Relevante:*** *se dois grupos colaborarem e juntarem este trabalho com o Repositório de Ficheiros Distribuído on-line, cada grupo pode libertar-se de uma parte do projeto e mesmo assim terem a mesma percentagem da nota. Portanto sugere-se colaboração estreita entre grupos para a elaboração de um sistema unico.*

## Sistema 2FA (preferivelmente c/ app Android)

Cada vez mais existem ataques a formas de validação simples baseadas em nomes de utilizadores e passwords. Desde há muito tempo que se iniciou a utilização de um sistema de dois fatores, baseado numa segunda validação que pode ser realizada de várias formas (uma notificação no telemovel; uma app que gere TOTP; etc).
O que se pretende é que os alunos desenvolvam um sistema de 2FA que seja tolerante a faltas e distribuído.

***Interessante e Relevante:*** *este sistema pode ser associado a todos os outro projetos, podendo cada grupo libertar-se de uma parte do projeto e mesmo assim terem a mesma percentagem da nota. Portanto sugere-se colaboração estreita entre grupos para a elaboração de um sistema unico.*
 
## Sistema de Armazenamento de Logs Distribuído

A capacidade de registar as várias operações realizadas por sistemas e aplicações é muito relevante para a implementação de politicas de segurança eficazes.
O que se pretende é criar um sistema que Logs que armazena as informações enviadas (por diversas vias a propor, incluindo webservices) de forma distribuída e replicada.
Para a implementação o projeto necessitará de pequenas aplicações "teste" que enviem os dados, para provar a correta implementação do sistema.

*Em alternativa a esse desenvolvimento de aplicações "teste", pode ser* ***Interessante e Relevante*** *juntar este projeto a qualquer um dos outros projetos, podendo cada grupo libertar-se de uma parte do projeto e mesmo assim terem a mesma percentagem da nota.*

---

Os trabalhos práticos são efetuados em [grupo](https://github.com/pmrosa-classes/SistemasDistribuidosEI/blob/main/TrabsP/TrabsP-grupos.md).

Tal como descrito na Avaliação, a classificação final do trabalho deve ser no minimo de 8 valores.
