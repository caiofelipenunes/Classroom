# Classroom

salario = float(input("Qual e o salario desejado? "))
vale_alimentacao = (salario*5)/100
vale_transporte = (salario*2)/100
fgts = (salario*8)/100
inss = (7000*11)/100
inss = (salario*11)/100
total = float(salario+vale_alimentacao+vale_transporte+fgts+inss)
print("O total para contratar o funcionário é R$" + str(total))


print("---- Entradas ----")
print("salario R$: " + str(salario))
print("vale alimentacao R$: " + str(vale_alimentacao))
print("vale transporte R$: " + str(vale_transporte))
print("FGTS R$: " + str(fgts))
print("INSS R$: " + str(inss))
print("------------------")
