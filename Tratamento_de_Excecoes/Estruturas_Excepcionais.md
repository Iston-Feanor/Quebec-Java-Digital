# **_Estruturas Excepcionais_**

### _Exceções_

- Ao executar o código java, diferentes erros podem acontecer. Quando ocorre um erro, o Java normalmente para e gera uma mensagem de erro. O termo técnico para isso é: Java lançará uma exceção.

- De forma interpretativa em Java, um erro é algo irreparável, a aplicação trava ou é encerrada drasticamente. Já exceções é um fluxo inesperado da nossa aplicação.

##### Conhecendo algumas exceções já mapeadas

- java.lang.NullPointerException: Quando tentamos obter alguma informação de alguma variável nula;
- java.lang.ArithmeticException: Quando tentamos dividir um valor por zero;
- java.sql.SQLException: Quando existe algum erro relacionado a interação com a base de dados;
- java.io.FileNotFoundException: Quando tentamos ler ou escrever um arquivo que não existe;

# Tratamentos de Exceções

- A instrução try permite que você defina um bloco de código para ser testado quanto a erros enquanto está sendo executado.
- A instrução cath permite definir um bloco de código a ser executado, caso ocorra um erro no bloco try;
- A instrução finally permite definir um bloco de código a ser executado independete de ocorrer um erro ou não. 

As palavras-chave try e cath vêm em pares.

- Estrutura

try {
	<bloco de código conforme esperado>
}
cath (Exception e)<precisamos saber qual exceção> {
	<bloco de código que captura as exceções que podem acontecer em caso de um fluxo não previsto>
}

# **_Hierarquia de Exceções_**

- A linguagem Java dispõe de um variedade de classes que representam exceções, e estas classes são organizadas em hierarquia denominadas Checked and Uncheked Exceptions ou Exceções Checadas e Não Checadas.

O que determina uma exceção ser classificado como checada ou não checada? 
É o risco dela ser disparada, logo você precisa tratá-la.

### Exceções customizadas

- Nós podemos criar nossas próprias exceções baseadas em regras de negócio e assim mlehor direcionar quem for utilizar os recursos desenvolvidos no projeto.

##### Estrutura

public class <nome da exceção> extends Exception {
}
