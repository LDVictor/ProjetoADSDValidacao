# Modelagem
![Imagem da modelagem](https://github.com/LDVictor/ProjetoADSDValidacao/blob/master/Documentos/modelo.png)

Situação 2:

γ =  5eps;
P clinico = 0,3;
P otorrino = 0,6;
P cardio = 0,1;
P medicação = 0,8;
P saída direta = 0,2.

λ1 = λ2 = λ3 = 5eps

λ4 = 1,5eps

λ5 = 3eps

λ6 = 0,5eps 

λ7 = 5eps

λ8 = 2,5eps

Tmax1 = Tmax2 = Tmax 3 = Tmax 6 = Tmax 7 = 0,2s

Tmax4 = 0,667s

Tmax5 = 0,333s

Tmax8 = 0,4s

T1 = T2 = T3 = T7= 0,05s
T4 = 0,1s
T5 = 0,07s
T6 = 0,8s
T8 = 0,08s


- Utilização:

  ρ1 = ρ2 = ρ3 = ρ7 = 0,25 = 25% 

  ρ4 = 0,15 = 15%

  ρ5 = 0,21 = 21%

  ρ6 = 0,40 = 40%

  ρ8 = 0,2 = 20%

- Quantidade de elementos:

  N1 = N2 = N3 = N7 = 0,333 elem 

  N4 =  0,176 elem

  N5 =  0,266 elem

  N6 =  0,667 elem

  N8 =  0,250 elem

- Tempo de resposta:

  TR1 = TR2 = TR3 = TR7 = 0,067s 

  TR4 = 0,118s

  TR5 = 0,089s

  TR6 = 1,333s

  TR8 = 0,100s

- Fluxo:

  X1 = X2 = X3 = X7 = 5 eps 

  X4 = 1,5 eps
 
  X5 = 3 eps

  X6 = 0,5 eps

  X8 = 2,5 eps

- Demanda: 

  D1 = D2 = D3 = D7 = 0,05 

  D4 = 0,03

  D5 = 0,042

  D6 = 0,08

  D8 = 0,04

- Limites Operacionais:

  -> Gargalo(0,080): D1, D2, D3 e D7
  
  -> Vazão: Xo <= 6,868 eps
  
  -> Tempo de resposta: R >= 0,392s
  
  [Para ver os cálculos detalhados, clique aqui](https://github.com/LDVictor/ProjetoADSDValidacao/tree/master/Documentos/C%C3%A1lculos)
