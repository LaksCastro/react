#  Uma breve jornada em rumo à base do Desenvolvimento Web com React Js

## Sobre o que é este artigo?
Estou escrevendo este README.md somente para compartilhar minha experiência atual com Desenvolvimento Web, e lembrando **eu não sou nenhum Dev Pleno ou Senior** encare este arquivo como um bate-bapo entre amigos, em que eu respondo sua pergunta: *Qual sua experiência e como está sendo sua jornada de programador desde que você iniciou?* (Leia com uma voz menos formal xD). E principalmente: sinta-se livre para enviar-me uma crítica, mensagem, email, sobre qualquer coisa que eu escrever e que você não concorde (Eu até agradeço se quiser compartilhar sua perspectiva sobre o assunto :D, afinal, não sou nenhuma fonte da verdade).

## Stack utilizada
Daqui para baixo vamos falar da Stack React Js, que inclui React Js (não me diga :O), Node Js, utilizando API Rest ou Firebase no Backend e outras subtecnologias que vamos citar mais a frente. (React Native não está incluido por que ainda não tive experiência sobre o mesmo).

## Tipos de aplicações
Na Web existem diferentes tipos e formatos de sites, dentre eles podemos destacar: (O tipo, e em seguida um exemplo) Ps: uma dica pra diferenciar com mais facilidade: Sites **estáticos**: Sites que **independente** do usuário, o conteúdo **não vai mudar**, já os **dinâmicos** é o contrário, **de acordo com o usuário, o conteúdo do site irá mudar**
- Blogs (Sites estáticos),
	- [Blog do Willian Justen](https://willianjusten.com.br/ "Blog do Willian Justen")
- Serviços (Sites dinâmicos)
	- [O próprio GitHub](http://github.com "O próprio GitHub")
	- [A plataforma da Netflix](https://www.netflix.com/br/ "A plataforma da Netflix")
	- [O Twitter](http://twitter.com "O Twitter")
- Sites institucionais (Sites estáticos)
	- [Single page do freelancer Jack](https://jacekjeznach.com/ "Single page do freelancer Jack")
	- Também poderia ser uma single page de uma instituição

Porém, foquei somente em **sites que oferecem algum tipo de serviço dinâmico.**

## Lista das tecnologias
1. **JavaScript**
	1. **Módulos (Sim, `require / module.exports` ou `import / export`)**
	2. **Manipulação de Arrays (Funções super utilizadas)**
		1. map
		2. filter
		3. reducer
		4. forEach
	3. **Fetch (Requisições à API)**
2. **Git**
	1. [Aqui está boa parte do conhecimento de Git que tenho](https://www.youtube.com/watch?v=MW7hrQe6aYo "Todo o conhecimento de Git necessário")
1. **React Js**
	1. **Estilização e pacote de ícones**
		1. [Styled Components](https://www.styled-components.com/ "Styled Components")
		2. [Styled Icons](https://styled-icons.js.org/ "Styled Icons")
	1. **React Hooks**
		1. useState
		2. useEffect
		3. useRef
	2. **React Redux**
		1. Reducer
		2. Actions
		3. Dispatch
		4. Ducks Pattern (Padrão da estrutura e de código)
		5. useDispatch
		6. useSelector
	3. **Firebase**
		1. Configuração do projeto
		2. Firebase Auth
		3. Firebase Storage
		4. Firebase Firestore
		5. Firebase Functions
	4. **Redux Saga**
		1. [De Redux Saga eu só sei o básico, e esse básico pode ser encontrado aqui](https://www.youtube.com/watch?v=qU9DesjDJic "De Redux Saga eu só sei o básico, e esse básico pode ser encontrado aqui")
3. **Netlify**
	1. [Plataforma](http://netlify.com "Plataforma") onde hospedo minhas aplicações React. [Como hospedar lá?](https://www.freecodecamp.org/news/how-to-deploy-a-react-application-to-netlify-363b8a98a985/ "Como hospedar lá?")
4. **Variáveis de Ambiente**
	1. Na primeira vez que fui utilizá-las com React perdi 12h por que não sabia que não precisava instalar nenhuma biblioteca adicional e nem que devia começar o nome das variáveis com `REACT_APP`
	2. O principal que sei sobre como utilizá-las fora do React Js está [aqui](https://blog.rocketseat.com.br/variaveis-ambiente-nodejs/ "aqui")
3. **Node**
    1. Iniciando
        1. Rotas
        2. Requisições
        3. Middlewares
        4. Entender esse fluxo de funcionamento BackEnd (Requisição, resposta)
        4. Começando com o Framework Express
    2. Primeiro Banco de Dados
        1. Banco de dados não relacional MongoDB (MongoDB Atlas o nome do serviço pra usar como um banco de dados remoto e conectar ao Node Js)
    7. Modelo MVC, porém apenas com o MC (Model e Controller), a View fica por parte do React
    8. Tratativa de arquivos no Node Js
        1. Biblioteca **Multer** para tratativa de arquivos (Imagens, Vídeos, etc...) A Rocketseat fez [uma série](https://www.youtube.com/watch?v=MkkbUfcZUZM "uma série") usando essa biblioteca.
    6. API Rest, [esse vídeo](https://www.youtube.com/watch?v=MkkbUfcZUZM "esse vídeo") explica muito bem na teoria.
    7. Nota: Tudo isso é ensinado na semana omnistack, exceto pela biblioteca Multer (Pelo menos não na Omnistack 8 e 9)

## Uma breve explicação do Backend das minhas aplicações
Durante minhas aplicações, eu não costumo misturar Node Js com Firebase, afinal, o Firebase já oferece uma série de serviços para serem consumidos, portanto não faz sentido utilizar o Node e Firebase na mesma aplicação, como diz  [este post](https://blog.rocketseat.com.br/firebase/ "este post") da Rocketseat.

## Inciando


