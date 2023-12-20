NewsLetterFeedApp foi construído seguindo as orientações previstas neste Readme. O app exibe um feed contendo uma lista de notícias, distribuídas em duas abas principais (Home e Agro).

Dos requisitos apontados, a paginação do Feed se mostrou desafiador no contexto de swiftUI, não tendo sido possível sua implementação na estimativa de entrega inicial. 

## Decisões e porquês

### Cache de dados

A aplicação conta com cache dos dados para tornar a experiência do usuário mais fluida.

### User Interface Tool kit

Como framework de layout, optou-se por se utilizar nesse projeto SwiftUI. A sua utilização garantiu um código mais limpo, mais rapidez e fluidez na criação de layouts e manipulação de dados. Além disso, a componentização da aplicação se tornou muito mais simples de ser realizada, com código mais limpo e sintaxe simplificada. Isso tudo contribui com a manutenabilidade e testabilidade da aplicação construída. 

### Arquitetura

Arquitetura permanece um tópico de discussões nas comunidades de swift. Muitos desenvolvedores utilizam MVVM em seus projetos de SwiftUI, o que parece ser uma boa ideia. No entanto, varios artigos apontam como o modelo arquitetural MV pode contribuir com a produtividade, legilibidade, manutenibilidade e testabilidade de projetos utilizando SwiftUI. Desta maneira, e , considerando a simplicidade do projeto apresentado, optou-se por seguir com a arquitetura MV. 

### Componentização

Visando a criação de uma aplicação escalável, optou-se por componentizar o máximo de views que fosse possível, tornando o código menos repetitivo.

### Bibliotecas

* SDWebImageSwiftUI: algumas materias possuiam 'gif's', a utilização de SDWebImage permitiu lidar com esses formatos e realizar sua renderização de maneira simples. Além disso, simplificou a forma de lidar com as imagens no geral.

* iOSSnapShotTestCase: lib de fácil criação de testes de snapShots. Infelizmente, não houve tempo hábil para a implementação dos testes.
