![](Media/Study.jpeg)

# :closed_book: `Estudo sobre a linguagem C#`
* Diário de bordo realizado para a matéria de Linguagens e Paradigmas de Programação;
* A linguagem escolhida foi C#;
* Os tópicos abordados nesse estudo foram retirados dos slides das aulas, as quais também serviram como base para o estudo.

## 🖥 O que é uma linguagem de programação?

* Uma linguagem de programação é um conjunto de regras e símbolos usados para escrever programas de computador. É uma forma padronizada de comunicação entre humanos e computadores, permitindo que os programadores expressem suas instruções de forma estruturada e compreensível para a máquina;

* As linguagens de programação são usadas para desenvolver uma ampla variedade de software, desde aplicativos simples até sistemas complexos. Elas fornecem um conjunto de comandos e estruturas de controle que permitem aos programadores criar algoritmos e instruções que serão executadas pelo computador;

* Existem muitas linguagens de programação diferentes, cada uma com suas próprias regras sintáticas e semânticas. Algumas das linguagens mais populares incluem C, C++, Java, Python, JavaScript e Ruby. Cada linguagem tem suas próprias características e finalidades específicas, e a escolha da linguagem depende do tipo de aplicativo ou sistema que está sendo desenvolvido, bem como das preferências do programador.

## :globe_with_meridians: Áreas de atuação da linguagem

*   **Desenvolvimento de software para Windows:** C# é uma das principais linguagens usadas para desenvolver aplicativos e sistemas para a plataforma Windows. O framework .NET, que inclui o ambiente de execução e bibliotecas, é amplamente utilizado para criar aplicativos desktop, serviços web e outros tipos de software para Windows;

*   **Desenvolvimento de aplicativos móveis:** Com a introdução do Xamarin, uma plataforma de desenvolvimento multiplataforma, é possível desenvolver aplicativos móveis nativos para iOS e Android usando C# e o framework .NET. O Xamarin permite compartilhar grande parte do código entre as plataformas, tornando o desenvolvimento mais eficiente;

*   **Desenvolvimento de jogos:** C# é uma linguagem muito popular para o desenvolvimento de jogos, especialmente para a plataforma Unity. O Unity é um motor de jogos amplamente utilizado e suporta a programação em C#. Muitos jogos populares foram desenvolvidos usando C# e Unity;

*   **Desenvolvimento de aplicações web:** Embora outras linguagens, como JavaScript e Python, sejam mais comumente usadas para o desenvolvimento web, C# também é usado nessa área. O framework ASP.NET permite criar aplicativos web robustos e escaláveis usando C#. Além disso, o ASP.NET Core, uma versão mais recente do framework, suporta o desenvolvimento web multiplataforma;

*   **Desenvolvimento de aplicações empresariais:** C# é frequentemente usado no desenvolvimento de aplicações empresariais devido à sua robustez, desempenho e integração com o ambiente Windows. Muitos sistemas de gerenciamento de conteúdo (CMS), sistemas de gerenciamento de relacionamento com o cliente (CRM) e aplicativos de negócios são desenvolvidos em C#.

## :clipboard: Critérios de Avaliação

* **Legibilidade:** A legibilidade de uma linguagem de programação refere-se à facilidade de leitura do código fonte. O C# é conhecido por sua sintaxe clara e bem estruturada, o que facilita a compreensão e o acompanhamento do fluxo de lógica. Alguns aspectos que contribuem para a legibilidade são:

  * **Uso de palavras-chave intuitivas:** utiliza palavras-chave que são facilmente compreendidas pelos programadores, tornando o código mais expressivo e claro;

  * **Blocos de código bem definidos:** usa chaves {} para delimitar blocos de código, tornando mais fácil identificar o escopo das instruções;

  * **Identação consistente:** a linguagem incentiva o uso consistente de espaçamento e indentação para melhorar a legibilidade;

  * **Nomes de variáveis descritivos:** a prática de dar nomes descritivos para variáveis e funções é incentivada, tornando o propósito das entidades do programa mais claro.

* **Redigibilidade:** A redigibilidade refere-se à facilidade com que um programador pode escrever código limpo e funcional. O C# oferece recursos que tornam a tarefa de desenvolvimento mais agradável e eficiente. Alguns aspectos que melhoram a redigibilidade são:

  * **Biblioteca padrão rica:** possui uma biblioteca padrão extensa, que fornece muitas estruturas de dados e funções úteis, evitando que os desenvolvedores tenham que reinventar a roda ao criar aplicativos;

  * **OOP (Programação Orientada a Objetos):** suporta totalmente conceitos de OOP, como classes, herança, polimorfismo e encapsulamento, tornando a estruturação do código mais organizada e reutilizável;

  * **Generics:** a utilização de tipos genéricos permite criar algoritmos e estruturas de dados que podem ser reutilizados com diferentes tipos, aumentando a eficiência da redação do código;

  * **Sintaxe amigável:** a linguagem possui uma sintaxe clara e natural, permitindo expressar ideias de forma concisa.

