## 1 VISÃO GERAL DO PRODUTO

### 1.1 Declaração de Posição do Produto:

O PAULA (Paranoá Alfabetizando Utilizando Letramento Analógico) é um aplicativo mobile cujo escopo é contribuir na alfabetização de jovens e adultos com baixo grau de escolaridade, isto é, com nenhuma ou pouca instrução — público que não completou, abandonou ou não teve acesso à educação formal por qualquer motivo na região administrativa do Paranoá. Sendo assim, o PAULA destina-se às pessoas que desejam iniciar ou retomar seu processo de alfabetização.

Diferentemente de outros aplicativos semelhantes, tal como o AJA e Duolingo, o PAULA visa proporcionar dizeres regionais do Paranoá, recriando sua cultura e origem nas citações de palavras que o aplicativo repetirá ao ser utilizado.

|                 |                                                                                                                                             |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| Para            | Jovens e adultos, da RA do Paranoá, com nenhuma ou pouca instrução.                                                                         |
| Dos quais(Quem) | Desejam retomar, ou começar sua alfabetização.                                                                                              |
| O PAULA         | É um aplicativo mobile educativo.                                                                                                           |
| Que             | Visa contribuir com a alfabetização inicial ou evolução da formação educacional básica com o usuário de forma lúdica e amigável ao usuário. |
| Ao contrário    | Plataforma AJA.                                                                                                                             |
| Nosso produto   | contará com dialetos e expressões populares da região, para maior familiaridade do usuário.                                                 |

### 1.2 Objetivos do Produto

A proposta desse projeto é desenvolver um aplicativo para aparelhos celulares, tipo smartphones com ferramentas visuais e auditivas, como o uso de uma dubladora para gravar falas para facilitar as informações, e didáticas para a alfabetização inicial dos usuários e terá como atrativo palavras e dizeres regionais do Paranoá para que a população se sinta orgulhosa de ter um software que recrie suas origens e cultura nas citações de palavras que o aplicativo repetirá ao ser utilizado.

### 1.3 Tecnologias a Serem Utilizadas

- Git: Controle de versionamento.
- GitHub: Repositório e definição de Sprints.
- GitHub Pages: Documentação do projeto
- Discord: Realização das reuniões.
- Telegram: Controle de contato com os integrantes do projeto.
- Flutter: Desenvolvimento do front-end.
- Python Django: Desenvolvimento do back-end.
- Trello: Organização do quadro Kanban — controle de sprints.

## 2 VISÃO GERAL DO PROJETO

### 2.1 Organização do Projeto

| Papel                      | Atribuições                                                                                                 | Responsável      | Participantes                                                                             |
| -------------------------- | ----------------------------------------------------------------------------------------------------------- | ---------------- | ----------------------------------------------------------------------------------------- |
| Desenvolvedores            | Codificar o produto, codificar testes unitários, realizar refatoração                                       | Emerson          | Emerson, Mateus Almeida, Caio Berg, Lucas de Padua, Thalis, Pedro Lucas, Fellipe Pereira  |
| Tech Lead                  | Será responsável pela qualidade do código e coordenará o uso e integração das tecnologias usadas no projeto | Emerson          | Emerson, Mateus Almeida, Caio Berg, Lucas de Padua, Thalis, Pedro Lucas, Fellipe Pereira. |
| Scrum Master               | Responsável por coordenar os rituais do Scrum de modo que sejam feitos corretamente                         | Cristian Furtado | Fellipe Pereira, Cristian Furtado, Rodrigo Santos, Valderson Junior, Victor Matheus.      |
| Product Owner              | Irá definir o escopo da sprint atual e fazer a verificação/validação dos requisitos com o cliente           | Fellipe Pereira  | Equipe de Requisitos                                                                      |
| Documentador de requisitos | Garantir a clareza dos requisitos e a realizar sua documentação, gerência e rastreabilidade.                | Rodrigo Santos   | Fellipe Pereira, Cristian Furtado, Rodrigo Santos, Valderson Junior, Victor Matheus.      |
| Cliente                    | Comunicar sobre as necessidades de seu projeto                                                              | Yoko, Emerson    | ---                                                                                       |

### 2.2 Planejamento das Fases e/ou Iterações do Projeto

