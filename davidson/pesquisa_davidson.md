# Conceitos de Biblioteca

**O conceito de biblioteca** em seu sentido tradicional, entendida como coleção pública ou privada de livros e documentos congêneres, organizada para estudo, leitura e consulta, é apresentado como parâmetro para os produtos e serviços oferecidos pelas Bibliotecas Digitais.

**A ideia da biblioteca** é compartilhar soluções por meio de funções ou métodos.

Se você tiver que fazer um trabalho de matemática, por exemplo, poderá ir até uma biblioteca física, pegar um livro e utilizar equações desenvolvidas no livro. Então, não será preciso desenvolver as equações desde o início. Em outras palavras, você não precisa reinventar a roda! Ainda bem, né?

Em programação, a biblioteca possui a mesma função. Desenvolvedores disponibilizam bibliotecas que possuem muitas funções prontas. Assim, outros programadores podem utilizá-las, permitindo que o desenvolvimento seja mais fácil e rápido.

Pode parecer que não, mas se você já desenvolveu programas que sejam um pouco mais complexos, certamente já utilizou uma biblioteca, mesmo sem perceber. Por exemplo, quando vamos fazer um sqrt em C, estamos utilizando a biblioteca math.h que possui a função de calcular a raiz quadrada de um número.

Quando você faz um Convert.ToInt32 em C#, está utilizando um método da classe Convert, que está na biblioteca System. Ou quando for fazer um toUpper em Java, você está usando a biblioteca java.Lang. Todas essas bibliotecas são externas ao seu projeto, porém, nativas da sua respectiva linguagem. Se for necessário, você também pode importar bibliotecas que não são nativas. Além disso, também é possível criar bibliotecas internas no seu projeto.

Para darmos um exemplo ainda mais popular, podemos citar o jQuery, talvez a biblioteca mais conhecida no universo da TI, principalmente, se você trabalha com desenvolvimento front-end.
A grande vantagem das Bibliotecas

Uma das grandes vantagens da criação de bibliotecas é que você pode utilizá-las em diferentes projetos. Essa prática vai ao encontro de um princípio muito importante de Clean Code: a divisão de responsabilidades. 

Mesmo que você não utilize uma linguagem orientada a objetos, com o uso adequado de bibliotecas, é possível dividir muito bem as responsabilidades do código. Isto ajuda a evitar repetições! Já, nas linguagens orientadas a objetos, as bibliotecas auxiliam ainda mais nesse princípio, permitindo o baixo acoplamento. Todos esses pontos demonstram como as bibliotecas são poderosas aliadas quando falamos de desenvolvimento rápido de softwares complexos.

# Conceitos de Framework

Esse é um conceito provavelmente ainda mais abstrato. Podemos dizer que é um conjunto de códigos abstratos e/ou genéricos que unem códigos com recursos iguais. Ou seja, está ligado à arquitetura do seu software.

Pensemos em uma tela de login! Normalmente, essas telas são muito parecidas em todas as aplicações, elas possuem campo para usuário, senha, um botão de recuperação de senha e um de ‘entrar’. Pensando nisso, alguns desenvolvedores criaram um framework que implementa essas funções no seu código. Assim, não é necessário reescrever o código sempre que for preciso criar uma tela de login.

As funcionalidades de um framework podem ser bem variadas. Entre elas:

* Persistência de dados;
* Mapeamento de banco de dados relacional;
* Implementação de MVC em aplicações web;
* Geração de logs;
* E entre outras possíveis funcionalidades.

O framework está ligado diretamente ao código fonte da aplicação. Isso significa que, para cada linguagem de programação, teremos frameworks diferentes, mesmo que eles exerçam a mesma função. Afinal, a criação de uma tela de login é diferente no Java, no Python e no .NET.

Na verdade, nem sempre essa afirmação é correta, existem muitos frameworks que não são assim… “tão bons”. Muitas vezes, frameworks podem engessar o seu código, pois em alguns casos não provém flexibilidade em suas utilizações.

É preciso tomar muito cuidado ao implementar um framework externo ao seu código fonte. O ideal é saber trabalhar com o código do framework e não apenas suas funcionalidades. Assim, é possível evitar surpresas na implementação.

Para não deixar de citar alguns exemplos de frameworks famosos, segue uma pequena lista:

