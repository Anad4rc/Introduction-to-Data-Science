# Introduction-to-Data-Science
Programa feito durante a live de introdução a ciência de dados da Ada

**💻 código** 

**Questão 13:** Faça um programa que peça um valor monetario e diminua-o em 15%. Seu programa deve imprimir a mensagem "O novo valor é [valor]". 📌

```python
valor = float(input('Digite um valor: '))

#x =  x - x*15/100
result = valor - valor * (15/100)

#print(f'O novo valor é {x}.')
print('O novo valor é ',result)

```

**Questão 14:** Peça para o usuario digitar uma velocidade inicial(em m/s), uma posição inicial(em m) e um instante de tempo(em s) e imprima a posição de uma projetil nesse instante de tempo.

**Use a fórmula mátematica:** <br>
*y(t) = y(0) + v(0)t + (g(t**2)/2)*

Onde **g** é a aceleração da gravidade(-10m/s), **y(t)** é a posição final, **y(0)** é a posição inicial, **v(0)** é a velocidade inicial e **t** é o instante de tempo. 📌

```python

#variaveis e seus respectivos inputs
v0 = float(input("Digite a velocidade inicial[em m\s]: "))    #velocidade_inicial
y0 = float(input("Digite a posição inicial do projetil[em m]: ")) #posição inicial
t = float(input("Digite o tempo[em s]: ")) #instante de tempo

"""
>> legenda

m/s = metros por segundo
m = metros
s = segundos
"""

#calcula a posição do projetil no intervalo de tempo indicado
p = v0 + (y0 * t) + (-10 * (t**2))/2

print("A projeção do projetil no intervalo de tempo indicado é: ",p)
```

