# CondicionalCor
Cor Fora do Prazo = 
VAR Cor = "#FD625E"
VAR Atraso = VALUES('Indicadores ANS GCON'[Prazo])
RETURN
SWITCH(
    TRUE(),
    Atraso = "Atrasado",
    Cor
)
