# Primeiros passos com Python em ciência de dados
Neste curso da alura foi apresentado o básico de ciência da computação e possíveis insights para projetos futuros.

# Aula 1
Apresentação do pandas e formas de navegar pelos dados    
Apresentação e import do pandas: `import pandas as pd`  
Leitura de arquivo csv: notas= `pd.read_csv('ratings.csv')`  
Apresentação das 5 primeiras linhass do arquivo lido: `notas.head()`  
Renomeação de colunas: `notas.columns= ['usuarioId', 'filmeId', 'nota', 'momento']`  
Leitura de apenas uma coluna do dataframe - série: `notas['nota']`  
Verificação de valores únicos na série: `notas['nota'].unique()`  

# Aula 2
Introdução às formas de plotagem e interpretação de dados    
Outra forma de acessar determinada coluna: `notas.nota`  
Plotagem de gráfico de linha: `notas.nota.plot()`  
Plotagem de gráfico tipo histograma: `notas.nota.plot(kind='hist')`  
Média de valores de uma coluna: `print(notas.nota.mean())`  
Meadiana de valores de uma coluna: `print(notas.nota.median())` 