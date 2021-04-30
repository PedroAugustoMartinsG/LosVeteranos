Sbotics-OBR 🏆
Parte 1 - Seguidor de linha preto 📝
 Seguidor de linha Preto 2 sensores
 Seguidor de linha Preto 5 sensores
 Implementar sistema 1
 Implementar sistema 2



Lógica 2 sensores 🎏



Sensor 1 = Direita
Sensor 2 = Esquerda



Casos Básicos
⚪ ⚫

Se S1 == Preto E S2 != Preto { Virar Direita até S1 != Preto }
⚫ ⚪

Se S1 != Preto E S2 == Preto { Virar Esquerda até S2 != Preto}
⚫ ⚫

Se S1 == Preto E S2 == Preto { Frente }



Sendores para rotacionar 90° direita:
Sensor 1 = "PRETO"
Sensor 2 = "BRANCO"
Sensor 3 = "BRANCO"



Sendores para rotacionar 90° esquerda:
Sensor 1 = "BRANCO"
Sensor 2 = "PRETO"
Sensor 3 = "BRANCO"



Casos Extras
⚪ ⚫

Se S1 == Preto E S2 != Preto { Virar Direita até S1 != Preto/ Se S2 == Preto{ Tras }}
⚫ ⚪

Se S1 == Preto E S2 != Preto { Virar Direita até S2 != Preto/ Se S1 == Preto{ Tras }}
⚫ ⚫

Se S1 == Preto E S2 == Preto { Frente/ Verficar Direita 90 graus Se {S1 == Preto} Senao {Volta Direita Verficar Esquerda 90 graus Se {S2 == Preto} Senao {Volta Esquerda Frente }}



Fase de teste



Lógica 5 sensores 🎏



Sendores:
⚪ ⚫

Sensor 1 = Direita
Sensor 2 = >Direita
Sensor 3 = Frente
Sensor 4 = >Esquerda
Sensor 5 = Esquerda
SensorCont = Valor do contador Para (Verificações)



Sendores para rotacionar 90° direita:
Sensor 1 = "PRETO"
Sensor 2 = "PRETO"
Sensor 3 = "PRETO"
Sensor 4 = "BRANCO"
Sensor 5 = "BRANCO"



Sendores para rotacionar 90° esquerda:
Sensor 1 = "BRANCO"
Sensor 2 = "BRANCO"
Sensor 3 = "PRETO"
Sensor 4 = "PRETO"
Sensor 5 = "PRETO"



Casos Básicos
⚪ ⚪ ⚫ ⚪ ⚪

Se S3 == Preto E SN != Preto { frente }



... ✏️
