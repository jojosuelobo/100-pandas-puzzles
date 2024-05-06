[Informações do desafio](Challenge.md)

### Como exibir dados de um DataFrame
#### **Info()**
```cmd
<class 'pandas.core.frame.DataFrame'>
Index: 10 entries, a to j
Data columns (total 4 columns):
 #   Column    Non-Null Count  Dtype  
---  ------    --------------  -----  
 0   animal    10 non-null     object 
 1   age       8 non-null      float64
 2   visits    10 non-null     int64  
 3   priority  10 non-null     object 
dtypes: float64(1), int64(1), object(2)
memory usage: 400.0+ bytes
```

#### describe()
|       |  age  |   visits     |   
|------:|---------:|-----------|
| count | 8.000000 | 10.000000 |   
|  mean | 3.437500 |  1.900000 |   
|   std | 2.007797 |  0.875595 |   
|   min | 0.500000 |  1.000000 |   
|   25% | 2.375000 |  1.000000 |   
|   50% | 3.000000 |  2.000000 |   
|   75% | 4.625000 |  2.750000 |   
|   max | 7.000000 |  3.000000 |   

#### print()
Útil para DataFrames pequenos, mas não é recomendado para DataFrames grandes, pois pode sobrecarregar a saída do console
|   | animal | age | visitors | priority |
|--:|-------:|----:|----------|---------:|
| a |    cat | 2.5 | 1        | yes      |
| b |    cat | 3.0 | 3        | yes      |
| c |  snake | 0.5 | 2        | no       |
| d |    dog | NaN | 3        | yes      |
| e |    dog | 5.0 | 2        | no       |
| f |    cat | 2.0 | 3        | no       |
| g |  snake | 4.5 | 1        | no       |
| h |    cat | NaN | 1        | yes      |
| i | dog    | 7.0 | 2        | no       |
| j | dog    | 3.0 | 1        | no       |