| Sprint | Produto (Entrega) | Data Início | Data Fim |
| ------ | ----------------- | ----------- | -------- |
| Sprint 1 | Definição do Produto | 26/06/22 | 02/07/22
| Sprint 2 | Levantamento de Requisitos | 03/07/22 | 09/07/22 |
| Sprint 3 | Levantamento de Requisitos | 10/07/22 | 16/07/22 |
| Sprint 4 | Levantamento de Requisitos | 17/07/22 | 23/07/22 |
| Sprint 5 | Refinamento de Requisitos | 24/07/22 | 30/07/22 |
| Sprint 6 | Funcionalidades | 31/07/22 | 06/08/22 |
| Sprint 7 | Funcionalidades | 07/08/22 | 13/08/22 |
| Sprint 8 | Funcionalidades | 14/08/22 | 20/08/22 |


### 2.3 Matriz de Comunicação

| Descrição                                                                  | Área/Envolvidos                                | Periodicidade  | Produtos Gerados                                           |
| -------------------------------------------------------------------------- | ---------------------------------------------- | -------------- | ---------------------------------------------------------- |
| Acompanhamento das Atividades em Andamento                                 | Equipe de Requisitos/Desenvolvimento           | Semanal/Diário | - Dailies                                                  |
| Acompanhamento dos Riscos, Compromissos, Ações Pendentes, Indicadores      | Equipe de Requisitos                           | Quinzenal      | - Resumo de reunião<br>- Relatório de situação do projeto  |
| Comunicar situação do projeto                                              | Equipe Requisitos e Desenvolvimento<br>Cliente | Quinzenal      | - Resumo de reunião<br>- Relatório de Situação do Projeto  |
| Reuniões de sanar dúvidas entre as equipes de desenvolvimento e requisitos | Equipe de Requisitos e desenvolvimento         | Semanal        | - Resumo de reunião<br>- Retrospectiva e Revisão da Sprint |

### 2.4 Gerenciamento de Riscos

| Descrição                     | Causa                                                                                                                                                         | Medida Mitigadora                                                                                                                                                                                                                                                                                                                                          |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Falta de conhecimento         | Tecnologia para captação de aúdio será deixada para ser implementada ao final do desenvolvimento.                                                             | Na pior das hipóteses, caso seja dada pela equipe a impossibilidade de implementação do requisito, será marcada uma reunião com o cliente para a exploração de vias alternativas.                                                                                                                                                                          |
| Diminuição da equipe          | Fatores externos, como trancamento de disciplina, ou internação hospitalar devido à pandemia ou outros fatores.                                               | Caso a equipe seja diminuída, será realizada uma reunião para a redefinição do backlog da sprint para a entrega do produto baseado na ordem de prioridade dos requisitos.                                                                                                                                                                                  |
| Diminuição do comprometimento | Os membros da equipe são universitários, então, é possível que compromissos externos afetem seus rendimentos — seja por estágio ou entrega de outras matérias | Dessa forma, de modo a mitigar tal fato, será questionado aos membros a cada reunião diária (daily) se eles conseguirão entregar a dada tarefa. Caso haja impedimentos, tal fato será tratado da mesma forma que a diminuição da equipe, isto é, redefinição do backlog da sprint para a entrega do produto baseado na ordem de prioridade dos requisitos. |

### 2.5 Critérios de Replanejamento

| Descrição                                                        | Causa                                                 | Replanejamento                                                                                                                                                                                     |
| ---------------------------------------------------------------- | ----------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Equipe com dificuldade de entregar e desenvolver funcionalidades | Comprometimento com outras matérias/ Motivos pessoais | Aliviar nas funcionalidades do ciclo de desenvolvimento atual/próximo ciclo                                                                                                                        |
| Falta da funcionalidade da captação de áudio do usuário          | Recurso e tempo                                       | Descartar essa funcionalidade, a fim de entregar um produto com qualidade, mediante a essa problemática.                                                                                           |
| Equipe com déficit de participantes                              | Trancamento/Desistiu da matéria                       | Tentar manter o desenvolvimento das funcionalidades, mesmo com a equipe com esse déficit. No último caso, colocar um integrante de uma equipe em outra para equilibrar Requisitos/Desenvolvimento. |

## 3 PROCESSO DE DESENVOLVIMENTO DE SOFTWARE

O processo de desenvolvimento de software será feito por uma abordagem ágil, onde a equipe de desenvolvimento terá fixo o tempo e os recursos, no caso o período letivo do semestre, com os requisitos variáveis, priorizados pelo cliente.

- Ciclo de vida evolutivo
- Scrum/Kanban
- Análise dos requisitos
- Analise e design:

  |Atividade | Objetivo | Papel | Método | Ferramenta |
  |----------|----------|-------|--------|------------|
  |Definir design das interfaces | Criar um modelo das interfaces que serão desenvolvidas | Product Owner e Equipe de Desenvolvimento | "UCD, Design Iterativo" | Figma
  | Definir do banco de dados | Criar um modelo do banco de dados que serão desenvolvidas | Equipe de Desenvolvimento | Modelo Relacional | Miro
  |Revisão de interface | Validar a interface para o desenvolvimento | Equipe de Desenvolvimento | Reunião com o Product Owner e cliente |"Figma, Miro"

