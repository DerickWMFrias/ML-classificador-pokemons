Este código é o projeto de um classificador binário de 'tipo 1' de pokemons. Este classificador binário decide tipos de pokemons entre 'water type' e 'normal type'.

A classificação de pokemons é feita com base apenas nas características físicas e de saude dos pokemons. Além disto, a classificação dos pokemons será feita com a ajuda do Pikachu, um pokemon de tipo elétrico, sendo assim podemos usar a característica 'against_electric' dos pokemons no nosso classificador. Como não queremos que nosso Pikachu se machuque, descartamos no classificador os campos referentes aos ataques de cada pokemon. Por fim, o tipo secundário dos pokemons é ignorado.

O objetivo deste projeto é estudar o comportamento dos algoritmos SVM, Decision Tree, Random Forest e Linear Regression, com amostras de dados normalizadas e não-normalizadas.

O código é dividido em seções curtas, e deve ser executado sequencialmente.


Antes de executar, importe pokedata.csv.
Get pokedata.csv at https://www.kaggle.com/datasets/rounakbanik/pokemon