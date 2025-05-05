Python Insights - Analisando Dados com Python
Case: Cancelamento de Clientes
Uma empresa com mais de 800 mil clientes observou que grande parte da sua base está inativa (cancelou o serviço). Fui contratado para identificar os principais motivos por trás desses cancelamentos e propor ações eficazes para reduzir esses números.

Objetivo
Analisar os dados de cancelamento de clientes utilizando Python para:

Entender os principais fatores que influenciam o cancelamento.

Visualizar padrões através de gráficos interativos.

Propor ações práticas que podem reduzir a taxa de churn.

Tecnologias Utilizadas
Python 3.x

Pandas

Plotly

Como usar
Clone o repositório:

bash
Copiar código
git clone https://github.com/SEU-USUARIO/python-insights-cancelamento-clientes.git
Instale as bibliotecas necessárias:

bash
Copiar código
pip install pandas plotly openpyxl numpy nbformat ipykernel
Abra o notebook cancelamento_clientes.ipynb em um ambiente como Jupyter, VS Code ou Google Colab.

Etapas da Análise
Importação da base de dados

Limpeza e tratamento dos dados

Análise geral da taxa de cancelamento

Análise detalhada por coluna com gráficos

Identificação de padrões de risco

Simulação de ações para redução do churn

Principais Conclusões
Clientes que ligaram mais de 4 vezes para o call center têm alta chance de cancelar.

Clientes com contrato mensal cancelam com muito mais frequência.

Clientes que atrasam mais de 20 dias acabam cancelando.

Estratégias como descontos em contratos anuais, alertas após a terceira ligação e ação do time de cobrança a partir de 10 dias de atraso podem reduzir drasticamente o cancelamento.