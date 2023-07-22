![](Media/Study.jpeg)

# :closed_book: Estudo sobre a linguagem C#
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

  * Uso de palavras-chave intuitivas: utiliza palavras-chave que são facilmente compreendidas pelos programadores, tornando o código mais expressivo e claro;

  * Blocos de código bem definidos: usa chaves {} para delimitar blocos de código, tornando mais fácil identificar o escopo das instruções;

  * Identação consistente: a linguagem incentiva o uso consistente de espaçamento e indentação para melhorar a legibilidade;

  * Nomes de variáveis descritivos: a prática de dar nomes descritivos para variáveis e funções é incentivada, tornando o propósito das entidades do programa mais claro.

* **Redigibilidade:** A redigibilidade refere-se à facilidade com que um programador pode escrever código limpo e funcional. O C# oferece recursos que tornam a tarefa de desenvolvimento mais agradável e eficiente. Alguns aspectos que melhoram a redigibilidade são:

  * Biblioteca padrão rica: possui uma biblioteca padrão extensa, que fornece muitas estruturas de dados e funções úteis, evitando que os desenvolvedores tenham que reinventar a roda ao criar aplicativos;

  * OOP (Programação Orientada a Objetos): suporta totalmente conceitos de OOP, como classes, herança, polimorfismo e encapsulamento, tornando a estruturação do código mais organizada e reutilizável;

  * Generics: a utilização de tipos genéricos permite criar algoritmos e estruturas de dados que podem ser reutilizados com diferentes tipos, aumentando a eficiência da redação do código;

  * Sintaxe amigável: a linguagem possui uma sintaxe clara e natural, permitindo expressar ideias de forma concisa.

* **Confiabilidade:** A confiabilidade de uma linguagem de programação está diretamente relacionada à previsibilidade e segurança do código gerado. O C# tem algumas características que o tornam uma linguagem confiável:

  * Tipagem estática: é uma linguagem com tipagem estática, o que significa que os tipos de dados das variáveis são verificados em tempo de compilação. Isso ajuda a capturar erros de tipo antes que o programa seja executado, tornando-o mais seguro;

  * Gerenciamento de memória: usa o Common Language Runtime (CLR) para gerenciar a memória, o que inclui coleta automática de lixo (garbage collection), ajudando a evitar vazamentos de memória e erros relacionados;

  * Tratamento de exceções: oferece um mecanismo de tratamento de exceções robusto, permitindo que os programadores capturem e lidem com erros de forma mais eficiente, melhorando a estabilidade dos programas;

  * Programação assíncrona: possui suporte nativo para programação assíncrona, o que facilita a criação de aplicativos que são mais responsivos e escaláveis.

## :interrobang: Categorias da Linguagem

* C# é principalmente uma linguagem de programação imperativa e orientada a objetos. No entanto, a partir da versão C# 3.0, ela também incorporou recursos do paradigma funcional, permitindo que os desenvolvedores usem conceitos funcionais em suas abordagens de programação.

* Vamos detalhar cada aspecto:

  * Imperativa: Em C#, os programas são escritos como uma sequência de instruções que especificam como as tarefas devem ser executadas. Os desenvolvedores usam estruturas de controle, como loops e condicionais, para definir o fluxo do programa;

  * Orientada a objetos: C# é uma linguagem fortemente orientada a objetos, o que significa que os programas são estruturados em torno de classes e objetos. Os objetos são instâncias de classes que contêm dados e comportamentos relacionados, permitindo uma modelagem mais organizada e modular do software;

  * Funcional: A partir da versão C# 3.0, a linguagem incorporou recursos do paradigma funcional, como funções de alta ordem, expressões lambda, delegados e LINQ (Language-Integrated Query). Isso permite que os desenvolvedores adotem uma abordagem mais funcional em certas partes do código, enfatizando a imutabilidade de dados e a avaliação de funções.

##  :inbox_tray: Métodos de Implementação

* A linguagem C# é implementada através de um compilador e de uma máquina virtual.

  * Compilador: O compilador de C# é responsável por transformar o código-fonte escrito em C# em código intermediário, conhecido como CIL (Common Intermediate Language) ou IL (Intermediate Language). O compilador C# converte o código-fonte em CIL, garantindo que ele siga a sintaxe e semântica da linguagem. O resultado é um arquivo com extensão .dll (biblioteca dinâmica) ou .exe (executável) contendo o código intermediário;

  * Máquina virtual: O código intermediário (CIL) é executado na máquina virtual da plataforma .NET, chamada CLR (Common Language Runtime). O CLR é responsável por carregar e executar o código intermediário gerado pelo compilador C#. Ele fornece várias funcionalidades, como gerenciamento de memória, coleta de lixo, segurança e verificação de tipos, garantindo que o código seja executado de forma segura e eficiente em diferentes ambientes de sistema operacional.

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

* **Tipos:**

  |Tipo | Valor |
  | ----------- | ----------- |
  |bool | Verdadeiro ou Falso (Valores booleandos) |
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
  |string | Seqüência de caracteres (16 bits por caractere) |

  ```
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