- Implementação:

  |Atividade | Objetivo | Papel | Método | Ferramenta |
  |----------|----------|-------|--------|------------|
  |Codificação das Interfaces | Desenvolver as telas definidas pela sprint | Equipe de Desenvolvimento | Seguir o design definido anteriormente | Flutter
  |Codificação do banco de dados | Desenvolver o banco de dados definido pela sprint | Equipe de Desenvolvimento | Seguir o design definido anteriormente| MySQL

- Testes:

  |Atividade | Objetivo | Papel | Método | Ferramenta |
  |----------|----------|-------|--------|------------|
  |Realizar Teste| Encontrar falhas no software| Equipe de Desenvolvimento| Testes manuais| xxx
  |Realizar Teste Unitarios| Encontrar falhas no software| Equipe de Desenvolvimento| Testes de widget| "Pacote ""test"""

## 4 PROCESSO DE ENGENHARIA DE REQUISITOS

O processo da engenharia de requisitos será feito por uma abordagem ágil, onde a equipe de desenvolvimento irá trabalhar com as metodologias Scrum/Kanban, um híbrido que pode auxiliar no desenvolvimento do nosso projeto.

### 4.1 Elicitação de Requisitos

| Atividade                                               | Método               | Ferramenta   | Entrega                          |
| ------------------------------------------------------- | -------------------- | ------------ | -------------------------------- |
| Pesquisa sobre o tema do projeto e seu campo de atuação | Pesquisa             | Google       | Conhecimento sobre o produto     |
| Conversa com o cliente                                  | Entrevista e reunião | Google meets | Lista de requisitos preliminares |

### 4.2 Análise de Requisitos

| Atividade                                                                             | Método  | Ferramenta           | Entrega                                                  |
| ------------------------------------------------------------------------------------- | ------- | -------------------- | -------------------------------------------------------- |
| Conversa com o cliente e com a equipe de desenvolvimento para verificar a viabilidade | Reunião | Discord/Google Meets | Lista de requisitos analisados que irão compor o Backlog |
| Refinamento da lista de requisitos analisados | Reunião | Discord/Meets | Lista de requisitos com níveis de abstração próprios |
| Definição do MVP/Épico com base nos requisitos refinados | Framework SAFe | Discord, Miro | MVP/Épico definido com suas features e histórias|
| Definir critérios de aceitação | Entrevistas, reuniões em equipe | Discord | Histórias de usuários com critérios de aceitação |

### 4.3 Documentação de Requisitos

| Atividade                                                             | Método                  | Ferramenta                | Entrega                                                                                         |
| --------------------------------------------------------------------- | ----------------------- | ------------------------- | ----------------------------------------------------------------------------------------------- |
| Tradução de requisitos em formato mais compreensível aos stakeholders | Linguagem natural       | Requisitos bem descritos  |
| Listagem de requisitos encontrados da fase de análise                 | Definição em categorias | GitHub Pages, Google Docs | Lista de requisitos documentados e seus tipos (não funcional e funcional), o Backlog do projeto |

### 4.4 Verificação e Validação de Requisitos

| Atividade                                                                 | Método                                    | Ferramenta           | Entrega                           |
| ------------------------------------------------------------------------- | ----------------------------------------- | -------------------- | --------------------------------- |
| Verificação da qualidade do código                                        | Inspeção, Walkthrough, Check-lists        | Discord              | Atualização do Backlog do produto |
| Conversa com o cliente para verificar se o requisito está como o esperado | Reunião com toda a equipe e com o cliente | Discord/Google Meets | Atualização do Backlog do produto |


### 4.5 Gerenciamento de Requisitos

| Atividade                                                                      | Método                                            | Ferramenta                | Entrega                                                           |
| ------------------------------------------------------------------------------ | ------------------------------------------------- | ------------------------- | ----------------------------------------------------------------- |
| Colocar tags e nomes para identificar requisitos e rastreá-los mais fácilmente | Etiquetação de cada requisito por números e nomes | Trello, Discord, Telegram | Requisitos nomeados e priorizados, facilitados para gerenciamento |

## 5 LIÇÕES APRENDIDAS

### 5.1 Unidade 1

#### MDS