1. Java – Hibernate e Spring
2. Ruby – Ruby on Rails
3. JavaScript – AngularJS
4. Python – Django
5. PHP – Zend e Laravel
6. C# – ASP .NET
7. CSS – Bootstrap

# Conceito de Linguagem de Programação

**Linguagem de Programação** é uma linguagem escrita e formal que especifica um conjunto de instruções e regras usadas para gerar programas (software). Um software pode ser desenvolvido para rodar em um computador, dispositivo móvel ou em qualquer equipamento que permita sua execução. Existem várias linguagens e elas servem para muitos propósitos. Alguns óbvios, como criar um software, outros menos, como controlar um carro ou uma torradeira.

Um app que roda no seu celular é um tipo de software criado com uma linguagem de programação. Um game, que roda em um PC ou em outros equipamentos, também. Uma TV smart, que possui a funcionalidade de se conectar na internet e permitir ao consumidor usar um navegador, usa linguagens de programação tanto no hardware quanto no software.

Uma torradeira não tem uma interface digital de comunicação, mas possui um micro-controlador com um software que gerencia o equipamento. Esse tipo de software, embarcado em circuitos eletrônicos, é chamado de firmware e também é escrito usando uma linguagem de programação. A internet das coisas (IoT) demanda muitas soluções que usam esse tipo de tecnologia.

Programar, na prática, é escrever um texto que será transformado em um software. Esse texto deve ser escrito em uma linguagem de programação e é chamado de código, mas não é um código lido apenas por uma máquina, é um código que pode ser lido por um ser humano. Para quem sabe inglês é ainda mais legível, pois várias linguagens de programação usam palavras nesse idioma, como if, else, do, while, integer, etc. Quem escreve códigos em linguagens de programação é chamado de programador(a) ou desenvolvedor(a).

**__Resumindo…__**

**Biblioteca:** é uma coleção de implementações de comportamentos escritos em uma linguagem e importadas no seu código. Nesse caso, há uma interface bem definida para cada comportamento invocado. Um bom exemplo é a biblioteca jQuery que implementa certos comportamentos, como por exemplo, a manipulação do HTML.

**Framework:** estrutura real, ou conceitual, que visa servir como suporte (ou guia) para a construção de algo (um produto, por exemplo). “Este algo” herdará as características desta estrutura, implementando o produto final (“algo”).

**Linguaguem de Programação:** conjunto de comandos, funções, protocolos e objetos em que programadores podem interagir com sistemas externos. Dessa forma, possibilitando a utilização de comandos padrões para agilizar operações comuns entre sistemas, de tal forma que desenvolvedores não precisarão escrever o código do zero. Imagine que você precisa implementar um módulo de mapas em sua aplicação, isso seria trabalhoso começado do zero, certo? Porque não usar algo já existente? O Google Maps através de sua API, por exemplo.
Como aplicar essas tecnologias?

**Para integrar esse conjunto de funcionalidades no seu desenvolvimento**, o ideal é começar os estudos com tecnologias mais acessíveis para facilitar o entendimento de outras mais complexas em seguida. Por exemplo, aprender linguagens como Python e Ruby será excelente nesse momento inicial.

Após isso, aos poucos você começará a compreender o funcionamento das bibliotecas em cada tipo de linguagem, saberá como importá-las e poderá, inclusive, dar início às suas próprias bibliotecas.

O próximo passo é entender como funcionam as APIs. Nesse caso, com um curso de RESTful APIs, você estará preparado para implementar APIs externas em seu desenvolvimento e até mesmo criar APIs hospedadas em serviços na nuvem. Assim, você ou outros desenvolvedores poderão utilizar a API em seus softwares via web.
Pratique!

Por último, com conhecimentos consolidados em APIs, chegará o momento de testar ou desenvolver frameworks para suas aplicações. Caso você escolha testar uma aplicação que já exista, lembre-se sempre de que é preciso conhecer o código desses frameworks a fundo, pois possivelmente você precisará fazer modificações e terá que flexibilizar o código para a sua aplicação.

É claro que não existe uma regra! Alguns frameworks são muito bons e flexíveis, permitindo sua utilização logo no começo do aprendizado. Então a dica principal é: utilize qualquer aplicação que você tenha conhecimento do que ela realmente faz! Assim, serão menores as chances de ocorrerem problemas que você não saiba como resolver.