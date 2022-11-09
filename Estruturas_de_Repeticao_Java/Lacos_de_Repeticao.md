# **_Laços de Repetição_**

- Também conhecidos como laços de iteração ou simplesmente loops, são comandos que permitem iteração do código, ou seja, que comandospresentes no bloco sejam repetidos diversas vezes.

### São eles:
- For (para)
- While (enquanto)
- Do While (faça enquanto)

### _For_

- Permite que uma variável contadora seja testada e incrementada a cada iteração, sendo essas informaçõse definidas na chamada do comando.
O comando for recebe como entrada uma variável contadora, a condição e o valor de incrementação.

- Estrutura 

for (bloco de inicialização; expressão booleana de validação; bloco de atualização) {
	<comando que será executado até que a expressão de validação torne-se falsa>
}

### _break e continue_

- Break significa quebrar, parar, frear, interromper. E é isso que se faz quando o Java encontra esse comando pela frente.

- Continue 'continua' o laço.

O comando break interrompe o laço, já o continue interrompe somente a iteração atual.


### _While_

- O laço While determina que enquanto uma condição for válida, o bloco de código será executado. O laço while testa a condição antes de executar o códig, logo, caso a condição seja inválida no primeiro teste o bloco nem será executado.

- Estrutura

While (expressão boolena de validação) {
	<comando que será executado até que a expressão de validação torne-se falsa>
}

### _Do-While_

- O laço do-while considera que enquanto uma determinada condição for válida o bloco de código será executado. Entretanto, testa a condição após a executar o código, sendo assim, mesmo que a condição seja considerada inválida no primeiro texte o bloco será executado ao menos uma vez.

- Estrutura

### Do {
	<comando que será executado até que a expressão de validação torne-se falsa>
} While (expressão de validação booleana);
