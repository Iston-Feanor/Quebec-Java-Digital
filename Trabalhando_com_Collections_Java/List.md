# **_List_**: 

### Inicializar um List: 

- List _nome da lista_ = new ArrayList() => antes do java 5
- List <tipo de dados> _nome da lista_ = new arrayList <>() => generics
- ArrayList <tipo de dados> _nome da lista_ = new ArrayList <>()
- List <tipo de dados> _nome da lista_ = new ArrayList <> (Arrays.asList (7d,8.5,9.3,5d,7d,0d,3.6))
- List <tipo de dados> _nome da lista_ = Arrays.asList (7d,8.5,9.3,5d,7d,0d,3.6) => imutável
- List <Double> _nome da lista_ = List.of (7d,8.5,9.3,5d,7d,0d,3.6) => imutável
- existem outras formas

### Adicionando itens a lista:

- _nome da lista_.add(elemento)
- existem outras formas de adicionar elementos a uma lista

### Imprimir a lista

- Sysout (nome da lista)
- Sysout (_nome da lista_.toString())

### Exibir posição de um elementos na Lista (método IndexOf):

- _nome da lista_.IndexOf(elementos que se quer a posição));

### Adicionar na lista um elemento em determinada posição:

- _nome da lista_.add (i:posição, e:elemento);

### Substituir um elemento por outro

- _nome da lista_.Set(posição para substituir e elemento que queremos colocar no lugar)

### Verificar se um elemento está na lista

- _nome da lista_.contains (elemento que se quer verificar)

### Exibir um elemento de uma posição específica

- _nome da lista_.get(posição);

### Exibir a maior e o menor elemento

- Collections.min(notas)
- Collections.max(notas)

### Exibir a soma dos elementos

- Iterator <tipo de dado> iterator = _nome da lista_.iterator()
  
  more soon...
