# Estudo-de-classificao_de_fraude
Um estudo realizando a aplicação de dois modelos de classificação KNN e Logit.

Foi utlizado dados do kangle cuja a base de dados se encontra https://www.kaggle.com/datasets/dhanushnarayananr/credit-card-fraud.

O trabalho buscou utilizar tecnicas de modelagem como padronização e normalização, para que assim entregasse da melhor maneira os dados  para os modelos. Além disso, buscou fazer uma comparação em relação a entregar dados normalizados a um modelo logit que espera receber dados padronizados, concluindo assim que a entrega incorreta pode afetar o poder de previsão do modelo.Isto posto, outra tecnica utlizada foi a do rebalanceamento dos dados, sendo feito também a utilização de diferentes tecnicas de separação de dados, como a Kflod e a train_test_split. 
Em relação a mensuração da capacidade de previsão dos dados foi utilizado classfication report que cria uma tabela que contem acuracia a o recall do modelo, util para ser saber o poder de previsão considerando os verdadeiros postivos, e assim não esta sujeito ao erro do tipo 2 em que classifca como incorreto dados corretos.
