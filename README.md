# FATEC Profº Jessen Vidal - São José dos Campos - 5º Semestre DSM - 2026

<p>Projeto desenvolvido para a API (Aprendizagem por Projeto Integrado) do 5° Semestre do curso Desenvolvimento de Software Multiplataforma (DSM) em parceria com a Xertica.</p>

> _A API se trata de um projeto submetido à metodologia de ensino em implantação na Fatec São José dos Campos, do qual os alunos formam equipes baseadas na metodologia ágil SCRUM, tendo um aluno como Scrum Master, um sendo o Product Owner e o restante dos integrantes como Dev Team._

<img src="https://github.com/Equipe-Skyfall/themis/blob/main/docs/c1953f4d-96e9-4539-a7be-647771145366.jpg">

---

### 📃 Repositórios
- [Repositório App](https://github.com/Equipe-Skyfall/themis-app)
- [Repositório BackEnd](https://github.com/Equipe-Skyfall/themis-back)
- [Repositório BD](https://github.com/Equipe-Skyfall/themis-db)

---

## 📑 Sumário
- [Visão do Projeto](#visao-do-projeto)
- [Dores do Cliente](#dores)
- [Cronograma do Projeto](#cronograma)
- [Tecnologias utilizadas](#tecnologias)
- [Padrões de Commit](#padrao)
- [Requisitos](#requisitos)
- [Arquitetura](#arquitetura)
- [Wireframes](#wireframes)
- [Definition of Ready (DoR)](#dor)
- [Definition of Done (DoD)](#dod)
- [Product Backlog](#backlog)
- [Sprint Backlog](#backsprint)
- [Links úteis](#links)
- [Equipe](#equipe)

---

## 🏥 Dores do Cliente <a name="dores"></a>

### Verificar

Problemas relacionados à identificação e compreensão de precedentes jurídicos:

- Grande volume de decisões judiciais espalhadas entre diversos tribunais.
- Dificuldade em encontrar rapidamente precedentes realmente relevantes para um caso específico.
- Necessidade de ler diversas decisões completas para identificar informações importantes.
- Falta de uma análise automática que indique a similaridade entre casos.
- Ausência de um resumo objetivo que facilite a compreensão inicial do precedente.

### Planejar

Problemas relacionados ao planejamento de estratégias jurídicas:

- Dificuldade em identificar precedentes fortes para fundamentar petições.
- Tempo elevado gasto na pesquisa jurídica.
- Incerteza sobre quais decisões possuem maior probabilidade de aplicabilidade ao caso.
- Falta de ferramentas que ajudem a estruturar rapidamente argumentos jurídicos baseados em jurisprudência.
- Dificuldade em avaliar a relevância estratégica de um precedente para um processo.

### Controlar

Problemas relacionados à organização e gestão da informação jurídica:

- Falta de centralização das informações sobre precedentes.
- Dificuldade em acompanhar o status atual de decisões judiciais (vigência, trânsito em julgado, etc.).
- Falta de indicadores claros que ajudem a priorizar precedentes mais relevantes.
- Falta de ferramentas que organizem automaticamente as informações jurídicas encontradas.
- Risco de utilizar precedentes inadequados ou pouco relevantes por falta de análise sistemática.

---

## 👁 Visão do Projeto <a name="visao-do-projeto"></a>

Nosso projeto consiste em uma plataforma inteligente de análise jurídica em nuvem que utiliza aprendizado de máquina e processamento de linguagem natural para analisar petições iniciais e identificar precedentes judiciais relevantes. O sistema gera um resumo do caso, consulta bases nacionais de precedentes e apresenta decisões potencialmente aplicáveis com informações estruturadas, percentual de similaridade e classificação de aplicabilidade. A solução será acessada por meio de um aplicativo móvel com interface intuitiva, auxiliando profissionais do Direito a encontrar precedentes relevantes com mais rapidez e precisão.

---

## Cronograma de Sprints <a name="cronograma"></a>

| Sprint | Período | Status | Relatório |
|:------:|:-------:|:------:|:---------:|
| 1 | 16/03/2026 à 05/04/2026 | Não Concluído | [Ver Relatório](https://github.com/Equipe-Skyfall/skytrack/blob/main/docs/Sprint%201) |
| 2 | 13/04/2026 à 03/05/2026 | Não Concluído | [Ver Relatório](https://github.com/Equipe-Skyfall/skytrack/blob/main/docs/Sprint%202) |
| 3 | 11/05/2026 à 31/05/2026 | Não Concluído | [Ver Relatório](https://github.com/Equipe-Skyfall/skytrack/tree/main/docs/Sprint%203) |

---

## 💻 Tecnologias utilizadas <a name="tecnologias"></a>

| Tecnologia | Finalidade |
|:----------:|------------|
| <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter"> | Desenvolvimento do aplicativo mobile (iOS e Android) |
| <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"> | Processamento de linguagem natural e lógica de análise jurídica |
| <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"> | API REST para comunicação entre o app e o backend |
| <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"> | Banco de dados para armazenamento de petições, precedentes e histórico |
| <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" alt="Figma"> | Design de interfaces e prototipação dos wireframes |
| <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"> | Empacotamento e orquestração da aplicação via containers (Docker Swarm) |

---

### 📃 Estrutura de Branches
- **Main** — Estado principal que armazena a versão estável do projeto
- **Dev** — Estado de desenvolvimento atual
- **Sprint X** — Instância de todos os repositórios ao fim da Sprint X

### ⏳ Status do projeto: 0/3 Sprints

---

## 💻 Padrões de Commit <a name="padrao"></a>

**FEAT**: Adiciona um novo recurso ou funcionalidade.
> Exemplo: `FEAT - Adição da navbar`

**FIX**: Corrige um bug.
> Exemplo: `FIX - Corrige o modal que não estava fechando`

**CHORE**: Atualizações de manutenção que não alteram a lógica de negócio ou visual.
> Exemplo: `CHORE - Atualização das dependências do Node.js`

**DOCS**: Altera a documentação.
> Exemplo: `DOCS - Atualiza README com informações sobre novas rotas`

**STYLE**: Modifica a formatação do código sem alterar a lógica.
> Exemplo: `STYLE - Adiciona comentários no código para facilitar a leitura`

**REFACTOR**: Refatora o código sem adicionar funcionalidades ou corrigir bugs.
> Exemplo: `REFACTOR - Refatora o código, deixando-o mais leve`

**TEST**: Adiciona, modifica ou remove testes.
> Exemplo: `TEST - Adiciona teste para o componente de login`

**PERF**: Melhora a performance.
> Exemplo: `PERF - Otimiza a execução de consultas no banco de dados`

**BUILD**: Altera o sistema de build ou dependências externas.
> Exemplo: `BUILD - Adiciona um Dockerfile para o ambiente de produção`

**REVERT**: Reverte um commit anterior.
> Exemplo: `REVERT - Reverte a adição de autenticação de middleware`

**HOTFIX**: Corrige um bug crítico em produção de forma urgente.
> Exemplo: `HOTFIX - Corrige vulnerabilidade crítica na autenticação de usuários`

> **Nomenclatura de variáveis:** padrão `camelCase` (ex: `nomeCompleto`).

---

## 📋 Requisitos <a name="requisitos"></a>

### Requisitos Funcionais

| RF | Nome | Descritivo |
|----|------|------------|
| RF1 | Upload de petição inicial | O sistema deve permitir que o usuário envie uma petição inicial em formato PDF para análise automática. |
| RF2 | Processamento do texto | O sistema deve analisar automaticamente o conteúdo textual da petição para identificar as informações jurídicas relevantes. |
| RF3 | Consulta à base de precedentes | O sistema deve consultar automaticamente a base própria de precedentes jurídicos já indexada para identificar decisões relacionadas ao caso analisado. |
| RF4 | Identificação de precedentes relacionados | O sistema deve identificar os precedentes mais relacionados ao caso com base no conteúdo da petição enviada. |
| RF5 | Classificação de aplicabilidade | O sistema deve calcular a similaridade entre a petição e cada precedente encontrado e classificá-los como "Aplicável", "Possivelmente aplicável" ou "Não aplicável". |
| RF6 | Exibição de dados estruturados | O sistema deve apresentar as informações de cada precedente, incluindo tribunal de origem, tema, enunciado, status e tese firmada quando disponível. |
| RF7 | Síntese explicativa | O sistema deve gerar uma explicação resumida que indique a relação entre o precedente identificado e o caso analisado. |
| RF8 | Geração de resumo | O sistema deve gerar um resumo automático da petição e apresentá-lo na tela de resultados, destacando as principais informações do caso. |
 

### Requisitos Não Funcionais

| RNF | Nome | Descritivo |
|-----|------|------------|
| RNF1 | Manual de Instalação | Documentação de instalação disponível no repositório do projeto. |
| RNF2 | Manual do Usuário | Documentação orientada ao usuário final explicando como utilizar as funcionalidades do sistema. |
| RNF3 | Documentação de APIs | Elaboração detalhada da documentação para todas as rotas da API, incluindo exemplos de uso. |
| RNF4 | Integração Contínua (CI) | Implementação de um processo automático de testes e validações a cada atualização do sistema. |
| RNF5 | Ambiente de Execução | A aplicação deve ser empacotada com Docker e disponibilizada via Swarm para facilitar a execução e a publicação do sistema. |

---

## 🏗 Arquitetura <a name="arquitetura"></a>

<img src="docs/themis_architecture.png" alt="Arquitetura do sistema Themis" width="800">

---

## 🖥 Wireframes <a name="wireframes"></a>

<table>
  <tr>
    <td align="center" valign="top"><strong>Página Principal</strong><br><img src="docs/Página Principal.png" alt="Wireframe - Página Principal" width="280"></td>
    <td align="center" valign="top"><strong>Cadastro</strong><br><img src="docs/Cadastro.png" alt="Wireframe - Cadastro" width="280"></td>
    <td align="center" valign="top"><strong>Nova Análise</strong><br><img src="docs/Nova Análise.png" alt="Wireframe - Nova Análise" width="280"></td>
  </tr>
  <tr>
    <td align="center" valign="top"><strong>Resultados</strong><br><img src="docs/Resultados.png" alt="Wireframe - Resultados" width="280"></td>
    <td align="center" valign="top"><strong>Resultado (Modal)</strong><br><img src="docs/Resultado (Modal).png" alt="Wireframe - Resultado (Modal)" width="280"></td>
    <td align="center" valign="top"><strong>Página do Usuário</strong><br><img src="docs/Página do Usuário.png" alt="Wireframe - Página do Usuário" width="280"></td>
  </tr>
</table>

---

## ✅ Definition of Ready (DoR) <a name="dor"></a>

Uma User Story está pronta para entrar em uma Sprint quando:

- [ ] A User Story está escrita no formato acordado ("Como... quero... para que...")
- [ ] Os critérios de aceitação estão claramente definidos
- [ ] A história foi estimada em story points pelo time
- [ ] As dependências foram identificadas
- [ ] Wireframes/mockups estão disponíveis (quando aplicável)
- [ ] O time compreende a abordagem técnica necessária

---

## ✅ Definition of Done (DoD) <a name="dod"></a>

Uma User Story é considerada concluída quando:

- [ ] A funcionalidade foi implementada conforme os critérios de aceitação
- [ ] O código foi revisado via Pull Request e aprovado
- [ ] O código foi mergeado na branch `dev`
- [ ] O pipeline de CI está passando
- [ ] Testes manuais foram realizados e validados
- [ ] Nenhum bug crítico foi introduzido
- [ ] A documentação foi atualizada, se aplicável (docs de API, README)

---
## 📜 Product Backlog <a name="backlog"></a>

| RANK | SPRINT | PRIORIDADE | ESTIMATIVA | USER STORY | RF | STATUS |
|:----:|:------:|:----------:|:----------:|------------|----|:------:|
| 1 | 1 | Alta | 5 | Como juiz, quero enviar uma petição inicial em PDF pelo aplicativo, para que o sistema possa analisá-la automaticamente. | RF1 | 🔲 |
| 2 | 1 | Alta | 8 | Como juiz, quero que o sistema identifique automaticamente as informações jurídicas relevantes da petição enviada, para que os precedentes encontrados sejam precisos. | RF2 | 🔲 |
| 3 | 1 | Alta | 8 | Como juiz, quero visualizar uma lista de precedentes da base jurídica relacionados ao caso, para que eu identifique rapidamente as decisões mais próximas. | RF3, RF4 | 🔲 |
| 4 | 1 | Alta | 5 | Como juiz, quero ver a classificação de aplicabilidade de cada precedente — Aplicável, Possivelmente aplicável ou Não aplicável —, para que eu saiba quais merecem atenção prioritária. | RF5 | 🔲 |
| 5 | 1 | Alta | 3 | Como juiz, quero ver o percentual de similaridade de cada precedente em relação ao caso, para que eu compreenda o grau de proximidade entre as decisões. | RF5 | 🔲 |
| 6 | 1 | Alta | 5 | Como juiz, quero visualizar as informações detalhadas de cada precedente — tribunal, tema, enunciado e status —, para que eu avalie sua aplicabilidade com precisão. | RF6 | 🔲 |
| 7 | 1 | Alta | 3 | Como juiz, quero que a tese firmada de um precedente seja exibida quando disponível, para que eu tenha acesso à posição consolidada sobre o tema. | RF6 | 🔲 |
| 8 | 2 | Média | 8 | Como juiz, quero que o sistema gere automaticamente um resumo da petição recebida, para que eu compreenda os pontos centrais do caso sem precisar ler o documento completo. | RF8 | 🔲 |
| 10 | 2 | Média | 8 | Como juiz, quero ler uma explicação sobre por que cada precedente se relaciona ao caso analisado, para que eu compreenda a conexão jurídica sem pesquisa adicional. | RF7 | 🔲 |
| 12 | 3 | Baixa | 5 | Como juiz, quero acessar o histórico das petições que já analisei, para que eu revise resultados anteriores sem precisar enviar o documento novamente. | — | 🔲 |
| 13 | 3 | Baixa | 5 | Como juiz, quero exportar o relatório de análise em PDF, para que eu arquive ou compartilhe os resultados com outros membros do processo. | — | 🔲 |

---

## 📝 Sprint Backlog <a name="backsprint"></a>

<details>
<summary><strong>Sprint 1 — Upload, Processamento e Comparação de Precedentes</strong></summary>

<br>

> **Período:** 16/03/2026 à 05/04/2026
> **Foco:** Estrutura base do sistema — o juiz envia a petição, o sistema identifica informações jurídicas relevantes, consulta a base de precedentes e retorna os resultados com classificação de aplicabilidade.

---

#### US01 — Envio de petição inicial em PDF

**User Story:** Como juiz, quero enviar uma petição inicial em PDF pelo aplicativo, para que o sistema possa analisá-la automaticamente.

**RF:** RF1 | **Prioridade:** Alta | **Estimativa:** 5 | **Status:** 🔲

**Definition of Ready (DoR)**
- [ ] User Story completa: requisitos descritos em formato de User Story e planejados para caber na sprint
- [ ] Tarefas detalhadas e atribuídas: ao menos uma task detalhada e atribuída a um responsável
- [ ] Critérios de aceitação definidos: critérios bem estabelecidos para validação da entrega
- [ ] Estimativa definida: esforço estimado pelo time (5 pts)
- [ ] Wireframe/Mockup aprovado: protótipo da tela de upload validado pelo cliente
- [ ] Modelo de dados finalizado: estrutura de dados definida e documentada
- [ ] Ambiente de desenvolvimento pronto: time com acesso a todos os ambientes, ferramentas e permissões necessárias

**Definition of Done (DoD)**
- [ ] Critérios de aceitação validados: todos os critérios foram atendidos e verificados
- [ ] Código-fonte completo e padronizado: 100% implementado, refatorado e seguindo os padrões de qualidade definidos
- [ ] Commits organizados e documentados: seguindo a nomenclatura acordada, segmentados e com histórico claro
- [ ] Guia de instalação detalhado: documentação clara e completa para configurar e executar a aplicação
- [ ] Manual do usuário disponível: manual criado para orientar o cliente sobre o funcionamento da funcionalidade

---

#### US02 — Identificação automática de informações jurídicas

**User Story:** Como juiz, quero que o sistema identifique automaticamente as informações jurídicas relevantes da petição enviada, para que os precedentes encontrados sejam precisos.

**RF:** RF2 | **Prioridade:** Alta | **Estimativa:** 8 | **Status:** 🔲

**Definition of Ready (DoR)**
- [ ] User Story completa: requisitos descritos em formato de User Story e planejados para caber na sprint
- [ ] Tarefas detalhadas e atribuídas: ao menos uma task detalhada e atribuída a um responsável
- [ ] Critérios de aceitação definidos: critérios bem estabelecidos para validação da entrega
- [ ] Estimativa definida: esforço estimado pelo time (8 pts)
- [ ] Wireframe/Mockup aprovado: protótipo validado pelo cliente (quando aplicável)
- [ ] Modelo de dados finalizado: estrutura de dados definida e documentada
- [ ] Ambiente de desenvolvimento pronto: time com acesso a todos os ambientes, ferramentas e permissões necessárias

**Definition of Done (DoD)**
- [ ] Critérios de aceitação validados: todos os critérios foram atendidos e verificados
- [ ] Código-fonte completo e padronizado: 100% implementado, refatorado e seguindo os padrões de qualidade definidos
- [ ] Commits organizados e documentados: seguindo a nomenclatura acordada, segmentados e com histórico claro
- [ ] Guia de instalação detalhado: documentação clara e completa para configurar e executar a aplicação
- [ ] Manual do usuário disponível: manual criado para orientar o cliente sobre o funcionamento da funcionalidade

---

#### US03 — Visualização de lista de precedentes relacionados

**User Story:** Como juiz, quero visualizar uma lista de precedentes da base jurídica relacionados ao caso, para que eu identifique rapidamente as decisões mais próximas.

**RF:** RF3, RF4 | **Prioridade:** Alta | **Estimativa:** 8 | **Status:** 🔲

**Definition of Ready (DoR)**
- [ ] User Story completa: requisitos descritos em formato de User Story e planejados para caber na sprint
- [ ] Tarefas detalhadas e atribuídas: ao menos uma task detalhada e atribuída a um responsável
- [ ] Critérios de aceitação definidos: critérios bem estabelecidos para validação da entrega
- [ ] Estimativa definida: esforço estimado pelo time (8 pts)
- [ ] Wireframe/Mockup aprovado: protótipo da tela de resultados validado pelo cliente
- [ ] Modelo de dados finalizado: estrutura de dados definida e documentada
- [ ] Ambiente de desenvolvimento pronto: time com acesso a todos os ambientes, ferramentas e permissões necessárias

**Definition of Done (DoD)**
- [ ] Critérios de aceitação validados: todos os critérios foram atendidos e verificados
- [ ] Código-fonte completo e padronizado: 100% implementado, refatorado e seguindo os padrões de qualidade definidos
- [ ] Commits organizados e documentados: seguindo a nomenclatura acordada, segmentados e com histórico claro
- [ ] Guia de instalação detalhado: documentação clara e completa para configurar e executar a aplicação
- [ ] Manual do usuário disponível: manual criado para orientar o cliente sobre o funcionamento da funcionalidade

---

#### US04 — Classificação de aplicabilidade dos precedentes

**User Story:** Como juiz, quero ver a classificação de aplicabilidade de cada precedente — Aplicável, Possivelmente aplicável ou Não aplicável —, para que eu saiba quais merecem atenção prioritária.

**RF:** RF5 | **Prioridade:** Alta | **Estimativa:** 5 | **Status:** 🔲

**Definition of Ready (DoR)**
- [ ] User Story completa: requisitos descritos em formato de User Story e planejados para caber na sprint
- [ ] Tarefas detalhadas e atribuídas: ao menos uma task detalhada e atribuída a um responsável
- [ ] Critérios de aceitação definidos: critérios bem estabelecidos para validação da entrega
- [ ] Estimativa definida: esforço estimado pelo time (5 pts)
- [ ] Wireframe/Mockup aprovado: protótipo com representação visual das categorias validado pelo cliente
- [ ] Modelo de dados finalizado: estrutura de dados definida e documentada
- [ ] Ambiente de desenvolvimento pronto: time com acesso a todos os ambientes, ferramentas e permissões necessárias

**Definition of Done (DoD)**
- [ ] Critérios de aceitação validados: todos os critérios foram atendidos e verificados
- [ ] Código-fonte completo e padronizado: 100% implementado, refatorado e seguindo os padrões de qualidade definidos
- [ ] Commits organizados e documentados: seguindo a nomenclatura acordada, segmentados e com histórico claro
- [ ] Guia de instalação detalhado: documentação clara e completa para configurar e executar a aplicação
- [ ] Manual do usuário disponível: manual criado para orientar o cliente sobre o funcionamento da funcionalidade

</details>

---

<details>
<summary><strong>Sprint 2 — Resumo e Síntese Explicativa</strong></summary>

<br>

> **Período:** 13/04/2026 à 03/05/2026
> **Foco:** Geração automática de resumo da petição e síntese explicativa por precedente.

---

#### US05 — Percentual de similaridade por precedente

**User Story:** Como juiz, quero ver o percentual de similaridade de cada precedente em relação ao caso, para que eu compreenda o grau de proximidade entre as decisões.

**RF:** RF5 | **Prioridade:** Alta | **Estimativa:** 3 | **Status:** 🔲

**Definition of Ready (DoR)**
- [ ] User Story completa: requisitos descritos em formato de User Story e planejados para caber na sprint
- [ ] Tarefas detalhadas e atribuídas: ao menos uma task detalhada e atribuída a um responsável
- [ ] Critérios de aceitação definidos: critérios bem estabelecidos para validação da entrega
- [ ] Estimativa definida: esforço estimado pelo time (3 pts)
- [ ] Wireframe/Mockup aprovado: protótipo validado pelo cliente (quando aplicável)
- [ ] Modelo de dados finalizado: estrutura de dados definida e documentada
- [ ] Ambiente de desenvolvimento pronto: time com acesso a todos os ambientes, ferramentas e permissões necessárias

**Definition of Done (DoD)**
- [ ] Critérios de aceitação validados: todos os critérios foram atendidos e verificados
- [ ] Código-fonte completo e padronizado: 100% implementado, refatorado e seguindo os padrões de qualidade definidos
- [ ] Commits organizados e documentados: seguindo a nomenclatura acordada, segmentados e com histórico claro
- [ ] Guia de instalação detalhado: documentação clara e completa para configurar e executar a aplicação
- [ ] Manual do usuário disponível: manual criado para orientar o cliente sobre o funcionamento da funcionalidade

---

#### US06 — Informações detalhadas do precedente

**User Story:** Como juiz, quero visualizar as informações detalhadas de cada precedente — tribunal, tema, enunciado e status —, para que eu avalie sua aplicabilidade com precisão.

**RF:** RF6 | **Prioridade:** Alta | **Estimativa:** 5 | **Status:** 🔲

**Definition of Ready (DoR)**
- [ ] User Story completa: requisitos descritos em formato de User Story e planejados para caber na sprint
- [ ] Tarefas detalhadas e atribuídas: ao menos uma task detalhada e atribuída a um responsável
- [ ] Critérios de aceitação definidos: critérios bem estabelecidos para validação da entrega
- [ ] Estimativa definida: esforço estimado pelo time (5 pts)
- [ ] Wireframe/Mockup aprovado: protótipo da tela de detalhe do precedente validado pelo cliente
- [ ] Modelo de dados finalizado: estrutura de dados definida e documentada
- [ ] Ambiente de desenvolvimento pronto: time com acesso a todos os ambientes, ferramentas e permissões necessárias

**Definition of Done (DoD)**
- [ ] Critérios de aceitação validados: todos os critérios foram atendidos e verificados
- [ ] Código-fonte completo e padronizado: 100% implementado, refatorado e seguindo os padrões de qualidade definidos
- [ ] Commits organizados e documentados: seguindo a nomenclatura acordada, segmentados e com histórico claro
- [ ] Guia de instalação detalhado: documentação clara e completa para configurar e executar a aplicação
- [ ] Manual do usuário disponível: manual criado para orientar o cliente sobre o funcionamento da funcionalidade

---

#### US07 — Exibição da tese firmada quando disponível

**User Story:** Como juiz, quero que a tese firmada de um precedente seja exibida quando disponível, para que eu tenha acesso à posição consolidada sobre o tema.

**RF:** RF6 | **Prioridade:** Alta | **Estimativa:** 3 | **Status:** 🔲

**Definition of Ready (DoR)**
- [ ] User Story completa: requisitos descritos em formato de User Story e planejados para caber na sprint
- [ ] Tarefas detalhadas e atribuídas: ao menos uma task detalhada e atribuída a um responsável
- [ ] Critérios de aceitação definidos: critérios bem estabelecidos para validação da entrega
- [ ] Estimativa definida: esforço estimado pelo time (3 pts)
- [ ] Wireframe/Mockup aprovado: protótipo validado pelo cliente (quando aplicável)
- [ ] Modelo de dados finalizado: estrutura de dados definida e documentada
- [ ] Ambiente de desenvolvimento pronto: time com acesso a todos os ambientes, ferramentas e permissões necessárias

**Definition of Done (DoD)**
- [ ] Critérios de aceitação validados: todos os critérios foram atendidos e verificados
- [ ] Código-fonte completo e padronizado: 100% implementado, refatorado e seguindo os padrões de qualidade definidos
- [ ] Commits organizados e documentados: seguindo a nomenclatura acordada, segmentados e com histórico claro
- [ ] Guia de instalação detalhado: documentação clara e completa para configurar e executar a aplicação
- [ ] Manual do usuário disponível: manual criado para orientar o cliente sobre o funcionamento da funcionalidade

---

#### US08 — Resumo automático da petição

**User Story:** Como juiz, quero que o sistema gere automaticamente um resumo da petição recebida, para que eu compreenda os pontos centrais do caso sem precisar ler o documento completo.

**RF:** RF8 | **Prioridade:** Média | **Estimativa:** 8 | **Status:** 🔲

**Definition of Ready (DoR)**
- [ ] User Story completa: requisitos descritos em formato de User Story e planejados para caber na sprint
- [ ] Tarefas detalhadas e atribuídas: ao menos uma task detalhada e atribuída a um responsável
- [ ] Critérios de aceitação definidos: critérios bem estabelecidos para validação da entrega
- [ ] Estimativa definida: esforço estimado pelo time (8 pts)
- [ ] Wireframe/Mockup aprovado: protótipo da seção de resumo na tela de resultados validado pelo cliente
- [ ] Modelo de dados finalizado: estrutura de dados definida e documentada
- [ ] Ambiente de desenvolvimento pronto: time com acesso a todos os ambientes, ferramentas e permissões necessárias

**Definition of Done (DoD)**
- [ ] Critérios de aceitação validados: todos os critérios foram atendidos e verificados
- [ ] Código-fonte completo e padronizado: 100% implementado, refatorado e seguindo os padrões de qualidade definidos
- [ ] Commits organizados e documentados: seguindo a nomenclatura acordada, segmentados e com histórico claro
- [ ] Guia de instalação detalhado: documentação clara e completa para configurar e executar a aplicação
- [ ] Manual do usuário disponível: manual criado para orientar o cliente sobre o funcionamento da funcionalidade

</details>

---

<details>
<summary><strong>Sprint 3 — Histórico e Exportação</strong></summary>

<br>

> **Período:** 11/05/2026 à 31/05/2026
> **Foco:** Completar a experiência do usuário com histórico de análises e exportação de relatórios.

---

#### US09 — Síntese explicativa por precedente

**User Story:** Como juiz, quero ler uma explicação sobre por que cada precedente se relaciona ao caso analisado, para que eu compreenda a conexão jurídica sem pesquisa adicional.

**RF:** RF7 | **Prioridade:** Média | **Estimativa:** 8 | **Status:** 🔲

**Definition of Ready (DoR)**
- [ ] User Story completa: requisitos descritos em formato de User Story e planejados para caber na sprint
- [ ] Tarefas detalhadas e atribuídas: ao menos uma task detalhada e atribuída a um responsável
- [ ] Critérios de aceitação definidos: critérios bem estabelecidos para validação da entrega
- [ ] Estimativa definida: esforço estimado pelo time (8 pts)
- [ ] Wireframe/Mockup aprovado: protótipo da exibição da síntese por precedente validado pelo cliente
- [ ] Modelo de dados finalizado: estrutura de dados definida e documentada
- [ ] Ambiente de desenvolvimento pronto: time com acesso a todos os ambientes, ferramentas e permissões necessárias

**Definition of Done (DoD)**
- [ ] Critérios de aceitação validados: todos os critérios foram atendidos e verificados
- [ ] Código-fonte completo e padronizado: 100% implementado, refatorado e seguindo os padrões de qualidade definidos
- [ ] Commits organizados e documentados: seguindo a nomenclatura acordada, segmentados e com histórico claro
- [ ] Guia de instalação detalhado: documentação clara e completa para configurar e executar a aplicação
- [ ] Manual do usuário disponível: manual criado para orientar o cliente sobre o funcionamento da funcionalidade

---

#### US10 — Histórico de petições analisadas

**User Story:** Como juiz, quero acessar o histórico das petições que já analisei, para que eu revise resultados anteriores sem precisar enviar o documento novamente.

**RF:** — | **Prioridade:** Baixa | **Estimativa:** 5 | **Status:** 🔲

**Definition of Ready (DoR)**
- [ ] User Story completa: requisitos descritos em formato de User Story e planejados para caber na sprint
- [ ] Tarefas detalhadas e atribuídas: ao menos uma task detalhada e atribuída a um responsável
- [ ] Critérios de aceitação definidos: critérios bem estabelecidos para validação da entrega
- [ ] Estimativa definida: esforço estimado pelo time (5 pts)
- [ ] Wireframe/Mockup aprovado: protótipo da tela de histórico validado pelo cliente
- [ ] Modelo de dados finalizado: estrutura de dados definida e documentada
- [ ] Ambiente de desenvolvimento pronto: time com acesso a todos os ambientes, ferramentas e permissões necessárias

**Definition of Done (DoD)**
- [ ] Critérios de aceitação validados: todos os critérios foram atendidos e verificados
- [ ] Código-fonte completo e padronizado: 100% implementado, refatorado e seguindo os padrões de qualidade definidos
- [ ] Commits organizados e documentados: seguindo a nomenclatura acordada, segmentados e com histórico claro
- [ ] Guia de instalação detalhado: documentação clara e completa para configurar e executar a aplicação
- [ ] Manual do usuário disponível: manual criado para orientar o cliente sobre o funcionamento da funcionalidade

---

#### US11 — Exportação do relatório em PDF

**User Story:** Como juiz, quero exportar o relatório de análise em PDF, para que eu arquive ou compartilhe os resultados com outros membros do processo.

**RF:** — | **Prioridade:** Baixa | **Estimativa:** 5 | **Status:** 🔲

**Definition of Ready (DoR)**
- [ ] User Story completa: requisitos descritos em formato de User Story e planejados para caber na sprint
- [ ] Tarefas detalhadas e atribuídas: ao menos uma task detalhada e atribuída a um responsável
- [ ] Critérios de aceitação definidos: critérios bem estabelecidos para validação da entrega
- [ ] Estimativa definida: esforço estimado pelo time (5 pts)
- [ ] Wireframe/Mockup aprovado: protótipo do relatório PDF validado pelo cliente
- [ ] Modelo de dados finalizado: estrutura de dados definida e documentada
- [ ] Ambiente de desenvolvimento pronto: time com acesso a todos os ambientes, ferramentas e permissões necessárias

**Definition of Done (DoD)**
- [ ] Critérios de aceitação validados: todos os critérios foram atendidos e verificados
- [ ] Código-fonte completo e padronizado: 100% implementado, refatorado e seguindo os padrões de qualidade definidos
- [ ] Commits organizados e documentados: seguindo a nomenclatura acordada, segmentados e com histórico claro
- [ ] Guia de instalação detalhado: documentação clara e completa para configurar e executar a aplicação
- [ ] Manual do usuário disponível: manual criado para orientar o cliente sobre o funcionamento da funcionalidade

</details>

---
## Links Úteis <a name="links"></a>

- [Base de Precedentes Pangea](https://pangeabnp.pdpj.jus.br/)
- [O que é um precedente jurídico?](https://www.jusbrasil.com.br/artigos/afinal-o-que-e-um-precedente/1889550599)

---

## 👥 Equipe <a name="equipe"></a>

| Foto | Função | Nome | LinkedIn | GitHub |
|:----:|:------:|:----:|:--------:|:------:|
| <img src="https://avatars.githubusercontent.com/u/160733714?v=4" width="75px"> | Product Owner | Eduardo da Silva Fontes | [LinkedIn](https://www.linkedin.com/in/eduardo-da-silva-fontes/) | [GitHub](https://github.com/DuuhZero) |
| <img src="https://avatars.githubusercontent.com/u/162118889?v=4" width="75px"> | Dev Team | Eduardo Kuwahara Jr. | [LinkedIn](https://www.linkedin.com/in/eduardo-kuwahara-3b2267303/) | [GitHub](https://github.com/EduardoKuwahara) |
| <img src="https://avatars.githubusercontent.com/u/161594793?v=4" width="75px"> | Dev Team | Eric Kawata | [LinkedIn](https://www.linkedin.com/in/eric-kawata-99678b302/) | [GitHub](https://github.com/ericFatec) |
| <img src="https://avatars.githubusercontent.com/u/144804717?v=4" width="75px"> | Dev Team | Fábio Hiroshi | [LinkedIn](https://www.linkedin.com/in/f%C3%A1bio-hiroshi-5393a51a0) | [GitHub](https://github.com/FabioHiros) |
| <img src="https://avatars.githubusercontent.com/u/162117916?v=4" width="75px"> | Dev Team | João Vitor Rossi Ferreira | [LinkedIn](https://www.linkedin.com/in/joão-rossi-7311a0301/) | [GitHub](https://github.com/joaorossiferreira) |
| <img src="https://avatars.githubusercontent.com/u/95691713?v=4" width="75px"> | Dev Team | Kathellyn Caroline Alves dos Santos | [LinkedIn](https://www.linkedin.com/in/kathellyn-caroline-a562101b9) | [GitHub](https://github.com/CarolineKathellyn) |
| <img src="https://avatars.githubusercontent.com/u/162117908?v=4" width="75px"> | Scrum Master | Paulo Henrique Martins de Almeida | [LinkedIn](https://www.linkedin.com/in/paulo-almeida-3102452a7/) | [GitHub](https://github.com/pauloalmeida46) |
