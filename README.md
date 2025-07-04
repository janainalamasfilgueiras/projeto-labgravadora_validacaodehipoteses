# Caso projeto cliente Gravadora Laboratória

Ficha Técnica https://www.notion.so/janainalamas/Caso-projeto-cliente-Gravadora-Laborat-ria-1d38a822de888012940df1803cf2b039

# Ficha Técnica

**Created by:** Janaina Lamas Filgueiras e Michele Regina

**Created:** 11/04/2025

**Status: Em progresso**

**Serviço:** Consultoria de Gestão de projetos, Customer Success e Business Intelligence

**Descrição do projeto:** Validação de hipóteses

## Consultoria Projeto Gravadora Laboratória

## Contexto:

A gravadora Laboratória enfrenta o emocionante desafio de lançar um novo artista no cenário musical global. Felizmente, ela tem uma ferramenta poderosa em seu arsenal: um extenso conjunto de dados do Spotify com informações sobre as músicas mais ouvidas em 2023. Num mundo onde a **indústria musical** é extremamente competitiva e em constante evolução, a capacidade de tomar decisões baseadas em dados tornou-se um ativo inestimável. A gravadora levantou uma série de hipóteses sobre o que faz uma música ser mais ouvida. Essas hipóteses levantadas precisam de embasamento para serem refutadas ou validadas.

1. **Músicas com BPM (Batidas Por Minuto) mais altos fazem mais sucesso em termos de número de streams no Spotify.**
2. **As músicas mais populares no ranking do Spotify também possuem um comportamento semelhante em outras plataformas, como a Deezer.**
3. **A presença de uma música em um maior número de playlists está correlacionada com um maior número de streams.**
4. **Artistas com um maior número de músicas no Spotify têm mais streams.**
5. **As características da música influenciam o sucesso em termos de número de streams no Spotify.**

## Objetivo:

A empresa  precisa de dados para  fundamentar as decisões para refutar ou confirmar essas hipóteses. O objetivo é fornecer a análise de dados e  fornecer recomendações estratégicas de forma que a gravadora e o novo artista possam tomar decisões informadas que aumentem as chances de alcançar o “sucesso”.

## Equipe responsável (Papéis e responsabilidades)

**Parceria:** Janaina Lamas Filgueiras/ Michele Cardoso

## Ferramentas, técnicas e tecnologias

### Ferramentas

Ferramentas 

- Google Suite (Google Sheet, Google Apresentações)
- Trello
- WhatsApp/Google Meeting
- Figma/Lean Inception
- BigQuery
- Power BI
- Google Colab
- Slidesgo https://slidesgo.com/
- Flaticon https://www.flaticon.com/
- Images
- Loom

**Linguagens** 

- SQL
- Python

### Metodologia e técnicas

- Estatística descritiva: medidas de tendência central (média, mediana, modo) e dispersão (amplitude, desvio padrão, variância, coeficiência de variação, intervalo intrquartil), gráficos de visualização (gráficos de barras, gráficos de linhas, diagrama de dispersão, histograma, boxplot) e tabelas de frequência (matriz de correlação) e resumos numéricos.
- SQL para consulta e criação de banco de dados
- Integração SQL com outras plataformas como PowerBI, Google Sheets e Google Colab
- DAX para criação de novas medidas, colunas e tabelas e Python para criação de gráficos e análises

## Processamento e análises

Destaque das visualizações/resultados principais

