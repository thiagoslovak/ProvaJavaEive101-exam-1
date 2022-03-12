Legenda: ícone :heavy_check_mark:, usado para mostrar a afirmação correta.

1. Qual comando possibilita a visualização de forma resumida dos commits realizados em um repositório?
   
   1. `git log --short`
   
   2. `git log --oneline` :heavy_check_mark:
   
   3. `git show --all`
   
   4. `git commits --summary`
   
   5. `git log --summary`
   
      
   
2. Quais os comandos para configurar sua identidade no Git? (desconsidere o uso de flags)
   1. `git config username "John Doe"`, `git config email "john.doe@db1.com.br"`
   
   2. `git config user.name "John Doe"`, `git config email "john.doe@db1.com.br"`
   
   3. `git config user.name "John Doe"`, `git config user.mail "john.doe@db1.com.br"`

   4. `git config user.name "John Doe"`, `git config user.email "john.doe@db1.com.br" `  :heavy_check_mark:
   
   5. `git config user.username "John Doe"`, `git config user.email "john.doe@db1.com.br"`
   
      
   
3. Qual(is) a(s) diferença(s) entre os comandos `git merge` e `git rebase`?

   - Git Merge -> Cria um novo commit de merge de uma branch a outra.

   - Git Rebase -> O rebase move todos os commit de uma branch para outra.	

     

4. No Git, é possível salvar o estado atual de seu trabalho e voltar ao estado do último commit da branch. Nesse caso, qual comando devemos utilizar? E para recuperar o trabalho posteriormente, qual é o comando?

   - Git Stash, guarda essas alterações e volta o arquivo alterado ao estado do ultimo commit. E Git Stash Pop, para retornar suas alterações para o arquivo novamente.

     

5. No contexto do Git, o que são, para que servem e em quais casos devemos criar `issues`?

   - É uma solicitação de alteração em um projeto no Git, é utilizado quando deseja sugerir alguma alteração, já mandado uma ideia de como seria essa modificação.

     

6. O que é e para que serve o `cherry-pick`?

   - É um comando no GIT usado para selecionar commits para trazer para a branch desejada. 

     

7. No cotidiano de um desenvolvedor, é comum que conflitos apareçam, e é de responsabilidade do mesmo resolvê-los. Qual o processo mostrado em curso para a resolução de um conflito?

   - Dado que eu tenha duas branchs, e ao fazer o merge de uma branch a outra e ocorrer um conflito. Vá ao arquivo que mostrara a diferença e terá 3 opções. 1° Deixar a alteração da branch 1. 2° Deixar a alteração da branch 2. E 3° deixar as duas alterações. Escolhe uma e faz o commit de merge.

     

8. Existe uma estratégia de branching chamada Git Flow, muito comumente aplicada no desenvolvimento de software. Qual das opções abaixo representam as branches presentes nessa estratégia, de acordo com o conteúdo?

   1. `master`, `develop`, `feat`, `hotfix` e `release`

   2. `master`, `develop`, `feature`, `fix` e `release`

   3. `master`, `develop`, `feature`, `hotfix` e `release`:heavy_check_mark:

   4. `master`, `develop`, `feat`, `fix` e `release`

   5. `master`, `develop`, `feat`, `fix` e `rc`

      

9. Qual(is) a(s) diferença(s) entre JRE e JDK?

   - JRE -> É uma camada de software que é utilizado para executar aplicações Java.

   - JDK -> É o kit  para se desenvolver na linguagem Java.

     

10. O que é um workspace, no contexto do Eclipse?

    - É o diretório de trabalho para armazenar suas preferências e artefatos de desenvolvimento. 

      

11. Em Java, o operador `+` possui duas funções básicas. Quais são elas? Dê um exemplo em código de cada uma delas.

    - O operador + é usado para concatenar ou somar operações matemáticas:	     

      ```
       Concatenar:
       
       String nome = "Thiago";
       String sobrenome = "Slovak";	     
       String nomeSobrenome = nome + sobrenome;
       System.out.println(nomeSobrenome);
      ---------------------------------------------------------------------------- 
       Fazer operações matemáticas:
       
       int valor1 = 3;
       int valor2 = 2;
       int total = valor1 + valor2;
       System.out.println(total);	
      ```

12. Ao realizar a operação abaixo, qual será o resultado mostrado no console?

    ```java
    class App {
        public static void main(String... args) {
            double divisionResult = 5 / 2;
            System.out.println(divisionResult);
        }
    }
    ```

    1. `2`
    2. `3.0`
    3. `3`
    4. `2.5`
    5. `2.0` :heavy_check_mark:

13. Por que o type casting "implícito" do Java não é possível no caso abaixo?

    ```java
    class App {
        public static void main(String... args) {
            float pi = 3.14;
        }
    }
    
    //Por conta que esta tentando atribuir um double que tem um tamanho de 8 bytes em um float que tem o tamanho de 4 byte. Assim o java não consegue fazer o casting "implícito".
    ```

