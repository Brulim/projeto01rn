## ANOTAÇÕES DE ESTUDO DO PROJETO IMHERE - ROCKET - IGNITE - REACT NATIVE

**INFORMAÇÕES PRELIMINARES**

[InstruçõesParaEditarREADME](https://raullesteves.medium.com/github-como-fazer-um-readme-md-bonit%C3%A3o-c85c8f154f8)

### 01 - O QUE É EXPO

**Configurando o ambiente de desenvolvimento:**

Entendendo diferença entre CLI e Expo

[Documentação React Native](https://reactnative.dev/docs/environment-setup)

O CLI não consegue emular IOS no windows, mas isso pode ser feito com Expo para emular direto em um aparelho iphone.
É muito mais fácil criar o ambiente de desenvolvimento com Expo.

**Managed workflow x Bare Workflow**

Managed workflow:
Não tem acesso ao código nativo, o Expo cuida pra você.

Bare Workflow:
Dependendo da biblioteca utilizada é possível ter que acessar o código nativo, é nesse caso que entra o Bare, podendo rodar o projeto dentro e fora do Expo Go. Nesse caso o CLI também precisa estar configurado na máquina.

[Documentação do expo:](https://docs.expo.dev/versions/latest/)
Acima as bibliotecas disponíveis para o expo pelo *- expo install*


### 02 - FUNDAMENTOS

[Passo-a-passo da rocket para configurar o ambiente de desenvolvimento:](https://react-native.rocketseat.dev/)

Recebi alguns avisos da minha versão do node ser superior ao que o expo está preparado mas foi instalado.

**Expo com NPX**

[Quickstart expo](https://docs.expo.dev/)

Realizar o seguinte comando pelo powershell na pasta do projeto:

*npx create-expo-app my-app*


**expo start**</br>
Esse comando executado no powershell roda o qrcode para abrir o app no celular.</br>
Deu um erro de autorização para rodar o script, antes tive que executar o seguinte comando:</br>
*Set-ExecutionPolicy AllSigned*</br>

**npx expo start**
(o npx independe de ter instalado o expo na máquina - busca o expo mais atualizado)


#### CRIANDO UM NOVO PROJETO

Nessa etapa não fiz como o exemplo da aula, criei com *npx create-expo-app imhere*, imaginei que essa fosse a forma mais atual para criar o projeto.

Na aula seguinte reparei que da forma que fiz não foi gerado o arquivo do typescript, vou refazer conforme o vídeo.



