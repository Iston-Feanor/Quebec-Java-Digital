# **_Métodos_**

### O que é um Método:

- É uma porção de código (sub-rotina) que é disponibilizado por uma classe.
Este é executado quando é feita uma requisiçãoa ele. São responsáveis
por definir e realizar determinado comportamento.

### Criação:

**<visibilidade?> <tipo?> <modificador?> retorno nome
<parametros?> <exceções?> corpo**

V: public, protected ou private
T: concreto ou abstrato
M: static ou final
R: tipo de dado ou void
N: nome que é fornecido ao método
P: parâmetros que pode receber
E: exceções que pode lançar
C: código que possui ou vazio

padrão comum: public static R N (P) {...}

### Utilização:

- Passa-se uma mensagem através de uma classe ou objeto.

nome_da_classe.nome_do_metodo()
nome_do_objt_.nome_do_metodo()

### Particularidades: 

- Assinatura: É a forma de identificar unicamente o método
Ass = nome + parâmetros

Método: public double calcularTotalVenda(double precoItem1, double precoItem2, double preocItem3) {...}

Assinatura: calcularTotalVenda (double precoItem1, double precoItem2, double preocItem3))

- Construtor e Destrutor: são métodos especiais usados na Orientação a Objetos

- Mensagem: É o ato de solicitar ao método que o mesmo execute.
Esta pode ser direcionada a um objeto ou a uma classe

### Passagem de Parâmetros: 
- Por valor (cópia): Passa uma cópia de uma variável para realizar as operações,
desse jeito, não acarreta em alterações na mesma
- Por referência (endereço)

### Boas Práticas

- Nomes devem ser descritivos, mas curtos 
- Nome Camelo
- Deve Possuir entre 80 e 120 linhas
- Evite lista de parâmetros longas
- Visibilidades adequadas

