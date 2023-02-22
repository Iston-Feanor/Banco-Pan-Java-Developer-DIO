# *_Anatomia de Classes_* 
## *Sintaxe de declaração de uma nova classe*:
	- public class MinhaClasse {
	  //seu código aqui
	  } 
OBS:
- Classe com o mesmo nome do arquivo 
- nomenclatura coerente com a função
- Nome da classe em maiúsculo

-> A classe principal precisa de um método main
	public class void main (String [] args) {
		// seu código aqui
		//EX:
		System.out.print ("Hello World!");
	}

OBS: essa é uma estrutura básica padrão, alguns elementos podem sofrer alterações para um propósito específico

## *Padrões de Nomenclatura*

### Arquivo .java: Todo arquivo .java deve começar com letra maiúscula. 
Se a palavra for composta, a segunda palavra deve também ser maiúscula

### Nome da classe no arquivo: A classe deve possuir o mesmo nome do arquivo.java

### Nome de variável: toda variável deve ser escrita com letra minúscula, porém, se a palavra for composta, a primeira letra da segunda palavra deverá ser maiúscula. "camelCase"
Exceção: se a variável não for sofrer alteração deve ser escrita totalmente  em letra maiúscula, separando-se as compostas por underline _

Recomendações: Para declarar uma variáve nós podemos utilizar caracteres, números e símbolos, porém devemos seguir algumas regras da linguagem
- Deve conter apenas letras, underline, $ ou os números de 0 a 9
- Deve obrigatoriamente se iniciar por letra (preferencialmente), underline ou $, jamais com número
- Deve iniciar com letra minúscula
- Não pode conter espaços
- Não podemos usar palavras-chave da linguagem
- O nome deve ser único dentro de um escopo

## *Declaração de variáveis e métodos*

### Declarar uma variável em Java seque sempre a seguinte estrutura:

	Tipo NomeBemDefinido = Atribuição (opcionalem alguns casos);
	// Ex: int idade = 23;

### Declarando métodos em Java segue uma estrutura bem simples:
	-> TipoRetorno NomeObjetivoNoInfinitivo (Parâmetro)
		//EX: int somar (int numeroUm, int numero2)

## *Identação*
	-> É um termo utilizado para escrever o código do programa de forma hierárquica, facilitando a visualização e o entendimento do programa.
		Uso da tabulação para hierarquizar o código
		//EX: if (condição){
				System.out.print ("Identação");
			}	

## *Organizando arquivos*
	
	Á medida que nosso sistema vai evoluindo, surgem novos arquivos (código fonte) em nossa estrutura de arquivos do projeto. 
Isso exige que seja realizado uma organização destes arquivos através de pacotes (packages);

## *Java Beans*

### Variáveis: 

	- Uma variável deve ser clara, sem abreviações ou definição sem sentido;
	- Uma variável é sempre no singular, exceto quando se referir a um array ou coleção;
	- Defina um idioma único para suas variáveis;

### Métodos

	- Deverão ser nomeados como verbos, através de uma mistura de letras minúsculas e maiúsculas. 
Em princípio todas as letras que compõem o nome devem ser mantidas em minúsculo, com exceção da primeira letra de cada palavra composta a partir da segunda palavra.
