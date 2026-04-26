# Slides - Modulo 4

## Slide 1 - Capa

**Modulo 4 - Analise Exploratoria de Dados (EDA)**

Curso Introdutorio de Python para Ciencia de Dados  
Qualidade dos dados, analise guiada e conclusoes

---

## Slide 2 - Objetivos

- Entender o papel da EDA
- Avaliar a qualidade dos dados
- Explorar padroes e relacoes
- Transformar resultados em insights

---

## Slide 3 - O que e EDA

EDA e a etapa em que investigamos os dados para:

- conhecer a estrutura do dataset
- identificar problemas e outliers
- encontrar padroes
- gerar hipoteses e conclusoes

---

## Slide 4 - Dataset e problema

**Dataset:** Brazilian Cities

Variaveis principais:

- populacao
- area
- densidade
- PIB per capita
- IDHM

**Pergunta central:** como os indicadores ajudam a explicar diferencas no desenvolvimento humano dos municipios brasileiros?

---

## Slide 5 - Etapas da analise

1. Carregamento e preparacao
2. Analise da qualidade dos dados
3. Estatisticas descritivas
4. Visualizacoes
5. Storytelling e conclusoes

---

## Slide 6 - Preparacao dos dados

Foram criadas colunas auxiliares para a analise:

- `REGIAO`
- `POP_FINAL`
- `DENSIDADE`
- `TIPO`
- `IDHM_FAIXA`

Essas variaveis facilitaram comparacoes mais claras.

---

## Slide 7 - Qualidade dos dados

Pontos verificados:

- tipos de variaveis
- valores nulos
- duplicidades
- dispersao dos dados

**Resumo:** o dataset possui boa base para EDA, mas algumas variaveis exigem interpretacao cuidadosa.

---

## Slide 8 - Estatisticas descritivas

As variaveis `POP_FINAL`, `GDP_CAPITA` e `DENSIDADE` apresentaram alta variacao.

**Leitura:**

- os municipios brasileiros sao muito heterogeneos
- media sozinha nao resume bem os dados
- mediana e quartis sao mais uteis em varios casos

---

## Slide 9 - Distribuicao do IDHM

**Grafico sugerido:** histograma do IDHM

**Insight principal:**

- a maior parte dos municipios esta em faixas intermediarias
- poucos municipios concentram valores extremos

Isso mostra que o desenvolvimento humano e desigual no territorio brasileiro.

---

## Slide 10 - Comparacao entre regioes

**Grafico sugerido:** boxplot de IDHM por regiao

**Leitura:**

- ha diferencas regionais relevantes
- algumas regioes apresentam mediana maior de IDHM
- a dispersao indica desigualdade tambem dentro das regioes

---

## Slide 11 - Capitais x interior

**Grafico sugerido:** boxplot por tipo de municipio

**Insight principal:**

- capitais tendem a ter melhores indicadores medianos
- o interior e mais diverso e heterogeneo

---

## Slide 12 - PIB per capita x IDHM

**Grafico sugerido:** scatter plot

**Leitura:**

- existe relacao positiva entre renda e IDHM
- a relacao nao e perfeita

**Conclusao:** renda influencia o desenvolvimento, mas nao explica tudo.

---

## Slide 13 - Storytelling com dados

O Brasil municipal apresenta tres marcas principais:

1. concentracao de populacao e atividade economica
2. desigualdade regional
3. diferencas sociais que nao se explicam apenas pela renda

---

## Slide 14 - Principais insights

- O dataset foi suficiente para uma EDA introdutoria consistente.
- O IDHM varia de forma clara entre regioes.
- PIB per capita e IDHM possuem associacao positiva.
- Capitais concentram melhores indicadores, mas o interior nao e uniforme.

---

## Slide 15 - Conclusao

A EDA mostrou que os municipios brasileiros possuem realidades muito diferentes. O IDHM ajuda a revelar desigualdades que nao aparecem ao observar apenas renda ou populacao. Por isso, qualquer decisao publica ou de negocio precisa combinar diferentes indicadores antes de definir prioridades.
