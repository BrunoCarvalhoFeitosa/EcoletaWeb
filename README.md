<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/BrunoCarvalhoFeitosa/EcoletaWeb">
    <img src="/web/src/assets/logo.svg" alt="Logo" />
  </a>

  <p align="center">
    Um app para cadastro de pontos de retirada de materiais recicláveis, saiba exatamente a localização dos locais aonde os materiais se encontram, facilitando a reciclagem e a sustentabilidade do mundo.
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Sumário</summary>
  <ol>
    <li>
      <a href="#sobre-o-projeto">Sobre o projeto</a>
      <ul>
        <li><a href="#feito-com">Feito com</a></li>
        <li><a href="#hospedagem">Hospedagem</a></li>
      </ul>
    </li>
    <li>
      <a href="#iniciando-o-projeto">Iniciando o projeto</a>
      <ul>
        <li><a href="#pré-requisitos">Pré-requisitos</a></li>
        <li><a href="#instalação">Instalação</a></li>
      </ul>
    </li>
    <li><a href="#uso">Uso</a></li>
    <li><a href="#license">Licenças</a></li>
    <li><a href="#contato">Contato</a></li>
    <li><a href="#reconhecimentos">Reconhecimentos</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## Sobre o projeto
Este app foi feito em React.js, Node.js e SQLite, seu intuíto é cadastrar pontos de coleta facilitando a reciclagem de resíduos, entre em contato com o proprietário do local e saiba onde existem pontos de retirada. 

### Home
Página que dará acesso ao sistema para cadastro de pontos de coleta.

![EcoletaHomeScreen](https://user-images.githubusercontent.com/46093815/133955767-c1e4e3a0-6c7a-4006-8340-fd227ce1a910.png)

### Cadastro de coletas
Página onde é possível preencher as informações e selecionar a exata localização (coordenadas) do ponto para retirada dos resíduos através do mapa gratuito React Leaflet.

![EcoletaRegisterPointScreen](https://user-images.githubusercontent.com/46093815/133956247-479046bf-8624-460c-a883-994cfc6caa79.png)


### Feito com

* [React.js](https://nextjs.org/)
* [Node.js](https://nodejs.org/en/)
* [SQLite](https://www.sqlite.org/index.html)

### Hospedagem

O app ainda não foi hospedado em nenhuma plataforma, porém você poderá cloná-lo. Basta acompoanhar o próximo tópico.


<!-- GETTING STARTED -->
## Iniciando o projeto

Primeiramente será necessário clonar este projeto em (https://github.com/BrunoCarvalhoFeitosa/EcoletaWeb.git), após o download será necessário abrir este projeto no seu
editor e no terminal digitar npm install ou yarn add dentro dos repositórios web e server, posteriormente dentro do diretório web basta executar npm run start ou yarn start e dentro do diretório server exucutar npm run dev ou yarn dev. 

### Pré-requisitos

* npm
  ```sh
  npm install npm@latest -g
  ```

### Instalação

1. Clone o repositório
   ```sh
   git clone https://github.com/BrunoCarvalhoFeitosa/EcoletaWeb.git
   ```
2. Instale os pacotes NPM dentro do diretório web e server
   ```sh
   npm install ou yarn install
   ```
2. Execute o projeto web
   ```sh
   npm run start ou yarn start
   ```
2. Execute o server backend
   ```sh
   npm run dev ou yarn dev
   ```


<!-- USAGE EXAMPLES -->
## Uso

Cadastre pontos de coleta para materiais recicláveis, ajudando o mundo a ser mais sustentável.

<!-- LICENSE -->
## License

Distribuído sob a licença MIT.

<!-- CONTACT -->
## Contato

Bruno Carvalho Feitosa - [GitHub](https://github.com/BrunoCarvalhoFeitosa) - [LinkedIn](https://www.linkedin.com/in/bruno-carvalho-feitosa/)


<!-- ACKNOWLEDGEMENTS -->
## Reconhecimentos
* [Rocketseat](https://rocketseat.com.br/)
* [React Leaflet](https://react-leaflet.js.org/)
