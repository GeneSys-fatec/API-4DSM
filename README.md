## 💻 Aprendizado por Projeto Integrado (API)
 
Projeto desenvolvido com base na Metodologia Ágil SCRUM, promovendo a colaboração entre os integrantes, a autonomia na execução das tarefas e o foco em entregas contínuas. A abordagem seguirá o ciclo CDIO — Conceber, Desenvolver, Implementar e Operar — permitindo que o grupo compreenda o desafio, proponha uma solução viável e entregue um MVP funcional.
 
As etapas do projeto, incluindo o Kick-Off e as Sprints, seguirão o cronograma e as diretrizes estabelecidas no Aviso Legal disponível no site da Fatec - São José dos Campos.

<br>

<span id="sumario">

<div align=center>
<a href ="#projeto"> Projeto </a> | <a href ="#requisitos"> Requisitos </a> | <a href ="#backlog&userstories"> Backlog do Produto </a> | <a href ="#dor-dod"> DoR e DoD </a> | <a href ="#sprints"> Sprints </a> | <a href ="#tecnologias"> Tecnologias </a> | <a href = "#branches-e-commits"> Branches e Commits </a> | <a href ="#instalacao"> Guia de Instalação </a> | <a href ="#equipe"> Equipe </a>
</div>

<br>

<span id="projeto">

## 📋 O Projeto
> **📌 Status do Projeto: A iniciar**
 
A empresa Tecsus busca expandir suas soluções de IoT para o monitoramento ambiental por meio de estações meteorológicas de baixo custo. Entretanto, para que os dados coletados por essas estações sejam úteis, é necessário um sistema capaz de receber, armazenar, processar e disponibilizar essas informações de forma organizada e acessível.

O Sistema de Coleta de Dados de Estações Meteorológicos foi desenvolvido para atender essa necessidade, permitindo a coleta automatizada de dados provenientes de sensores instalados em estações meteorológicas e sua disponibilização em um portal web com dashboards e relatórios analíticos.

Baseado na Metodologia Ágil SCRUM e no ciclo CDIO (Conceber, Desenvolver, Implementar e Operar), o projeto integra conceitos de IoT, processamento de dados e visualização de informações, garantindo uma solução escalável e eficiente para o monitoramento ambiental.

<br>

<span id="requisitos">

### 🔸 Requisitos Funcionais
- Cadastro e gerenciamento de estações meteorológicas, permitindo registrar diferentes dispositivos de coleta de dados.
- Cadastro e gerenciamento de parâmetros meteorológicos (ex.: temperatura, umidade, pressão atmosférica, direção e velocidade do vento, índice pluviométrico).
- CRUD completo para as entidades principais do sistema: Estações, Parâmetros, Alertas e Usuários.
- Recepção, processamento e armazenamento dos dados enviados pelas estações meteorológicas.
- Visualização de dashboards interativos com gráficos e indicadores sobre os parâmetros meteorológicos coletados.
- Geração automática de alertas quando determinados parâmetros ultrapassarem limites configurados.
- Controle de acesso ao sistema, com pelo menos dois perfis de usuário: Administrador e Usuário Público.
- Geração de relatórios com análises e insights baseados nos dados meteorológicos coletados.
- Tutorial ou guia educativo explicando o significado e a importância de cada parâmetro meteorológico monitorado.
- Desenvolvimento de um datalogger para registrar e enviar os dados coletados pela estação meteorológica.
- Montagem de uma estação meteorológica física, composta pelos sensores necessários para coleta de dados ambientais.

### 🔸 Requisitos Não Funcionais
- Experiência do Usuário (UX): a interface do sistema deve priorizar usabilidade, clareza das informações e visualização intuitiva dos dashboards.
- Documentação da API: todas as rotas da API devem possuir documentação clara, com exemplos de requisição e resposta.
- Pipeline de Integração Contínua (CI): implementação de pipeline para automação de testes, build e validação de código.
- Deploy automatizado: o sistema deve permitir deploy automatizado conforme o ambiente ou cliente.
- Escalabilidade do serviço de recepção de dados, garantindo processamento eficiente das informações enviadas pelas estações meteorológicas.
- Aplicação de conceitos estatísticos nos dashboards e relatórios para enriquecer a análise dos dados coletados.
 
<br>

<span id="backlog&userstories">

## 🎯 Backlog do Produto & User Stories

| ID  | Prioridade | User Story | Sprint | Story Points |
|-----|------------|------------|--------|--------------|
| US1 | Alta | Eu como **ADMINISTRADOR**, desejo realizar login na área administrativa do sistema, para acessar e gerenciar as funcionalidades administrativas da plataforma, garantindo que apenas usuários autorizados possam realizar alterações no sistema. | 1 | 13 |
| US2 | Alta | Eu como **ADMINISTRADOR**, desejo cadastrar estações meteorológicas, para registrar os locais de coleta de dados climáticos. | 1 | 8 |
| US3 | Alta | Eu como **ADMINISTRADOR**, desejo configurar parâmetros meteorológicos e seus limites, para definir quais variáveis ambientais serão monitoradas e identificar condições climáticas de risco. | 1 | 8 |
| US4 | Alta | Eu como **ADMINISTRADOR**, desejo cadastrar novos administradores no sistema para permitir que outros usuários autorizados possam gerenciar a plataforma. | 1 | 8 |
| US5| Média | Eu como **USUÁRIO DO SISTEMA**, desejo visualizar as métricas das regiões cadastradas, para acompanhar e analisar as condições climáticas de cada local monitorado. | 2 | 8 |
| US6 | Média | Eu como **USUÁRIO DO SISTEMA**, desejo visualizar alertas climáticos gerados automaticamente quando uma medição ultrapassar um limite configurado, para identificar possíveis situações de risco ou desastres naturais. | 2 | 5 |
| US7 | Média | Eu como **USUÁRIO DO SISTEMA**, desejo visualizar dashboards com dados organizados por parâmetro e apresentados em gráficos e cards, para analisar variações de temperatura, umidade e outros indicadores climáticos de forma clara e eficiente. | 2 | 8 |
| US8 | Média | Eu como **USUÁRIO DO SISTEMA**, desejo visualizar as estações meteorológicas em um mapa para identificar facilmente a localização geográfica dos pontos de coleta de dados climáticos. | 2 | 13 |
| US9 | Baixa | Eu como **USUÁRIO DO SISTEMA**, desejo visualizar guias explicativos sobre os parâmetros meteorológicos, para entender o significado das medições apresentadas. | 3 | 5 |
| US10 | Baixa | Eu como **ADMINISTRADOR**, desejo gerar relatórios com dados meteorológicos coletados pelo sistema, para analisar informações climáticas e apoiar tomadas de decisão em situações de risco. | 3 | 5 |
| US11 | Baixa | Eu como **ADMINISTRADOR**, desejo editar meu perfil administrativo para manter minhas informações atualizadas no sistema. | 3 | 5 |
 