14. Observe o código abaixo. Ele compilará? Qual a diferença entre as variáveis `firstValue` e `secondValue`?

    ```java
    class App {
        public static void main(String... args) {
            char firstValue = 'a';
            char secondValue = 97;
        }
    }
    //Compilará, por conta a representação do número 97 na tabela ASCII é a letra a.
    //As duas variáveis são a representação do mesmo valor. Uma recebendo o valor 'a' e a outra recebendo a representação do valor 'a' na tabela ASCII.
    ```

15. Observe os códigos abaixo. Ao serem compilados e executados, o que é exibido no terminal?

    ```java
    // código 1
    class App {
        boolean hasValue;
        public static void main(String... args) {
            System.out.println(hasValue);
        }
    }
    
    //Não vai ser compilador, por conta que a variável hasValue, não foi declarada da forma correta, nesse contexto a variável hasValue teria que ter uma referência static.
    ```

    ```java
    // código 2
    class App {
        public static void main(String... args) {
            boolean hasValue;
            System.out.println(hasValue);
        }
    }
    
    //Não vai ser compilador, por conta que a variável hasValue, não foi iniciada com nem um valor.
    ```

16. Para que serve e quando utilizar o comando `break`?

    - É utilizado quando se deseja interromper uma execução. Se não for usando nos momentos corretos a aplicação fica executando eternamente.

      

17. Quais as diferenças entre classe, objeto e referência?

    - Classe, é a uma representação, a base para algo, é onde declaramos atributos, métodos...

    - Objeto ele guarda a referência de uma classe. É quando conseguimos trabalhar com objeto a partir da Classe. 

    - Referência, é um espaço em memoria que é criado no momento que se cria um objeto, a referência é um indicador que representa a classe.

      

18. O que é exibido no terminal ao executar o código abaixo, considerando que ClasseExemplo não sobreescreveu o método `toString()`? Explique cada parte da estrutura do que é mostrado.

    ```java
    class App {
        public static void main(String... args) {
            ClasseExemplo exemplo = new ClasseExemplo();
            System.out.println(exemplo);
        }
    }
    
    //É uma estrutura de uma classe chamada App, onde se tem o método main, nesse main tem uma instrução para instanciar um objeto chamado exemplo do tipo ClasseExemplo que faz uma referencia a ClasseExemplo(). Seguindo na próxima linha se tem um chamada a classe System para imprimir o objeto (exemplo).. Ao compilar irá sair o número alfanumérico que representa a referência em memoria desse objeto.
    ```

19. O que é exibido no terminal ao executar o código abaixo?

    ```java
    class Pessoa {
        Endereco endereco;
    }
    
    class Endereco {
        String cep;
    }
    
    class App {
        public static void main(String... args) {
            Pessoa aluno = new Pessoa();
            System.out.println(aluno.endereco.cep);
        }
    }
    
    
    //Irá dar uma exeção, dizendo que o ponteiro é nulo. Para isso funcionar a classe Pessoa tinha que ter um construtor que instancia a classe Endereco:
    
    public class Pessoa {
    	Endereco endereco;
    
    	public Pessoa() {
    		this.endereco = new Endereco();
    	}
    }
    
    ```

20. Em Java, existem atributos e métodos de classe. Explique como declará-los e qual(is) a(s) diferença(s) entre eles e os atributos e métodos de instância.

    - ~~~java
      ```
      public class Teste {
      	//Declarando atributos
          //Atributos são as caracteristicas de algo.
          private String nome;
          private String sobrenome;
          
          public void metodoTeste() {
              //Declarando um método publico que não tem retorno, e sem parâmetro.
              //Métodos é a ação, é oque irá fazer.
              
              //Métodos de instância, métodos acessados a partir de uma criação de    		objeto.
             	InstanciandoObj obj = new InstanciandoObj();
              obj.metodoInstancia();
          }    
      }
      ```
      ~~~

      

      

21. Os códigos mostrados até agora não respeitam os pilares da Programação Orientada a Objetos. Descreva cada um deles e explique seus benefícios e aplicações.

    - Abstração -> Filosoficamente, é abstrair algo do mundo real para o código.

    - Herança -> É a capacidade de herdar funcionalidades de uma outra classe. Muito usado quando se tem uma classe com funcionalidades que será muito usada.

    - Polimorfismo -> É usado quando classes herdadas podem implementar de forma diferente os métodos da classe mãe. Uma das funcionalidades é sobrescrever algum método da classe mãe.

    - Encapsulamento -> É usado para esconder ou deixar visível funcionalidades/atributos de uma classe. É  a capacidade de usar os especificadores de visibilidade, para não deixar um atributo/método ser acessado de qualquer maneira.

      