* **Confiabilidade:** A confiabilidade de uma linguagem de programação está diretamente relacionada à previsibilidade e segurança do código gerado. O C# tem algumas características que o tornam uma linguagem confiável:

  * **Tipagem estática:** é uma linguagem com tipagem estática, o que significa que os tipos de dados das variáveis são verificados em tempo de compilação. Isso ajuda a capturar erros de tipo antes que o programa seja executado, tornando-o mais seguro;

  * **Gerenciamento de memória:** usa o Common Language Runtime (CLR) para gerenciar a memória, o que inclui coleta automática de lixo (garbage collection), ajudando a evitar vazamentos de memória e erros relacionados;

  * **Tratamento de exceções:** oferece um mecanismo de tratamento de exceções robusto, permitindo que os programadores capturem e lidem com erros de forma mais eficiente, melhorando a estabilidade dos programas;

  * **Programação assíncrona:** possui suporte nativo para programação assíncrona, o que facilita a criação de aplicativos que são mais responsivos e escaláveis.

## :interrobang: Categorias da Linguagem

* C# é principalmente uma linguagem de programação imperativa e orientada a objetos. No entanto, a partir da versão C# 3.0, ela também incorporou recursos do paradigma funcional, permitindo que os desenvolvedores usem conceitos funcionais em suas abordagens de programação.

* Vamos detalhar cada aspecto:

  * **Imperativa:** Em C#, os programas são escritos como uma sequência de instruções que especificam como as tarefas devem ser executadas. Os desenvolvedores usam estruturas de controle, como loops e condicionais, para definir o fluxo do programa;

  * **Orientada a objetos:** C# é uma linguagem fortemente orientada a objetos, o que significa que os programas são estruturados em torno de classes e objetos. Os objetos são instâncias de classes que contêm dados e comportamentos relacionados, permitindo uma modelagem mais organizada e modular do software;

  * **Funcional:** A partir da versão C# 3.0, a linguagem incorporou recursos do paradigma funcional, como funções de alta ordem, expressões lambda, delegados e LINQ (Language-Integrated Query). Isso permite que os desenvolvedores adotem uma abordagem mais funcional em certas partes do código, enfatizando a imutabilidade de dados e a avaliação de funções.

##  :inbox_tray: Métodos de Implementação

* A linguagem C# é implementada através de um compilador e de uma máquina virtual.

  * **Compilador:** O compilador de C# é responsável por transformar o código-fonte escrito em C# em código intermediário, conhecido como CIL (Common Intermediate Language) ou IL (Intermediate Language). O compilador C# converte o código-fonte em CIL, garantindo que ele siga a sintaxe e semântica da linguagem. O resultado é um arquivo com extensão .dll (biblioteca dinâmica) ou .exe (executável) contendo o código intermediário;

  * **Máquina virtual:** O código intermediário (CIL) é executado na máquina virtual da plataforma .NET, chamada CLR (Common Language Runtime). O CLR é responsável por carregar e executar o código intermediário gerado pelo compilador C#. Ele fornece várias funcionalidades, como gerenciamento de memória, coleta de lixo, segurança e verificação de tipos, garantindo que o código seja executado de forma segura e eficiente em diferentes ambientes de sistema operacional.

* Portanto, o processo de implementação da linguagem C# envolve o uso do compilador C# para gerar código intermediário (CIL) e a execução desse código no ambiente da máquina virtual CLR da plataforma .NET. Isso permite que os programas escritos em C# sejam executados em diferentes sistemas operacionais que suportem o CLR, tornando a linguagem portátil e multiplataforma.

______________________

<p align="center">
  <img width="720" height="227" src="Media/Logo.png">
</p>

##  :1234: Atributos das Variáveis

* **Nome:**

  * Forma:

    * Os nomes de variáveis em C# podem ser compostos por letras, dígitos numéricos e caracteres de sublinhado (underscore "_");
    * O nome deve começar com uma letra (a-z, A-Z) ou um caractere de sublinhado ("_");
    * Não é permitido começar um nome com um dígito numérico.

  * Tamanho:

    * O tamanho máximo de um nome de variável em C# é ilimitado. No entanto, é uma boa prática manter os nomes de variáveis razoavelmente curtos e descritivos para facilitar a legibilidade do código.

  * Caracteres de conexão:

    * Sim, caracteres de sublinhado ("_") podem ser usados em nomes de variáveis. Por exemplo, "minha_variavel" é um nome de variável válido em C#.

  * Distinção :

    * Sim, C# é uma linguagem case sensitive, ou seja, faz distinção entre maiúsculas e minúsculas nos nomes de variáveis. Isso significa que as letras maiúsculas e minúsculas são tratadas como caracteres diferentes. Por exemplo, "minha_variavel" e "Minha_Variavel" são considerados nomes de variáveis distintos.

  * Palavras reservadas:

    * A linguagem C# reserva setenta e cinco palavras para seu próprio uso. Estas palavras são chamadas de palavras reservadas e cada uma tem um uso particular. Palavras reservadas não são permitidas como nome de variáveis.

    * Segue uma lista que identifica todas estas palavras:

      | abstract | as       | base    | Bool     |
      | ----------- | ----------- | ----------- | ----------- |
      | break    | byte     | case    | Catch    |
      | char     | checked  | class   | Const    |
      | continue | decimal  | default | Delegate |
      | do       | double   | else    | Enum     |
      | event    | explicit | extern  | false    |
      | finally  | fixed    | float   | for      |
      | foreach  | goto     | if      | implicit |
      | in       | int      | interface | internal |
      | is       | lock     | long    | namespace|
      | new      | null     | object  | operator |
      | out      | override | params  | private  |
      | protected| public   | readonly| ref      |
      | return   | sbyte    | sealed  | short    |
      | sizeof   | stackalloc | static | string   |
      | struct   | switch   | this    | throw    |

