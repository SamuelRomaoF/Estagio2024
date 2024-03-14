Dado a sequência de Fibonacci, onde se inicia por 0 e 1 e o próximo valor sempre será a soma dos 2 valores anteriores (exemplo: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34...), escreva um programa na linguagem que desejar onde, informado um número, ele calcule a sequência de Fibonacci e retorne uma mensagem avisando se o número informado pertence ou não a sequência.


    # a) 1, 3, 5, 7, ___
# Resposta: 9
print("a) 1, 3, 5, 7, ___: 9")

# b) 2, 4, 8, 16, 32, 64, ___
# Resposta: 128
print("b) 2, 4, 8, 16, 32, 64, ___: 128")

# c) 0, 1, 4, 9, 16, 25, 36, ___
# Resposta: 49
print("c) 0, 1, 4, 9, 16, 25, 36, ___: 49")

# d) 4, 16, 36, 64, ___
# Resposta: 100
print("d) 4, 16, 36, 64, ___: 100")

# e) 1, 1, 2, 3, 5, 8, ___
# Resposta: 13
print("e) 1, 1, 2, 3, 5, 8, ___: 13")

# f) 2, 10, 12, 16, 17, 18, 19, ___
# Resposta: 20
print("f) 2, 10, 12, 16, 17, 18, 19, ___: 20")

texto = input("Digite uma string para inverter: ")
invertido = texto[::-1]
print("String invertida:", invertido)

