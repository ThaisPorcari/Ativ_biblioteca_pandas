# 📊 Análise de Dados de Shows e Eventos com Python

Este projeto consiste em uma análise exploratória de dados (EDA) de uma base de eventos musicais e shows no Brasil. Utilizando a biblioteca **Pandas**, o objetivo é extrair insights sobre a venda de ingressos, faturamento (receita), taxas de ocupação dos locais e o perfil do público por artista, gênero musical e cidade.

## 🚀 Funcionalidades e Métricas Calculadas

No notebook, realizamos as seguintes etapas e análises:
* **Ficha Técnica dos Dados:** Inspeção dos tipos de variáveis, detecção de valores nulos e resumo geral com `info()`. 
* **Estatística Descritiva (Quantitativa):** Análise de médias, valores mínimos/máximos e desvio padrão para o preço médio dos ingressos, ingressos vendidos e capacidade dos locais.
* **Estatística Descritiva (Qualitativa):** Identificação de frequências, cidades mais comuns (ex: São Paulo) e gêneros dominantes.
* **Novas Métricas Geradas:**
  * **Faturamento/Receita Estimada:** Calculada multiplicando a quantidade de ingressos vendidos pelo preço médio do ingresso.
  * **Taxa de Ocupação (%):** Proporção de público presente em relação à capacidade total do local do evento.
* **Exportação:** Salvamento automático da nova base enriquecida em formato `.csv` (`Shows_eventos_novo.csv`).

## 🛠️ Tecnologias Utilizadas

* **Python 3**
* **Pandas** (Análise e manipulação de dados)
* **Google Colab** (Ambiente de desenvolvimento)

## 📂 Estrutura do Projeto

├── shows_eventos.csv # Base de dados bruta (input) ├── Shows_eventos_novo.csv # Base de dados limpa e calculada (output) ├── analise_eventos.ipynb # Notebook com os códigos em Python └── README.md # Documentação do projeto


## 📈 Exemplo de Insights Obtidos

* **Cidade Destaque:** São Paulo se consolida como a cidade com maior frequência de grandes eventos na base analisada.
* **Gênero Pop:** Lidera em recorrência e volume de shows dentre as categorias registradas.
* **Eficiência de Vendas:** O cálculo da *taxa de ocupação* permite identificar quais artistas têm maior poder de atração de público em relação ao espaço disponível.

## 🔧 Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
Abra o arquivo .ipynb no Google Colab ou em seu ambiente Jupyter local.
Certifique-se de fazer o upload do arquivo shows_eventos.csv para a mesma pasta do script.
Execute todas as células para ver os resultados e gerar a nova base calculada.
