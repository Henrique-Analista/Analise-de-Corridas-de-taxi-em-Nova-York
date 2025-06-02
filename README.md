Análise de Corridas de Táxi em Nova York

Este repositório apresenta um projeto completo de análise de dados de corridas de táxi na cidade de Nova York, desenvolvido em Python e Power BI. O objetivo é demonstrar um fluxo de trabalho profissional, desde o pré-processamento até a entrega de dashboards interativos.

📋 Conteúdo do Projeto

dados/: Link para os dados originais do site do governo de Nova-York: https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page,
Link para as pastas com os arquivos(dados e relatório): https://drive.google.com/drive/folders/1e3gI3Ko1H4cv_JP6HC9j5_1lXXZuC1IS?usp=sharing

notebooks/: Jupyter notebooks com código em Python para:

Leitura e limpeza de dados (pandas).

Criação de colunas auxiliares e identificação de outliers.

Análise exploratória e geração de gráficos iniciais.

powerbi/: arquivo TaxiAnalysis.pbix do Power BI com as três páginas de dashboard:

Visão Geral (KPIs e visão executive).

Análise por Faixa de Distância e Horário.

Detecção de Corridas Suspeitas.

🚀 Como Usar

Clone o repositório:

git clone https://github.com/seu-usuario/nyc-taxi-analysis.git
cd nyc-taxi-analysis

Pré-processamento (Python):

Instale as dependências:

pip install pandas matplotlib seaborn pyarrow

Execute o notebook notebooks/1_data_preparation.ipynb para gerar dados/dados_limpos.csv.

Análise no Power BI:

Abra powerbi/TaxiAnalysis.pbix no Power BI Desktop.

Navegue pelas páginas do dashboard e explore os filtros interativos.

Visualização e Relatório:

Confira as imagens em images/ ou abra PDF/Relatorio_Final.pdf.

🎯 Principais Insights

Picos de demanda: corridas concentram-se de terça a quinta, entre 17h e 19h.

Gorjetas: passageiros pagam mais gorjetas em corridas de maior distância.

Outliers: >2,5 milhões de registros inconsistentes foram identificados e filtrados.

🤝 Contribuições

Contribuições são bem-vindas! Abra uma issue ou envie um pull request para melhorias no código, dashboards ou documentações.
