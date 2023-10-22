# teste de velocidade

V_execidida = 80 
multa = 7 
velocidade = float(input("Coloque a velocidade do elemento: ")) 
v = velocidade - V_execidida 
multa = v * multa 

if velocidade > V_execidida:
    print(f"ei meu fi tá achando que é piloto de f1? tome {multa}RS de multa") 
else: print("Pode passar cidadão")
