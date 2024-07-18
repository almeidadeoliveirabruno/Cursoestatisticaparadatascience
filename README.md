# Cursoestatisticaparadatascience
Atividades realizadas no curso Estatística para Ciência de Dados e Machine Learning na udemy

Exercício 1:
O objetivo deste exercício é utilizar outra base de dados para testar as amostragens e comparar os resultados 
Faça o download e carregue a base de dados credit_data.csv, que possui informações sobre empréstimos (se o cliente pagará ou não pagará o empréstimo)
Teste cada uma das técnicas de amostragem, selecionando 1000 registros
Para a amostragem estratificada, utilize o atributo c#default para separar as categorias
No final, faça o comparativo da média utilizando os atributos age, income e loan.


Exercício 2:
O objetivo é fazer um algoritmo de previsão de reputação com base nos dados fornecidos.
Deve ser usando random forest.


Exercício 3:
O objetivo desta tarefa é encontrar algum tipo de relação entre o atributo education e o atributo income da base de dados do censo 
1)Carregue o arquivo census.csv
2)Crie um novo dataframe com o pandas utilizando somente esses dois campos
3)Você pode utilizar o comando groupby do pandas para agrupar os dados, ou seja, a quantidade de registros baseado nesses dois atributos. Acesse aqui a documentação
4)Identifique o nível de educação que possuem as maiores e menores rendas. Lembre-se que nesta base de dados a renda assume somente os valores >50 e <=50


Exercício 4:
O objetivo deste exercício é calcular o coeficiente e a taxa de evasão utilizando a tabela dísponivel no notebook. Faça os cálculos manuais e depois implemente em Python.


Exercício 5:
O objetivo desta tarefa é aplicar a distribuição de frequência utilizando o atributo age da base de dados do censo 
Carregue a base de dados census.csv 
Faça testes utilizando o parâmetro bins para visualizar a distribuição dos dados 


Exercício 6:
O objetivo desta tarefa é gerar as estatísticas para o atributo age da base de dados do censo;
Carregue o arquivo census.csv
Calcule a média aritmética, média harmônica, média geométrica, média quadrática, a mediana e a moda. Compare os resultados.


Exercício 7:
Nas aulas anteriores você aprendeu a dividir a base de dados entre treinamento e teste para avaliar os algoritmos de classificação. Porém, existe uma outra técnica que é mais utilizada no meio científico, que é a validação cruzada.
O objetivo deste exercício é aplicar a validação cruzada e comparar os resultados com a abordagem de treinamento e teste. 


Exercício 9:
Agora que você aprendeu os principais tipos de distribuições, o objetivo é utilizar a base de dados do censo para identificar as distribuições para cada um dos atributos. Para isso, carregue o arquivo census.csv e gere o histograma para cada atributo


Exercício 10:
Uma série de exercícios de probabilidade foram resolvidos utilizado python. 
Alguns deles possuem duas soluções devido ao enunciado não ser muito claro, gerando debates na página de dúvidas do curso. Por isso, esses problemas possuem ambas as soluções. 


Exercício 11:
Calculo do intervalo de confiança dos salários disponibilizados.


Exercício 12:
Assim como você pode fazer testes de hipóteses usando a estatística Z, é também possível utilizar a estatística T da Distribuição T Student para realizar testes de hipóteses quando você possui poucos registros (até 30 amostras). Implemente a base de dados abaixo com a alturas de somente 9 pessoas 
np.array([149. , 160., 147., 189., 175., 168., 156., 160., 152.])
Depois siga o seguinte roteiro: 
Crie uma nova variável também com alturas de 9 pessoas, porém, com valores diferentes .
Faça a importação do pacote from scipy.stats import ttest_rel para realizar o teste de hipótese. Caso tenha dúvidas, consulte aqui a documentação. 
Realize o teste de hipótese para verificar se as distribuições são ou não são diferentes.


Exercício 13:
Nas aulas anteriores nós fizemos os testes de hipóteses utilizando técnicas de estatística não paramétrica. Porém, como os resultados dos algoritmos seguem uma distribuição normal (conforme os testes de normalidade realizados), o objetivo desta tarefa é aplicar o ANOVA e também o teste de Tukey para comparar os resultados dos algoritmo.


Exercício 14:
Agora que você aprendeu o básico sobre correlação, é hora de aplicar esse conhecimento em uma base de dados real! Carregue a base de dados das casas (house-prices.csv) e gere as correlações entre todos os atributos. Quais atributos estão mais relacionados com o preço das casas?

Exercício 15:
Na aula anterior nós utilizamos somente 4 atributos para aplicar a regressão múltipla. O objetivo deste exercício é criar um modelo de regressão linear múltipla utilizando todos os atributos da base de dados. Compare os resultados entre os algoritmos