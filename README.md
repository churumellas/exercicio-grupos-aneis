# Isso aqui foi um exercicio para a materia grupos e aneis quando estava fazendo matematica ainda
## Soluções

$S=\{a,b,c,d \}$
$\ast:S\times S \rightarrow S$


$\ast$|a|b|c|d
-|-|-|-|-
**a**|b|c|a|a
**b**|d|b|c|c
**c**|a|d|c|b
**d**|d|a|d|b

### Questão 1
a|b|c|d
-|-|-|-
$a\ast a = b$|$b\ast a = d$|$c\ast a = a$|$d\ast a = d$
$a\ast b = c$|$b\ast b = b$|$c\ast b = d$|$d\ast b = a$
$a\ast c = a$|$b\ast c = c$|$c\ast c = c$|$d\ast c = d$
$a\ast d = a$|$b\ast d = c$|$c\ast d = b$|$d\ast d = b$

### Questão 2
$\exist x \in \{ a,b,c,d\}$ tal que, $x\ast x=x$ ?

$\{ b*b, c*c\}$. A estratégia é olhar para a diagonal da tabela dada.

### Questão 3
$\exist x \in \{a,b,c,d\}$ tal que $a\ast x = b$ ? 

$\{ b\ast b, c\ast c\}$. Basta olhar a coluna `a` da resposta da questão 1.

### Questão 4
$\exist x \in \{a,b,c,d\}$ tal que $x\ast a = b$ ? 

$\{ a\ast a\}$. Basta olhar a primeira linha da reposta da questão 1.

### Questão 5
$x \ast y = y \ast x, \forall x, y \in \{a,b,c,d\}$ ?

Não vale, basta tomar $a\ast b = c$ e $b\ast a = d$ como contra-exemplo.

### Questão 6
$\exist x \in \{a,b,c,d\}$ tal que $a\ast x = a$ e $x\ast a = a$

Sim vale basta olhar nas outra colunas de Q1 onde tem `a` e verificar se seu valor é igual ao valor da operação trocada na coluna de `a` .

### Questão 7
$\exist x,y \in \{a,b,c,d\}$ tal que $y\ast x = y$ e $x\ast y = y$

Não pois poussuo o elemento neutro apenas para $y=a$ e $x=c$.
