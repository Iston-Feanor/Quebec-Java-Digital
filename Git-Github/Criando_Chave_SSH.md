# _Criando Chave SSH_

- ssh -keygen -t ed 25519 -C +email = cria um par de chaves (1 pública e 1 privada) (vai pedir para digitar "senha")
- cat id_ed25519.pub = mostra a chave pública (cola no github)

Inicializando o SSH agent:
- eval $ (ssh -agent -s)
- ssh -add +chave privada 