* **Tipos e seus intervalos de valores:**

  |Tipo | Valor |
  | ----------- | ----------- |
  |bool | Verdadeiro ou Falso (Valores booleanos) |
  |byte | 0 a 255 (8 bits) |
  |sbyte | -128 a 127 (8 bits) |
  |char | Um caractere (16 bits) |
  |decimal | ±1.0 × 10−28 a ±7.9 × 1028 (128 bits) |
  |double | ±5.0 × 10−324 a ±1.7 × 10308 (64 bits) |
  |float | ±1.5 × 10−45 a ±3.4 × 1038 (32 bits) |
  |int | -2,147,483,648 a 2,147,483,647 (32 bits) |
  |uint | 0 a 4,294,967,295 (32 bits) |
  |long | –9,223,372,036,854,775,808 a 9,223,372,036,854,775,807 (64 bits) |
  |ulong | 0 a 18,446,744,073,709,551,615 (64 bits) |
  |object | Qualquer tipo |
  |short | -32,768 a 32,767 (16 bits) |
  |ushort | 0 a 65,535 (16 bits) |
  |string | Sequência de caracteres (16 bits por caractere) |

  * Exemplo das variáveis em forma de código:

    ```csharp
    using System;

    class Program
    {
        static void Main()
        {
            // Declaração e inicialização de variáveis
            bool isTrue = true;
            bool isFalse = false;
            byte myByte = 200;
            sbyte mySByte = -50;
            char myChar = 'A';
            decimal myDecimal = 1234.56789M;
            double myDouble = 3.141592653589793;
            float myFloat = 2.718281828459045f;
            int myInt = 42;
            uint myUInt = 4294967295;
            long myLong = 9223372036854775807;
            ulong myULong = 18446744073709551615;
            object myObject = "Qualquer tipo pode ser armazenado aqui.";
            short myShort = -1000;
            ushort myUShort = 5000;
            string myString = "Exemplo de sequência de caracteres.";
        }
    }
    ```
* **Amarração de tipo:**

  * Estática

    * O tipo de amarração (binding) das variáveis é estático. Isso significa que o tipo de uma variável é definido em tempo de compilação e não pode ser alterado durante a execução do programa. Quando você declara uma variável, precisa especificar explicitamente o tipo dela.

      ```csharp
      //Exemplo de amarração estática
      int idade = 25;
      string nome = "João";
      ```
  
  * Inferência

    * C# também suporta o recurso de inferência de tipo, introduzido na versão 3.0 através do recurso "var". Com a inferência de tipo, o compilador é capaz de deduzir automaticamente o tipo da variável com base no valor atribuído a ela.

      ```csharp
      //Exemplo de inferência
      var numero = 42; // O compilador infere que "numero" é do tipo int.
      var texto = "Hello, world!"; // O compilador infere que "texto" é do tipo string.
      ```
    * Apesar do uso de "var", é importante notar que o tipo da variável é definido em tempo de compilação, e não há mudança na natureza estática. A inferência de tipo é apenas uma forma de escrever o código de forma mais concisa, sem perder a tipagem estática da linguagem.

  * Dinâmica

    * Em C# existe a possibilidade de utilizar amarração dinâmica de tipos através do tipo especial "dynamic". O tipo "dynamic" foi introduzido na versão 4.0 da linguagem e permite que você defina variáveis cujos tipos são resolvidos em tempo de execução, em vez de serem definidos em tempo de compilação.

    * Quando você declara uma variável com o tipo "dynamic", o compilador não faz a verificação de tipo em tempo de compilação. Isso significa que você pode realizar operações em variáveis "dynamic" sem que o compilador verifique se essas operações são válidas para o tipo atribuído a ela. Em vez disso, essas verificações são feitas em tempo de execução.

      ```csharp
      dynamic valor = 10;
      Console.WriteLine(valor); // Saída: 10

      valor = "Olá";
      Console.WriteLine(valor); // Saída: Olá

      valor = DateTime.Now;
      Console.WriteLine(valor); // Saída: A data e hora atual

      valor = 3 + 4;
      Console.WriteLine(valor); // Saída: 7
      ```

    * Observe que o tipo da variável "valor" é definido dinamicamente conforme o valor que é atribuído a ela. No primeiro caso, o tipo é inferido como int, no segundo caso, como string e assim por diante.

    * É importante ter cuidado ao usar "dynamic", pois você perde as verificações de tipo em tempo de compilação, o que pode levar a erros em tempo de execução se as operações não forem compatíveis com o tipo real da variável. A utilização de "dynamic" é recomendada apenas em situações específicas em que é realmente necessário lidar com tipos desconhecidos ou em interoperação com APIs dinâmicas, como COM ou linguagens dinâmicas. Em geral, é preferível utilizar a tipagem estática para obter maior segurança e desempenho.

