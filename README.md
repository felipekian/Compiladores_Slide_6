# Compiladores: Exercício do slide 6

Construir um analisador Léxico para identificar 4 Linguagens diferentes

* ## Linguagem C
* ## Recebe um ***arquivo.txt*** para ser lido

----

## Liguagens a serem reconhecidas: 
* Números Inteiros;
* Números decimais;
* Data no formato dd/mm/aaaa ou dd-mm-aaaa;
* reconhecer número de CPF no formato 000.000.000-00

---

## Compilar
```
gcc main.c validators.c decimal.c inteiro.c cpf.c dataBR.c -o code
```

## Executar
```
./code arquivo.txt
```

---

## Exemplo:

![Exemplo](/images/exemplo.png)

---


Author: Felipe Derkian
