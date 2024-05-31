## Exercícios do curso Universidade dos Dados.
### Nesse dataset, temos as informações de diversos pacientes (gênero, se é fumante, imc, etc) e seus gastos com saúde. Respondendo as questões em Python, utilizando o Jupyter Notebook:
1) Importe os dados e verifique as primeiras linhas do dataset. Verifique também as últimas linhas do dataset.

2) Verifique se existe algum valor missing no dataset.

3) Quanto de memória o dataset está consumindo?

4) Gere as estatísticas descritivas das colunas numéricas do dataset. Qual a mediana da coluna BMI? E a média? Qual desses valores é maior? O que isso significa? Caso não saiba o que isso significa, passe os 2 valores ao chatGPT e pergunte a ele o que significa a média ser maior ou menor que a mediana.

5) Qual a proporção de fumantes no nosso dataset? E de não fumantes?

6) Existe alguma diferença na cobrança para fumantes e não fumantes? Se sim, ao que você imagina que isso se deve?

7) Qual a média de BMI para fumantes? Ela é muito diferente da observada para fumantes? Se sim, por qual motivo você acha que isso ocorre?

8) Existe alguma diferença de cobrança para quem tem filhos? Identifique se ter filhos parece acarretar numa cobrança maior olhando a média de charges para quem tem 0 filhos e a média para quem tem 1 ou mais filhos.

9) Para nós seres humanos, o BMI de 20 a 24,9 é considerado normal. Acima disso, é considerado acima do peso, abaixo é considerado abaixo do peso. Crie uma nova coluna, chamada "bmi_male" que receberá o texto "abaixo do normal" para BMI abaixo de 20, "normal" para BMI de 20 a 24,9 e "acima do normal" para BMI acima de 24,9.

10) Se uma pessoa é fumante e ainda tem um BMI acima do considerado normal, é possível que isso seja um indicador negativo para a seguradora. Quantos homens estão nessa situação?