* **Escopo:**

  * Em C#, o tempo de vida de uma variável depende do escopo em que ela é declarada. Existem três principais escopos em que as variáveis podem ser declaradas:

    * **Escopo de bloco (local):** Variáveis declaradas dentro de um bloco de código, como dentro de um método, têm tempo de vida restrito ao bloco em que foram declaradas. Quando o bloco é concluído, a variável é destruída e a memória que ocupava é liberada. Isso é conhecido como "variável local".

      ```csharp
      public void ExemploMetodo()
      {
          int variavelLocal = 10; // variável local
          // outras operações com variavelLocal
      } // variavelLocal será destruída após a conclusão do método
      ```
    
    * **Escopo de classe (campo):** Variáveis declaradas em nível de classe têm tempo de vida igual ao tempo de vida da instância da classe. Elas existem enquanto o objeto da classe existe e são destruídas quando o objeto é liberado da memória.

      ```csharp
      public class MinhaClasse
      {
          private int campo = 20; // variável de classe (campo)
          // outras operações com campo
      } // campo será destruída quando a instância de MinhaClasse for liberada da memória
      ```

    * **Escopo estático (variáveis estáticas):** Variáveis declaradas como "static" têm tempo de vida igual ao tempo de vida do programa. Elas são criadas quando o programa começa sua execução e só são destruídas quando o programa termina.

      ```csharp
      public class MinhaClasse
      {
          private static int variavelEstatica = 30; // variável estática
          // outras operações com variavelEstatica
      } // variavelEstatica será destruída quando o programa terminar
      ```

