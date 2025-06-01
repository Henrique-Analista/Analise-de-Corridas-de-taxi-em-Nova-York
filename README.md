Análise de Corridas de Táxi em Nova York

Este repositório apresenta um projeto completo de análise de dados de corridas de táxi na cidade de Nova York, desenvolvido em Python e Power BI. O objetivo é demonstrar um fluxo de trabalho profissional, desde o pré-processamento até a entrega de dashboards interativos.

📋 Conteúdo do Projeto

dados/: scripts para download ou amostras do dataset (yellow_tripdata_2025-01.parquet e versão limpa em CSV).

notebooks/: Jupyter notebooks com código em Python para:

Leitura e limpeza de dados (pandas).

Criação de colunas auxiliares e identificação de outliers.

Análise exploratória e geração de gráficos iniciais.

powerbi/: arquivo TaxiAnalysis.pbix do Power BI com as três páginas de dashboard:

Visão Geral (KPIs e visão executive).

Análise por Faixa de Distância e Horário.

Detecção de Corridas Suspeitas.

images/: prints de tela dos dashboards, para ilustrar no README.

linkedin/: material para post no LinkedIn (texto e descrições de imagem).

PDF/: relatório final em PDF com todas as visualizações e contexto.

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



📜 Licença

Este projeto está licenciado sob a MIT License.