Na unidade 1 os ensinamentos aprendidos foram relacionados ao processo de desenvolvimento de software, métodos e metodologias, disciplinas de engenharia de software e ciclo de vida. Ademais, para melhorar nosso ambiente de desenvolvimento optamos por utilizar uma abordagem ágil e nos baseamos no framework Scrum, pois o design e a implementação do software são a base dessa abordagem.

Como também, escolhemos o ciclo de vida evolutivo que se encaixa no nosso projeto, devido aos requisitos ainda estarem passíveis de mudança. Tais escolhas foram feitas a partir da abordagem de Sommerville, que nos nortearam a utilizar esse ciclo de vida e a utilizar o modelo de processos de desenvolvimento de software (Scrum).

#### Requisitos

A primeira unidade deu ao grupo instrução para que fosse possível a escolha de uma metodologia de desenvolvimento, visto que nenhum dos integrantes possuía conhecimento sobre esse assunto e não sabia qual metodologia se encaixaria melhor no projeto. E também foi iniciado o aprendizado de execução do planejamento de engenharia de requisitos.

#### MDS-Requisitos

Aprendemos um pouco sobre a dinâmica de cada membro da equipe e como nós iremos nos comunicar e delegar tarefas.

Nesta primeira etapa, estabelecemos a comunicação entre equipes, entender as necessidades específicas de cada um para o conhecimento mútuo entre ambas as equipes.

### 5.2 Unidade 2

#### MDS

A colocar

#### Requisitos

A colocar

#### MDS-Requisitos

A colocar


<!-- ### 5.3 Unidade 3

#### MDS

[Liste as lições aprendidas na retrospectiva, com ênfase especial nas ações a serem tomadas para melhorar, por exemplo: o ambiente de desenvolvimento, o processo ou a colaboração da equipe.]

#### Requisitos

A primeira unidade deu ao grupo instrução para que fosse possível a escolha de uma metodologia de desenvolvimento, visto que nenhum dos integrantes possuía conhecimento sobre esse assunto e não sabia qual metodologia se encaixaria melhor no projeto.

#### MDS-Requisitos

[Liste as lições aprendidas na retrospectiva, com ênfase especial nas ações a serem tomadas para melhorar, por exemplo: o ambiente de desenvolvimento, o processo ou a colaboração da equipe.] -->

<!-- ### 5.4 Unidade 4

#### MDS

[Liste as lições aprendidas na retrospectiva, com ênfase especial nas ações a serem tomadas para melhorar, por exemplo: o ambiente de desenvolvimento, o processo ou a colaboração da equipe.]

#### Requisitos

A primeira unidade deu ao grupo instrução para que fosse possível a escolha de uma metodologia de desenvolvimento, visto que nenhum dos integrantes possuía conhecimento sobre esse assunto e não sabia qual metodologia se encaixaria melhor no projeto.

#### MDS-Requisitos

[Liste as lições aprendidas na retrospectiva, com ênfase especial nas ações a serem tomadas para melhorar, por exemplo: o ambiente de desenvolvimento, o processo ou a colaboração da equipe.] -->

## 6 REFERÊNCIAS BIBLIOGRÁFICAS

> [1]. Sommerville, Software Engineering, 2004 <br> [2]. P. Bourque, SWEBOK Guide Call for Reviewers, May 2003. <br>  [3]. Ambler, S., Agile Modeling, Wiley, 2002. <br>

## 7 Histórico de Revisão

| Data       | Versão	| Descrição | Autor |
| ---------- | ------ | --------- | -----
| 25/06/2022 | 1.0    | Inicia preenchimento do documento | Cristian Furtado, Valderson Junior, Rodrigo Santos, Fellipe Pereira |
| 27/06/2022 | 1.1    | Preenche campos de Visão Geral do Projeto e Produto e indica dúvidas para serem solucionadas |Cristian Furtado, Valderson Junior, Rodrigo Santos, Fellipe Pereira |
| 28/06/2022 | 1.1.1  | Preenche campos indicados com dúvida | Cristian Furtado, Fellipe Pereira |
| 29/06/2022 | 1.2    | Adicionado documento à Github Pages | Rodrigo Santos
| 29/06/2022 | 1.3    | Revisão do Documento de Visão Geral do Produto e Projeto | Cristian Furtado, Fellipe Pereira, Rodrigo Santos, Valderson Junior
| 13/07/2022 | 1.4 | Revisão do documento | Cristian Furtado
| 20/07/2022 | 1.5 | Revisão do documento | Cristian Furtado, Fellipe Pereira, Rodrigo Santos, Valderson Junior
| 26/07/2022 | 1.6 | Revisão do documento | Cristian Furtado, Valderson Junior
