# Prevendo Fraudes

## Sobre o projeto
O projeto utiliza Machine Learning para prever se uma conta vai ter um fraude bancária ou não, sendo que foram utilizados três modelos diferentes de Machine Learning para conseguir a melhor versão. Foram utilizados os algoritmos RadomForest, SVM e KNE da biblioreca Scikit-Learn.

## Etapas do projeto
1 - Limpeza do dataset

2 - Engenharia de atributos

3 - Visualização dos dados categóricos e numéricos

4 - Modelos de Machine Learning

5 - Comparações entre os resultados

## Tecnologias e bibliotecas utilizadas
- Python
- pandas
- matplotlib
- seaborn
- numpy
- scikit-learn
- imblearn

## Melhorias
No geral toda a parte de limpeza, engenharia e visualização dos dados esta boa, porém para os modelos de Machine Learning é possível fazer algumas melhorias, como utilizar métricas diferentes para avaliar o ajuste geral do modelo ou até utilizar modelos diferentes.

## Conclusão
Todos os modelos utilizados nesse projeto foram testados em diferentes hiperparâmetros, sendo que os melhores deram esses resultados.
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
