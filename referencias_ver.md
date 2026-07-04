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

Citação sem função
Verificar

A referência sustenta explicitamente alguma afirmação da frase?

Problema

A frase descreve apenas o próprio estudo (método, projeto, resultados, figuras, tabelas, etapas, decisões dos autores etc.) e a citação é inserida sem justificar nenhuma afirmação.

Ação
Identificar a afirmação que a referência deveria sustentar.
Caso nenhuma afirmação dependa da literatura, recomendar a remoção da citação.


### Contribuição própria × conhecimento da literatura
Verificar

Está claro quais informações pertencem ao presente estudo e quais são provenientes da literatura?

Problema

A redação mistura decisões dos autores com conceitos, métodos ou recomendações da literatura, fazendo parecer que toda a frase é sustentada pela referência.

Ação

Separar explicitamente:

contribuição do artigo;
conhecimento previamente estabelecido.

Quando necessário, sugerir reformulação para deixar essa distinção evidente.

### Escopo da referência
Verificar

A referência realmente sustenta a parte da frase onde foi inserida?

Problema

A citação aparece ao final de uma frase contendo diversas afirmações, impossibilitando identificar exatamente qual delas está sendo referenciada.

Ação

Indicar qual trecho é sustentado pela literatura e, se necessário, recomendar reposicionar ou reescrever a frase.

4. Atribuição incorreta
Verificar

A redação faz parecer que uma decisão específica do estudo foi retirada da literatura?

Exemplos comuns
número de etapas;
checkpoints;
instrumentos criados pelos autores;
rubricas;
organização do experimento;
fluxo do projeto.
Ação

Se a decisão pertence ao presente estudo, a literatura deve sustentar apenas o princípio metodológico, nunca a decisão específica.

### Citações decorativas
Verificar

A referência foi inserida apenas porque o assunto é semelhante?

Problema

A citação não adiciona fundamentação científica à frase.

Ação

Recomendar a remoção.

### Conceitos versus aplicação
Verificar

A referência define um conceito ou está sendo utilizada para justificar um resultado obtido pelos autores?

Problema

A literatura é utilizada para validar resultados do próprio estudo.

Ação

Separar:

definição do conceito (literatura);
aplicação ou resultado observado (presente estudo).

### Figuras, tabelas e descrições do estudo
Verificar

A citação foi inserida em legendas ou descrições que pertencem exclusivamente ao presente trabalho?

Problema

A referência transmite a impressão de que a figura, tabela ou processo foi extraído da literatura.

Ação

Remover a citação, exceto quando a figura ou tabela for adaptada ou reproduzida de outra fonte.

Pergunta obrigatória para cada citação

Para cada referência encontrada, responder objetivamente:

O que exatamente esta referência sustenta nesta frase?

Se a resposta não puder ser formulada de maneira objetiva, considerar a citação potencialmente inadequada.

Critério final

Uma citação é considerada adequada quando:

possui uma função explícita;
sustenta uma afirmação específica;
não gera ambiguidade sobre autoria das contribuições;
distingue claramente conhecimento da literatura das contribuições do presente estudo;
está posicionada exatamente onde a informação referenciada é utilizada.

Caso qualquer um desses critérios não seja atendido, registrar o problema e sugerir uma correção.

---

## Restrições

* Não inventar conteúdo.
* Não inferir além do que os artigos originais afirmam.
* Não adicionar novas referências sem autorização explícita.
* Preservar o máximo possível da redação original.
* Preferir suavizar afirmações a remover conteúdo.
* Em caso de dúvida, adotar a interpretação mais conservadora.
