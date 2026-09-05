# 🌎 Efeitos do El Niño no Brasil em 2026

![Status](https://img.shields.io/badge/Status-Concluído-success)
![DIO](https://img.shields.io/badge/Projeto-DIO-purple)
![IA](https://img.shields.io/badge/IA-NotebookLM-blue)
![Tema](https://img.shields.io/badge/Tema-El%20Niño%202026-orange)

## 📌 Sobre o Projeto

Este projeto foi desenvolvido como parte de um desafio da **DIO**, com o objetivo de utilizar Inteligência Artificial como ferramenta de aprendizagem ativa.

Para a atividade, foi criado um caderno temático no **NotebookLM** sobre os **efeitos do El Niño no Brasil em 2026**, utilizando fontes abertas e confiáveis em texto.

O projeto envolveu:

- curadoria de fontes;
- organização do conhecimento;
- engenharia de prompts;
- comparação entre respostas;
- análise crítica das informações;
- registro de dificuldades e ajustes realizados;
- construção de um miniguia de estudo;
- criação de glossário;
- elaboração de prompts reutilizáveis.

---

## 🎯 Tema

**Efeitos do El Niño no Brasil em 2026**

O estudo busca compreender o fenômeno El Niño, sua evolução ao longo de 2026 e seus possíveis impactos no Brasil, considerando temperatura, chuvas, agricultura, recursos hídricos e consequências sociais e econômicas.

---

## 🎯 Objetivos de Estudo

### Objetivo Geral

Compreender os principais efeitos do El Niño no Brasil em 2026 utilizando fontes confiáveis e Inteligência Artificial como ferramenta de apoio à aprendizagem.

### Objetivos Específicos

- Entender o que é o El Niño e como ele se forma;
- analisar a evolução do fenômeno durante 2026;
- diferenciar fatos observados de previsões;
- identificar impactos nas cinco regiões brasileiras;
- compreender efeitos sobre temperatura e precipitação;
- analisar impactos sobre agricultura e recursos hídricos;
- comparar informações de diferentes fontes;
- identificar incertezas e divergências entre modelos climáticos;
- avaliar como diferentes estruturas de prompt alteram a qualidade das respostas.

---

## 📚 Curadoria de Fontes

Foram selecionadas **quatro fontes abertas em texto**, atendendo ao requisito proposto no desafio.

### 1. INMET — Boletim Mensal nº 02 do Painel El Niño

**Título:** El Niño 2026: saiba detalhes sobre o monitoramento, previsões e os possíveis impactos do fenômeno no Brasil  
**Instituições envolvidas:** INMET, INPE, ANA, CEMADEN, SGB, SEDEC e CENSIPAM  
**Data:** 31/07/2026  
🔗 https://portal.inmet.gov.br/noticias/el-ni%C3%B1o-2026-saiba-detalhes-sobre-o-monitoramento-previs%C3%B5es-e-os-poss%C3%ADveis-impactos-do-fen%C3%B4meno-no-brasil-2

### 2. INMET — Boletim nº 03

**Título:** El Niño tem 90% de probabilidade de se configurar como muito forte no trimestre de Setembro-Outubro-Novembro  
**Data:** 01/09/2026  
🔗 https://portal.inmet.gov.br/noticias/el-ni%C3%B1o-tem-90-de-probabilidade-de-se-configurar-como-muito-forte-no-trimestre-de-setembro-outubro-novembro

### 3. Agência Brasil / Organização Meteorológica Mundial

**Título:** ONU prevê El Niño "muito forte" com duração até fevereiro de 2027  
**Data:** 03/09/2026  
🔗 https://agenciabrasil.ebc.com.br/internacional/noticia/2026-09/onu-preve-el-nino-muito-forte-com-duracao-ate-fevereiro-de-2027

### 4. Universidade Federal de Santa Catarina — UFSC

**Título:** Cientista da UFSC e referência em El Niño esclarece sobre possibilidade de evento climático intenso no país  
**Pesquisadora:** Regina Rodrigues  
**Data:** 22/05/2026  
🔗 https://noticias.ufsc.br/2026/05/cientista-da-ufsc-e-referencia-em-el-nino-esclarece-sobre-possibilidade-de-evento-climatico-intenso-no-pais/

---

## 🤖 Uso do NotebookLM

As fontes foram reunidas em um caderno temático no **NotebookLM**.

A ferramenta foi utilizada para:

- resumir conteúdos;
- explicar conceitos;
- comparar fontes;
- separar fatos observados de previsões;
- identificar concordâncias e divergências;
- organizar os impactos por região;
- produzir um glossário;
- testar diferentes estruturas de prompts.

Um cuidado adotado durante os testes foi solicitar que as respostas fossem elaboradas **exclusivamente a partir das fontes adicionadas ao caderno**.

---

# 🧠 Engenharia de Prompts

Foram testadas diferentes formas de formular perguntas para observar como a estrutura do prompt influencia o resultado.

## 🧪 Prompt 1 — Simples

> Quais são os efeitos do El Niño no Brasil em 2026?

### Resultado observado

O primeiro prompt produziu uma visão ampla do fenômeno, abordando seu funcionamento, evolução durante 2026, padrões gerais de chuva e temperatura, impactos regionais, agricultura, recursos hídricos e riscos sociais.

A resposta foi útil para obter um panorama inicial, porém apresentou grande quantidade de informação em uma única sequência.

### Aprendizado

Uma pergunta aberta pode gerar bastante conteúdo, mas nem sempre oferece a organização ideal para estudo e revisão.

---

## 🧪 Prompt 2 — Contextualizado

> Com base exclusivamente nas fontes deste caderno, explique os principais efeitos do El Niño no Brasil em 2026. Diferencie os efeitos nas regiões Sul, Sudeste, Centro-Oeste, Norte e Nordeste e utilize linguagem simples.

### Resultado observado

A resposta tornou-se mais didática e passou a apresentar os impactos separadamente para cada região brasileira.

Entre os principais padrões apresentados:

- **Sul:** maior probabilidade de chuvas acima da média e risco de enchentes;
- **Sudeste:** possibilidade de chuvas abaixo da média em grande parte da região;
- **Centro-Oeste:** calor, estiagem e risco elevado de incêndios em algumas áreas;
- **Norte:** atraso da estação chuvosa, redução de níveis dos rios e maior risco de queimadas;
- **Nordeste:** manutenção da estiagem e dificuldades relacionadas à disponibilidade de água.

### Aprendizado

Definir o público, o recorte geográfico e a origem das informações torna a resposta mais adequada ao objetivo de estudo.

---

## 🧪 Prompt 3 — Estruturado

> Com base exclusivamente nas fontes deste caderno, analise os efeitos do El Niño no Brasil em 2026. Organize a resposta em: situação atual do fenômeno; evolução durante 2026; efeitos sobre temperaturas; efeitos sobre as chuvas; impactos por região do Brasil; impactos sobre agricultura; impactos sobre recursos hídricos; possíveis consequências socioeconômicas. Diferencie claramente fatos já observados de previsões e indique as fontes utilizadas.

### Resultado observado

Este foi o prompt que apresentou a resposta mais organizada.

O NotebookLM separou claramente:

1. fatos observados;
2. previsões;
3. evolução do fenômeno;
4. temperatura;
5. precipitação;
6. impactos regionais;
7. agricultura;
8. recursos hídricos;
9. consequências sociais.

A distinção entre **dados já observados** e **cenários previstos** foi especialmente importante para evitar que projeções climáticas fossem interpretadas como acontecimentos já confirmados.

### Aprendizado

Um prompt estruturado melhora a qualidade da resposta quando define:

- fonte;
- escopo;
- formato;
- critérios de análise;
- grau de detalhamento;
- necessidade de separar fatos de previsões.

---

## 📊 Comparação dos Testes

| Teste | Estrutura | Resultado |
|---|---|---|
| Prompt 1 | Pergunta aberta | Bom panorama geral, porém amplo |
| Prompt 2 | Contexto + regiões + linguagem | Resposta mais didática e regionalizada |
| Prompt 3 | Contexto + estrutura + critérios | Resposta mais organizada e adequada para análise |

### Conclusão dos testes

Os experimentos mostraram que a qualidade de uma interação com IA não depende apenas da pergunta, mas também da forma como o resultado desejado é especificado.

O prompt estruturado foi o mais eficiente porque determinou previamente como a informação deveria ser organizada e exigiu a diferenciação entre fatos e previsões.

---

# 🩹 Cicatrizes e Troubleshooting

## Problema identificado

Durante a comparação das fontes, foi possível perceber que nem todos os modelos climáticos apresentam exatamente o mesmo cenário para todas as regiões do Brasil.

O material analisado mostrou uma divergência importante entre modelos nacionais e internacionais para partes do Sudeste e Centro-Oeste.

Também ficou evidente que a intensidade física do El Niño no oceano não determina automaticamente a intensidade de seus efeitos em uma cidade ou região específica.

## Ajuste realizado

Os prompts passaram a solicitar explicitamente:

- separação entre fatos observados e previsões;
- identificação de concordâncias;
- identificação de divergências;
- exposição de incertezas;
- comparação entre fontes;
- tratamento de previsões como probabilidades, e não como certezas.

## Resultado

As respostas deixaram de apresentar apenas um único cenário e passaram a evidenciar os limites das previsões climáticas.

Um exemplo importante foi a identificação de que modelos podem apontar tendências com meses de antecedência para grandes regiões, mas a localização exata de determinados eventos extremos possui horizonte de previsão muito menor.

## Aprendizado

**Previsões climáticas não são profecias.**

A comparação entre fontes e a identificação das incertezas são etapas fundamentais para utilizar IA de forma crítica e responsável.

---

# 📖 Miniguia de Estudo

## 1. O que é o El Niño?

O El Niño é um fenômeno climático natural associado ao aquecimento anormal das águas superficiais do Oceano Pacífico Equatorial.

Em condições normais, os ventos alísios ajudam a empurrar as águas mais quentes para oeste. Durante o El Niño, esses ventos enfraquecem ou mudam de comportamento, permitindo que águas mais quentes se concentrem no centro e no leste do Pacífico.

Essa redistribuição de calor interfere na circulação atmosférica e pode modificar padrões de chuva e temperatura em diferentes partes do planeta.

---

## 2. Evolução do El Niño em 2026

### Fatos observados

As fontes utilizadas indicam que:

- o El Niño foi oficialmente estabelecido em junho de 2026;
- houve aquecimento significativo das águas do Pacífico Equatorial;
- os ventos alísios apresentaram enfraquecimento;
- foram registrados valores negativos do Índice de Oscilação Sul.

### Previsões

As fontes analisadas também apontaram:

- elevada probabilidade de manutenção do fenômeno até o início de 2027;
- possibilidade de atingir intensidade muito forte durante o segundo semestre de 2026.

Essas informações representam **projeções**, portanto devem ser interpretadas de forma probabilística.

---

## 3. Temperaturas

As previsões analisadas indicam temperaturas acima da média histórica em grande parte do Brasil durante o segundo semestre de 2026.

Esse cenário pode favorecer:

- ondas de calor;
- baixa umidade relativa do ar;
- maior evaporação da água do solo;
- aumento do risco de queimadas.

Ainda assim, eventos de curta duração, como a entrada de frentes frias, podem provocar quedas temporárias de temperatura.

---

## 4. Chuvas

O principal padrão indicado pelas fontes é uma divisão entre diferentes regiões do país.

### Tendência de chuva acima da média

- Região Sul;
- possibilidade de extensão para áreas do sul de São Paulo e do sul de Mato Grosso do Sul.

### Tendência de chuva abaixo da média

- grande parte do Norte;
- Nordeste;
- partes do Centro-Oeste;
- partes do Sudeste.

---

## 5. Impactos por Região

### Região Sul

A principal preocupação é o excesso de chuva.

Possíveis consequências:

- aumento da vazão dos rios;
- cheias;
- inundações;
- dificuldade para operações agrícolas;
- maior ocorrência de doenças fúngicas em culturas de inverno.

### Região Sudeste

O cenário apresentado pelas fontes indica possibilidade de chuvas abaixo da média em grande parte da região.

Possíveis consequências:

- agravamento da estiagem;
- redução da umidade do solo;
- impactos em pastagens;
- riscos para culturas como café, citros e cana-de-açúcar.

### Região Centro-Oeste

As projeções indicam condições de calor e restrição de chuvas em diversas áreas.

Possíveis consequências:

- secamento do solo;
- maior demanda de irrigação;
- risco de incêndios;
- impactos em pastagens e no preparo da safra de verão.

### Região Norte

Um El Niño forte pode atrasar o início da estação chuvosa na Amazônia.

Possíveis consequências:

- redução do nível de rios;
- aumento do risco de queimadas;
- dificuldades de navegação;
- isolamento de comunidades ribeirinhas;
- impactos sobre a agricultura de subsistência.

### Região Nordeste

A principal preocupação é a continuidade das condições de estiagem.

Possíveis consequências:

- menor disponibilidade de água;
- aumento da evaporação;
- dificuldades para lavouras de sequeiro;
- impactos na pecuária;
- pressão sobre sistemas de abastecimento.

---

## 6. Agricultura

Os impactos podem ser positivos ou negativos conforme a atividade e a região.

### Possíveis efeitos favoráveis

O tempo mais seco pode facilitar:

- colheita do milho segunda safra;
- colheita do algodão;
- algumas operações agrícolas no Norte, Nordeste e Centro-Oeste;
- colheitas de inverno no Sudeste.

### Possíveis efeitos desfavoráveis

A falta de chuva pode:

- reduzir a umidade do solo;
- prejudicar pastagens;
- elevar necessidade de irrigação;
- atrasar o plantio da safra de verão;
- afetar culturas perenes.

No Sul, o excesso de chuva pode:

- favorecer doenças fúngicas;
- prejudicar a qualidade de grãos;
- atrasar plantios;
- gerar necessidade de replantio.

---

## 7. Recursos Hídricos

Os efeitos também variam regionalmente.

As fontes indicaram condições de seca severa ou extrema em algumas bacias, enquanto outras apresentavam níveis confortáveis de armazenamento.

Isso demonstra que o impacto do El Niño não é uniforme em todo o sistema hídrico brasileiro.

Entre as principais preocupações estão:

- redução de vazões em rios do centro-norte;
- continuidade da estiagem em algumas bacias;
- aumento de vazões e risco de cheias no Sul.

---

## 8. Consequências Sociais e Econômicas

As fontes utilizadas destacaram principalmente riscos ligados a:

- incêndios florestais;
- segurança hídrica;
- abastecimento;
- isolamento de comunidades ribeirinhas;
- perdas agrícolas;
- preparação para enchentes no Sul;
- necessidade de reforço em planos de contingência e sistemas de alerta.

Esses efeitos não devem ser tratados como inevitáveis, pois dependem da evolução do fenômeno, das condições locais e das medidas de prevenção adotadas.

---

# 📕 Glossário

| Conceito | Definição |
|---|---|
| **El Niño** | Aquecimento anormal e temporário das águas superficiais do Pacífico Equatorial, capaz de alterar padrões atmosféricos e climáticos. |
| **La Niña** | Fenômeno associado ao resfriamento anormal das águas superficiais do Pacífico Equatorial. |
| **ENOS** | El Niño–Oscilação Sul. Sistema de interação entre oceano e atmosfera que engloba El Niño, La Niña e sua componente atmosférica. |
| **TSM** | Temperatura da Superfície do Mar, utilizada no monitoramento das condições oceânicas. |
| **Anomalia de temperatura** | Diferença entre uma temperatura observada e a média histórica esperada para o período. |
| **Precipitação** | Água que cai da atmosfera. Nos boletins climáticos, refere-se principalmente à chuva. |
| **Estiagem** | Período prolongado de pouca ou nenhuma chuva, capaz de reduzir a umidade do solo e os níveis de rios e reservatórios. |
| **Previsão climática** | Estimativa de tendências do clima para períodos mais longos, como meses ou estações. |
| **Ventos alísios** | Ventos persistentes que sopram sobre as regiões tropicais e têm papel importante na circulação do Pacífico. |
| **Ressurgência** | Subida de águas profundas e frias para a superfície do oceano. |
| **SOI** | Índice de Oscilação Sul, indicador atmosférico utilizado no acompanhamento do ENOS. |

---

# 💬 Prompts Reutilizáveis

## 📌 Resumo

> Com base exclusivamente nas fontes deste caderno, resuma [TEMA] em até cinco tópicos. Diferencie fatos observados de previsões e indique as fontes utilizadas.

## 📌 Comparação de fontes

> Compare o que as diferentes fontes deste caderno dizem sobre [TEMA], identificando concordâncias, diferenças e incertezas.

## 📌 Explicação para iniciantes

> Explique [CONCEITO] para uma pessoa que está estudando o assunto pela primeira vez. Utilize linguagem simples, exemplo prático e somente informações presentes nas fontes.

## 📌 Revisão

> Crie 10 perguntas para revisar [TEMA], divididas em níveis básico, intermediário e avançado. Não apresente as respostas inicialmente.

## 📌 Quiz

> Crie um quiz com 10 perguntas de múltipla escolha sobre [TEMA], utilizando exclusivamente as fontes deste caderno. Apresente quatro alternativas e forneça o gabarito somente ao final.

## 📌 Identificação de incertezas

> Analise as fontes deste caderno sobre [TEMA] e identifique quais afirmações representam fatos observados, quais são previsões e quais apresentam incertezas ou divergências entre modelos.

---

# 💡 Principais Aprendizados

O desenvolvimento deste projeto permitiu compreender que:

1. a qualidade das fontes é essencial para uma boa utilização da IA;
2. perguntas genéricas e estruturadas produzem resultados diferentes;
3. definir formato e critérios melhora a organização da resposta;
4. previsões devem ser diferenciadas de fatos observados;
5. fontes confiáveis podem divergir sem que uma delas esteja necessariamente errada;
6. modelos climáticos trabalham com probabilidades;
7. a IA é mais útil quando utilizada para comparar, questionar e organizar informações, e não apenas para fornecer respostas prontas.

---

# 🏁 Conclusão

O projeto mostrou como o NotebookLM pode ser utilizado como ferramenta de aprendizagem ativa para estudar um tema complexo e atual.

Ao reunir fontes confiáveis sobre o El Niño de 2026, foi possível organizar informações, comparar previsões, identificar diferenças entre modelos e compreender os limites do conhecimento disponível.

Os testes de engenharia de prompts mostraram que respostas mais úteis são obtidas quando o usuário define claramente o contexto, as fontes, a estrutura desejada e os critérios de análise.

O principal aprendizado foi que a Inteligência Artificial não elimina a necessidade de pensamento crítico. Pelo contrário: quanto mais complexa e incerta é a informação, mais importante se torna verificar as fontes, comparar perspectivas e distinguir fatos de previsões.

---

# 🛠️ Ferramentas Utilizadas

- NotebookLM
- Inteligência Artificial Generativa
- Engenharia de Prompts
- Markdown
- GitHub

---

# 👤 Autor

**Otavio Henrique Silva**

Projeto desenvolvido como parte de um desafio de aprendizagem da **DIO**.
