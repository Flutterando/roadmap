# Flutter Roadmap 2025

O objetivo desse repositório é catalogar os conteúdos existentes na internet sobre Flutter e concatenar em uma espécie de roadmap para auxiliar os iniciantes.

# Começando a escrever códigos

É recomendado assistir [ESTE VÍDEO](https://www.youtube.com/watch?v=BTENKdRVS2U) antes de iniciar.

## Lógica de Programação

Precisamos entender como criar algorítmos, por tanto, antes de realmente colocar a mão no código, é importante estudar um pouco sobre lógica de programação.

Nessa etapa não é necessário saber nenhuma linguagem.

- [Curso de lógica de programação](https://www.youtube.com/watch?v=8mei6uVttho&list=PLHz_AreHm4dmSj0MHol_aoNYCSGFqvfXV);
- [Curso Lógica de Programação Completo 2021](https://www.youtube.com/watch?v=iF2MdbrTiBM).


## O Dart

Após entender mais sobre Lógica de Programação, devemos focar na linguagem principal do Flutter, o Dart.

Assista primeiro:
- [Dart (a linguagem do Flutter)](https://www.youtube.com/watch?v=i7IzlVImHEc)
- [Por que o Flutter usa o Dart (Ative as legendas)](https://www.youtube.com/watch?v=5F-6n_2XWR8)

É importante ressaltar que o Dart sofreu mudanças consideráveis na segunda metade de 2021, por tanto, não é recomendado para iniciantes os cursos gravados antes de julho de 2021.

Não pule essa etapa, pois conhecer a base do Dart será o principal diferencial para desenvolver em Flutter.

**DOCUMENTAÇÃO**:

- [Dart doc](https://dart.dev/guides/language/language-tour)

**CURSOS GRATUITOS**:

- [Curso de Dart (Deivid Willyan)](https://www.youtube.com/watch?v=PgRv_aeqf-4&list=PLRpTFz5_57cseSiszvssXO7HKVzOsrI77)

**CURSOS PAGOS**:

- [Lógica de programação com Dart (Flutterando Masterclass)](https://masterclass.flutterando.com.br/public/products/e141c9c5-0b60-4e0e-96f1-e31d433e2a09)


## Orientação a Objetos (POO)

Esse é o paradigma mais utilizado no Flutter. Por isso devemos conhecer o básico para iniciar nesse framework.

Não tenha medo de aprender 2 ou 3 linguagens a mais para dominar esse paradigma.

É recomendado (~e não obrigatório~) aprender um pouco sobre o Java, pois é uma linguagem que utiliza exclusivamente a POO, forçando-o a entender toda a base desse paradgma. 

- [Programação Orientada a Objetos (POO)](https://www.youtube.com/watch?v=QY0Kdg83orY)
- [Curso de programação oriendada a objetos](https://www.youtube.com/watch?v=KlIL63MeyMY&list=PLHz_AreHm4dkqe2aR0tQK74m8SFe-aGsY)
- [Classes abstratas no FLUTTER](https://youtu.be/nZov6ztrocc)


# Flutter

Após seguir os passos da sessão anterior, chegou a hora de usar as ferramentas do SDK. Se não conhece o Flutter, assista [ESTE VÍDEO](https://www.youtube.com/watch?v=vIP2iLFjEIk&t=66s).

EXPLORE o catálogo de widgets; será muito importante conhecer suas principais ferramentas:
- [Catálogo de Widgets](https://docs.flutter.dev/reference/widgets)

**DOCUMENTAÇÃO**:

- [Flutter doc](https://docs.flutter.dev/get-started/learn-flutter)

## Cursos gratuitos

- [Flutter Curso 2022 (Flutterando)](https://www.youtube.com/playlist?list=PLlBnICoI-g-fuy5jZiCufhFip1BlBswI7)

## Cursos pagos

- [Masterclass Iniciante (Flutterando)](https://masterclass.flutterando.com.br/public/products)
  > ficar atento ao canal do Youtube para ver o anuncio de vagas
- [Curso de Flutter (COD3R)](https://www.udemy.com/course/curso-flutter/)
- [Curso de Flutter em Inglês (Angela)](https://www.udemy.com/course/flutter-bootcamp-with-dart/)


## Widgets nativos

Tudo no Flutter é Widget.

A tela de um aplicativo Flutter é constituida pela união de outros widgets nativos.

- Domine os principais widgets de alinhamento: **(Column, Row, Stack)**.
- Entenda o funcionamento do **Container**.
- Teste todos os widgets disponíveis [NESSE CATÁLOGO](https://docs.flutter.dev/reference/widgets).


## Criação de widgets

Existem três formas básicas de criar widgets customizados, o StatelessWidget, StatefulWidget e InheritedWidget. A diferênça entre os três deve ser entendida desde o início.




## Componentização de widget

Após aprender a criar widgets customizados, o desenvolvedor deve aprender a dividir esses widgets em arquivos separados para que possa facilitar a compreenção de outras pessoas que estarão lendo o código posteriomente (inclusive ele próprio.

Algumas dicas:
- Tente ter um arquivo por Widget.
- Reflita o nome do Widget no nome do arquivo, Ex:
  - Tela inicial = home_page.dart
  - Botao de adicionar tarefa = add_task_button.dart


## Formulários

"TUDO é CRUD."

Parte da nossa tarefa no front-end é receber dados e enviá-los para a API.

- [AULÃO: Criação de formulários](https://www.youtube.com/watch?v=5SIw8bXiP7o)
- [Tudo sobre Máscaras](https://www.youtube.com/watch?v=sjQLmibDEu4)


## Consumo de APIs

Consumir informações do mundo externo.
Para montar sua Pokédex, resgatar os dados de um cep...

- [AULÃO: Consumo de APIs (Flutterando)](https://www.youtube.com/watch?v=PUQEd7xRldM)


## Aprenda a fazer animações

Para encantar os clientes! (Principalmente seu chefe)

- [Tudo sobre animações no Flutter](https://www.youtube.com/watch?v=XM-8UTkFr4c&t=3108s)


## Domine o Provider

O Provider é a recomendação da equipe do Flutter para quem está iniciando no mundo Flutter para gerenciar estados e injeção de dependência.

- [AULÃO sobre o Provider(Flutterando)](https://www.youtube.com/watch?v=VhsqMahAmOk)
- [Provider em 10 minutos (Renato Mota)](https://www.youtube.com/watch?v=Gm8QuYvOTwE)
- [Como utilizar o Provider e o ChangeNotifier(Prof. Diego Antunes)](https://www.youtube.com/watch?v=xDdAXmAUt6c)
- [Flutter Provider for Beginners (Inglês)](https://www.youtube.com/watch?v=P47JJU6dlcA)


## Aprenda alguns Design Patterns

Padrões de projetos são importantes para manter a qualidade do código além de facilitar o trabalho em equipe.

- [Repository Pattern no Flutter (balta.io)](https://www.youtube.com/watch?v=Q05t3mgaMfk)
- [CopyWith (Jacob)](https://blog.flutterando.com.br/o-padr%C3%A3o-copywith-no-flutter-dart-267e3d218ffc)
- [Injeção de dependências (Flutterando)](https://www.youtube.com/watch?v=KpPnDHpgHnA&t=60s)
- [MVC, MVP e MVVM no Flutter (Flutterando)](https://www.youtube.com/watch?v=WgadnZcujuc)
- [Factory(Felipe Deschamps)](https://www.youtube.com/watch?v=arAz2Ff8s88&ab_channel=FilipeDeschamps)

## Testes de unidade

Para garantir a qualidade do software e facilitar a manutenção os testes de unidade serão seus maiores aliados.

- [Um programador confiável (Elemar Jr)](https://www.youtube.com/watch?v=XSdT2myLlw4)
- [AULÃO sobre testes de unidade (Flutterando)](https://www.youtube.com/watch?v=BLHPRg8ickY)
- [Semana do Flutter sobre testes (Flutterando)](https://www.youtube.com/playlist?list=PLlBnICoI-g-etEtbvgDnO40SYKOSktCj4)
- [Curso Pago de testes de unidade (Flutterando)](https://masterclass.flutterando.com.br/public/products/94222fd5-92e5-4890-8e87-455ef4346858)

## Gerência de estado

O StatefulWidget concede ao widget a possibilidade de gerenciar o próprio estado, mas às vezes é necessário mudar o estado de vários widgets em uma ação. Para isso, existem alguns padrões que podemos utilizar para facilitar a execução e o entendimento.

- [BASE DA GERENCIA DE ESTADO (Flutterando)](https://www.youtube.com/watch?v=XGjCatQadrk&ab_channel=JacobMouradaFlutterando)
- [AULÃO sobre gerência de estado (Flutterando)](https://www.youtube.com/watch?v=_F0GI2dnt-g)
- [ValueNotifier. A reatividade mais rápida do Flutter](https://www.youtube.com/watch?v=S1PgnMqVgsM)
- [Curso de gerência de estado com ValueNotifier (Flutterando)](https://www.youtube.com/playlist?list=PLlBnICoI-g-eG0eVkHu2IaO48TljxPjPq)
- [AULÃO sobre BLoC (Flutterando)](https://www.youtube.com/watch?v=UB28e59GmK8)
- [AULÃO sobre MobX (Flutterando)](https://www.youtube.com/watch?v=Z6U6L9e8gmE)
- [AULÃO sobre Triple (Flutterando)](https://www.youtube.com/watch?v=CS97q2PwjSo)


## Aprenda GIT.

Git é essencial para um desenvolvedor. Atualmente, é o meio universal para compartilhamento de código.

- [Git para desenvolvedores Flutter](https://www.youtube.com/watch?v=Kx3M6XUpcFE)


## Gerenciadores de versão

Principais (~e únicos~) gerenciadores de versão do Flutter

- [Link do Puro](https://puro.dev/) | [Video Explicativo](https://www.youtube.com/watch?v=ImCGQM6jhic&t=181s&ab_channel=JacobMouradaFlutterando)
- [Link do FVM](https://fvm.app/) | [Video Explicativo](https://www.youtube.com/watch?v=9n5dLXJMSqU&ab_channel=JacobMouradaFlutterando)

- Qual é melhor? 

Atualmente, o approach do Puro com sua configuração de ambientes tem agradado mais à comunidade. Sua instalação acaba sendo mais simples também.


## Se você chegou até aqui, já tem os conhecimentos necessários para construir seus apps, mas agora veremos para onde se aprofundar:

## Arquitetura

A arquitetura de um projeto define sua vida útil. Todo App tem alguma arquitetura, mesmo que o desenvolvedor não tenha pensado nisso.

1. **App Architecture (Recomendada)**
- [Documentação da arquitetura recomendada](https://docs.flutter.dev/app-architecture)
- [Finalmente o Flutter recomendou uma Arquitetura! É oficial!](https://www.youtube.com/watch?v=_pPUqNXudXg)
- [MVVM, Result e Command. Descubra os Design da Nova ARQUITETURA do Flutter](https://www.youtube.com/watch?v=uFOTMiU82vs)
- [Flutter recomenda o uso de “Optimistic State”](https://www.youtube.com/watch?v=49LD384mlS0)
- [O Design Pattern que irá mudar na nova arquitetura do Flutter](https://youtu.be/gzmmK4dfE_g)
- [Deixando o Flutter mais intuitivo com o result_dart](https://youtu.be/5kJog_PhGbY)
- [Implementando a NOVA Arquitetura recomendada do Flutter AO VIVO]()


2. **Conteúdos sobre Clean Architecture:**

- [AULÃO sobre Clean Architecture (Flutterando)](https://www.youtube.com/watch?v=fABLC2fxQwg)
- [Playlist sobre Clean Dart (Flutterando)](https://www.youtube.com/playlist?list=PLlBnICoI-g-d-v_fWlkZX2HRgHHPnJx9s)
- [Masterclass Intermediária (Flutterando)](https://masterclass.flutterando.com.br/public/products)
  > ficar atento ao canal do Youtube para ver o anuncio de vagas


Criadores de conteúdo relevante que estão sempre colaborando ou já tem um acervo de qualidade:

- [Jacob Moura da Flutterando](https://www.youtube.com/@JacobMoura7)
- [Prof. Diego Antunes](https://www.youtube.com/@drantunes)
- [Paulo Mendes](https://www.youtube.com/@paulomendesdev)
- [Flutter Mapp](https://www.youtube.com/@FlutterMapp/videos)
- [Flutter Official](https://www.youtube.com/@flutterdev)

Links gerais da comunidade:

- [Youtube](https://www.youtube.com/@FlutterandoTV)
- [Discord](https://discord.flutterando.com.br)
- [Site Oficial](https://flutterando.com.br)

Sugestões de Livros. (Leia para aprender, nunca levando tudo como regra e sim absorvendo as partes que lhe fizerem sentido)

- Clean Code
  
![image](https://github.com/thKali/roadmap_fork/assets/100535432/48bd94af-05dd-4148-8a2f-41384146e368)

- Clean Arch

![image](https://github.com/thKali/roadmap_fork/assets/100535432/286b11ae-89e0-4ace-bfe1-fec626bf02fa)

- Padrões de Projeto

![image](https://github.com/thKali/roadmap_fork/assets/100535432/45e1bfcc-090a-41b2-8cf5-d434ec7a4e86)

- Refatoração

![image](https://github.com/thKali/roadmap_fork/assets/100535432/438a86c8-e526-443c-a8c7-66e78109b83f)

- Flutter in Action
  
![image](https://github.com/user-attachments/assets/88b757f5-2d3e-4ed0-bb28-9b160b8feef6)

- Flutter Complete Reference

![image](https://github.com/user-attachments/assets/6590e38f-4bc1-4dee-a233-6a2e08b86692)

