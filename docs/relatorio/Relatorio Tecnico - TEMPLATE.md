# Informações do Projeto
Dificuldade em organizar rotina

Curso de ciência da computação
## Participantes

> Os membros do grupo são: 
> - Pedro Judice Quintanilha de Albuquerque
> - Larissa Cássia de Miranda
> - Ji Xinyi

# Estrutura do Documento

- [Informações do Projeto](#informações-do-projeto)
  - [Participantes](#participantes)
- [Estrutura do Documento](#estrutura-do-documento)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
  - [Justificativa](#justificativa)
  - [Público-Alvo](#público-alvo)
- [Especificações do Projeto](#especificações-do-projeto)
  - [Personas e Mapas de Empatia](#personas-e-mapas-de-empatia)
  - [Histórias de Usuários](#histórias-de-usuários)
  - [Requisitos](#requisitos)
    - [Requisitos Funcionais](#requisitos-funcionais)
    - [Requisitos não Funcionais](#requisitos-não-funcionais)
  - [Restrições](#restrições)
- [Projeto de Interface](#projeto-de-interface)
  - [User Flow](#user-flow)
  - [Wireframes](#wireframes)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)
  - [Controle de Versão](#controle-de-versão)
- [**############## SPRINT 1 ACABA AQUI #############**](#-sprint-1-acaba-aqui-)
- [Projeto da Solução](#projeto-da-solução)
  - [Tecnologias Utilizadas](#tecnologias-utilizadas)
  - [Arquitetura da solução](#arquitetura-da-solução)
- [Avaliação da Aplicação](#avaliação-da-aplicação)
  - [Plano de Testes](#plano-de-testes)
  - [Ferramentas de Testes (Opcional)](#ferramentas-de-testes-opcional)
  - [Registros de Testes](#registros-de-testes)
- [Referências](#referências)


# Introdução
A maioria das pessoas nos dias de hoje vivem uma vida bastante corrida, nosso dia a dia nos priva de realizarmos todas as tarefas que gostaríamos e assim acabamos ficando sem tempo para fazer aquele trabalho da faculdade, sair com os amigos, ter um dia de lazer e etc.
Conciliar todas essas tarefas parece impossível dentro das 24 horas de um dia, e infelizmente não tem como aumentar nossas horas diárias, então o que nos resta é organizar nossa rotina de forma inteligente, de forma que consigamos achar tempo para todas (ou quase todas).


## Problema

Observando esse contexto, nota-se que o dia a dia das pessoas está cada vez mais corrido e a quantidade de afazeres está sempre aumentando, então para dar conta de todas as tarefas precisa-se de ser muito organizado e sem a ajuda de terceiros se organizar pode ser uma tarefa quase impossível.
Percebemos que, nos dias de hoje, existem certos problemas envolvendo a organização de rotina, tais como:
 - Falta de tempo para a realização das tarefas
 - Esquecimento das tarefas devido a falta de organização
 - dificuldade em achar uma forma prática para se organizar


## Objetivos

O objetivo do grupo é desenvolver um software que auxilie o usuário a planejar sua rotina de forma que ela fique mais prática e organizada. Assim o usuário consegue melhorar sua gestão de tempo, tornando-o mais produtivo.
objetivos específicos:
 - oferecer um local em que o usuário consiga organizar sua rotina de forma fácil e eficaz
 - entregar para o usuário uma rotina personalizada para as suas demandas



## Justificativa

Ter uma rotina organizada traz vários benefícios para nossa vida, tais quais
 - aumentar nossa produtividade
 - ter tempo para atividades de lazer
 - melhor gestão de tempo
 - diminuição no estresse
sendo assim não ter uma rotina organizada pode te custar uma vaga de emprego, ou sua própria saúde mental


## Público-Alvo

Nosso público alvo são principalmente as pessoas que realizam alguma ativdade, seja estudar, trabalhar ou os dois
 
Porém devido as informações adquiridas através das entrevistas vimos que a maioria do nosso publico alvo são estudantes de 18 a 25 anos

 
# Especificações do Projeto


## Personas e Mapas de Empatia

Exemplo de persona 1

![persona 1 miro](https://user-images.githubusercontent.com/81862048/165854914-0d81ed5f-8940-481e-8ba6-dde9399153bc.png)

Exemplo de Persona 2

![persona 2 miro](https://user-images.githubusercontent.com/81862048/165855004-4a31cbc5-def4-48de-9169-bdee134ad40e.png)

Exemplo de Persona 3

![persona 3 miro](https://user-images.githubusercontent.com/81862048/165855063-94558ad8-db8c-43a1-b1b7-10be1b836c01.png)
> 
> **Exemplo de Persona**
> 
> Persona 1
> 
> ![persona 1](https://user-images.githubusercontent.com/81862048/165855094-c49402fc-b512-41a0-8340-cac3da3ab98d.PNG)

> Perona 2

> ![persona 2](https://user-images.githubusercontent.com/81862048/165855135-bd717fc1-713c-4305-8120-6be5c885159c.PNG)

> Persona 3


> ![persona 3](https://user-images.githubusercontent.com/81862048/165855196-15449428-df4f-449e-b872-4183a3ed30e6.PNG)


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Registrar minhas tarefas           | Não esquecer de fazê-las               |
|Usuário do sistema       | Registrar Horarios                | Para ter controle de tempo |
|Usuário do sistema       | Registrar tarefas              | Para não esquecer de faze-las |


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RF-002| Gerar uma planilha com rotina   | MÉDIA |
|RF-003| Permitir que o usuario altere suas tarefas   | MÉDIA |
|RF-004| Permitir que o usuario Cadastre seus horarios   | ALTA |
|RF-005| Permitir que o usuario altere seus horarios   | MÉDIA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| O sistema deve ser interativo |  MEDIA |
|RNF-002| O cadastramento de informações deve ser rapido e facil |  ALTA | 



## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |
|03| O projeto deve respeitar as datas de entrega       |
|04| Não devera ter ajuda de terceiros no projeto       |

sitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)


# Projeto de Interface


## User Flow
User Flow 

![User flow](https://user-images.githubusercontent.com/81862048/165855910-c8f90e99-2c09-4dee-8ae6-5a09b6c8973d.PNG)

## Wireframes

Wireframe

![wireframe](https://user-images.githubusercontent.com/81862048/165855966-68f743f8-fb7f-4713-8744-08bcde1da704.png)

# Metodologia

O grupo resolveu dividir as tarefas de forma que nenhum membro do grupo fique sobrecarregados. estipulamos datas de entrega e analisamos em grupo as entregas.
## Divisão de Papéis
 - Github -- Pedro
 - Wireframe -- Larissa
 - Apresentação -- Todos

## Ferramentas

......  COLOQUE AQUI O SEU TEXTO - SIGA O EXEMPLO DA TABELA ABAIXO  ......

| Ambiente  | Plataforma              |Link de Acesso |
|-----------|-------------------------|---------------|
|Processo de Design Thinkgin  | Miro |  https://miro.com/XXXXXXX | 
|Repositório de código | GitHub | https://github.com/XXXXXXX | 
|Comunicação | Discord |  https://discord.com | 
|Design Grafico | Canva | https://canva.com | 

>

> As ferramentas empregadas no projeto são:
> 
> - Editor de código.
> - Ferramentas de comunicação
> - Ferramentas de diagramação
> - Plataforma de Design Grafico
> 
## Controle de Versão

> A ferramenta de controle de versão adotada no projeto foi o
> [Git](https://git-scm.com/), sendo que o [Github](https://github.com)
> foi utilizado para hospedagem do repositório `upstream`.
> 
> O projeto segue a seguinte convenção para o nome de branchs:
> 
> - `master`: versão estável já testada do software
> - `unstable`: versão já testada do software, porém instável
> - `testing`: versão em testes do software
> - `dev`: versão de desenvolvimento do software
> 
> Quanto à gerência de issues, o projeto adota a seguinte convenção para
> etiquetas:
> 
> - `bugfix`: uma funcionalidade encontra-se com problemas
> - `enhancement`: uma funcionalidade precisa ser melhorada
> - `feature`: uma nova funcionalidade precisa ser introduzida

# **############## SPRINT 1 ACABA AQUI #############**


# Projeto da Solução

......  COLOQUE AQUI O SEU TEXTO ......

## Tecnologias Utilizadas

......  COLOQUE AQUI O SEU TEXTO ......

> Descreva aqui qual(is) tecnologias você vai usar para resolver o seu
> problema, ou seja, implementar a sua solução. Liste todas as
> tecnologias envolvidas, linguagens a serem utilizadas, serviços web,
> frameworks, bibliotecas, IDEs de desenvolvimento, e ferramentas.
> Apresente também uma figura explicando como as tecnologias estão
> relacionadas ou como uma interação do usuário com o sistema vai ser
> conduzida, por onde ela passa até retornar uma resposta ao usuário.
> 
> Inclua os diagramas de User Flow, esboços criados pelo grupo
> (stoyboards), além dos protótipos de telas (wireframes). Descreva cada
> item textualmente comentando e complementando o que está apresentado
> nas imagens.

## Arquitetura da solução

......  COLOQUE AQUI O SEU TEXTO E O DIAGRAMA DE ARQUITETURA .......

> Inclua um diagrama da solução e descreva os módulos e as tecnologias
> que fazem parte da solução. Discorra sobre o diagrama.
> 
> **Exemplo do diagrama de Arquitetura**:
> 
> ![Exemplo de Arquitetura](images/arquitetura-exemplo.png)


# Avaliação da Aplicação

......  COLOQUE AQUI O SEU TEXTO ......

> Apresente os cenários de testes utilizados na realização dos testes da
> sua aplicação. Escolha cenários de testes que demonstrem os requisitos
> sendo satisfeitos.

## Plano de Testes

......  COLOQUE AQUI O SEU TEXTO ......

> Enumere quais cenários de testes foram selecionados para teste. Neste
> tópico o grupo deve detalhar quais funcionalidades avaliadas, o grupo
> de usuários que foi escolhido para participar do teste e as
> ferramentas utilizadas.
> 
> **Links Úteis**:
> - [IBM - Criação e Geração de Planos de Teste](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Práticas e Técnicas de Testes Ágeis](http://assiste.serpro.gov.br/serproagil/Apresenta/slides.pdf)
> -  [Teste de Software: Conceitos e tipos de testes](https://blog.onedaytesting.com.br/teste-de-software/)

## Ferramentas de Testes (Opcional)

......  COLOQUE AQUI O SEU TEXTO ......

> Comente sobre as ferramentas de testes utilizadas.
> 
> **Links Úteis**:
> - [Ferramentas de Test para Java Script](https://geekflare.com/javascript-unit-testing/)
> - [UX Tools](https://uxdesign.cc/ux-user-research-and-user-testing-tools-2d339d379dc7)

## Registros de Testes

......  COLOQUE AQUI O SEU TEXTO ......

> Discorra sobre os resultados do teste. Ressaltando pontos fortes e
> fracos identificados na solução. Comente como o grupo pretende atacar
> esses pontos nas próximas iterações. Apresente as falhas detectadas e
> as melhorias geradas a partir dos resultados obtidos nos testes.


# Referências

......  COLOQUE AQUI O SEU TEXTO ......

> Inclua todas as referências (livros, artigos, sites, etc) utilizados
> no desenvolvimento do trabalho.
> 
> **Links Úteis**:
> - [Formato ABNT](https://www.normastecnicas.com/abnt/trabalhos-academicos/referencias/)
> - [Referências Bibliográficas da ABNT](https://comunidade.rockcontent.com/referencia-bibliografica-abnt/)
