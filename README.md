# FATEC Profº Jessen Vidal - São José dos Campos - 4º Semestre DSM - 2025

<p>Projeto desenvolvido para a API (Aprendizagem por Projeto Integrado) do 4° Semestre do curso Desenvolvimento de Software Multiplataforma (DSM) em parceria com a Tecsus.</p>

> _A API se trata de um projeto submetido à metodologia de ensino em implantação na Fatec São José dos Campos, do qual os alunos formam equipes baseadas na metodologia ágil SCRUM, tendo um aluno como Scrum Master, um sendo o Product Owner e o restante dos integrantes como Dev Team._

 <img src="https://github.com/Equipe-Skyfall/skytrack/blob/main/dev-docs/Sistema%20de%20Monitoramento%20Meteorol%C3%B3gico.png">


### 📃 Respositórios 
- [Repositório FrontEnd](https://github.com/Equipe-Skyfall/skytrack-front)
- [Respositório BackEnd](https://github.com/Equipe-Skyfall/skytrack-back)
- [Respositório BD](https://github.com/Equipe-Skyfall/skytrack-bd)
- [Respositório Principal](https://github.com/Equipe-Skyfall/skytrack)

---

## 📑 Sumário
- [Visão do Projeto](#visao-do-projeto)
- [Cronograma do Projeto](#cronograma)
- [Tecnologias utilizadas](#tecnologias)
- [Padrões de Commit](#padrao)
- [Requisitos](#requisitos)
- [Product Backlog](#backlog)
- [Sprint Backlog](#backsprint)
- [Links úteis](#links)
- [Equipe](#equipe)
---

## 🏥Dores do Cliente

### Verificar
**Problemas Identificados**:
- **Ausência de dados em tempo real**: Atualmente o cliente não dispõe de informações atualizadas instantaneamente sobre direção e velocidade do vento, índice pluviométrico, umidade, temperatura e pressão.
- **Dificuldade em antecipar riscos**: Sem medições contínuas, se torna complexo a análise de riscos como enchentes, deslizamentos ou eventos climáticos extremos com antecedência.
- **Falta de Padronização**: Estações e sensores seguem padrões diferentes, afetando o recebimento de dados de multiplas fontes em um único sistema.
- **Decisões Estratégicas Prejudicadas**: Sem dados claros e estruturados, o que afeta o entendimento de usuários comuns (Ex: Alunos, Pesquisadores)

### Planejar
**Objetivos**:
- **Instalação de Estações**: Montar e instalar estações meteorológicas de baixo custo, com sensores para chuva, vento, temperatura, umidade e pressão.
- **Sistema de Alerta Automático**: Implementar um sistema de alertas automáticos, notificando em tempo real sobre riscos como chuvas intensas, enchentes e deslizamentos com base na média da medição de uma ou varias estações.
- **Centralização de modelos**: Garantir um modelo de dados dinâmico que permita integrar diferentes tipos de sensores e protocolos, como LoRa, Sigfox e NB-IoT, sendo realizado uma padronização desses modelos.
- **Estruturação para acadêmicos**: Envolver alunos do ensino médio por meio de dashboards interativos e conteúdo educativo, clarificando de maneira que o entendimento seja próprio, não sendo necessário nenhum nível superior para compreensão.
- **Escalabilidade e Desenvolvimento**: Preparar o sistema para escalabilidade, possibilitando a adição de novas estações, assim otimizando o escopo para recepção de dados.

### Controlar
**Ações para Garantir a Efetividade**:
- **Monitoramento da Rede de Estações**: Acompanhar se todas as redes estão ligadas por meio do modelo de dados dinâmico, identificando falhas em sensores ou na comunicação
- **Garantir a escalabilidade da solução**: Monitorar por meio de testes de carga e desempenho à medida que novas estações forem adicionadas, sendo possível observar a operação da nova estação em conjunto das antigas.
- **Verificação de Medição para Alertas**: Verificar por meio de alertas gerados anteriormente a veracidade por meio dos dados coletados das estações, possibilitando de maneira palpável a captação das medições responsáveis por gerar notificações de risco.
- **Análise dos Relatórios Estratégicos**: Revisar regularmente os relatórios para garantir que os dados ofereçam insights relevantes, possibilitando ajustes rápidos nas estratégias impostas sobre as estações.
---

## 👁 Visão do Projeto <a name="visao-do-projeto"></a>
<p>Nosso projeto é um Sistema de Coleta de Dados Meteorológico em Tempo Real, com foco na prevenção de riscos e desastres naturais. A plataforma visa centralizar e analisar informações, como índices de chuva, captadas por uma rede de sensores de baixo custo. Será incluso um modelo dinâmico para a aceitação de diversos tipos de estações, facilitando a obtenção de dados oriundos de diversas fontes. As informações serão exibidas em um painel de controle moderno e intuitivo, enquanto um sistema de notificações proativo alertará os usuários sobre potenciais riscos, como inundações e deslizamentos. O sistema também incluirá um espaço de conteúdo educacional, expondo de forma clara a lógica utilizada pelo sistema para captação de dados e informações estimadas.</p>

---
## Cronograma de Sprints <a name="cronograma"></a>
| Sprint | Data | Status | Relatório |
|:------:|:----:|:------:|:---------:|
| 1 | 08/09/2025 à 28/09/2025 | Concluído | [Ver Relatório](https://github.com/Equipe-Skyfall/skytrack/blob/main/docs/Sprint%201)|
| 2 | 06/10/2025 à 26/09/2025 | Concluído |[Ver Relatório](https://github.com/Equipe-Skyfall/skytrack/blob/main/docs/Sprint%202)|
| 3 | 03/11/2025 à 23/11/2025 | Concluído | [Ver Relatório](https://github.com/Equipe-Skyfall/skytrack/tree/main/docs/Sprint%203) |
---

## 💻 Tecnologias utilizadas <a name="tecnologias"></a>
<div align="center">
<img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=black&color=ADD8E6">
<img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=black&color=ADD8E6">
<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=black&color=ADD8E6">
<img src="https://img.shields.io/badge/Jira-217346?style=for-the-badge&logo=Jira&logoColor=black&color=ADD8E6">
<img src="https://img.shields.io/badge/Microsoft_Teams-6264A7?style=for-the-badge&logo=microsoft-teams&logoColor=black&color=ADD8E6">
<img src="https://img.shields.io/badge/typescript-000000?style=for-the-badge&logo=typescript&logoColor=black&color=ADD8E6">
<img src="https://img.shields.io/badge/react-000000?style=for-the-badge&logo=react&logoColor=black&color=ADD8E6">
<img src="https://img.shields.io/badge/tailwind-000000?style=for-the-badge&logo=tailwindcss&logoColor=black&color=ADD8E6">
<img src="https://img.shields.io/badge/mongodb-000000?style=for-the-badge&logo=mongodb&logoColor=black&color=ADD8E6">
<img src="https://img.shields.io/badge/postgresql-000000?style=for-the-badge&logo=postgresql&logoColor=black&color=ADD8E6">
<img src="https://img.shields.io/badge/arduino-000000?style=for-the-badge&logo=arduino&logoColor=black&color=ADD8E6">
<img src="https://img.shields.io/badge/prisma-000000?style=for-the-badge&logo=prisma&logoColor=black&color=ADD8E6">
<img src="https://img.shields.io/badge/vercel-000000?style=for-the-badge&logo=vercel&logoColor=black&color=ADD8E6">
<img src="https://img.shields.io/badge/node-000000?style=for-the-badge&logo=node&logoColor=black&color=ADD8E6">
<img src="https://img.shields.io/badge/git-000000?style=for-the-badge&logo=git&logoColor=black&color=ADD8E6">
</div>

### 📃 Estrutura de Branchs 
  #### Main - Estado principal que armazena a versão estável do projeto
  #### Dev - Estado de desenvolvimento atual
  #### Sprint X - Instancia de todos respositórios ao fim da Sprint X
### ⏳ Status do projeto: 3/3 Sprint ✅

## 💻 Padrões de commit <a name="padrao"></a>

**FEAT**: Adiciona um novo recurso ou funcionalidade.
  Exemplo: FEAT - Adição da navbar

**FIX**: Corrige um bug.
  Exemplo: FIX - Corrige o modal que não estava fechando

**CHORE**: Atualizações de manutenção que não alteram a lógica de negócio ou visual, como atualização de dependências, configurações de build, etc.
  Exemplo: CHORE - Atualização das dependências do Node.js

**DOCS**: Altera a documentação, como o README, comentários no código ou arquivos de documentação do projeto.
  Exemplo: DOCS - Atualiza README com informações sobre novas rotas

**STYLE**: Modifica a formatação do código, como espaços em branco, quebra de linha ou pontuação, sem alterar a lógica.
  Exemplo: STYLE - Adiciona comentários no código para facilitar a leitura

**REFACTOR**: Refatora o código sem adicionar novas funcionalidades ou corrigir bugs, visando melhorar a estrutura, legibilidade ou desempenho.
  Exemplo: REFACTOR - Refatora o código, deixando-o mais leve

**TEST**: Adiciona, modifica ou remove testes unitários ou de integração.
  Exemplo: TEST - Adiciona teste para o componente de login

**PERF**: Melhora a performance.
Exemplo: PERF - Otimiza a execução de consultas no banco de dados

**BUILD**: Altera o sistema de build ou as dependências externas, como npm, gradle, ou docker.
  Exemplo: BUILD - Adiciona um Dockerfile para o ambiente de produção

**REVERT**: Reverte um commit anterior.
  Exemplo: REVERT - Reverte a adição de autenticação de middleware

**HOTFIX**: Corrige um bug crítico em produção de forma urgente.
  Exemplo: HOTFIX - Corrige vulnerabilidade crítica na autenticação de usuários

Convenções Adicionais

Nomenclatura de Variáveis: Utiliza-se o padrão camelCase (ex: nomeCompleto).

---

### Requisitos Funcionais <a name="requisitos"><a>

| RF | Nome | Descritivo |
|:--:|:----:|:----------:|
|RF1 | Integração de novas estações meteorológicas |O sistema deve possibilitar a conexão rápida e simples de novas estações físicas, de maneira dinâmica para diferentes tipos de sensores.|
|RF2 | Aquisição de dados meteorológicos | O software precisa coletar, armazenar e interpretar de forma persistente e segura os dados recebidos dos sensores.|
|RF3 | Dashboards | Deve existir um painel visual que mostre graficamente os parâmetros de cada estação e também um panorama geral.|
|RF4 | Montagem de Estação Meteorológica | É necessária a construção física de uma estação meteorológica para a utilização de dados da mesma.|
|RF5 | Notificações meteorológicas | Devem ser emitidos avisos e alertas baseados em condições climáticas específicas.|
|RF6 | Guias interativos |  A aplicação deve oferecer explicações sobre parâmetros e riscos associados.|
|RF7 | Gestão de administradores | Deve ser possível cadastrar novos administradores para possibilitar a configuração do software.|
|RF8 | Relatórios | A aplicação deve gerar ao menos três relatórios distintos, trazendo análises sobre os dados coletados.|
|RF9 | Crud de Entidades | Deve ser possível a utilização de um CRUD completo de Estação, Parâmetros, Tipo Alertas e Usuários Administradores.|

### Requisitos Não Funcionais

| RFN | Nome | Descritivo |
|:--:|:----:|:----------:|
|RFN1 | Experiência do Usuário (UX) |Design dos dashboards deve priorizar a usabilidade e a estética para melhor engajamento dos usuários.|
|RFN2 | Engajamento Estudantil | Fomentar o interesse dos alunos do ensino médio pelo estudo através da aplicação prática de conceitos em um contexto de aprendizado baseado em problemas.|
|RFN3 | Documentação de APIs | Elaboração detalhada da documentação para todas as rotas da API, incluindo exemplos de uso.|
|RFN4 | Pipeline de Integração Contínua (IC) | Implementação de um pipeline de CI para automação de testes e validações de código.|
|RFN5 | Deploy Automático | Configuração de processos automáticos de deploy para garantir atualizações consistentes do sistema.|





---


## 📜 Product Backlog <a name="backlog"><a>

| RANK | SPRINT | PRIORIDADE | ESTIMATIVA | USER STORY (NOME)                                             | STATUS |
|:----:|:------:|:----------:|:----------:|:-------------------------------------------------------------:|:------:|
| 1    |   1   |    Alta     |     5      | Como Administrador, quero um CRUD para as estações, para gerenciamento de suas informações.|   ✅     |
| 2    |   1   |    Alta     |     3      | Como Usuário Público, quero visualizar a lista de estações, para que eu saiba qual é a estação dos dados exibidos.|  ✅      |
| 3    |   1   |    Alta     |     5      | Como Administrador, quero um CRUD para os parâmetros utilizados nas estações, para manusear os dados de maneira adequada.|  ✅      |
| 4   |   1   |   Alta     |      3     | Como Administrador, quero que o sistema tenha um serviço de recepção de dados a cada periodo de tempo, para que múltiplas estações enviem informações sem perda.|   ✅     |
| 5    |   1   |    Alta     |    5       | Como Administrador, quero um CRUD para os tipos de alertas para condições meteorológicas, para gerar notificações com base em informações meteorológicas.|   ✅     |
| 6   |   1   |   Alta      |     8      | Como Administrador, quero processar e armazenar automaticamente os dados recebidos por meio de um datalogger, para utilização destes no Dashboard|   ✅     |
| 7   |   1   |  Alta   |      8     | Como Cliente, quero que o sistema tenha um modelo dinâmico que seja capaz de receber e registrar diversas estações com sensores diferentes, para a possibilidade de receber os dados de diversas fontes.|  ✅      |
| 8    |   1   |    Alta      |     5      | Como Administrador, quero um CRUD para os usuários da aplicação, para melhor gerênciamento de acesso.|   ✅     |
| 9    |   2   |    Média    |      8     | Como Usuário Público, quero que seja possível receber alertas relevantes, para que eu saiba quando condições perigosas ocorrerem.|  ✅    |
| 10    |   2   |    Média     |    3       | Como Cliente, quero um controle de acesso que diferencie as permissões do Administrador e do Usuário Público, para que tenha segurança no gerênciamento de informações do sistema.| ✅    |
| 11    |   2   |   Média   |      3     | Como Usuário Público, quero acessar um Dashboard de informações, para que eu compreenda os dados meteorológicos facilmente.|  ✅  |
| 12    |  2   |    Média    |     5      | Como Administrador, quero poder editar as informações exibidas no Dashboard, para dados de minha escolha.|  ✅  |
| 13    |  2   |    Média    |    3       | Como Administrador, quero gerar relatórios detalhados em forma de gráfico no Dashboard, para que seja possível a geração de insights.| ✅   |
| 14   |   2   |    Média    |      3      | Como Administrador, quero consultar o histórico de alertas gerados. Para que eu entenda os padrões de ocorrências.| ✅  |
| 15   |   3   |    Baixa    |      3     | Como Usuário, eu quero visualizar conceitos estatísticos nos dashboards, para análises mais precisas.|  ✅  |
| 16    |  3   |    Baixa    |      2     | Como Usuário Público, quero acessar uma planilha de relatório em CSV, para que eu possa utilizar como fonte de dados.|    ✅  |
| 17   |   3   |    Baixa    |      2     | Como Usuário Público, quero acessar um guia explicativo sobre cada parâmetro meteorológico, incluindo as fórmulas utilizadas, para que eu aprenda o que significam os dados coletados.|    ✅   |
| 18   |   3   |   Baixa    |      8     | Como Cliente, quero uma estação meteorológica física montada com sensores, para que os dados sejam coletados em tempo real e enviados ao sistema.|   ✅   |




---

## 📝 Sprint Backlog <a name="backsprint"><a>

| Sprint | Backlog da Sprint |
|:------:|:-----------------:|
| 1 | [Ver Sprint Backlog](https://github.com/Equipe-Skyfall/skytrack/blob/main/docs/Sprint%201/Backlog_sprint1.MD)|
| 2 | [Ver Sprint Backlog](https://github.com/Equipe-Skyfall/skytrack/blob/main/docs/Sprint%202/Backlog_sprint2.MD)|
| 3 | [Ver Sprint Backlog](https://github.com/Equipe-Skyfall/skytrack/blob/main/docs/Sprint%203/Backlog_sprint3.md)|
---

## Links Úteis <a name="links"><a>

- [Arquitetura do Projeto](https://github.com/Equipe-Skyfall/skytrack/blob/main/dev-docs/Arquitetura%20do%20Projeto.pdf)
- [Modelo de Entidade e Relacionamento](https://github.com/Equipe-Skyfall/skytrack/blob/main/dev-docs/Modelo-Entidade-Relacionamento.png)
- [WireFrame](https://github.com/Equipe-Skyfall/skytrack/blob/main/dev-docs/Wireframe-Skytrack.pdf)
- [Product Backlog e Requisitos](https://github.com/Equipe-Skyfall/skytrack/blob/main/dev-docs/Product%20Backlog%20e%20Requisitos-2.pdf)


---

## 👥 Equipe <a name="equipe"><a>
|  Foto        |     Função    |           Nome            |                            LinkedIn                            |                      GitHub                       |
| :----: | :-----------: | :-----------------------: | :------------------------------------------------------------: | :-----------------------------------------------: |
| <img src="https://avatars.githubusercontent.com/u/160733714?v=4" width="75px"> | Product Owner  | Eduardo da Silva Fontes | [Linkedin](https://www.linkedin.com/in/eduardo-da-silva-fontes/)  | [GitHub](https://github.com/DuuhZero)           |
| <img src="https://avatars.githubusercontent.com/u/162118889?v=4" width="75px"> | Dev Team | Eduardo Kuwahara Jr. |  [Linkedin](https://www.linkedin.com/in/eduardo-kuwahara-3b2267303/)  | [GitHub](https://github.com/EduardoKuwahara) |
| <img src="https://avatars.githubusercontent.com/u/161594793?v=4" width="75px"> | Dev Team      | Eric Kawata |  [Linkedin](https://www.linkedin.com/in/eric-kawata-99678b302/)  | [GitHub](https://github.com/ericFatec)    |
| <img src="https://avatars.githubusercontent.com/u/144804717?v=4" width="75px"> | Dev Team      | Fábio Hiroshi |  [Linkedin](https://www.linkedin.com/in/f%C3%A1bio-hiroshi-5393a51a0)  | [GitHub](https://github.com/FabioHiros)    |
| <img src="https://avatars.githubusercontent.com/u/119539664?v=4" width="75px">|Dev Team| João Pedro França Alves de Souza |  [Linkedin](https://www.linkedin.com/in/joão-pedro-frança-alves-de-souza-8700a62b3/)  | [GitHub](https://github.com/jofran2001)  |
| <img src="https://avatars.githubusercontent.com/u/162117916?v=4" width="75px"> | Dev Team  | João Vitor Rossi Ferreira |  [Linkedin](https://www.linkedin.com/in/joão-rossi-7311a0301/)  | [GitHub](https://github.com/joaorossiferreira)    |
| <img src="https://avatars.githubusercontent.com/u/95691713?v=4" width="75px"> | Dev Team      | Kathellyn Caroline Alves dos Santos |  [Linkedin](https://www.linkedin.com/in/kathellyn-caroline-a562101b9)  | [GitHub](https://github.com/CarolineKathellyn)    |
| <img src="https://avatars.githubusercontent.com/u/162117908?v=4" width="75px"> | Scrum Master      | Paulo Henrique Martins de Almeida |  [Linkedin](https://www.linkedin.com/in/paulo-almeida-3102452a7/)  | [GitHub](https://github.com/pauloalmeida46)    |
| <img src="https://avatars.githubusercontent.com/u/161987258?v=4" width="75px"> | Dev Team      | Victor Daniel |  [Linkedin](https://www.linkedin.com/in/victor-daniel-ramos-bessa-1436a3215/)  | [GitHub](https://github.com/victordanielrb)    |


