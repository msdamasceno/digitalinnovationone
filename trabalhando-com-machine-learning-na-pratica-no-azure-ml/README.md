## Criando modelo de previsão - Passo a passo

<img align="right" src="https://raw.githubusercontent.com/msdamasceno/digitalinnovationone/main/imagens/Machine%20Learning/01.png" width=""/> 
<img align="right" src="https://raw.githubusercontent.com/msdamasceno/digitalinnovationone/main/imagens/Machine%20Learning/02.png" width=""/> 
<img align="right" src="https://raw.githubusercontent.com/msdamasceno/digitalinnovationone/main/imagens/Machine%20Learning/03.png" width=""/> 
<img align="right" src="https://raw.githubusercontent.com/msdamasceno/digitalinnovationone/main/imagens/Machine%20Learning/04.png" width=""/> 
<img align="right" src="https://raw.githubusercontent.com/msdamasceno/digitalinnovationone/main/imagens/Machine%20Learning/05.png" width=""/> 
<img align="right" src="https://raw.githubusercontent.com/msdamasceno/digitalinnovationone/main/imagens/Machine%20Learning/06.png" width=""/> 
<img align="right" src="https://raw.githubusercontent.com/msdamasceno/digitalinnovationone/main/imagens/Machine%20Learning/07.png" width=""/> 
<img align="right" src="https://raw.githubusercontent.com/msdamasceno/digitalinnovationone/main/imagens/Machine%20Learning/08.png" width=""/> 
<img align="right" src="https://raw.githubusercontent.com/msdamasceno/digitalinnovationone/main/imagens/Machine%20Learning/09.png" width=""/> 
<img align="right" src="https://raw.githubusercontent.com/msdamasceno/digitalinnovationone/main/imagens/Machine%20Learning/10.png" width=""/> 
<img align="right" src="https://raw.githubusercontent.com/msdamasceno/digitalinnovationone/main/imagens/Machine%20Learning/11.png" width=""/> 
<img align="right" src="https://raw.githubusercontent.com/msdamasceno/digitalinnovationone/main/imagens/Machine%20Learning/12.png" width=""/> 



## Teste do modelo
utilizei o json para Input abaixo:

``` JASON
{
  "input_data": {
    "data": [
       {
         "day": 1,
         "mnth": 1,   
         "year": 2022,
         "season": 2,
         "holiday": 0,
         "weekday": 1,
         "workingday": 1,
         "weathersit": 2, 
         "temp": 0.3, 
         "atemp": 0.3,
         "hum": 0.3,
         "windspeed": 0.3 
       }
     ]
  }
}
```

Resultado Json Output

``` JASON
[
  347.6694218243964
]
```
<img align="right" src="https://raw.githubusercontent.com/msdamasceno/digitalinnovationone/main/imagens/Machine%20Learning/13.png" width=""/> 