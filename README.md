# Exercício sobre OO e List em Java - Aulão #003
###### DevSuperior - sua carreira dev com fundamento de ensino superior

[![Image](https://s3-sa-east-1.amazonaws.com/educandoweb.com.br/img/devsuperior/bt-youtube.png "DevSuperior no Youtube")](https://youtube.com/devsuperior) [![Image](https://s3-sa-east-1.amazonaws.com/educandoweb.com.br/img/devsuperior/bt-facebook.png "DevSuperior no Facebook")](https://facebook.com/devsuperior.fb) [![Image](https://s3-sa-east-1.amazonaws.com/educandoweb.com.br/img/devsuperior/bt-instagram.png "DevSuperior no Instagram")](https://instagram.com/devsuperior.ig)

Assista o vídeo:

[![Image](https://img.youtube.com/vi/Xj-osdBe3TE/mqdefault.jpg "Vídeo no Youtube")](https://youtu.be/Xj-osdBe3TE)

## Sumário
- [O que você vai aprender](#O-que-você-vai-aprender)
- [Pré-requisitos](#pré-requisitos)
- [Enunciado do exercício](#Enunciado-do-exercício)

## O que você vai aprender
- Listas (tipo List)
- Operações: adicionar elemento na lista, acessar um elemento, percorrer e analisar os elementos da lista

## Pré-requisitos

- Lógica de programação
  - Variáveis, entrada, processamento, saída
  - Estrutura condicional
  - Estruturas repetitivas
- OOP básica
  - Classes, atributos, métodos, objetos
  - Construtores, encapsulamento

## Enunciado do exercício

```
Fazer um programa para ler um número inteiro N e depois os 
dados (id, nome e salario) de N funcionários. Não deve haver 
repetição de id. 
 
Em seguida, efetuar o aumento de X por cento no salário de 
um determinado funcionário. Para isso, o programa deve ler 
um id e o valor X. Se o id informado não existir, mostrar 
uma mensagem e abortar a operação. Ao final, mostrar a 
listagem atualizada dos funcionários, conforme exemplos.
 
Lembre-se de aplicar a técnica de encapsulamento para não 
permitir que o salário possa ser mudado livremente. Um 
salário só pode ser aumentado com base em uma operação 
de aumento por porcentagem dada.
```

EXEMPLO 1:
```
How many employees will be registered? 3

Emplyoee #1:
Id: 333
Name: Maria Brown
Salary: 4000.00

Emplyoee #2:
Id: 536
Name: Alex Grey
Salary: 3000.00

Emplyoee #3:
Id: 772
Name: Bob Green
Salary: 5000.00

Enter the employee id that will have salary increase : 536
Enter the percentage: 10.0

List of employees:
333, Maria Brown, 4000.00
536, Alex Grey, 3300.00
772, Bob Green, 5000.00
```

EXEMPLO 2:
```
How many employees will be registered? 2

Emplyoee #1:
Id: 333
Name: Maria Brown
Salary: 4000.00

Emplyoee #2:
Id: 536
Name: Alex Grey
Salary: 3000.00

Enter the employee id that will have salary increase: 776
This id does not exist!

List of employees:
333, Maria Brown, 4000.00
536, Alex Grey, 3000.00
```
