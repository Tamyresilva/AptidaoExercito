# AptidaoExercito
'''FaÃ§a um programa que pergunte a idade, o peso e a altura
de uma pessoa e decide se ela estÃ¡ apta a ser do Exercito
Para entrar no exercito Ã© preciso ter mais de 18 anos idade>= 18
pesar mais ou igual  60 kilos peso>=60
e medir mais ou igual 1,70 metros altura >=1.70'''

idade= int(input("Idade: "))
peso= float(input("Peso: "))
altura= float(input("Altura: "))

if((idade>= 18) and (peso>=60)and(altura>=1.70)):
 print("Você está apto a entra para o exercíto")
else:
 print("Você não está apto")