22. Em Java, conseguimos aplicar a herança entre classes com a _keyword_ `extends`. Explique quais os benefícios de utilizar esse conceito no código.

    - Usando esse pilar e aplicando a extensão de alguma outra classe, é possível acessar, sobrescrever  e reutilizar códigos da classe mãe.

      

23. Explique a(s) diferença(s) entre as *keywords* `this` e `super`. No caso da `super`, ela pode ser utilizada tanto no formato `super.` quanto `super()`, porém com aplicações diferentes - explique essas duas aplicações e dê exemplos de quando utilizar cada uma.

    - this -> Usado para acessar atributos/métodos da mesma classe.

    - super -> Usado para acessar atributos/métodos da classe mãe.

    - super() -> Usado para chamar o construtor da classe mãe.

    - ``` java
      public class Conta {
          private int agencia;
          private int conta;
          protected int numeroAleatorio;
          
          public Conta(int agencia, int conta) {
              //Usando this para acessar os atributos da classe.
              this.agencia = agencia;
              this.conta = conta;
          }
      }
      
      public class ContaCorrente extends Conta{
          
          public ContaCorrente(int agencia, int numero) {
              ////Construtor da classe ContaCorrente obrigando a passar agencia e numero ao criar a ContaCorrente, e fazendo a chamada através do super(), passando para o construtor da classe mãe os parâmetros que estão sendo recebidos.
              super(agencia, numero);
              
              //Acessando a classe mae e atribuindo ao atributo numeroAleatorio o numero 1.
              super.numeroAleatorio = 1;
          }
      }
      ```

      

      

24. No exemplo abaixo, a classe `Ornitorrinco` é herdada de `Mamifero`. Por que o código não compila, como seria possível ajustá-lo para que compilasse e, após ajustado, o que ele exibirá quando for executado?

    ```java
    class Mamifero {
    	public void fazerSom() {
    		System.out.println("...");
    	}
    }
    
    class Cachorro extends Mamifero {
    	public void fazerSom() {
    		this.latir(); 
    	}
    
    	private void latir() {
    		System.out.println("Woof woof");
    	}
    }
    
    class App {
        public static void main(String... args) {
            Cachorro beethoven = new Mamifero(); 
            //Erro: Não é possivel converter Mamifero para Cachorro;
            // Para funcionar o tipo do objeto tinha que ser de um tipo generico, como extends de Mamifero, o tipo do objeto poderia ser Mamifero e a referência a classe Cachorro, ai funcionaria.
            //Após arrumar sairia Woof woof
            beethoven.fazerSom();
        }
    }
    ```

    

25. Sobre construtores, qual(is) das alternativas abaixo está(ão) correta(s)?

    1. O construtor `default` do Java deixa de existir assim que algum outro é declarado; :heavy_check_mark:
    2. O construtor `default` do Java possui como parâmetros todos os atributos da classe;
    3. É obrigatória a criação de construtores explícitos quando a classe é herdada em algum local; :heavy_check_mark:
    4. Os construtores sempre precisam ter o modificador de acesso `public`. Caso contrário, o código não compila;
    5. O construtor `super()` precisa sempre ser chamado de forma explícita, em todos os casos de herança. :heavy_check_mark:

    

26. Qual a utilidade de classes abstratas em Java? E de métodos abstratos?

    - Classe abstratas -> É usado para fazer com que a classe seja restrita apenas aos que herdarem dela. Não é possível instanciar objetos desta classe.

    - Métodos abstratos -> Usado para fazer a declaração dos métodos na classe, sem a implementação. Usado quando deseja  fazer a declaração de algum método na classe, ai ao herdar dessa classe é obrigatório fazer a implementação desse método.

      

27. Qual a utilidade de interfaces em Java?

    - É como assinar um contrato, se uma classe é implementada de uma Interface é obrigatório fazer a declaração dos métodos dessa Interface. Muito usado quando se tem uma ação em comum e quer que as classe tenha esses métodos.

      

28. Como funciona a composição em Java?

    - É um classe composta por outros objetos em seus atributos

    - ```java
      //Exeplo
      
      public class Pessoa {
          private Strint nome;
          private Endereco endereco; //Atributo endereco do tipo da classe Endereco.
      }
      ```

      

29. Quando devemos utilizar classes abstratas (herança) e quando devemos utilizar interfaces? Qual o principal problema que o uso da segunda opção pode gerar, se não for feito da forma correta?

    - Classes abstratas(herança) -> Deve ser utilizado quando for necessário unir os dois pilares da POO, herança e polimorfismo. Com a reutilização de códigos e reescrita.
    - Interfaces -> Utilizado quando quer assinar um contrato com a classe, obrigando assim a classe fazer a implementação dos métodos da Interface. O maior problema do uso da Interface é essa obrigação de implementação de seus métodos, se for implementar uma Interface em uma classe deve se pensar se irá usar os métodos da tal.