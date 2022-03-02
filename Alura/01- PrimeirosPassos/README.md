# Primeiros passos com Python em ciência de dados
Neste curso da alura foi apresentado o básico de ciência da computação e possíveis insights para projetos futuros.

# Aula 1
Apresentação e import do pandas: import pandas as pd  
Leitura de arquivo csv: notas= pd.read_csv('ratings.csv')  
Apresentação das 5 primeiras linhass do arquivo lido: notas.head()  
Renomeação de colunas: notas.columns= ['usuarioId', 'filmeId', 'nota', 'momento']  
Leitura de apenas uma coluna do dataframe - série: notas['nota']  
Verificação de valores únicos na série: notas['nota'].unique()  

# Aula 2