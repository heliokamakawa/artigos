# Prompt para Auditoria Final de Referências e Citações em Artigos Científicos

## Objetivo

Realizar uma auditoria rigorosa das referências e citações do artigo, verificando consistência bibliográfica, adequação científica, sustentação das afirmações e padronização formal, sem introduzir novas referências, exceto quando explicitamente solicitado.

---

## Materiais Disponíveis

Serão fornecidos:

* Artigo científico em PDF ou LaTeX.
* Arquivo `.bib` contendo as referências.
* Pasta contendo os artigos originais em PDF.
* Arquivos `.md` gerados a partir dos PDFs originais.

Os arquivos `.md` devem ser utilizados como fonte principal de análise **somente após confirmar que representam fielmente os respectivos PDFs originais**.

---

## Etapa 1 — Verificação da Integridade dos Arquivos `.md`

Para cada referência:

1. Localizar o PDF original correspondente.
2. Comparar PDF e arquivo `.md`.
3. Confirmar que o `.md` preserva adequadamente:

   * título;
   * autores;
   * resumo;
   * principais seções;
   * conclusão;
   * ausência de erros graves de extração.

Problemas graves incluem:

* mistura de colunas;
* perda de parágrafos;
* perda de negações ("not", "no", etc.);
* textos truncados;
* seções ausentes;
* conteúdo claramente corrompido.

Após validação, considerar o `.md` como representação oficial do artigo para toda a auditoria.

---

## Etapa 2 — Cobertura Bibliográfica

Verificar:

### 2.1 Referências citadas

Toda entrada do arquivo `.bib` deve possuir pelo menos uma citação no texto.

Identificar:

* referências não utilizadas;
* citações órfãs;
* chaves inexistentes.

Reportar todas as inconsistências.

---

## Etapa 3 — Validação das Citações

Analisar cada citação presente no artigo.

Para cada afirmação:

1. Localizar a(s) referência(s) citada(s).
2. Verificar no arquivo `.md` correspondente se a afirmação é efetivamente sustentada.

Classificar cada caso como:

### A. Sustentação Forte

A referência sustenta claramente a afirmação.

**Ação:** manter.

---

### B. Sustentação Parcial

A referência apoia parcialmente a afirmação, mas não permite generalizações fortes.

**Ação:** sugerir suavização textual.

Exemplos de suavização:

* "demonstra" → "sugere";
* "prova" → "indica";
* "evidencia" → "relata";
* "mostra que" → "apresenta evidências de que";
* "a literatura estabelece" → "estudos sugerem".

Sempre preservar o significado original do artigo.

---

### C. Sustentação Insuficiente

A referência não sustenta a afirmação.

**Ações permitidas (nesta ordem):**

1. Verificar se outra referência já existente no conjunto bibliográfico sustenta a afirmação.
2. Se não houver:

   * reformular a afirmação;
   * suavizar a redação;
   * ou remover o trecho.

**Não adicionar novas referências, salvo solicitação explícita do autor.**

---

## Etapa 4 — Qualidade dos Veículos de Publicação

Verificar o status de cada referência científica.

### Manter:

* periódicos revisados por pares;
* conferências reconhecidas;
* revisões sistemáticas;
* mapeamentos sistemáticos;
* livros acadêmicos;
* capítulos publicados por editoras acadêmicas.

### Manter apenas para dados contextuais:

* relatórios institucionais;
* documentos governamentais;
* estatísticas oficiais.

Exemplos:

* WEF;
* OCDE;
* Brasscom;
* UNESCO.

### Sinalizar para remoção:

* preprints não publicados;
* arXiv, TechRxiv, HAL ou equivalentes sem publicação formal;
* manuscritos "under review";
* manuscritos "submitted";
* documentos sem revisão por pares utilizados como evidência científica central.

---

## Etapa 5 — Padronização Bibliográfica

Verificar uniformidade em todas as referências.

Conferir:

* nomes de autores;
* ano;
* título;
* periódico ou evento;
* volume;
* número;
* páginas;
* DOI;
* URL (quando aplicável).

Identificar inconsistências como:

* abreviações diferentes do mesmo veículo;
* capitalização inconsistente;
* estilos misturados;
* campos ausentes;
* duplicidades.

---

## Etapa 6 — Verificação das Descrições e Interpretações

Para toda descrição de literatura feita no artigo:

Verificar se:

1. os autores originais realmente afirmam o que está sendo descrito;
2. não há extrapolações indevidas;
3. não há generalizações excessivas;
4. não há causalidade inferida quando o estudo apenas observou associação;
5. limitações do estudo original não foram ignoradas.

Sinalizar:

* exageros;
* simplificações excessivas;
* interpretações incorretas;
* inferências não sustentadas.

---

## Etapa 7 — Priorização

Priorizar a auditoria nas afirmações centrais do artigo:

1. problema de pesquisa;
2. motivação;
3. fundamentação teórica principal;
4. contribuições declaradas;
5. discussão dos resultados;
6. conclusões.

---

## Formato Esperado da Resposta

Organizar os achados utilizando a estrutura:

### Trecho do artigo

> trecho original

### Referência(s)

* Autor, ano

### Classificação

* Sustentação forte
* Sustentação parcial
* Sustentação insuficiente

### Problema identificado

Descrição objetiva.

### Evidência encontrada no artigo original

Trecho ou síntese encontrada no arquivo `.md`.

### Ação recomendada

* manter;
* suavizar;
* substituir por referência já existente;
* remover.

### Sugestão de redação revisada

Apresentar apenas quando necessário.

---

## Restrições

* Não inventar conteúdo.
* Não inferir além do que os artigos originais afirmam.
* Não adicionar novas referências sem autorização explícita.
* Preservar o máximo possível da redação original.
* Preferir suavizar afirmações a remover conteúdo.
* Em caso de dúvida, adotar a interpretação mais conservadora.
