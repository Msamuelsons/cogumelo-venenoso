# Análise de Cogumelos Comestíveis

Este é um exemplo de análise de dados de cogumelos comestíveis usando Python e bibliotecas como pandas e scikit-learn.

![Cogumelo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQWdzZFTQcOZX9RX_lzUTXidbOqpkTQyV9hrg&usqp=CAU)
  
## Sobre o Projeto

Este projeto analisa um conjunto de dados de cogumelos para determinar se são comestíveis ou venenosos com base em várias características. O código a seguir realiza a análise e a construção de um modelo de classificação.

## Como Usar

1. Certifique-se de ter as bibliotecas necessárias instaladas:


2. Execute o código Python em seu ambiente de desenvolvimento. Certifique-se de que o arquivo de dados 'mushroom_dataset.csv' esteja no mesmo diretório.

3. O código realiza as seguintes etapas:

- Carrega o conjunto de dados.
- Aplica a codificação one-hot nas colunas categóricas.
- Divide os dados em recursos (X) e rótulos (y).
- Treina um modelo de classificação ExtraTreesClassifier.
- Exibe a importância das características.
- Plota um gráfico de barras mostrando a contagem de cogumelos comestíveis e venenosos.

4. O resultado da validação cruzada é impresso no console.

## Resultados

O modelo ExtraTreesClassifier é treinado e validado com uma taxa de acurácia média impressa no console.

Também são mostradas as características mais importantes e um gráfico de barras que exibe a contagem de cogumelos comestíveis e venenosos.

## Contribuições

Contribuições são bem-vindas! Se você deseja melhorar ou adicionar algo a este projeto, sinta-se à vontade para criar um fork e enviar um pull request.

## Licença

Este projeto é distribuído sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para obter detalhes.