[](https://console.cloud.google.com/bigquery?ws=!1m4!1m3!3m2!1sprojeto2laboratoriajlf!2shipoteses)

[Google Colab](https://colab.research.google.com/drive/17yjdRfjfoBWdPNxiQ5EtnkM9DckKEyRE?usp=sharing)

[Google Colab](https://colab.research.google.com/drive/1GdrsVFFfYGZAo_cBwPAFzedRnIHwDl03?usp=sharing)

https://docs.google.com/presentation/d/1Oqe364lNHI3XUU2XWrR5r9hoDhp0m4V0pFsEK8CkAXY/edit?usp=sharing

[Laboratória -Projeto 2-Hipóteses Atividades20240501.pbix](attachment:aff4ec7b-46ec-4fca-989e-11810889673f:Laboratria_-Projeto_2-Hipteses_Atividades20240501.pbix)

[](https://trello.com/invite/b/67f98fb5b92444e5e0d33567/ATTI875610cf389ac5f58166ee9c9399a3f70D3973D1/projeto-2-hipoteses)

https://www.figma.com/board/NIWcsTNhSuUC2yVa6SAKFs/Laborat%C3%B3ria---Projeto-2---Hip%C3%B3teses?t=dLYoh8jX1o5hHrI6-1

[Laboratória - Projeto 2 - Análise de dados músicas - Validação de Hipóteses Fatores de Sucesso](https://www.loom.com/share/a76ac56b751e4321840417bb00b610cd?sid=e2858ba1-7978-4644-bcd3-a29d3f439bb1)

[https://docs.google.com/presentation/d/1nFbz93ijam02lWVxBkUyueC6D9z5J6uNbegZt0VtiqU/edit?usp=sharing](https://docs.google.com/presentation/d/1nFbz93ijam02lWVxBkUyueC6D9z5J6uNbegZt0VtiqU/preview?usp=sharing)

### Etapas de processamento e análise

1. Importar base CSV providenciada pela empresa no Google Big Query
2. Realizar consultas de análise da base
3. Realizar análise do caso do projeto e seu principal problema e objetivo e da base cruzando viabilidade, possibilidades e alinhando visão, plano de trabalho e objetivos.
4. Realizar limpeza da base
5. Realizar configuração da base
6. Realizar união das planilhas em uma planilha/base única
7. Realizar análise pelo Power Bi
8. Destacar gráficos e 
9. Criar o Dashboard no POwer Bi
10. Criar análise e gráficos no Google Colab
11. Revisar os dados
12. Criar apresentação
13. Revisar apresentação
14. Submeter projeto
15. Apresentar dados ao cliente

**Registro de consideração e mudanças na bases de origem**

Registro de mudanças: Limpeza e configuração de base de dados

| Descrição de ação de configuração | Descrição | Código BigQuery (Exemplos) | Análise realizada? | Trackincompetition | Tracktechnicalinfo | Trackinspotify | Descrição (DE-PARA) |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Configuração do tipo de dado | Verificar e corrigir se o tipo de dado da coluna corresponde ao conteúdo (TEXT, INT, FLOAT, DATE, etc.). Considerar a granularidade (ex: DATE vs. TIMESTAMP). | sql ALTER TABLE `seu_projeto.seu_dataset.sua_tabela` ALTER COLUMN nome_da_coluna SET DATA TYPE INT64;&lt;br/>sql SELECT CAST(coluna_texto AS DATE) FROM `seu_projeto.seu_dataset.sua_tabela`; | Sim | Não | Sim | Sim | 📄 trackinspotify.csvtrack_id: object → STRING, track_name: object → STRING, artists_name: object → STRING, artist_count: float64 → INT64, released_year: float64 → INT64, released_month: float64 → INT64, released_day: float64 → INT64, in_spotify_playlists: float64 → INT64, in_spotify_charts: float64 → INT64, streams: float64 → INT64📄 tracktechnicalinfo.csvtrack_id: object → STRING, bpm: object → INT64, key: object → STRING, mode: object → STRING, danceability: object → FLOAT64, valence: object → FLOAT64, energy: object → FLOAT64, acousticness: object → FLOAT64, instrumentalness: object → FLOAT64, liveness: object → FLOAT64, speechiness: object → FLOAT64📄 trackincompetition.csvtrack_id: object → STRING, in_apple_playlists: object → INT64, in_apple_charts: object → INT64, in_deezer_playlists: object → INT64, in_deezer_charts: object → INT64, in_shazam_charts: object → INT64 |
| Inconformidade de caracteres | Identificar e padronizar caracteres especiais, codificação (UTF-8), capitalização. Remover ou substituir caracteres de controle. | sql SELECT REGEXP_REPLACE(coluna_texto, r'[^a-zA-Z0-9\s]', '') FROM `seu_projeto.seu_dataset.sua_tabela`;&lt;br/>sql SELECT LOWER(coluna_texto) FROM `seu_projeto.seu_dataset.sua_tabela`;&lt;br/>sql SELECT REPLACE(coluna_texto, '\n', '') FROM `seu_projeto.seu_dataset.sua_tabela`; | Sim | Não | Sim | Sim | transformação da informação BPM110KeyAModeMajorDanceability53Valence75Energy69Acousticness7Instrumentalness0Liveness17Speechiness3 na coluna Streams, Track ID 4061483 PARA 0transformação dos nomes de colunas danceability, valence, energy, acusticness, instrumentality, liveness e speechiness retirando o símbolo de %transformação de caracteres  () que se relacionava a palavras (possivelmente) com acento como referência () excluindo os valores inconformes |
| Espaço no início ou final | Remover espaços em branco extras no início ou final de strings. Considerar espaços duplicados no meio. | sql SELECT TRIM(coluna_texto) FROM `seu_projeto.seu_dataset.sua_tabela`;&lt;br/>sql SELECT REGEXP_REPLACE(coluna_texto, r'\s{2,}', ' ') FROM `seu_projeto.seu_dataset.sua_tabela`; | Sim (Análise principalmente de espaços no início) | Não | Não | Sim | Foi realizada a remoção dos espaços, mas sem alterações nos dados a serem consideradas.  |
| Informações em branco | Identificar e tratar células vazias ou contendo apenas espaços. Padronizar outras representações de vazio ("-", "N/A") para NULL. | sql SELECT IF(coluna_texto = '', NULL, coluna_texto) FROM `seu_projeto.seu_dataset.sua_tabela`;&lt;br/>sql SELECT NULLIF(coluna_texto, '-') FROM `seu_projeto.seu_dataset.sua_tabela`; | Sim | Sim | Sim |  | Não há valores em branco identificados, mas no BIGQUERY apresentam-se como nulos. Criada uma coluna adicional para a classificação do valor nulo. Transformado valor nulo em colunas numéricas para 0 e em colunas de texto para "Não informado" |
| Valores duplicados | Identificar e remover ou manter registros duplicados (linhas inteiras ou combinações de colunas). | sql SELECT DISTINCT * FROM `seu_projeto.seu_dataset.sua_tabela`;&lt;br/>sql SELECT * FROM ( SELECT *, ROW_NUMBER() OVER(PARTITION BY coluna1, coluna2 ORDER BY alguma_coluna) as rn FROM `seu_projeto.seu_dataset.sua_tabela` ) WHERE rn = 1; | Sim | Não | Não | Sim | Foram constatados valores duplicados de referências de nome de artista e música, mas esses dados não foram desconsiderados da análise. O correto seria selelcionar uma única linha dos duplicados, mas considerou-se que no geral não causaria impacto.  |
| Outliers (Valores Atípicos) | Identificar valores que se desviam significativamente. Investigar causas e decidir tratamento (remover, transformar, manter). Definir métodos de detecção. | sql SELECT * FROM `seu_projeto.seu_dataset.sua_tabela` WHERE nome_da_coluna < limite_inferior OR nome_da_coluna > limite_superior;&lt;br/>(Cálculo dos limites pode envolver subqueries com STDDEV, PERCENTILE, etc.) | Não realizado | - | - | - | Não foi identificado um outlier no contexto geral descrito.  |
| Escala e unidades | Garantir escala e unidades consistentes em dados numéricos. | sql SELECT IF(unidade = 'cm', valor / 100, valor) AS valor_em_metros FROM `seu_projeto.seu_dataset.sua_tabela`; | Não realizado | - | - | - | Não foi necessário fazer mudanças na classificação ou representação por porcentagem. Por si só o tipo de coluna já indica o valor e o formato automático. |

## trackinspotify.csv

| Coluna | Tipo Original (CSV) | Tipo Proposto (BigQuery) |
| --- | --- | --- |
| `track_id` | `object` (string) | `STRING` |
| `track_name` | `object` (string) | `STRING` |
| `artists_name` | `object` (string) | `STRING` |
| `artist_count` | `float64` ou `int64` | `INT64` |
| `released_year` | `float64` | `INT64` |
| `released_month` | `float64` | `INT64` |
| `released_day` | `float64` | `INT64` |
| `in_spotify_playlists` | `float64` | `INT64` |
| `in_spotify_charts` | `float64` | `INT64` |
| `streams` | `float64` | `INT64` |

---

## tracktechnicalinfo.csv

| Coluna | Tipo Original (CSV) | Tipo Proposto (BigQuery) |
| --- | --- | --- |
| `track_id` | `object` (string) | `STRING` |
| `bpm` | `object` (texto numérico ou int)` | `INT64` |
| `key` | `object` (string) | `STRING` |
| `mode` | `object` (string) | `STRING` |
| `danceability_%` | `object` com `%` | `FLOAT64` |
| `valence_%` | `object` com `%` | `FLOAT64` |
| `energy_%` | `object` com `%` | `FLOAT64` |
| `acousticness_%` | `object` com `%` | `FLOAT64` |
| `instrumentalness_%` | `object` com `%` | `FLOAT64` |
| `liveness_%` | `object` com `%` | `FLOAT64` |
| `speechiness_%` | `object` com `%` | `FLOAT64` |

---

## trackincompetition.csv

| Coluna | Tipo Original (CSV) | Tipo Proposto (BigQuery) |
| --- | --- | --- |
| `track_id` | `object` (string) | `STRING` |
| `in_apple_playlists` | `object` (texto numérico) | `INT64` |
| `in_apple_charts` | `object` (texto numérico) | `INT64` |
| `in_deezer_playlists` | `object` (texto numérico) | `INT64` |
| `in_deezer_charts` | `object` (texto numérico) | `INT64` |
| `in_shazam_charts` | `object` (texto numérico) | `INT64` |

**Proposta de boas práticas realizadas e recomendadas (a validar)**

- 

**Como utilizei o ChatGPT e o Gemini para o processo de análise?**

- 

### 5. Resultados e conclusões

### Acesse os resultados do projeto

### 6. Desafios e limitações

### 7. Próximos passos

1. Apresentação para o cliente
2. Realização de sessão de feedback
3. Recolhimento de pesquisa de satisfação do cliente

## **Referências**

- Curso Laboratória: Jornada de Dados
- https://basedosdados.org/
- https://cloud.google.com/bigquery/docs/reference/standard-sql/query-syntax
- Página principal GoogleConsole: [https://console.cloud.google.com/welcome](https://console.cloud.google.com/welcome?hl=pt-br&invt=Abuo_g&project=projeto2laboratoriajlf&supportedpurview=folder)
- https://learnsql.com.br/blog/os-comandos-sql-mais-importantes/
- Acesso ao Bucket do Google Cloud: https://console.cloud.google.com/storage/browser/projeto2hipoteses;tab=objects?forceOnBucketsSortingFiltering=true&inv=1&invt=AbwOxw&project=projeto2laboratoriajlf&prefix=&forceOnObjectsSortingFiltering=false

## Gestão de mudança: Registro de revisões

- 

## Base de conhecimento: Glossário, lições aprendidas e destaques

- O BigQuery é uma plataforma de dados totalmente gerenciada e pronta para IA que ajuda você a gerenciar e analisar seus dados com recursos integrados como aprendizado de máquina, pesquisa, análise geoespacial e Business Intelligence. A arquitetura sem servidor do BigQuery permite usar linguagens como SQL e Python para responder às maiores dúvidas da sua organização sem nenhum gerenciamento de infraestrutura. `https://console.cloud.google.com/bigquery`
O console do Google Cloud é a interface gráfica que você usa para criar e gerenciar recursos do BigQuery e executar consultas SQL.

Guia: Lista de limpeza e configuração inicial da base

| Configuração do tipo de dado | Verificar se o tipo de dado de cada coluna corresponde ao tipo de informação que ela contém (ex: números como INTEGER ou FLOAT, textos como STRING, datas como DATE ou TIMESTAMP).Identificar colunas com tipos de dados incorretos que precisam de conversão (casting). |
| --- | --- |
| Inconformidade de caracteres | Identificar caracteres especiais inesperados ou inconsistentes dentro dos dados textuais.Verificar a codificação de caracteres (UTF-8 é geralmente recomendado).Padronizar a capitalização (maiúsculas/minúsculas) em colunas de texto, se necessário. |
| Espaço no início ou final | Identificar e remover espaços em branco extras no início ou no final de strings. |
| Informações em branco | Identificar células que parecem vazias, mas podem conter apenas espaços em branco (' ') em vez de NULL.Decidir como tratar essas "informações em branco" (converter para NULL, remover a linha, etc.). |
| Valores duplicados | Identificar e decidir como tratar registros duplicados (remover, manter um específico).Considerar se a duplicidade se refere a linhas inteiras ou a combinações de colunas específicas. |
| Dados faltantes (Nulos): | Verificar quais colunas possuem valores nulos.Contar a quantidade de nulos por coluna.Entender o padrão dos nulos e decidir a estratégia de tratamento (remover, imputar, manter, criar indicador). |

Guia: Testes estatísticos

| **Tipo de Dado** | **Normalidade** | **Teste** | **O que o teste faz** | **Objetivo** | **Quando usar** | **O que preciso ter e fazer antes** | **O que fazer** | **O que fazer** | **O que observar** | **Como interpretar** | **Código/Como usar (BigQuery & Power BI)** |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Numérico (2 grupos) | Normal | t de Student (independente) | Compara médias. **Compara a média de duas amostras independentes (ex: músicas pop vs. rock).** | Ver se grupos diferem em média | Popularidade com vs. sem feat | ✅ Dados numéricos✅ 2 grupos independentes✅ Verificar normalidade com Shapiro-Wilk✅ Variância semelhante | Aplicar teste | Ver normalidade, aplicar teste | p-valor, médias | p < 0.05: diferença significativa | Power BI: T.TEST()BigQuery: usar Python externo |
| Numérico (2 grupos) | Não normal | Mann-Whitney U | Compara distribuições. **Versão não paramétrica do teste t independente — compara distribuições, não médias.** | Ver se um grupo tende a ter valores maiores | Popularidade entre grupos assimétricos | ✅ Dados numéricos✅ 2 grupos independentes❌ Não normal✅ Tamanho razoável | Aplicar teste | Aplicar mannwhitneyu() | p-valor, medianas | p < 0.05: distribuição diferente | Power BI: Script R/PythonBigQuery: via Python externo |
| Numérico (antes/depois) | Normal | t pareado | Compara médias do mesmo grupo. **Compara a média de dois momentos ou condições do mesmo grupo (antes e depois).** | Medir efeito de uma mudança | Popularidade antes e depois de playlist | ✅ Mesmos elementos medidos 2x✅ Normalidade das diferenças | Aplicar teste | Pares definidos, normalidade | p-valor, diferença média | p < 0.05: mudança significativa | Power BI: T.TEST() com opção pareada |
| Numérico (antes/depois) | Não normal | Wilcoxon | Compara pares sem normalidade. **Versão não paramétrica do t pareado — compara se as diferenças são consistentes (mais positivos ou negativos).** | Mudança em dados pareados | Idem acima com assimetria | ✅ Mesmos elementos 2x✅ Diferença não normal❌ Muitos empates | Aplicar teste | Usar wilcoxon() | p-valor, ranks | p < 0.05: mudança significativa | Power BI/BigQuery: R ou Python externo |
| Categórico | — | Qui-quadrado (χ²) | Verifica associação entre categorias. **Usado com dados categóricos. Exemplo: "A chance de um artista ganhar prêmio depende do gênero musical?"** | Ver se variáveis estão relacionadas | Gênero × presença em playlist | ✅ Tabela de frequência✅ Categorias independentes✅ Valores esperados > 5 | Fazer tabela cruzada | Contar frequências | p-valor, discrepância | p < 0.05: associação significativa | Power BI: CHISQ.TEST()BigQuery: criar tabela com COUNT(*), aplicar lógica χ² |
| Numérico x Numérico | Normal | Correlação de Pearson | Mede relação linear. **Mede relação linear entre duas variáveis. Ex: quanto maior o BPM, maior a popularidade?** | Ver se A cresce com B | BPM x Popularidade | ✅ 2 variáveis numéricas✅ Distribuição normal✅ Relação linear | Calcular r | Ver normalidade, aplicar pearsonr() | r e p-valor | r > 0 positiva, r < 0 negativap < 0.05: significativa | Power BI: CORREL()BigQuery: CORR(col1, col2) |
| Numérico x Numérico | Não normal | Spearman | Mede relação monotônica. **Mede relação em forma de ranking. Serve quando os dados não seguem uma linha reta nem distribuição normal.** | Relação sem assumir linearidade | Ex: relação entre tempo e engajamento | ✅ 2 variáveis numéricas✅ Ranking ou monotonicidade❌ Não exige normalidade | Calcular ρ | Usar spearmanr() | ρ e p-valor | ρ > 0 positiva, ρ < 0 negativap < 0.05: significativa | Power BI: R/Python visualBigQuery: externo |
| Numérico x Categórico (3+) | Normal | ANOVA | Compara médias entre 3+ grupos | Ver se há grupo diferente | Popularidade por gênero | ✅ 1 variável numérica, 1 categórica com ≥3 níveis✅ Normalidade e homogeneidade | Aplicar teste | Normalidade, variância homogênea | p-valor, médias | p < 0.05: pelo menos um grupo difere | Power BI: R/Python visualBigQuery: via Python |
| Numérico x Categórico (3+) | Não normal | Kruskal-Wallis | ANOVA sem suposição de normalidade | Mesmo que ANOVA com dados assimétricos | Popularidade por gênero (não normal) | ✅ 1 variável numérica, 1 categórica com ≥3 níveis❌ Não exige normalidade✅ Grupos independentes | Aplicar teste | Usar kruskal() | p-valor, ranks | p < 0.05: grupos diferentes | Power BI/BigQuery: via Python/R |

Guia: Etapas do processo de análise (Resumo visual)

- Identifique o tipo de dado (numérico, categórico, pareado ou não)
- Verifique a distribuição dos dados (normal ou não normal) com Shapiro-Wilk, histogramas, boxplots ou Q-Q plots
- Escolha o teste estatístico com base na tabela acima
- Prepare os dados conforme as exigências do teste
- Aplique o teste no ambiente (Power BI, BigQuery, Colab)
- Analise os resultados: p-valor, diferenças de média, coeficiente r ou ρ
- Tome decisões com base em significância (p < 0.05)

Guia: Tipos de gráficos

| **Método** | **O que é** | **O que preciso ter/fazer antes** | **Como organizar os dados** | **Como aplicar** | **Como interpretar** | **Observações** |
| --- | --- | --- | --- | --- | --- | --- |
| Histograma | Gráfico de barras que mostra a frequência de valores numéricos agrupados por faixas | ✅ Dados numéricos✅ Preferível ter amostra ≥ 30 para formar curva | Uma coluna com os dados | Power BI: Gráfico de histogramaExcel: Inserir → Gráfico de histograma | Se a curva for em forma de sino (simétrica), pode indicar normalidade | Pode ser subjetivo. Use junto com testes |
| Boxplot (diagrama de caixa) | Gráfico que mostra mediana, quartis e outliers dos dados | ✅ Dados numéricos✅ Amostra mínima razoável (~20+) | Uma coluna com os dadosOpcional: uma coluna com grupos (ex: gênero musical) | Power BI: Box and whisker chart (ou custom visual)Python: sns.boxplot() | Se simétrico e sem muitos outliers: possível normalidadeSe muito assimétrico: suspeite de não normalidade | Ótimo para comparar grupos (ex: popularidade por gênero) |
| Q-Q Plot (Quantile-Quantile Plot) | Gráfico que compara os quantis dos seus dados com os de uma distribuição normal | ✅ Dados numéricos✅ Sem valores faltantes✅ Amostra ≥ 30 | Uma coluna com os dados | Python: qqplot(dados, line='s')R/Python visual no Power BI | Se os pontos formam uma linha reta, os dados são normaisSe curvam, indicam assimetria | Muito visual e sensível a outliers |

Guia: Análise de gráficos de Dispersão e correlação 

![image.png](attachment:baa89ea8-c667-4a59-8f7e-51fe31284629:image.png)

- **1.0:** Correlação negativa perfeita (linha reta decrescente).
- **0.8 / -0.5:** Correlação negativa forte/moderada.
- **0.0:** Sem correlação (distribuição aleatória).
- **0.5 / 0.8:** Correlação positiva moderada/forte.
- **1.0:** Correlação positiva perfeita (linha reta crescente).

## Dúvidas e Perguntas e Respostas

## Feedback e opinião do cliente e partes interessadas
