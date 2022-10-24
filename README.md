# CondicionalCor
Cor Fora do Prazo = 
VAR Cor = "#FD625E" //vermelho
VAR Atraso = VALUES(//tabela[//coluna])
RETURN
SWITCH(
    TRUE(),
    Atraso = "//texto",
    Cor
)
