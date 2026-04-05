# Sprint 1 - Upload, Processamento e Comparacao de Precedentes

**Periodo:** 16/03/2026 a 05/04/2026  
**Foco:** Estrutura base do sistema - o juiz envia a peticao, o sistema identifica informacoes juridicas relevantes, consulta a base de precedentes e retorna os resultados com classificacao de aplicabilidade.

## User Stories da Sprint

| RANK | PRIORIDADE | ESTIMATIVA | USER STORY | RF | STATUS |
|:----:|:----------:|:----------:|------------|----|:------:|
| 1 | Alta | 5 | Como juiz, quero enviar uma peticao inicial em PDF pelo aplicativo, para que o sistema possa analisa-la automaticamente. | RF1 | ✅ |
| 2 | Alta | 8 | Como juiz, quero que o sistema identifique automaticamente as informacoes juridicas relevantes da peticao enviada, para que os precedentes encontrados sejam precisos. | RF2 | ✅ |
| 3 | Alta | 8 | Como juiz, quero visualizar uma lista de precedentes da base juridica relacionados ao caso, para que eu identifique rapidamente as decisoes mais proximas. | RF3, RF4 | ✅ |
| 4 | Alta | 5 | Como juiz, quero ver a classificacao de aplicabilidade de cada precedente - Aplicavel, Possivelmente aplicavel ou Nao aplicavel -, para que eu saiba quais merecem atencao prioritaria. | RF5 | ✅ |

---

## US01 - Envio de peticao inicial em PDF

### Criterios de Aceitacao
- [x] O sistema deve aceitar arquivos exclusivamente no formato PDF.
- [x] O envio deve ser confirmado visualmente ao usuario apos o upload.
- [x] Arquivos invalidos ou corrompidos devem exibir mensagem de erro clara.

## US02 - Identificacao automatica de informacoes juridicas

### Criterios de Aceitacao
- [x] O sistema deve extrair automaticamente as informacoes juridicas relevantes da peticao enviada.
- [x] As informacoes extraidas devem ser utilizadas como base para a consulta a base de precedentes.
- [x] O processamento deve ocorrer sem necessidade de intervencao manual do usuario.

## US03 - Visualizacao de lista de precedentes relacionados

### Criterios de Aceitacao
- [x] O sistema deve retornar ao menos um precedente relacionado ao conteudo da peticao.
- [x] Os precedentes devem ser exibidos em lista ordenada por grau de relevancia.
- [x] Cada item da lista deve apresentar informacoes basicas de identificacao do precedente.

## US04 - Classificacao de aplicabilidade dos precedentes

### Criterios de Aceitacao
- [x] Cada precedente deve ser classificado como "Aplicavel", "Possivelmente aplicavel" ou "Nao aplicavel".
- [x] A classificacao deve ser visualmente distinta para cada categoria.
- [x] A logica de classificacao deve ser baseada no percentual de similaridade calculado.
