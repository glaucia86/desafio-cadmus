# desafio-cadmus

##Desafio Técnico
  Projeto com objetivo implementar uma proposta de 3 desafios:
  - Subcadeia de soma máxima
  > 
    Dado um conjunto de números, descobrir o subconjunto em que a soma dos elementos são de máxima soma. 

    Exemplo: dado o conjunto de elementos 
    [2, -4, 6, 8, -10, 100, -6, 5]
    O subconjunto de soma máxima é:
    [2, -4, 6, 8, -10, 100, -6, 5]
    Assim, o programa deve retornar a posição do primeiro e do último elemento da subcadeia. Neste exemplo, as posições 2 e 5,     considerando a primeira posição com índice 0.

  - Conjectura de Collatz
  - Sistema Robô

##Dependências
- [JDK 1.8+](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
- [Maven 3+](http://maven.apache.org/download.cgi) Opicional

##Informações Gerais
> Para a execução dos comandos de compilação e execução dos desafios é necessário estar posicionado no diretório raiz do projeto

##Compilação do Projeto
###Utilizando o Apache Maven
```shell
mvn clean install
```

###Utilizando o Javac
**Desafio Subcadeia de soma máxima:**
```shell
#Unix Like
javac -sourcepath src/main/java -d target/classes src/main/java/br/com/rjansen/desafios/SubcadeiaSomaMaxima.java

#Windows
javac -sourcepath src\main\java -d target\classes src\main\java\br\com\rjansen\desafios\SubcadeiaSomaMaxima.java
```

**Desafio Conjectura de Collatz**
```shell
#Unix Like
javac -sourcepath src/main/java -d target/classes src/main/java/br/com/rjansen/desafios/Collatz.java

#Windows
javac -sourcepath src\main\java -d target\classes src\main\java\br\com\rjansen\desafios\Collatz.java
```

**Desafio Sistema Robô**
```shell
#Unix Like
javac -sourcepath src/main/java -d target/classes src/main/java/br/com/rjansen/desafios/SistemaRobo.java

#Windows
javac -sourcepath src\main\java -d target\classes src\main\java\br\com\rjansen\desafios\SistemaRobo.java
```

##Execução dos Desafios
**Desafio Subcadeia de soma máxima:**
```shell
#Unix Like
java -cp target/classes/ br.com.rjansen.desafios.SubcadeiaSomaMaxima [cadeia]

#Windows
java -cp target\classes\ br.com.rjansen.desafios.SubcadeiaSomaMaxima [cadeia]
```
**Onde:**
- [cadeia]=1,20,-3,4000,n
- n precisa ser um numero inteiro valido

**Desafio Conjectura de Collatz**
```shell
#Unix Like
java -cp target/classes/ br.com.rjansen.desafios.Collatz [numero_inicial_collatz]

#Windows
java -cp target\classes\ br.com.rjansen.desafios.Collatz [numero_inicial_collatz]
```
**Onde:**
- [numero_inicial_collatz]=n
- n precisa ser um numero inteiro longo valido

**Desafio Sistema Robô**
```shell
#Unix Like
java -cp target/classes/ br.com.rjansen.desafios.SistemaRobo [arquivo_comandos]

#Windows
java -cp target\classes\ br.com.rjansen.desafios.SistemaRobo [arquivo_comandos]
```
**Onde:**
- [arquivo_comandos]=/caminho_arquivo/comandos
