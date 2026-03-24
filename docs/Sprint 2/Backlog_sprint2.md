# Sprint 2 - Resumo e Sintese Explicativa

**Periodo:** 13/04/2026 a 03/05/2026  
**Foco:** Geracao automatica de resumo da peticao e sintese explicativa por precedente.

## User Stories da Sprint

| RANK | PRIORIDADE | ESTIMATIVA | USER STORY | RF | STATUS |
|:----:|:----------:|:----------:|------------|----|:------:|
| 5 | Alta | 3 | Como juiz, quero ver o percentual de similaridade de cada precedente em relacao ao caso, para que eu compreenda o grau de proximidade entre as decisoes. | RF5 | 🔲 |
| 6 | Alta | 5 | Como juiz, quero visualizar as informacoes detalhadas de cada precedente - tribunal, tema, enunciado e status -, para que eu avalie sua aplicabilidade com precisao. | RF6 | 🔲 |
| 7 | Alta | 3 | Como juiz, quero que a tese firmada de um precedente seja exibida quando disponivel, para que eu tenha acesso a posicao consolidada sobre o tema. | RF6 | 🔲 |
| 8 | Media | 8 | Como juiz, quero que o sistema gere automaticamente um resumo da peticao recebida, para que eu compreenda os pontos centrais do caso sem precisar ler o documento completo. | RF8 | 🔲 |

---

## US05 - Percentual de similaridade por precedente

### Criterios de Aceitacao
- [ ] O percentual de similaridade deve ser calculado e exibido para cada precedente listado.
- [ ] O valor deve ser apresentado em formato numerico percentual (ex.: 87%).
- [ ] O calculo deve ser coerente com o conteudo da peticao enviada.

## US06 - Informacoes detalhadas do precedente

### Criterios de Aceitacao
- [ ] Os campos tribunal, tema, enunciado e status devem ser exibidos para cada precedente.
- [ ] Campos indisponiveis na base de dados devem ser sinalizados como "Nao disponivel".
- [ ] As informacoes devem ser apresentadas de forma estruturada e legivel.

## US07 - Exibicao da tese firmada quando disponivel

### Criterios de Aceitacao
- [ ] A tese firmada deve ser exibida quando disponivel na base de dados do precedente.
- [ ] O campo deve ser omitido ou sinalizado como indisponivel quando ausente.
- [ ] A exibicao deve ser visualmente diferenciada dos demais campos do precedente.

## US08 - Resumo automatico da peticao

### Criterios de Aceitacao
- [ ] O sistema deve gerar automaticamente um resumo a partir do conteudo da peticao enviada.
- [ ] O resumo deve ser exibido na tela de resultados antes da lista de precedentes.
- [ ] O conteudo do resumo deve refletir os pontos centrais identificados na peticao.
