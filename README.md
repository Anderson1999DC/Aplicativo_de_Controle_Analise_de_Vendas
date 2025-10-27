💼 SalesApp — Dashboard Interativo de Vendas

O SalesApp é um aplicativo web desenvolvido em Python 
utilizando o Streamlit Cloud, com o objetivo de analisar, 
visualizar e gerenciar dados de vendas de forma interativa e intuitiva.

🧠 Objetivo do Projeto
Demonstrar a aplicação prática das principais etapas do fluxo de Análise de Dados, incluindo:
Coleta e integração de dados (ETL) com arquivos CSV.
Limpeza e tratamento de dados com Pandas e NumPy.
Modelagem e criação de visualizações com Plotly e Matplotlib.
Construção de interface web com Streamlit, dividida em múltiplas páginas.
Deploy do aplicativo na nuvem via Streamlit Cloud.

⚙️ Funcionalidades Principais
Visão geral com KPIs de desempenho de vendas, produtos e filiais.
Visualização dinâmica com filtros interativos.
Tabelas de dados com atualização em tempo real.
Página de gerenciamento para adição e remoção de vendas.
Design responsivo e intuitivo, ideal para demonstrações em análise de negócios.

🧩 Tecnologias e Bibliotecas Utilizadas
Python → Linguagem principal do projeto.
Streamlit → Framework para criação da interface web interativa.
Pandas → Manipulação, limpeza e estruturação dos dados.
NumPy → Operações numéricas e vetorização de cálculos.
Plotly → Visualizações gráficas dinâmicas e interativas.
Matplotlib → Gráficos complementares e personalização visual.
Datetime → Manipulação e filtragem de dados por período.
OS / Pathlib → Gerenciamento de diretórios e leitura de arquivos.
CSV → Armazenamento e leitura de dados simulados.

🧰 Estrutura do Projeto
SalesApp/
│
├── Home.py                 # Arquivo principal do aplicativo Streamlit
├── datasets/               # Bases de dados (filiais, produtos e vendas)
├── pages/                  # Páginas do app (visão geral, visualização, tabelas, adição e remoção de vendas.)
├── gerador_vendas.py       # Script para geração de dados simulados
├── utilidades.py           # Funções utilitárias reutilizáveis (tratamento, cálculo e formatação de dados)
├── requirements.txt        # Dependências do projeto
└── README.md               # Documentação do projeto

📈 Aprendizados e Resultados
Durante o desenvolvimento do SalesApp, foram consolidados conhecimentos em:
Estruturação de projetos em Python voltados para análise de dados.
Modularização de código e reutilização de funções com utils.py.
Criação de dashboards interativos com foco em usabilidade e performance.
Aplicação de lógica de negócios e storytelling com dados.
Deploy e versionamento de aplicações com GitHub e Streamlit Cloud.

🔗 Deploy Online
Acesse o projeto completo em:
https://salesapp32.streamlit.app/
