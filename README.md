# README
# MARKDOWN
# 🚀 Projeto Integrador P15: Pipeline End-to-End de Delivery no Amapá

**Autores:** Soraia Costa da Costa  
**Disciplina:** Engenharia de Dados e Machine Learning  

## 🎯 Objetivo do Projeto
Desenvolver um pipeline completo de Engenharia de Dados e Machine Learning para prever atrasos nas entregas de uma startup de delivery operando no estado do Amapá.

## 🛠️ Arquitetura e Tecnologias
- **Coleta:** Simulação de duas fontes de dados (Sistema de Pedidos e API de Tráfego/Clima).
- **Armazenamento:** PostgreSQL (simulado via SQLite em memória para facilitar a execução no Colab).
- **ETL:** Python com a biblioteca Pandas.
- **Machine Learning:** Scikit-Learn (Random Forest e Logistic Regression).
- **Métricas:** F1-Score, Acurácia e Classification Report.

## ⚙️ Como Reproduzir a Solução
1. Abra o arquivo `notebook_final_p15.ipynb` no Google Colab.
2. Execute todas as células sequencialmente. O notebook é autossuficiente e irá:
   - Gerar os dados brutos e carregá-los no banco de dados.
   - Extrair e transformar os dados (ETL).
   - Criar as *features* e treinar os modelos.
   - Apresentar as métricas de avaliação e salvar o melhor modelo.

## 📊 Resultados e Conclusão
O modelo treinado é capaz de identificar padrões que levam a atrasos nas entregas (ex: distância, chuva, trânsito), permitindo que a startup otimize rotas e melhore a experiência do cliente.
