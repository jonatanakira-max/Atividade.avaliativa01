[codigoatv01.py](https://github.com/user-attachments/files/22429306/codigoatv01.py)# Atividade.avaliativa01

#Atividade.avaliativa1051 Usando obrigatoriamente o IF e ELSE no exercício.

[# Atividade Avaliativa 1051 Usando Obrigatoriamente o IF e ELSE No Exercício 1051
# Caulculando Imposto de Renda
# Entrada Do Valor Da Renda
sal = float(input().strip())
# Calculo Do Inposto
imposto = 0.0
if sal <= 2000.00:
    imposto = 0.0
elif sal <= 3000.00:
    imposto = (sal - 2000.00) * 0.08
elif sal <= 4500.00:
    imposto = (1000.00 * 0.08) + (sal - 3000.00) * 0.18
else:
    imposto = (1000.00 * 0.08) + (1500.00 * 0.18) + (sal - 4500.00) * 0.28
# Saida Do Resuldado Do Calculo De Imposto De Renda
if imposto == 0.0:
    print("Isento")
else:
    print(f"R$ {imposto:.2f}")
Uploading codigoatv01.py…]()


<img width="1404" height="183" alt="print terminal atv01 1051" src="https://github.com/user-attachments/assets/4270e248-3835-45af-b095-6bf7711fb324" />
