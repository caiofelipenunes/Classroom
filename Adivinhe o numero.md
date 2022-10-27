# Classroom

# Adivinhe o numero de 1 a 10

import random

numero = (random.randint(1,10))
print("acerte o numero que pensei de 1 a 10...") 
palpite = int(input("Qual e seu palpite? "))
if palpite == numero:
  print("Voce acertou, parabens!")

if palpite > numero:
  print("Seu palpite e maior que o numero, tente novamente")
  palpite = int(input("Qual e seu palpite? "))

if palpite < numero:
  print("Seu palpite e menor que o numero, tente novamente")
  palpite = int(input("Qual e seu palpite? "))

if palpite == numero:
  print("Voce acertou, parabens!")

if palpite > numero:
  print("Seu palpite e maior que o numero, tente novamente")
  palpite = int(input("Qual e seu palpite? "))

if palpite < numero:
  print("Seu palpite e menor que o numero, tente novamente")
  palpite = int(input("Qual e seu palpite? "))

if palpite == numero:
  print("Voce acertou, parabens!")

else:
  print("você perdeu!!!")
  print("O numero pensado é: " + str(numero))
