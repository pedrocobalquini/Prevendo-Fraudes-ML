# Prevendo Fraudes

## Sobre o projeto

O projeto utiliza Machine Learning para prever se uma conta vai ter um fraude bancária ou não, sendo que foram utilizados três modelos diferentes de Machine Learning para conseguir a melhor versão. Foram utilizados os algoritmos RadomForest, SVM e KNE da biblioreca Scikit-Learn.

## Etapas do projeto

1 - Limpeza do dataset

2 - Engenharia de atributos

3 - Visualização dos dados categóricos e numéricos

4 - Modelos de Machine Learning

5 - Comparações entre os resultados

## Projeto

### 1 - Limpeza do dataset

Nesta primeira etapa foram visualizados os dados para ter uma noção dos valores de cada variável, sabendo quais poderiam ter valores nulos, sendo que aqui, a variável 'QT_Dias_Atraso' tinha muitos valores nulos e eles foram substituídos com a mediana da mesma variável.

A engenharia de atributos ocorreu na primeira etapa também principalmente nas variáveis 'Idade', 'Faixa salarial', 'Quantidade de dias em atraso', 'Faixa prazo emprestimo' e 'Faixa prazo restante' em que foram agrupadas em certos valores para facilitar o modelo futuramente.

### 2 - Novo dataset 

Nesta etapa foi criado um novo conjunto de dados com as colunas mais relevantes para o modelo, sendo que foram retiradas as variáveis sem relevância, como 'Contrato' e 'Data_Contratação'.

### 3 - Visualização dos dados

Primeiramente foram os dados categóricos do conjunto de dados em comparação com a variável alvo. Em sequência foram os dados numéricos para visualizar possíveis outliers.

Após tudo isso foi realizado o OneHotEncoder em todas variáveis do tipo 'object' e 'category' e foi realizado o balanceamento da variável alvo e a separação dela com as demais do conjunto de dados.

### 4 - Modelos de machine learning
#### 4.1 - RadomForest

O primeiro dos três modelos utilizados no projeto, em que coloquei diferentes parâmetros para teste. Como resultado, ele teve uma acurácia de 99.30% em treinamento, com 324 treinos realizados e exibindo os melhores hiperparâmetros.

#### 4.2 - SVM

O segundo dos três modelos utilizados no projeto, em que coloquei diferentes parâmetros para teste. Como resultado, ele teve uma acurácia de 99.07% em treinamento, com 1536 treinos realizados e exibindo os melhores hiperparâmetros.

#### 4.3 - KNN

O terceiro e último modelos utilizados no projeto, em que coloquei diferentes parâmetros para teste. Como resultado, ele teve uma acurácia de 97.47% em treinamento, com 120 treinos realizados e exibindo os melhores hiperparâmetros.

### Conclusão
<body>
    <table>
        <tr>
            <th>Modelos</th>
            <th>RF</th>
            <th>SVM</th>
            <th>KNN</th>
        </tr>
        <tr>
            <td>Modelos Treinados</td>
            <td>324</td>
            <td>1536</td>
            <td>120</td>
        </tr>
        <tr>
            <td>Melhor Score</td>
            <td>99.3%</td>
            <td>99.07%</td>
            <td>97.47%</td>
        </tr>
    </table>
</body>
