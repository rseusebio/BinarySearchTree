# BinarySearchTree
Uma árvore binária de busca para nodejs.

# Descrição 
  Este repositório contém duas classes principais. A primeira é a classe Node cujas instâncias servem de modelagem para os nós de uma árvore binária. Já a segunda é a própria classe BinarySearchTree que modela a árvore em si.
  
# Instalação 

 O manual de instalação tem o intuito de preparar o ambiente do sistema, incluindo o compilador Babel para executar o javascript conforme a atualização do ecmascript 2015.

Para ter acesso ao codigo basta fazer um git clone: 
	https://github.com/rserafael/BinarySearchTree.git/
  
O proximo passo é configurar e instalar as dependências e bibliotecas utilizadas:
   npm install --save

# Documentação da API BinarySearchTree

# Construtor
  
  O construtor da árvore binária exige um nó raiz de inicialização. A configuração da raiz é feita através da chamada do método setRoot.
  Além disso, é instaciada uma lista que vazia onde serão armazenadas as chaves dos nós durante o método inorderWalk.

# setRoot

  Este método configura a raiz da árvore com um objeto instância da clase Node. Caso não seja passado ou passado algum objeto de outro tipo ocorre uma exceço do tipo TypeError.
  Como se trata de uma raiz o parente deste nó é configurado como nulo.
 
# hasRoot

  Este método verifica se a árvore têm raiz ou está vazia. Retorna um objeto do tipo booleano, ou seja, true ou false.
  
# Insert

  Este método insere novas chaves na árvore. O argumento deve ser um objecto numérico, caso contrário ocorre um TypeError exception. 
