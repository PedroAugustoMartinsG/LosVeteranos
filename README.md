# OBR 2021 :trophy:
<br></br>
## Lógica 2 sensores :flags:
<br></br>
##### Sensor 1 = Direita
##### Sensor 2 = Esquerda
<br></br>
### Casos Básicos
:white_circle: :black_circle:
##### Se S1 == Preto E S2 != Preto { Virar Direita até S1 != Preto }
:black_circle: :white_circle:
##### Se S1 != Preto E S2 == Preto { Virar Esquerda até S2 != Preto}
:black_circle: :black_circle:
##### Se S1 == Preto E S2 == Preto { Frente }
<br></br>
### Sendores para rotacionar 90° direita:
##### Sensor 1 = "PRETO" 
##### Sensor 2 = "BRANCO" 
##### Sensor 3 = "BRANCO"
<br></br>
### Sendores para rotacionar 90° esquerda:
##### Sensor 1 = "BRANCO" 
##### Sensor 2 = "PRETO" 
##### Sensor 3 = "BRANCO"
<br></br>
### Casos Extras
:white_circle: :black_circle:
##### Se S1 == Preto E S2 != Preto { Virar Direita até S1 != Preto/ Se S2 == Preto{ Tras }}
:black_circle: :white_circle:
##### Se S1 == Preto E S2 != Preto { Virar Direita até S2 != Preto/ Se S1 == Preto{ Tras }}
:black_circle: :black_circle:
##### Se S1 == Preto E S2 == Preto { Frente/ Verficar Direita 90 graus Se {S1 == Preto} Senao {Volta Direita Verficar Esquerda 90 graus Se {S2 == Preto} Senao {Volta Esquerda Frente }}
<br></br>
####
<br></br>
## Lógica 5 sensores :flags:
<br></br>
### Sendores:
:white_circle: :black_circle:
##### Sensor 1 = Direita
##### Sensor 2 = >Direita
##### Sensor 3 = Frente
##### Sensor 4 = >Esquerda
##### Sensor 5 = Esquerda
##### SensorCont = Valor do contador Para (Verificações)
<br></br>
### Sendores para rotacionar 90° direita:
##### Sensor 1 = "PRETO"
##### Sensor 2 = "PRETO"
##### Sensor 3 = "PRETO"
##### Sensor 4 = "BRANCO"
##### Sensor 5 = "BRANCO"
<br></br>
### Sendores para rotacionar 90° esquerda:
##### Sensor 1 = "BRANCO"
##### Sensor 2 = "BRANCO"
##### Sensor 3 = "PRETO"
##### Sensor 4 = "PRETO"
##### Sensor 5 = "PRETO"
<br></br>
### Casos Básicos
:white_circle: :white_circle: :black_circle: :white_circle: :white_circle:
##### Se S3 == Preto E SN != Preto { frente }
<br></br>
##### ... :pencil2:
