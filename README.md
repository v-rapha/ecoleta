<h3 align="center">
    <img alt="Logo" title="#logo" width="300px" src=".github/logo.png">
</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/vinicius-raphael/">
    <img alt="Made by v-rapha" src="https://img.shields.io/badge/made%20by-Vinicius%20Raphael-brightgreen" />
  </a>
    
  <a href="https://github.com/v-rapha/ecoleta/blob/master/LICENSE">
    <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen" />
  </a>
</p>

## Sobre
O <strong>Ecoleta</strong> serve como um marketplace, uma conexão entre entidades que coletam resísuos orgânicos e inorgânicos a pessoas que necessitam descartar esses resíduos.

Essa aplicação foi construída na <strong>Next Level Week</strong> distribuída pela <a href="https://rocketseat.com.br">Rocketseat</a>. A ideia veio para reforçar a <strong>semana do meio ambiente</strong>.

## Tecnologias utilizadas
- [TypeScript](https://www.typescriptlang.org)
- [Node.js](https://nodejs.org/en/)
- [React](https://reactjs.org)
- [React Native](https://reactnative.dev)

## Como usar
- Para rodar a aplicação você precisará ter instalado na sua máquina o [Node.js](https://nodejs.org/en/), [NPM](https://www.npmjs.com/) ou [YARN](https://yarnpkg.com/) também o [Expo](https://expo.io/).
- Caso for rodar a aplicação mobile no dispositivo fisico, você irá precisar ter instalado o aplicativo do [Expo](https://play.google.com/store/apps/details?id=host.exp.exponent&hl=pt).

### 1º -  Clone o repositório:
```bash
$ git clone https://github.com/v-rapha/ecoleta.git
```
### 2º - Instale as dependências usando NPM ou YARN e inicie
- ### Iniciando o server
```bash
# Entre no arquivo server
$ cd ecoleta/server

# Instale as dependências
$ npm install

# Rode as migrations
$ npm run knex:migrate

# Rode as seeds
$ npm run knex:seed

# Inicie o server
$ npm run dev

# Nos arquivos ItemsController.ts e PointsController.ts, trocar a image_url pelo seu endereço IP
```

- ### Iniciando a aplicação web
```bash
# Entre no arquivo web
$ cd ecoleta/web

# Instale as dependências
$ npm install

# Inicie a aplicação
$ npm start
```

- ### Iniciando a aplicação mobile
```bash
# Entre no arquivo mobile
$ cd ecoleta/mobile

# Instale as dependências
$ npm install

# Inicie a aplicação
$ npm start

# O Expo irá abrir no terminal e/ou no navegador.
# Você precisa apenas escanear o QRcode com seu dispositivo fisico ou rodar a aplicação no seu emulador

# No arquivo api.ts, troque a baseURL pelo seu endereço IP

# Se ocorrer algum problema com as fontes, execute
$ expo install expo-font @expo-google-fonts/ubuntu @expo-google-fonts/roboto
```

## Como contribuir

- Faça um fork desse repositório
- Crie uma branch com a sua feature: `git checkout -b my-feature`
- Commit suas mudanças: `git commit -m 'feat: My new feature'`
- Faça um push para sua branch: `git push origin my-feature`


## Quem ministrou
As aulas foram ministradas pelo mestre <a href="https://github.com/diego3g">Diego Fernandes</a> nas aulas da <strong>Next Level Week</strong>.

## Licença
Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---
    
Feito com ♥ by [Vinicius Raphael](https://www.linkedin.com/in/vinicius-raphael/)
