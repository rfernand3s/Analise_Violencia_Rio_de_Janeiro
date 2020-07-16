<p align="center">
  <img src="https://raw.githubusercontent.com/ka1chou/sigmoidal_data_science/master/Screen%20Shot%202020-06-23%20at%2011.23.58.png" >
</p>

# Analise da Violencia no Rio de Janeiro

## Este projeto utiliza um dataset publico, analisa seus dados e produz estatísticas acerca da violência no estado do Rio de Janeiro.

Este é o projeto referente ao módulo II do curso "Data Science na Prática", da plataforma sigmoidal.ai

# **Analisando a criminalidade do Rio de Janeiro**

<img alt="Rio de Janeiro" width="40%" src="https://user-images.githubusercontent.com/45701541/87468069-514bd000-c5ef-11ea-8b51-b9c1c3a6dc06.png">



Independente se você é uma pessoa que assiste ou não aos telejornais, é provável que esteja consciente de que o Brasil, infelizmente, é um país com altos índices de criminalidade. No estado do Rio de Janeiro os dados nos mostram que essa realidade pode ser ainda pior se comparado à média nacional.

Hoje é possível consultar essas informações em sites oficiais do estado, pois estão disponibilizadas na Intenret. O governo do Rio de Janeiro, por exemplo, traz a iniciativa do [portal ISPDados](http://www.ispdados.rj.gov.br/) com essas informações.

No projeto deste Módulo, faremos uma análise acerca dos indicadores estatísticos da violência no Rio, explorando algumas das variáveis fornecidas.



### <center>**Análise Estatística: O retrato da violência no RJ**

<center><img alt="Rio de Janeiro" width="40%" src="https://user-images.githubusercontent.com/45701541/87477807-1f426a00-c5ff-11ea-9c15-403ea333e67d.png"></center>

Nesta parte começaremos a análise estatística do nosso _dataset_. Utilizaremos o método `describe()` para nos informar acerca da distribuição dos dados e para identificarmos a presença de **outliers** em nosso conjunto de dados.

_Outliers_ são valores que divergem em demasia do restante dos dados, e que podem nos levar a erros na interpretação do dataset. Uma das causas da existência de outliers podem ser erros de medição ou aquisição dos dados. Para ter acesso aos resultados, clique no link do [Jupyter Notebook](https://github.com/rfernand3s/Analise_Violencia_Rio_de_Janeiro/blob/master/Analisando_a_criminalidade_no_Rio_de_Janeiro.ipynb) deste repositório, e confira a análise completa.



<img alt="Rio de Janeiro" width="40%" src="https://user-images.githubusercontent.com/45701541/87597167-b541c780-c6c7-11ea-9ecc-bea9abe92f17.png">
No gráfico acima, alguns dados chamam a nossa atenção, como:

* Houve quase 70 meses com 500-550 homicídios dolosos registrados ao longo do período em estudo.
* Houve menos de 10 meses ao longo de todo o período estudado na casa de 800 registros de homicídio doloso.






## **Conclusão**

A principal lição aprendida aqui foi a necessidade de se atentar a cada detalhe do seu *dataset* quando se está lidando com dados reais, extraídos diretamente de sites e portais com dados abertos.

A etapa de aquisição, tratamento e exploração dos dados é o que mais vai consumir o tempo do seu projeto, por isso é necessário dedicar a devida atenção nessa parte para não comprometer os resultados.

No mais, concluímos o projeto referente ao módulo II do curso "Data Science na pratica" do sigmoidal. Este projeto proporcionou aos alunos uma visão mais clara e objetiva da importância da ciência de dados. Tratando-se de dados oficiais do governo do estado, podemos sugerir, por exemplo, um modelo de políticas publicas, tendo em vista novas diretrizes para as quais os órgãos de segurança devem se focar ou otimizar seus resultados. 

Este trabalho contudo, ainda não é profundo o suficiente para tal, mas indica que é possível ser feito e que a ciência de dados é uma ferramenta para interpretação da realidade com base nos dados que são coletados.



