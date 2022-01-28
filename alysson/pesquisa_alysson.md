# QUAL A DIFERENÇA ENTRE FRANMEWORK E BIBLIOTECA

## O que são bibliotecas?

Vamos imaginar que precisamos calcular quantos dias existem entre duas datas utilizando JavaScript. Mas no momento não há uma funcionalidade da linguagem que faça este cálculo para nós. Então teremos que criar uma função em que a gente passe duas datas e ela nos retornará a quantidade de dias.

E depois pode aparecer a necessidade de pegar uma data e adicionar um certo número de dias. Que data teremos como resultado? E se precisarmos adicionar horas ou minutos?

A príncipio podem parecer funções sem conexão, mas note que estamos falando de cálculos que nos remetem a tempo. Com o intuito de deixar o código mais organizado, podemos juntar estas funções em uma “coleção” de funções relacionadas ao cálculo de tempo.

Em conclusão, podemos dizer que uma biblioteca (do inglês library, não confundir com livraria que em inglês é book store) é uma coleção de códigos voltados a resolver um determinado tipo de problema.

## O que são Frameworks?

Um framework possui várias funcionalidades prontas, e normalmente já possuem um fluxo de trabalho ou estrutura a serem seguidos. É algo bem mais abstrato do que uma biblioteca. Isso realmente confunde muitas pessoas. Por exemplo, o jQuery se autodenominava um framework, mas já faz um bom tempo que ele se chama de biblioteca.

O foco dos frameworks é mais amplo que das bibliotecas. Aliás, um framework pode ser feito a partir de uma coleção de padrões, APIs e até mesmo de bibliotecas.

Só para exemplificar, o Angular, framework JavaScript para desenvolvimento de aplicações, é feito a partir de bibliotecas de animação, requisições http, internacionalização, testes, tratamento de dados em formulários, reatividade, roteamento, etc.

## Mas então, qual a diferença entre Framework e Biblioteca?

Por mais que a gente tenha visto características de framework e biblioteca, ainda assim há confusão, pois nem sempre as funções do software deixa claro a sua natureza. É provável até que não seja nenhum dos dois. Bem como também é comum ver lugares chamando Angular de biblioteca e React de framework, sendo que na verdade é ao contrário.

Antes de tudo, algo que podemos notar além das diferenças já mostradas aqui é que normalmente as bibliotecas são usadas pelos nossos códigos, enquanto os frameworks é quem costumam utilizar os nossos códigos.

Por isso podemos diferenciar React de Angular. Se acaso você já usou os dois verá as seguintes diferenças:

No React nós temos basicamente funções para a criação de componentes e criação de estados. Estamos no controle o tempo todo, nós chamamos as funções do React, podemos decidir qual será a estrutura da nossa aplicação e o fluxo com o qual ela funciona. Se acaso a gente precisar de funcionalidades de roteamento, animações, internacionalização, etc, precisaremos buscar bibliotecas para isso.

Em contrapartida no Angular todas essas funcionalidades já vêm inclusas. Há uma estrutura que devemos seguir (componentes, serviços, pipes, rotas, módulos), e o Angular é quem vai chamar o nosso código seguindo seu próprio fluxo. Essa característica de já ter uma estrutura é o principal diferencial entre um framework e uma biblioteca. Você pode notar que em nenhum momento nós chamamos alguma função como Angular.nomeFuncao(). Eventualmente, caso queira fazer algo num fluxo ou estrutura diferente, o Angular não vai entender e você terá um erro.

## Qual o melhor? Framework ou Biblioteca?

Podemos concluir que enquanto na biblioteca nós mesmos criamos a base e o fluxo, no framework já temos toda a estrutura pronta para utilizarmos e seguirmos. Mas isso não significa necessariamente que um é melhor do que o outro. São ferramentas diferentes para propósitos diferentes.

Ao passo que no Angular nós já temos toda a estrutura pronta, nos poupando desse trabalho, teremos menos liberdade para certas escolhas. Em contrapartida, no React temos que definir coisas comuns como arquitetura e fluxo, mas teremos mais liberdade de escolher cada biblioteca responsável por cada funcionalidade em nossa aplicação.






