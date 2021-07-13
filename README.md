# Diferenca_Entre_Modelo_vs_previsor

Esse código gera um dataframe com os dados extraidos do https://openweathermap.org/, através do nome da cidade. Com a tabela csv a segunda parte do código destina-se a realizar um comparativo de previsões entre o modelo e o previsor, calculando seu percentual de diferença. O projeto está em andamento, com posterior agregação dos dados de superfície.

Requirimentos:
import pandas as pd (versão: 0.24.2)
import pyowm (versão: 2.10.0)
import requests, json
import matplotlib.pyplot as plt
Key de acesso obtido através do cadastro no site https://openweathermap.org/


I - Resultado referente ao dados extraidos pelo script.
![image](https://github.com/vlsantos-bit/Diferenca_Entre_Modelo_vs_previsor/blob/main/result_table.png)


II - Resultado plotado referente a tendencia de temperatura extraida da tabela anterior. 
![image](https://github.com/vlsantos-bit/Diferenca_Entre_Modelo_vs_previsor/blob/main/resultad_plot.png)

III - Resultado da previsão de 3 dias com as previsões inseridas (valores inseridos são apenas para teste)

![image](https://github.com/vlsantos-bit/Diferenca_Entre_Modelo_vs_previsor/blob/main/result_comp.png)
