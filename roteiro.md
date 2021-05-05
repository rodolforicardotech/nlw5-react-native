Anotações dos estudos:



#### Instalar o Node

*baixar do site*

#### Instalar o Expo

`*npm install --global expo-cli*`

**OBS:** npm é relacionado ao Node!

### Iniciar o Expo na pasta (eu criei uma pasta no togit para o projeto = nlw5-react-native)

*No expo -> blank (Typescript)*

(RELAXA! Demora!)



Entre na pasta criada (plantmanager)

e digite

 `code .`

ISSO ABRIRÁ O VS CODE

INICIANDO O PROJETO PELO TERMINAL:

expo start

Ao iniciar, ele dá várias opções: abrir no android, no ios, no browser, etc.

Dica de instalar no celular (o meu do android estava desatualizado! atenção nisso!)

(é preciso estar na mesma rede, tanto no computador como no celular para tudo funcionar direitinho. A primeira vez demora bastante para ficar tudo pronto.)





APP.TSX

É o que está sendo exibido na tela

importa o React de 'react'

depois exporta uma função padrão

adiciona o text

adiciona o view

adiciona o estilo na view

exporta também o stylesheet para criar um objeto lá no final para o código não ficar tão poluído

(pesquisar sobre as diferenças entre justifycontent e alignitens)





OBS: o react tem que retornar somente UM elemento. Então, as "coisas"tem que ficar dentro de algum elemento. Existe um artifício chamado FRAGMENT <> </>. Ele empacota tudo e mostra como se fosse uma coisa só. POrém, não é algo muito visto no mobile.



Mudar os itens da pasta assets.

Criamos uma nova pasta src -> pages -> Welcome.tsx

No app.tsw TEM QUE SER O EXPORT DEFAULT para que o React entenda o que ele precisa mostrar.

pasta assets na src

arquivo custom.d.ts -> para agilizar as imagens que estarão na página



Com um componente eu posso reaproveitar os atributos e propriedades várias vezes.

Ele deu um exemplo de reaproveitamento de botão. Adicionou somente a propriedade title para alterar o texto do botão.



É possóvel extender as propriedades.















