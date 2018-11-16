# Modelagem
![Imagem da modelagem](https://github.com/LDVictor/ProjetoADSDValidacao/blob/master/Documentos/modelo.png)

γ =  8eps

λ1 = λ2 = λ3 = 8eps

λ4 =  0,5 * λ3 = 4eps

λ5 =  0,3 * λ3 = 2,4eps

λ6 = 0,2 * λ3 = 1,6eps 

λ7 =  λ4 + λ5 + λ6 = 8eps

λ8 =  0,5 * λ7 = 4eps

Tmax1 =  1/8 = 0,125s = Tmax2  Tmax3

Tmax4 =  1/4 = 0,25s

Tmax5 =  1/2,4 = 0,42s

Tmax6 =  1/1,6 = 0,625s

Tmax7 =  0,125s

Tmax8 =  0,25s

T1 = 0,08s = T2 = T3
T4 = 0,12s
T5 = 0,2s
T6 = 0,32s
T7 = 0,08s
T8 = 0,12s


- Utilização:

  ρ1 = λ1 * T1 = 0,64 = 64% = ρ2 = ρ3

  ρ4 = 0,48 => 48%

  ρ5 = 0,48 => 48%

  ρ6 = 0,512 => 51,2%

  ρ7 = 0,64 => 64%

  ρ8 = 0,48 => 48%

- Quantidade de elementos:

  N1 =  ρ1/(1 - ρ1) = 0,64 / 0,36 = 1,78elem = N2 = N3

  N4 =  0,48 / 0,52 = 0,92 elem

  N5 =  0,48 / 0,52 = 0,92 elem

  N6 =  0,512 / 00,488 = 1,05 elem

  N7 =  1,78 elem

  N8 =  0,92 elem

- Tempo de resposta:

  TR1 =  (1 / μ1) / (1 - ρ1) = (1 / 12,5) / (1 - 0,64) = 0,08 / 0,36 = 0,22s = TR2 = TR3

  TR4 =  (1 / 8,33) / (1 - 0,48) = 0,12 / 0,52 = 0,23s

  TR5 =  0,2 / 0,52 = 0,38s

  TR6 =  0,32 / 0,488 = 0,655s

  TR7 =  0,22s

  TR8 =  0,23s

- Fluxo: Xi = Vi * X0

  X1 = 1 * 8 = 8eps = X2 = X3

  X4 =  0,5 * 8 = 4eps
 
  X5 =  0,3 * 8 = 2,4eps

  X6 = 0,2 * 8 = 1,6eps

  X7 =  1 * 8 = 8eps

  X8 = 0,5 * 8 = 4eps

- Demanda: Di = ρ1 / X0

  D1 = ρ1 / X0 = 0,64 / 8 = 0,08 = D2 = D3

  D4 = 0,48 / 8 = 0,06

  D5 = 0,48 / 8 = 0,06

  D6 = 0,512 / 8 = 0,064

  D7 = 0,08

  D8 = 0,06

- Limites Operacionais:

  -> Gargalo: D1 e D7
  
  -> Vazão: Xo <=  min(1 / 0,08 ; 10,93 / 0,564) = min(12,5 ; 19,38) => X0 <= 12,5eps
  
  -> Tempo de resposta: R >= max(10,93 * 0,08 ; 0,564) = max(0,86 ; 0,564) -> R >= 0,87s
  
  [Para ver os cálculos detalhados, clique aqui](https://github.com/LDVictor/ProjetoADSDValidacao/tree/master/Documentos/C%C3%A1lculos)
