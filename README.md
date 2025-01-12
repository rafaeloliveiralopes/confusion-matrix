# confusion-matrix

## Machine Learning - Cálculos de Métricas de Avaliação de Aprendizado

Este projeto foi desenvolvido como parte do curso "Modelos de Machine Learning: Métricas de Avaliação de Desempenho", oferecido pela DIO em parceria com a empresa BairesDev. O objetivo principal foi aprofundar os conhecimentos sobre as principais métricas de avaliação utilizadas em modelos de aprendizado supervisionado, com foco na análise de classificadores.

Durante o desenvolvimento, foi utilizado o conjunto de dados MNIST para treinar um modelo de rede neural convolucional, onde foram exploradas métricas como acurácia, sensibilidade, especificidade, precisão, F-Score e matriz de confusão para avaliar o desempenho do modelo.

## Bibliotecas e Frameworks Utilizados

- **TensorFlow e Keras:** Para a construção, treinamento e avaliação do modelo de Machine Learning.
- **Matplotlib e Seaborn:** Para a visualização de métricas e criação de gráficos.
- **Pandas e NumPy:** Para manipulação e análise de dados.
- **TensorBoard:** Para monitoramento do treinamento e visualização das métricas.
- **IO e OS:** Para manipulação de arquivos e diretórios.
- **Scikit-learn:** Para cálculo das métricas de desempenho (como acurácia, sensibilidade, especificidade, precisão e F-Score) diretamente a partir da matriz de confusão.

## Notebook

O notebook utilizado no projeto está disponível neste repositório. Ele contém:

1. O pré-processamento dos dados do dataset MNIST.
2. A construção e treinamento de uma rede neural convolucional.
3. A análise detalhada das métricas de avaliação, incluindo a matriz de confusão.
4. Implementação de métodos automáticos para cálculo de acurácia, sensibilidade, especificidade, precisão e F-Score utilizando a biblioteca Scikit-learn.

## Resultados

O modelo desenvolvido atingiu os seguintes resultados no conjunto de validação:

- **Acurácia:** **99.90%**, indicando um desempenho excelente ao classificar os dígitos do dataset MNIST.
- **Sensibilidade Média:** **99.90%**, demonstrando que o modelo é altamente eficaz em identificar corretamente os dígitos reais.
- **Especificidade Média:** **99.98%**, mostrando que o modelo possui alta capacidade de identificar corretamente os casos negativos, evitando falsos positivos.
- **Precisão Média:** **99.90%**, evidenciando a eficácia do modelo em prever os casos positivos corretamente.
- **F1-Score Médio:** **99.90%**, refletindo um excelente equilíbrio entre precisão e sensibilidade.

Adicionalmente, foi implementado um cálculo automatizado de métricas diretamente da matriz de confusão utilizando a biblioteca **Scikit-learn**, simplificando o processo de análise.

### **Gráficos e Resultados**

#### Cálculo da Acurácia Usando a Matriz de Confusão
![Imagem do cálculo da acurácia do modelo](https://github.com/user-attachments/assets/c0b2da63-152d-42ce-887e-692e5eaa04fe)


#### Visualização da Matriz de Confusão com Heatmap
![image](https://github.com/user-attachments/assets/5bffc9b6-145d-4ade-aff2-f1f8e3b18224)

Essa experiência reforçou a importância de métricas de avaliação na criação de modelos confiáveis e eficientes. O aprendizado adquirido será aplicado em projetos futuros, fortalecendo minha base técnica em Machine Learning.

## Contato

Dúvidas ou sugestões? Entre em contato:

- **Email:** rafaellopes.dev@gmail.com
- **LinkedIn:** [Rafael Lopes](https://www.linkedin.com/in/rafael-lopes-desenvolvedor-fullstack/)
