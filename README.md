# FATEC Profº Jessen Vidal - São José dos Campos - 5º Semestre DSM - 2026

<p>Projeto desenvolvido para a API (Aprendizagem por Projeto Integrado) do 5° Semestre do curso Desenvolvimento de Software Multiplataforma (DSM) em parceria com a Xertica.</p>

> _A API se trata de um projeto submetido à metodologia de ensino em implantação na Fatec São José dos Campos, do qual os alunos formam equipes baseadas na metodologia ágil SCRUM, tendo um aluno como Scrum Master, um sendo o Product Owner e o restante dos integrantes como Dev Team._

<img src="https://github.com/Equipe-Skyfall/themis/blob/main/docs/bannerthemis.jpg">
### 📃 Respositórios

---

### 📃 Respositórios 
- [Repositório App](https://github.com/Equipe-Skyfall/themis-app)
- [Respositório BackEnd](https://github.com/Equipe-Skyfall/themis-back)
- [Respositório BD](https://github.com/Equipe-Skyfall/themis-db)

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

| Sprint | Data | Status | Relatório |
|:------:|:----:|:------:|:---------:|
| 1 | 16/03/2026 à 05/05/2026 | Não Concluído | [Ver Relatório](https://github.com/Equipe-Skyfall/skytrack/blob/main/docs/Sprint%201)|
| 2 | 13/04/2026 à 03/05/2026 | Não Concluído |[Ver Relatório](https://github.com/Equipe-Skyfall/skytrack/blob/main/docs/Sprint%202)|
| 3 | 11/05/2026 à 31/05/2026 | Não Concluído | [Ver Relatório](https://github.com/Equipe-Skyfall/skytrack/tree/main/docs/Sprint%203) |

---

## 💻 Tecnologias utilizadas <a name="tecnologias"></a>

---

### 📃 Estrutura de Branchs
#### Main - Estado principal que armazena a versão estável do projeto
#### Dev - Estado de desenvolvimento atual
#### Sprint X - Instancia de todos respositórios ao fim da Sprint X
### ⏳ Status do projeto: 0/3 Sprint

---

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

### Requisitos Funcionais <a name="requisitos"></a>

| RF   | Nome                                      | Descritivo                                                                                                                                                     |
| ---- | ----------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| RF01 | Upload de petição inicial                 | O sistema deve permitir que o usuário envie uma petição inicial em formato digital para análise automática.                                                    |
| RF02 | Processamento do texto                    | O sistema deve analisar automaticamente o conteúdo textual da petição utilizando técnicas de processamento de linguagem natural.                               |
| RF03 | Geração de resumo                         | O sistema deve gerar um resumo automático da petição destacando os principais pontos e informações relevantes do caso.                                         |
| RF04 | Consulta à base de precedentes            | O sistema deve consultar automaticamente uma base nacional de precedentes jurídicos para identificar decisões relacionadas ao caso analisado.                  |
| RF05 | Identificação de precedentes relacionados | O sistema deve identificar precedentes potencialmente relacionados com base na similaridade entre o texto da petição e os registros da base jurídica.          |
| RF06 | Cálculo de similaridade                   | O sistema deve calcular um percentual de similaridade ou probabilidade de aplicabilidade entre a petição analisada e cada precedente encontrado.               |
| RF07 | Classificação de aplicabilidade           | O sistema deve classificar cada precedente encontrado como "Aplicável", "Possivelmente aplicável" ou "Não aplicável".                                          |
| RF08 | Exibição de dados estruturados            | O sistema deve apresentar informações estruturadas de cada precedente, incluindo tribunal de origem, tema, enunciado, status e tese firmada quando disponível. |
| RF09 | Síntese explicativa                       | O sistema deve gerar uma explicação resumida que indique a relação entre o precedente identificado e o caso analisado.                                         |
| RF10 | Ordenação dos resultados                  | O sistema deve apresentar os precedentes encontrados organizados por grau de similaridade ou relevância.                                                       |
| RF11 | Acesso via aplicativo móvel               | O sistema deve permitir que o usuário acesse as funcionalidades por meio de um aplicativo móvel conectado à nuvem.                                             |


### Requisitos Não Funcionais

| RNF   | Nome                          | Descritivo                                                                                                                     |
| ----- | ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| RNF01 | Tempo de resposta             | O sistema deve apresentar o resultado da análise da petição em até 10 segundos após o envio do documento.                      |
| RNF02 | Desempenho de busca           | A consulta de precedentes na base de dados deve ocorrer em tempo inferior a 5 segundos.                                        |
| RNF03 | Escalabilidade                | O sistema deve suportar múltiplos usuários realizando consultas simultâneas sem perda significativa de desempenho.             |
| RNF04 | Disponibilidade               | O sistema deve possuir disponibilidade mínima de 99% para garantir acesso contínuo.                                            |
| RNF05 | Infraestrutura em nuvem       | A aplicação deve ser hospedada em ambiente de computação em nuvem para garantir escalabilidade e alta disponibilidade.         |
| RNF06 | Segurança dos dados           | O sistema deve garantir a confidencialidade e proteção das petições enviadas pelos usuários.                                   |
| RNF07 | Comunicação segura            | Toda comunicação entre o aplicativo e o servidor deve utilizar protocolo seguro HTTPS.                                         |
| RNF08 | Autenticação de usuários      | O sistema deve exigir autenticação para acesso às funcionalidades da aplicação.                                                |
| RNF09 | Usabilidade                   | A interface do aplicativo deve ser simples e intuitiva, facilitando a utilização por profissionais do Direito.                 |
| RNF10 | Compatibilidade               | O sistema deve ser compatível com dispositivos móveis Android e iOS.                                                           |
| RNF11 | Suporte a formatos de arquivo | O sistema deve aceitar arquivos de petições nos formatos PDF, DOCX e TXT.                                                      |
| RNF12 | Arquitetura modular           | O sistema deve possuir arquitetura modular para facilitar manutenção e evolução da aplicação.                                  |
| RNF13 | Atualização do modelo de IA   | O sistema deve permitir atualização do modelo de aprendizado de máquina sem necessidade de reconstrução completa da aplicação. |
| RNF14 | Tratamento de erros           | O sistema deve identificar e tratar erros de processamento ou consulta, informando o usuário de forma clara.                   |

---

## 📜 Product Backlog <a name="backlog"></a>

---

## 📝 Sprint Backlog <a name="backsprint"></a>

---

## Links Úteis <a name="links"></a>

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
| <img src="https://avatars.githubusercontent.com/u/161987258?v=4" width="
