# confusion-matrix

## Modelos de Machine Learning: Métricas de Avaliação de Desempenho

Este projeto foi desenvolvido como parte do curso "Modelos de Machine Learning: Métricas de Avaliação de Desempenho", oferecido pela DIO em parceria com a empresa BairesDev. O objetivo principal foi aprofundar os conhecimentos sobre as principais métricas de avaliação utilizadas em modelos de aprendizado supervisionado, com foco na análise de classificadores.

Durante o desenvolvimento, foi utilizado o conjunto de dados MNIST para treinar um modelo de rede neural convolucional, onde foram exploradas métricas como acurácia, sensibilidade, especificidade, precisão, F-score e matriz de confusão para avaliar o desempenho do modelo.

## Bibliotecas e Frameworks Utilizados

- **TensorFlow e Keras:** Para a construção, treinamento e avaliação do modelo de Machine Learning.
- **Matplotlib e Seaborn:** Para a visualização de métricas e criação de gráficos.
- **Pandas e NumPy:** Para manipulação e análise de dados.
- **TensorBoard:** Para monitoramento do treinamento e visualização das métricas.
- **IO e OS:** Para manipulação de arquivos e diretórios.
- **Scikit-learn:** Para cálculo das métricas de desempenho (como acurácia e sensibilidade) diretamente a partir da matriz de confusão.

## Notebook

O notebook utilizado no projeto está disponível neste repositório. Ele contém:

1. O pré-processamento dos dados do dataset MNIST.
2. A construção e treinamento de uma rede neural convolucional.
3. A análise detalhada das métricas de avaliação, incluindo a matriz de confusão.
4. Implementação de métodos automáticos para cálculo de acurácia e sensibilidade utilizando a biblioteca Scikit-learn.

## Resultados

O modelo desenvolvido atingiu uma acurácia de **99.80%** no conjunto de validação, demonstrando um desempenho excelente ao classificar os dígitos do dataset MNIST. Além disso, a sensibilidade foi analisada para cada classe, resultando em uma **sensibilidade média de 99.80%**, indicando que o modelo é altamente eficaz em identificar corretamente os dígitos reais.

Durante a análise, a matriz de confusão revelou pequenos erros de classificação entre dígitos similares (como 4 e 9), destacando a necessidade de:

- Ajustar hiperparâmetros para refinar o modelo.
- Ampliar o conjunto de dados com técnicas de aumento de dados (*data augmentation*).
- Explorar diferentes arquiteturas de redes neurais para melhorar ainda mais a generalização.

Adicionalmente, foi implementado um cálculo automatizado de métricas diretamente da matriz de confusão utilizando a biblioteca **Scikit-learn**, simplificando o processo de análise.

### **Gráficos e Resultados**

#### Matriz de Confusão
![image](https://github.com/user-attachments/assets/bd0cf1d0-61d4-4374-b0ed-a20be291650c)

#### Histograma do TensorBoard
![Histograma do TensorBoard](https://github.com/user-attachments/assets/dbd901cc-b49f-40cd-85e6-9d2c702b4aeb)

Essa experiência reforçou a importância de métricas de avaliação na criação de modelos confiáveis e eficientes. O aprendizado adquirido será aplicado em projetos futuros, fortalecendo minha base técnica em Machine Learning.

## Contato

Dúvidas ou sugestões? Entre em contato:

- **Email:** rafaellopes.dev@gmail.com
- **LinkedIn:** [Rafael Lopes](https://www.linkedin.com/in/rafael-lopes-desenvolvedor-fullstack/)
