# Calculadora de ROI (Return on Investment)

A ideia da aplicação é calcular o ROI e comparar com o de clientes do **olist** da mesma categoria, para que o lead veja a vantagem de anunciar conosco

 Anexo ao app [Olist Store](https://app.olist.com/)
>*Repositório do projeto principal [aqui](https://github.com/olist/mobile-app)*

------------
### Figma

[Prototipos das telas](https://www.figma.com/proto/jXGfMRoyTOH5fJRu37KPtE/Untitled?node-id=7%3A7&scaling=scale-down "Link do Figma com os prototipos de tela")
>Navegar pelas telas clicando nos botões para entender o fluxo

------------
### Pré requisitos
- NPM
- Yarn (optional)
- Cocoa Pods
- React Native Cli
- Android Studio
- XCode

------------
### Instalações
- Gerenciador de pacotes para Javascript -> Yarn
1. para instalar: 
```shell
yarn install
```
2. em seguida, entre em sua pasta ios e execute o comando abaixo para instalar todas as dependências do projeto:
```shell
 pod install
```
3. para executar o projeto em um dispositivo android: 
>*o emulador ou dispositivo deve ser aberto / conectado antes de executar o comando*
```shell
  yarn run android
  ```
4. para executar o projeto em um dispositivo IOS: 
>*não é necessário ter o emulador ou dispositivo aberto / conectado*
```shell
yarn run ios
```

### Comunicação com backend
A integração é feita via requisições HTTP, com o uso da biblioteca [Axios](https://www.npmjs.com/package/react-native-axios)
>*[Aqui](https://github.com/olist/shops-app/blob/master/src/services/api.ts) tem um exemplo de implementação do consumo de API*