<br>

<span id="dor-dod">

## ✅ DoR e DoD
### DoR Definition of Ready
Uma tarefa é considerada **pronta para ser iniciada** quando:
- História bem definida e escrita no formato: “Como [tipo de usuário], quero [funcionalidade], para [benefício esperado]”.
- Dados de teste definidos.
- Mockups ou fluxos UX disponíveis.
- Regras de negócio claras.
- Estimada pela equipe (Story Points definidos).
- Critérios de aceitação definidos.

### DoD Definition of Done
Uma tarefa é considerada **pronta** quando:
- Código revisado e integrado.
- Testes unitários aprovados.
- Critérios de aceitação atendidos.
- Regras de negócio respeitadas.
- Documentação atualizada.
- Interface implementada conforme mockups.

<br>

<span id="sprints">

## 📊 Sprints
Sprint | Previsão | Status | Relatório | Vídeo do Projeto |
|------|--------|------|---------|----------|
|01 | 16/03/2026 - 05/04/2026 |⏳ A iniciar| [Ver Relatório]() | <a href=''>Ver Vídeo</a> |
|02|  13/04/2026 - 03/05/2026 |⏳ A iniciar| [Ver Relatório]() | <a href=''>Ver Vídeo</a> |
|03| 11/05/2026 - 31/05/2026 |⏳ A iniciar| [Ver Relatório]() | <a href=''>Ver Vídeo</a> |

<br>

<span id="tecnologias">

## 🔧 Tecnologias
 
As seguintes ferramentas, linguagens, bibliotecas e tecnologias foram usadas na construção do projeto:
 
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white) ![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white) ![Jira](https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white) ![Figma](https://img.shields.io/badge/Figma-696969?style=for-the-badge&logo=figma&logoColor=figma) ![Swagger](https://img.shields.io/badge/Swagger-696969?style=for-the-badge&logo=swagger&logoColor=figma) 

<br>

<span id="branches-e-commits">

## 🌿 Padrão de Branches e Commits

| Branch | Descrição |
|------------|------------|
| **GEN-001** | Branch criada para o **desenvolvimento de uma tarefa**, O nome segue a identificação da task no Jira e é utilizada para implementar uma funcionalidade ou correção. |
| **develop** | Branch principal de **desenvolvimento**, onde são integradas as funcionalidades concluídas pelas branches de tarefa. |
| **release** | Criada a partir da `develop` → utilizada para testes finais, correções de bugs e ajustes antes do merge na `master`. |
| **master** | Branch principal de **produção**, contendo a versão estável e pronta para uso do sistema. |

Os commits são realizados de forma **frequente** e com mensagens escritas **no modo imperativo**, descrevendo de forma direta as alterações realizadas no código:
- ```feat:``` Usado para adicionar uma nova funcionalidade ao sistema (ex: `feat: implementa cadastro de estações meteorológicas`).
- ```fix:``` Usado para corrigir um erro no sistema (ex: `fix: corrige erro na exibição de temperatura no dashboard`).
- ```refactor:``` Usado para refatorar o código (ex: `refactor: reorganiza estrutura das rotas de estações meteorológicas`).
- ```docs:``` Usado para alterar ou adicionar documentação (ex: `docs: adiciona requisitos funcionais no README`).

<br>

<span id="instalacao">

## ⬇ Guia de Instalação

<br>

<span id="equipe">

## 👤 Equipe
|    Função     | Nome                                  |                                                                                                                                                      LinkedIn & GitHub                                                                                                                                                      |
| :-----------: | :------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Product Owner | Marianne Valério Nunes |         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/marianne-valério-nunes-701568292/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/mariannevalerion)        |
| Scrum Master |   Ana Beatriz Coelho         |     [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/abeatrizcoelho/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/abeatrizdscoelho)              |
| Team Member | Ana Júlia Gaspar |         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/ana-gaspar-957775325/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/anajgaspar)        |
| Team Member |   Emmanuel Yokoyama         |     [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/emmanuelyokoyama/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/EmmanuelJYokoyama)              |
| Team Member  | Gabriel Calebe |      [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/gabriel-medeiros-516ab3325/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/gbmedeiros00)          |
| Team Member |   Gabriel Robert       |     [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)]() [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)]()              |
| Team Member |   Giovanni Kanjiscuk      |     [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/giovanni-kanjiscuk/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/GKanjiscuk)              |
| Team Member | Francisco Rafael Pires |      [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)]() [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/franciscorafaelpires)          |

<br>

→ <a href="#sumario"> Voltar ao topo </a>
