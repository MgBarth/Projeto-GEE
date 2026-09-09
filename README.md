# Inventário Brasileiro de Emissões de Gases de Efeito Estufa

## Sobre o projeto

Este projeto tem como foco a análise das emissões de Gases de Efeito Estufa (GEE) no Brasil a partir de dados históricos do inventário nacional.

Nesta primeira etapa, a análise está concentrada na **Região Sul do Brasil**, permitindo observar a evolução das emissões ao longo dos anos, comparar estados e identificar os setores e atividades que mais contribuem para as emissões e remoções de GEE.

O projeto também busca transformar uma base de dados extensa e complexa em informações mais acessíveis por meio de análises e visualizações.

## Objetivo

O principal objetivo é identificar padrões e tendências nas emissões de GEE, permitindo responder questões como:

- Como as emissões evoluíram ao longo do tempo?
- Quais estados apresentam os maiores volumes de emissão?
- Quais setores são responsáveis pelas maiores emissões?
- Quais atividades possuem maior participação dentro desses setores?
- Como as remoções de carbono influenciam a emissão líquida?
- Quais segmentos apresentam maior potencial para redução ou compensação de emissões?

## Escopo atual

A primeira versão do projeto está concentrada nos estados da **Região Sul**:

- Paraná;
- Santa Catarina;
- Rio Grande do Sul.

A análise permite trabalhar tanto com cada estado individualmente quanto com os dados consolidados da região.

O período disponível atualmente compreende dados históricos até **2024**.

## Dados

Os dados originais são disponibilizados em arquivos CSV e passam por etapas de tratamento e otimização antes de serem utilizados nas análises.

Entre as principais etapas estão:

- padronização dos tipos de dados;
- tratamento e organização das variáveis;
- transformação dos dados para facilitar análises temporais;
- redução do consumo de memória;
- consolidação das bases dos estados da Região Sul;
- armazenamento dos dados processados em formato **Parquet**.

O uso de Parquet busca melhorar principalmente a velocidade de leitura e a eficiência no consumo dos dados durante as análises.

## Análises e visualizações

O projeto busca explorar as emissões em diferentes níveis de granularidade, incluindo:

- evolução histórica das emissões;
- emissão total e emissão líquida;
- comparação entre estados;
- comparação entre setores;
- participação das diferentes fontes de emissão;
- remoções de GEE;
- identificação de tendências e mudanças ao longo do tempo.

A proposta é disponibilizar essas análises por meio de uma aplicação desenvolvida em **Streamlit**, permitindo que o usuário navegue pelos períodos, estados e diferentes categorias dos dados.

## Impacto para o mercado de crédito de carbono

Além da análise ambiental, o projeto possui uma perspectiva de aplicação de negócio voltada ao **mercado de créditos de carbono**.

A identificação dos estados, setores e atividades com maiores níveis de emissão pode ajudar a direcionar análises para segmentos com maior potencial de redução, compensação ou desenvolvimento de projetos relacionados ao carbono.

Essas informações podem servir como ponto de partida para empresas e profissionais do setor na identificação de:

- setores com maior concentração de emissões;
- atividades com potencial para projetos de redução de GEE;
- regiões relevantes para prospecção de oportunidades;
- mudanças históricas no perfil de emissão;
- potenciais mercados para soluções de descarbonização e compensação.

Dessa forma, o projeto busca ir além da visualização dos dados, conectando a análise de emissões a **possíveis oportunidades de negócio e tomada de decisão no mercado de carbono**.

## Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Parquet / PyArrow
- Streamlit
- Git e GitHub

## Status do projeto

🚧 **Em desenvolvimento**

O projeto será atualizado progressivamente conforme novas etapas de tratamento, análise, visualização e desenvolvimento da aplicação forem concluídas.

## Fonte de dados

Fonte: SEEG – Sistema de Estimativa de Emissões e Remoções de Gases de Efeito Estufa, Observatório do Clima, acessado em [data] – seeg.eco.br”.
Data da última atualização: 17/12/2025 (13.0)