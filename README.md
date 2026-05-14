# 📊 Análise de Correlação Estatística: Logística e Transportes

Este projeto faz parte de uma atividade acadêmica de **Ciência de Dados**, focada na aplicação de técnicas de correlação (**Pearson** e **Spearman**) para entender as relações entre variáveis em um cenário realista de logística.

## 📝 Descrição do Cenário
O conjunto de dados fictício simula o desempenho de uma frota de transporte de cargas com 100 observações. O objetivo é analisar como a **distância percorrida** impacta outros indicadores operacionais e financeiros.

### Variáveis do Dataset:
*   **distancia_percorrida_km**: Quilometragem total da rota (Variável de Interesse).
*   **tempo_viagem_horas**: Tempo gasto para completar o percurso.
*   **eficiencia_combustivel_kml**: Média de consumo de combustível (km/l).
*   **custo_manutencao_rs**: Gastos com manutenção preventiva/corretiva.
*   **idade_motorista_anos**: Idade do condutor (Variável de controle/ruído).

## 🚀 Tecnologias Utilizadas
*   **Python 3.x**
*   **Pandas**: Manipulação e tratamento de dados.
*   **Seaborn & Matplotlib**: Visualização de dados e matrizes de correlação.
*   **Numpy**: Geração de dados sintéticos e cálculos estatísticos.

## 🔍 Principais Insights
*   **Correlação Forte Positiva**: Observou-se que o tempo de viagem e o custo de manutenção crescem proporcionalmente à distância.
*   **Correlação Negativa**: A eficiência de combustível tende a diminuir em rotas mais longas no cenário proposto.
*   **Relações Não Lineares**: Identificamos que o custo de manutenção possui um crescimento acelerado (exponencial) em relação à quilometragem, sendo um ponto ideal para comparar a sensibilidade de Pearson vs. Spearman.
*   **Ausência de Correlação**: A idade do motorista não apresentou vínculo estatístico com o desempenho da rota, validando a integridade dos dados aleatórios.

## 📂 Como Executar
1. Clone este repositório.
2. Certifique-se de ter o arquivo `logistica_transporte.csv` no mesmo diretório.
3. Abra o notebook no **Google Colab** ou ambiente Jupyter local.
4. Execute as células para gerar a matriz de correlação e os gráficos de dispersão.

---
📌 *Projeto desenvolvido por Rafael Henrique (Captano) para a disciplina de Ciência de Dados - Faculdade Senac PE.*
