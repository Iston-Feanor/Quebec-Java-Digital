# **_Swith Case_**

- Compara o valor de cada caso com o da variável sequencialmente, e sempre que encontra um valor correspondete, executa o código associado ao caso.
Para evitar que as comparações continuem a ser executadas após um caso correspondenete ter sido encontrado, acrescentamos o comando break no final de cada
bloco de códigos. O comando break, quando executado, encerra a execução da estrutura onde ele se encontra.

### Estrutura: 

Switch (variável para verificar) {

	case <condição1>: {
	<comandos>;
	break;
	}
	case <condição2>: {
	<comandos>;
	break;
	}
	case <condiçãoN>: {
	<comandos>;
	break;
	}
	default: 
	<comando caso as condições não forem satisfeitas>
}
	