* **Ambiente de referênciação:**

  * Ambiente de referenciação de uma sentença é o conjunto de todas as variáveis visíveis naquela posição. Em uma linguagem de escopo estático (que é o caso da nossa linguagem C#) são as variáveis declaradas em seu escopo local, mais o conjunto de todas as variáveis de seus escopos ancestrais visíveis.

* **Constantes:**

  * Em C# existem constantes nomeadas, que são valores fixos que não podem ser alterados durante a execução do programa. Em vez de usar valores literais diretamente no código, as constantes nomeadas permitem atribuir um nome significativo a um valor constante, tornando o código mais legível e facilitando a manutenção.

  * Para definir uma constante nomeada em C#, você pode usar a palavra-chave const ou readonly.

  * Constantes com a palavra-chave const:

    ```csharp
    public class MinhaClasse
    {
        // Constante nomeada usando a palavra-chave 'const'
        public const int MinhaConstante = 42;

        // Outros membros da classe
    }
    ```
    * Neste exemplo, MinhaConstante é uma constante nomeada que foi atribuída ao valor inteiro 42. O valor de uma constante definida com const é avaliado em tempo de compilação, e a constante é considerada uma constante literal. Isso significa que o valor deve ser conhecido em tempo de compilação e deve ser um tipo de dado primitivo ou uma string.

  * Constantes com a palavra-chave readonly:

    ```csharp
    public class MinhaClasse
    {
        // Constante nomeada usando a palavra-chave 'readonly'
        public static readonly int MinhaConstante = 100;

        // Outros membros da classe
    }
    ```
    * Neste caso, MinhaConstante é uma constante nomeada definida com a palavra-chave readonly. O valor de uma constante readonly é avaliado em tempo de execução, o que significa que ele pode ser atribuído durante a inicialização da variável ou em um construtor, permitindo a inicialização com base em lógica mais complexa.

  * Uma diferença importante entre const e readonly é que as constantes readonly podem ser usadas em classes e estruturas, enquanto as constantes const são restritas a tipos primitivos ou strings e só podem ser usadas em nível de classe.

  * Independente da palavra-chave utilizada, as constantes nomeadas em C# são uma maneira eficaz de tornar o código mais legível, manutenível e de evitar erros ao usar valores constantes em várias partes do programa.

##  :game_die: Tipos de Dados

  * **Tipos primitivos:** 

    * Os tipos de dados primitivos, também conhecidos como tipos de valor, são usados para armazenar valores individuais. Esses tipos são fornecidos pela linguagem e não requerem instância de objetos. Os tipos de dados primitivos incluem:

      * Tipos Numéricos Inteiros:
        *  **int:** Representa números inteiros com sinal de 32 bits/ 4 bytes;
        *  **uint:** Representa números inteiros sem sinal de 32 bits/ 4 bytes;
        *  **short:** Representa números inteiros com sinal de 16 bits/ 2 bytes;
        *  **ushort:** Representa números inteiros sem sinal de 16 bits/ 2 bytes;
        *  **long:** Representa números inteiros com sinal de 64 bits/ 8 bytes;
        *  **ulong:** Representa números inteiros sem sinal de 64 bits/ 8 bytes;
        *  **byte:** Representa números inteiros sem sinal de 8 bits/ 1 byte;
        *  **sbyte:** Representa números inteiros com sinal de 8 bits/ 1 byte.

      * Tipos Numéricos de Ponto Flutuante:
        *  **float:** Representa números de ponto flutuante de precisão simples de 32 bits/ 4 bytes;
        *  **double:** Representa números de ponto flutuante de precisão dupla de 64 bits/ 8 bytes;
        *  **decimal:** Representa números de ponto flutuante de alta precisão de 128 bits/ 16 bytes.

      * Tipo Char:
        *  **char:** Representa um único caractere Unicode de 16 bits/ 2 bytes.

      * Tipo Booleano:
        * **bool:** Representa um valor verdadeiro ou falso (true ou false).

  * **Tipos não primitivos:**

    * Os tipos de dados não primitivos, também conhecidos como tipos de referência, são usados para armazenar referências a objetos. Eles exigem uma instância de objeto para serem utilizados e são armazenados na memória gerenciada. Os tipos de dados não primitivos incluem:

      *  **string:** Representa uma sequência de caracteres Unicode. É usado para armazenar e manipular texto.

      *  **object:** É a classe base de todos os tipos em C#. Pode armazenar qualquer valor de qualquer tipo e é comumente usado quando a especificação exata do tipo é desconhecida ou não é relevante.

      *  **Array:** Representa uma coleção fixa de elementos do mesmo tipo. Os arrays podem ser unidimensionais, multidimensionais ou jagged (arrays de arrays).

      *  **Classe (class):** É um tipo de referência personalizado definido pelo programador. Uma classe é uma estrutura de dados que encapsula dados e comportamentos relacionados.

      *  **Interface (interface):** É uma referência a um contrato que define um conjunto de métodos que uma classe deve implementar. As interfaces permitem a implementação de múltiplas interfaces por uma classe.

      *  **Delegate (delegado):** Representa uma referência a um método, permitindo tratar métodos como entidades que podem ser passadas como parâmetros e invocadas.

      *  **Enumeração (enum):** É um tipo de valor que consiste em um conjunto de constantes nomeadas, representando valores simbólicos associados a um tipo de dados integral.

      *  **Struct (struct):** É um tipo de valor personalizado, semelhante a uma classe, mas geralmente usado para tipos de valor mais simples e leves.

      *  **Nullable (Tipos Nullable):** Permitem que tipos de valor aceitem valores nulos além de seus valores normais. Por exemplo, int? é usado para um inteiro que pode ser nulo.

  * **Tipos ordinais:**

    * Os tipos ordinais (também conhecidos como enums) definidos pelo usuário são tipos enumerados personalizados que permitem definir um conjunto nomeado de constantes com valores associados. Eles são úteis para representar conjuntos discretos de valores, como dias da semana, estados, opções, etc.

    * Para criar um tipo ordinal definido pelo usuário (enum) em C#, você pode usar a palavra-chave enum. Aqui está um exemplo de como definir um tipo enum para representar os dias da semana:

      ```csharp
      public enum DiaDaSemana
      {
        Domingo,
        Segunda,
        Terca,
        Quarta,
        Quinta,
        Sexta,
        Sabado
      }
      ```

      * Neste exemplo, definimos um tipo enum chamado DiaDaSemana e listamos os dias da semana como constantes nomeadas. Por padrão, os valores associados começam a partir de 0 (Domingo = 0, Segunda = 1, Terça = 2, etc.), mas você pode atribuir valores específicos se necessário.

    * Exemplo com valores específicos:

      ```csharp
      public enum DiaDaSemana
      {
        Domingo = 1,
        Segunda = 2,
        Terca = 3,
        Quarta = 4,
        Quinta = 5,
        Sexta = 6,
        Sabado = 7
      }
      ```

       * Aqui, atribuímos explicitamente valores numéricos aos dias da semana, começando por 1.

    * Com a definição do enum, podemos usar esse tipo como qualquer outro tipo de dados, e as constantes nomeadas facilitam o uso e a legibilidade do código:

      ```csharp
      DiaDaSemana dia = DiaDaSemana.Segunda;
      Console.WriteLine("Hoje é " + dia); // Saída: Hoje é Segunda
      ```
    
    * Os tipos ordinais definidos pelo usuário são uma forma conveniente e segura de representar um conjunto limitado de valores em C#, e eles ajudam a tornar o código mais legível e autodocumentado.

  * **Arrays:**

    * Tipos:

      * **Array estático:** Um array estático em C# é uma coleção de elementos do mesmo tipo com tamanho fixo, onde o tamanho precisa ser definido em tempo de compilação e não pode ser alterado durante a execução do programa.

        ```csharp
          int[] staticArray = new int[5]; // Cria um array estático de inteiros com tamanho 5.
        ```

      * **Array heap-dinâmico:** Em C#, os arrays são alocados no heap (memória gerenciada) e o tamanho do array pode ser definido em tempo de execução usando o construtor new.

        ```csharp
          int size = 3;
          int[] dynamicArray = new int[size]; // Cria um array dinâmico de inteiros com tamanho definido em tempo de execução.
        ```

    * Inicialização:

      * **Inicialização direta:** você pode inicializar um array diretamente com os valores dos elementos entre chaves {}.
        ```csharp
        int[] numbers = { 1, 2, 3, 4, 5 };
        ```

      * **Usando o construtor new:** você pode usar o construtor new para criar um array e definir o tamanho explicitamente.
        ```csharp
        int[] dynamicArray = new int[3]; // Cria um array de inteiros com tamanho 3.
        ```      
      
      * **Inicialização com valores padrão:** um array é automaticamente preenchido com valores padrão (zero, no caso de inteiros) se você não definir valores para todos os elementos.
        ```csharp
        int[] uninitializedArray = new int[5]; // Todos os elementos serão 0.
        ```      
      
      * **Inicialização com valor único:** você pode inicializar todos os elementos do array com o mesmo valor usando Enumerable.Repeat().
        ```csharp
        int[] repeatedArray = Enumerable.Repeat(10, 5).ToArray(); // Cria um array com 5 elementos, todos com valor 10.
        ```
      
      * **Inicialização com array existente:** você pode inicializar um novo array com os elementos de um outro array já existente.
        ```csharp
        int[] sourceArray = { 1, 2, 3 };
        int[] newArray = new int[sourceArray.Length];
        Array.Copy(sourceArray, newArray, sourceArray.Length);
        ```
      
      * **Array multidimensional:** além de arrays unidimensionais, você pode criar arrays multidimensionais (matrizes).
        ```csharp
        int[,] matrix = { { 1, 2 }, { 3, 4 } }; // Cria uma matriz 2x2.
        ```

      * **Array de arrays (jagged arrays):** você pode criar arrays que contêm outros arrays.
        ```csharp
        int[][] jaggedArray = new int[3][];
        jaggedArray[0] = new int[] { 1, 2 };
        jaggedArray[1] = new int[] { 3, 4, 5 };
        jaggedArray[2] = new int[] { 6 };
        ```
    
    * Implementação:

      * **Tipo Base:**  
        * Em C#, todos os tipos de arrays são derivados da classe base System.Array. Isso inclui arrays unidimensionais, multidimensionais e arrays de arrays (jagged arrays).

      * **Alocação de Memória:**
        * Quando você cria um array usando o operador new, a memória é alocada no heap (memória gerenciada). Isso é verdade mesmo para arrays primitivos, pois o C# trata todos os tipos como objetos.
        * A memória alocada é contígua e igual ao tamanho do array multiplicado pelo tamanho do tipo de elemento.

      * **Acesso aos Elementos:**
        * Os elementos de um array são acessados usando índices baseados em zero. Por exemplo, array[0] acessa o primeiro elemento do array.
        * O acesso direto aos elementos é rápido, pois os arrays mantêm informações sobre o tipo de elemento e a localização na memória, o que permite calcular rapidamente a posição do elemento.

      * **Tamanho Fixo:**
        * Os arrays em C# têm tamanho fixo, o que significa que você precisa definir o tamanho do array no momento da criação e não pode alterá-lo posteriormente.
        * Se você precisar de uma coleção dinâmica, pode usar outras estruturas de dados como listas (List<T>) ou coleções genéricas.

      * **Performance:**
        * Os arrays oferecem acesso rápido aos elementos, pois eles estão armazenados em memória contígua, permitindo um acesso direto e eficiente aos endereços de memória.
        * A busca e a modificação de elementos em arrays são operações O(1) (constante), desde que o índice seja conhecido.
        
      * **Comprimento do Array:**
        * O comprimento de um array (número de elementos) é armazenado como uma propriedade chamada Length. Essa propriedade é usada para iterar pelos elementos de um array.
      
      * **Limitações:**
        * Os arrays têm limitações, como tamanho fixo e ineficiência na inserção/remoção de elementos. Para casos onde a flexibilidade é mais importante, outras estruturas de dados, como listas, podem ser mais adequadas.

      * **Array Multidimensional e Jagged Arrays:**
        * Arrays multidimensionais (matrizes) são implementados como arrays de arrays. Cada elemento do array principal contém um sub-array.
        * Jagged arrays (arrays de arrays) são arrays onde cada elemento é um array separado. Eles podem ter comprimentos diferentes para cada sub-array.

  * **Registro:**

    * Um registro em C# é uma classe ou um struct que fornece sintaxe e comportamento especiais para trabalhar com modelos de dados. O modificador `record` instrui o compilador a sintetizar membros que são úteis para tipos cuja função primária é armazenar dados. Esses membros incluem uma sobrecarga de ToString() e membros que dão suporte à igualdade de valor.

    * Considere usar um registro no lugar de uma classe ou struct nos seguintes cenários:

      * Você deseja definir um modelo de dados que depende da igualdade de valor.
      * Você deseja definir um tipo para o qual os objetos são imutáveis.

    * Igualdade de valor:

      * Para registros, a igualdade de valor significa que duas variáveis de um tipo de registro são iguais se os tipos corresponderem e todos os valores de propriedade e de campo corresponderem. Para outros tipos de referência, como classes, igualdade significa igualdade de referência. Ou seja, duas variáveis de um tipo de classe são iguais quando se referem ao mesmo objeto. Métodos e operadores que determinam a igualdade de duas instâncias de registro usam igualdade de valor.

    * Imutabilidade: 

      * Um tipo imutável é aquele que impede que você altere qualquer propriedade ou valor de campo de um objeto após ser instanciado. A imutabilidade pode ser útil quando você precisa que um tipo seja thread-safe ou que um código hash permaneça o mesmo em uma tabela de hash. Os registros fornecem sintaxe concisa para criar e trabalhar com tipos imutáveis.
    
    * Diferenças: 

      * A mesma sintaxe que declara e instancia classes ou structs pode ser usada com registros. Basta substituir a palavra-chave `class` por `record`, ou usar `record struct` em vez de `struct`. Da mesma forma, as classes de registro dão suporte à mesma sintaxe para expressar relações de herança. Os registros diferem das classes das seguintes maneiras:

        * Você pode usar parâmetros posicionais em um construtor primário para criar e instanciar um tipo com propriedades imutáveis.
        * Os mesmos métodos e operadores que indicam igualdade de referência ou desigualdade em classes (como Object.Equals(Object) e `==`), indicam igualdade de valor ou desigualdade nos registros.
        * Você pode usar uma expressão with para criar uma cópia de um objeto imutável com novos valores em propriedades selecionadas.
        * O método `ToString` de um registro cria uma cadeia de caracteres formatada que mostra o nome do tipo de um objeto e os nomes e valores de todas as propriedades públicas dele.
        * Um registro pode herdar de outro registro. Um registro não pode herdar de uma classe, e uma classe não pode herdar de um registro.
      
      * Os structs de registro diferem dos structs, pois o compilador sintetiza os métodos de igualdade e `ToString`. O compilador sintetiza o método `Deconstruct` para structs de registro posicional.

      * O compilador sintetiza uma propriedade public init-only para cada parâmetro de construtor primário em um `record class`. Em um `record struct`, o compilador sintetiza uma propriedade pública de leitura/gravação. O compilador não cria propriedades para parâmetros de construtor primário em tipos `class` e `struct` que não incluem modificador `record`.

      * Exemplos:

        O exemplo a seguir define um registro público que usa parâmetros posicionais para declarar e instanciar um registro. Em seguida, ele imprime o nome do tipo e os valores de propriedade:
          ```csharp
          public record Person(string FirstName, string LastName);

          public static void Main()
          {
              Person person = new("Nancy", "Davolio");
              Console.WriteLine(person);
              // saída: Person { FirstName = Nancy, LastName = Davolio }
          }
          ```
        
        O seguinte exemplo demonstra a igualdade de valor em registros:
          ```csharp
          public record Person(string FirstName, string LastName, string[] PhoneNumbers);

          public static void Main()
          {
              var phoneNumbers = new string[2];
              Person person1 = new("Nancy", "Davolio", phoneNumbers);
              Person person2 = new("Nancy", "Davolio", phoneNumbers);
              Console.WriteLine(person1 == person2); // saída: Verdadeiro

              person1.PhoneNumbers[0] = "555-1234";
              Console.WriteLine(person1 == person2); // saída: Verdadeiro

              Console.WriteLine(ReferenceEquals(person1, person2)); // saída: Falso
          }
          ```

  * **Ponteiro:**

    * Unsafe: 

      * A maior parte do código C# que você escreve é "código seguro verificável". Código seguro verificável significa que as ferramentas do .NET podem confirmar que o código é seguro. Em geral, o código seguro não acessa diretamente a memória usando ponteiros. Ele também não aloca memória bruta. Em vez disso, ele cria objetos gerenciados.

      * O C# dá suporte a um contexto unsafe em que você pode escrever códigos não verificáveis. Em um contexto `unsafe`, o código pode usar ponteiros, alocar e liberar blocos de memória e chamar métodos usando ponteiros de função. O código não seguro em C# não é necessariamente perigoso; é apenas um código cuja segurança não pode ser verificada.

      * O código não seguro tem as propriedades a seguir:

        * Blocos de código, tipos e métodos podem ser definidos como não seguros;
        * Em alguns casos, o código não seguro pode aumentar o desempenho de um aplicativo removendo as verificações de limites de matriz;
        * O código não seguro é necessário quando você chama funções nativas que exigem ponteiros;
        * Usar o código não seguro apresenta riscos de segurança e estabilidade;
        * O código que contém blocos não seguros deve ser compilado com a opção do compilador AllowUnsafeBlocks.

    * Tipos de Ponteiro:

      * Em um contexto não seguro, os tipos podem ser de ponteiro, além de tipo de valor ou tipo de referência. Uma declaração de tipo de ponteiro usa uma das seguintes formas:
        ```csharp
        type* identifier;
        void* identifier; //permitido, mas não recomendado
        ```

      * O tipo especificado antes do `*` em um tipo de ponteiro é chamado de tipo *referent*. Somente um tipo não gerenciado pode ser um tipo referent.

      * Os tipos de ponteiro não são herdados de object e não há conversão entre tipos de ponteiro e `object`. Além disso, as conversões boxing e unboxing não oferecem suporte a ponteiros. No entanto, você pode converter entre diferentes tipos de ponteiro e tipos de ponteiro e tipos integrais.

      * Ao declarar vários ponteiros na mesma declaração, você escreve o asterisco (`*`) juntamente com o tipo subjacente apenas. Ele não é usado como um prefixo para cada nome de ponteiro. Por exemplo:
        ```csharp
        int* p1, p2, p3;   // Ok
        int *p1, *p2, *p3;   // Inválido em C#
        ```
      
      * Um ponteiro não pode apontar para uma referência ou um struct que contenha referências, pois uma referência de objeto pode ser coletada como lixo mesmo se um ponteiro estiver apontando para ela. O coletor de lixo não se dá conta de que um objeto está sendo apontado por qualquer tipo de ponteiro.

      * O valor da variável de ponteiro do tipo `MyType*` é o endereço de uma variável do tipo `MyType`. Estes são exemplos de declarações de tipos de ponteiro:

        * `int* p`: p é um ponteiro para um inteiro.  
        * `int** p`: p é um ponteiro para um ponteiro para um inteiro.
        * `int*[] p`: p é uma matriz unidimensional de ponteiros para inteiros.
        * `char* p`: p é um ponteiro para um caractere.
        * `void* p`: p é um ponteiro para um tipo desconhecido.

      * O operador de indireção de ponteiro * pode ser usado para acessar o conteúdo no local apontado pela variável de ponteiro. Por exemplo, considere a seguinte declaração:

        ```csharp
        int* myVariable;
        ```

      * A expressão *myVariable denota a variável int encontrada no endereço contido em myVariable.
    
    
    * Operações:

      * Em C# é possível realizar as seguintes ações com ponteiros:

        * **Declaração de Ponteiro:**

          Você pode declarar um ponteiro usando o tipo do valor que ele aponta, seguido pelo operador `*`.

        * **Atribuição de Endereço:**

          Você pode atribuir um endereço de memória a um ponteiro usando o operador de referência `&`.

        * **Desreferenciamento:**
        
          Para acessar o valor apontado por um ponteiro, você usa o operador de desreferenciamento `*`.

        * **Atribuição de Valor:**

          Você pode atribuir um valor a um endereço apontado por um ponteiro.

        * **Aritmética de Ponteiro:**

          Em C#, a aritmética de ponteiro é restrita a adição e subtração de valores inteiros constantes.

        * **Comparação de Ponteiro:**

          Você pode comparar ponteiros usando os operadores de comparação (==, !=, <, <=, >, >=).

        * **Uso com Arrays:**

          Ponteiros podem ser usados para percorrer arrays.

    * Operadores:

      | Operador/Instrução  |  Uso  |
      | ----------- | ----------- |
      |`*`  | Executa indireção de ponteiro|
      |`->` | Acessa um membro de um struct através de um ponteiro|
      |`[]` | Indexa um ponteiro|
      |`&`  | Obtém o endereço de uma variável|
      |`++` e `--`  | Incrementa e decrementa ponteiros|
      |`+` e `-`  | Executa aritmética de ponteiros|
      |`==`, `!=`, `<`, `>`, `<=` e `>=`  | Compara ponteiros|
      |_stackalloc_ | Aloca memória na pilha|
      |_fixedinstrução_ | Corrige temporariamente uma variável para que seu endereço possa ser encontrado|

  * Verificação de Tipo:

    * C# é uma linguagem de programação que faz verificação de tipo em tempo de compilação e em tempo de execução para garantir a segurança e a integridade do programa. Aqui estão as principais informações sobre a verificação de tipo em C#:

    * Verificação de Tipo em Tempo de Compilação:

      * Durante o processo de compilação, o compilador C# verifica se as operações e atribuições estão sendo feitas com tipos compatíveis. Ele garante que você não esteja tentando fazer operações inválidas, como adicionar um número a uma string ou atribuir um tipo incompatível a uma variável. Isso ajuda a detectar erros de tipo antes mesmo de executar o programa.

    * Verificação de Tipo em Tempo de Execução:

      * Além da verificação em tempo de compilação, C# também faz verificações de tipo em tempo de execução. Isso é especialmente relevante quando se trabalha com polimorfismo, herança e tipos dinâmicos. Durante a execução, o Common Language Runtime (CLR) do .NET verifica se as chamadas de método e as operações de tipo são válidas, evitando erros e exceções relacionados a tipos incompatíveis.

    * Verificação de Tipo para Segurança:

      * A verificação de tipo em C# também desempenha um papel fundamental na segurança. A linguagem é projetada para prevenir operações inseguras que poderiam levar a problemas de acesso à memória ou corrupção de dados. Isso é especialmente importante para prevenir vulnerabilidades como buffer overflows e vazamentos de memória.

  * Tipagem Forte (Strong Typing):

    * A tipagem forte em C# significa que os tipos de dados são rigorosamente aplicados e verificados durante o desenvolvimento e a execução do programa. Isso implica que operações inválidas entre tipos diferentes não são permitidas, e todas as conversões de tipo devem ser feitas explicitamente. Essa abordagem ajuda a prevenir erros de tipo e promove a segurança e integridade do código.

##  :triangular_ruler: Expressões e Sentenças de Atribuição

  * Operadores: 

    * **Operadores Unários:** operam em um único operando.
      * Exemplos:

        * `+` (positivo)
        * `-` (negativo)
        * `!` (negação lógica)
        * `~` (complemento bit a bit)
        * `++` (incremento)
        * `--` (decremento)

    * **Operadores Binários:** operam em dois operandos.
      * Exemplos:

        * `+` (adição)
        * `-` (subtração)
        * `*` (multiplicação)
        * `/` (divisão)
        * `%` (módulo)
        * `==` (igual a)
        * `!=` (diferente de)
        * `<` (menor que)
        * `>` (maior que)
        * `<=` (menor ou igual a)
        * `>=` (maior ou igual a)
        * `&` (AND bit a bit)
        * `|` (OR bit a bit)
        * `^` (XOR bit a bit)
        * `&&` (AND lógico)
        * `||` (OR lógico)
        * `<<` (deslocamento de bits à esquerda)
        * `>>` (deslocamento de bits à direita)

    * **Operador Ternário:** só existe um operador ternário em C# e ele é usado para criar expressões condicionais.
      * Exemplo:

        * `?` : (operador condicional ternário)

  * Precedência:

    * A precedência de operadores em C# determina a ordem em que as operações são avaliadas em uma expressão. É importante entender a precedência dos operadores para garantir que as expressões sejam avaliadas da maneira correta. Aqui está uma lista dos operadores em C# ordenados por precedência, do mais alto ao mais baixo:

      | Operador |  Significado  |
      | ----------- | ----------- |
      | `()`, `[]`, `->`, `.` | Acesso a membros|
      | `++`, `--` | Incremento e Decremento|
      | `+`, `-` | Operadores unários de sinal|
      | `!`, `~` | Operadores de negação|
      | `*`, `/`, `%` | Multiplicação, Divisão, Módulo|
      | `+`, `-` | Adição, Subtração|
      | `<<`, `>>` | Deslocamento de bits|
      | `<`, `<=`, `>`, `>=` | Operadores de comparação|
      | `==`, `!=` | Igualdade e Desigualdade|
      | `&` | AND Bitwise|
      | `^` | XOR Bitwise|
      | `\|` | OR Bitwise|
      | `&&` | AND Lógico|
      | `\|\|` | OR Lógico|
      | `? :` | Operador condicional ternário|
      | `=`, `+=`, `-=`, `*=`, `/=`, `%=`, `&=`, `\|=`, `^=`, `<<=`, `>>=` | Atribuição|
      | `,` | Operador de vírgula, usado para separar expressões|