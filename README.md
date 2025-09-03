# 📊 Pipeline de Coleta e Armazenamento de Dados Financeiros

Este repositório contém um projeto em **Python** que coleta dados de ações da B3 a partir de duas fontes:

1. **[Fundamentus](http://www.fundamentus.com.br/resultado.php)** – informações fundamentalistas das empresas.
2. **[Yahoo Finance](https://finance.yahoo.com/)** – histórico de preços das ações.

Todos os dados são tratados, padronizados e salvos em um **banco de dados PostgreSQL** para futuras análises.

---

## 🚀 Funcionalidades
- Coleta automática dos dados fundamentalistas do site Fundamentus.
- Coleta do histórico de preços de ações do Yahoo Finance.
- Limpeza e padronização dos dados.
- Armazenamento dos resultados em tabelas no PostgreSQL.
- Consulta de verificação para checar se os dados foram salvos corretamente.

---

## 🛠️ Tecnologias utilizadas
- **Python 3**
- [Requests](https://docs.python-requests.org/) → para acessar os dados do site Fundamentus  
- [Pandas](https://pandas.pydata.org/) → manipulação e limpeza dos dados  
- [yFinance](https://pypi.org/project/yfinance/) → coleta dos preços históricos do Yahoo Finance  
- [SQLAlchemy](https://www.sqlalchemy.org/) → conexão com PostgreSQL  
- [PostgreSQL](https://www.postgresql.org/) → armazenamento dos dados  

