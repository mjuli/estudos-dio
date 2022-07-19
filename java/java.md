# JAVA

## IDE's

### Eclipse

#### COMANDOS:
* `Ctrl + Command + Espaço` => completa a função
* `Command + 3` => pesquisa (igual a lupa)
* `Command + D` => apaga a linha
* `Command + Shift + F` => Identar tudo
* `Alt + seta para cima/baixo` => move o bloco de texto para cima e para baixo
* `Command + Shift + o` => importa a classe necessária
* `Ctrl + Alt + seta para baixo/cima` => copia o bloco selecionado 

### IntelliJ

#### COMANDOS:
* `Ctrl + Shift + R` => executar o programa atual
* `Alt + Command + L` => identar código
* `Command + N` => Generate constructor, getters, setters, etc
* `Alt + Command + /` => commenta bloco
* `Command + /` => comenta linha
* `Command + Backspace` => deleta uma linha
* `Command + D` => duplica a linha
* `Alt + Shift + seta para cima/baixo` => move o bloco de texto para cima e para baixo
* `Command + Alt + V` => cria o nome da variável

## Variáveis:

### Boas Práticas:
	Nomes expressivos/descritivo
	camelCase => primeiraMinúscula
	final (variáveis constantes) => TUDO_MAIÚSCULO
	Não usar $ ou _

### Erros:
	Começar com número
	Colocar espaço
	Usar caracter especial
	Usar palavra reservada
	Mudar valor de uma constante

### Tipos:
* Textual:
```
  char c1 = 'W'; // aspas simples
  String st1 = "Fulano"; // aspas duplas
```
* Numeral:
```
  byte b1 = 10;
  short s1 = 20000;
  int i1 = 28500;
  long l1 = 1000000000000000000L; // Necessário adicionar o 'L' no final para informar que o tipo é long
  float f1 = 10.68F; // Necessário adicionar o 'F' no final, ao contrário o Java entende como double
  double d1 = 85.69;
```
* Lógico:
``` 
  boolean bo1 = true; 
  boolean bo2 = false; 
```
* Objeto

### Casting:
* Menor para maior => implícito (não há perda de informação)
```
  long l1;
  int i1 = 10;
  l1 = i1;
```
* Maior para menor => explícito (pode haver perda de informação)
```
  int i2;
  long l2 = 1000000000000000000L;
  i2 = (int) l2;
```

## Operadores Relacionais

```
>, <, >=, <=, ==, !=
```

## Operadores Lógicos
* Conjunção: `&&` => só é verdade se ambos forem verdade
* Disjunção: `||` => só é falso quando ambos forem falso
* Disjunção Exclusiva: `^` => só é verdade quando um é diferente do outro (true + false => true)
* Negação: `!` => inverte o valor (!true => false)

## Controle de Fluxo:

### IF
```
if (recebeAuxilio) {
    System.out.println("Funcionário deve receber auxílio.");
} else {
    System.out.println("Funcionário não deve receber auxílio.");
}
```
### SWITCH

```
switch (mes) {
    case "dezembro":
    case "julho":
    case "janeiro":
        System.out.println("Férias");
        break;
    default:
        System.out.println("Mês Indefinido");
        break;
}
```

## Estruturas de Repetição:

### WHILE
```
while (true) {
	...
}
```
### DO ... WHILE
```
do {
...
} while (true);
```
### FOR
```
for (int i = 0; i <= 10; i++) {
	...
}
```
```
for(int valor : valores) {
	...
}
```
## Arrays
	
