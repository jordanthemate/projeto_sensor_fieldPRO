Calibração de Sensor de Chuva

Este é o repositório para a criação de um sensor de chuva baseado em impactos mecânicos da empresa FieldPRO.



O objetivo deste projeto foi construir um modelo de calibração de um sensor de chuva usando dados de um piezoelétrico, um acumulador de carga e um sensor de temperatura. Os dados são transmitidos de hora em hora e incluem a carga do acumulador, a temperatura da placa, o número de resets da placa e as condições atmosféricas do ambiente.

## Etapas do Projeto

1. Análise Exploratória de Dados (EDA)
   - Verificação da estrutura dos dados
   - Tratamento de dados ausentes
   - Visualizações preliminares dos dados

2. Pré-processamento de Dados
   - Transformações necessárias nos dados para o treinamento do modelo
   - Lidar com dados ausentes
   - Normalização ou padronização de variáveis, se necessário

3. Treinamento do Modelo de Regressão Linear
   - Criação e treinamento do modelo de regressão
   - Avaliação do desempenho do modelo usando MSE e R2

4. Visualização das Previsões
   - Comparação das previsões do modelo com os valores reais
   - Visualização das previsões em um gráfico de linhas

5. Análise dos Resíduos
   - Verificação da normalidade dos resíduos
   - Identificação de padrões não explicados pelos dados

6. Importância das Features
   - Análise da importância relativa das variáveis na calibração do sensor

## Resultados

- Mean Squared Error (MSE): 0.0021612811786517424
- R-squared (R2): 0.9483135915152914


## Observações

Este projeto foi concluído utilizando a linguagem de programação Python, utilizando bibliotecas como pandas, numpy, scikit-learn e matplotlib. O modelo de regressão utilizado foi linear e Árvore de Decisão, foram realizadas análises de desempenho e visualizações para compreender a calibração do sensor de chuva.

## Contato

Em caso de dúvidas ou feedback, entre em contato através do e-mail: jordanmatos98@gmail.com.
