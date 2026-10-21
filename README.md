# Analise Exploratória de ações da B3 com foco no setor Bancário


# Análise Fundamentalista de Bancos da B3 📊🏦

Este repositório contém um projeto de Análise Exploratória de Dados (EDA) focado nos principais indicadores financeiros do setor bancário listado na B3. O objetivo é aplicar ferramentas de Data Analytics para avaliar cenários, criar narrativas visuais e identificar oportunidades com base em métricas de valuation, rentabilidade e proventos.

## 🎯 Objetivos da Análise
- **Panorama de Mercado:** Mapear os maiores bancos brasileiros por Valor de Mercado, removendo distorções (ex: exclusão da *holding* Itaúsa).
- **Geração de Renda:** Identificar e destacar o Top 10 de instituições financeiras com os maiores *Dividend Yields (DY)*.
- **Matriz de Oportunidades (P/L vs. ROE):** Construir um gráfico de dispersão cruzando o múltiplo de preço (P/L) com o retorno sobre o patrimônio (ROE), identificando visualmente os ativos mais descontados e com maior rentabilidade.
- **Valuation por Benjamin Graham:** Aplicar a clássica fórmula de Graham (`VI = √(22.5 * LPA * VPA)`) para calcular o Valor Intrínseco e a respectiva Margem de Segurança dos papéis.

## 🛠️ Tecnologias e Bibliotecas Utilizadas
- **Linguagem:** Python 3 (Jupyter Notebook / Google Colab)
- **Manipulação e Limpeza de Dados:** Pandas, NumPy
- **Visualização de Dados e Storytelling:** Matplotlib, Seaborn
- **Otimização Gráfica:** adjustText (para organização automática de rótulos nos gráficos de dispersão)

## 📂 Estrutura da Base de Dados
A análise consome uma base de indicadores fundamentalistas contendo dezenas de métricas. As colunas principais trabalhadas no processo de ETL e visualização incluem:
- Preço de Cotação, `VPA` (Valor Patrimonial por Ação) e `LPA` (Lucro por Ação)
- Múltiplos de Valuation: `P/L` (Preço/Lucro) e `P/VP` (Preço/Valor Patrimonial)
- Rentabilidade e Proventos: `ROE` (Return on Equity) e `DY` (Dividend Yield)

## 🚀 Como Executar o Projeto
1. Clone este repositório para o seu ambiente local:  https://github.com/Vitor-neia/Analise-Exploratoria-de-acoes-da-B3-com-foco-no-setor-Bancario.git
   ```bash
git clone  

pip install pandas numpy matplotlib seaborn adjustText
Abra o arquivo .ipynb no seu editor de preferência (VS Code, Jupyter ou Google Colab).
Certifique-se de que a base de dados .csv esteja no diretório correto configurado no script e execute as células sequencialmente.  

⚠️ Aviso Legal
Este projeto foi desenvolvido com fins estritamente educacionais e para demonstração de habilidades práticas na construção de soluções em Ciência de Dados. Os resultados da análise não constituem recomendação de compra, venda ou manutenção de ativos financeiros.

Desenvolvido com foco na extração de insights acionáveis e modelagem analítica a partir de dados reais do mercado financeiro.
