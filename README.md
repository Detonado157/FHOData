Primeiro projeto desenvolvido em Python para tratamento de dados envolvendo a biblioteca Pandas junto a técnicas de modelagem estatística como regressão linear.

Inicialmente carregamos nosso dataset com o pandas, denominado mydataset.csv. Com ele carregado conseguimos utilizar o DataFrame gerado.

Com o DF, aplicamos ele a função heatmap da biblioteca seaborn, ele transforma nosso DF em uma "matriz de correlação" ja com os dados tratados e somente com as variaveis que precisamos. A funcão corr() calcula a correlação entre as variáveis do DF (variando entre 1 e -1).

Depois, aplicamos nossos coeficientes x e y a instancia criada da classe LinearRegression gerando nosso coenficientes angular e linear.

Com o matplotlib.pyplot apresentamos a equação y = a + bx gerando a reta da regressao linear.

