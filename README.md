Um banco concederá um crédito especial aos seus clientes de acordo com o saldo médio no último ano. Crie o fluxograma de um programa que recebe o saldo médio de um cliente, calcula e mostra o valor do crédito, de acordo com a tabela a seguir. 
Saldo Médio
Percentual do saldo médio
Acima de R$ 4.000,00
30%
De R$ 3.000,01 a R$ 4.000,00
25%
De R$ 2.000,01 a R$ 3.000,00
20%
Até R$ 2.000,00
10%




saldo_medio = float(int("Digite o valor do saldo médio da sua conta conrrente no ultimo ano")

if saldo_medio > 4000:
    valor_credito = saldo_medio * 0.30
elif 3000.01 <= saldo_medio  <= 4000:
    valor_credito = saldo_medio * 0.25
elif 2000.01 <= saldo_medio  <= 3000:
    valor_credito = saldo_medio * 0.20
else:
    valor_credito = saldo_medio * 0.10

print(f"O valor do crédito será ", {valor_credito})  
