## ANOTAÇÕES DE ESTUDO DO PROJETO IMHERE - ROCKET - IGNITE - REACT NATIVE

**INFORMAÇÕES PRELIMINARES**

[Instruções para editar README](https://raullesteves.medium.com/github-como-fazer-um-readme-md-bonit%C3%A3o-c85c8f154f8)

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

#### EXECUTANDO O PROJETO

*expo start*</br>
Aparece um QR code, apontando a câmera do telefone consegui abrir no expo go </br>
No momento aparece apenas uma tela em branco com a seguinte mensagem</br>
*Open up App.tsx to start working on your app!*</br>
É necessário que o telefone esteja conectado na mesma rede que o PC</br>

Para parar o servidor basta executar o comando *Ctrl+C*

#### FUNCIONAMENTO DO REACT NATIVE

A grande vantagem do React Native em relação aos ambientes tradicionais é que não é necessário desenvolver duas vezes para IOS / Android, o React Native é cross plataform com uma única base de código em Javascript.

#### ENTENDENDO O JSX

Os elementos precisam iniciar em letra maiúscula ```<Text></Text>```</br>
Para criar componentes, arquivo iniciando com letra maiúscula e extenção .tsx;</br>

#### ENTENDENDO A LOGBOX

Logbox Amarela - Erros que não quebram a aplicação mas devem ser tratados;
Logbox Vermelha - Erros que quebram a aplicação.

#### ESTILIZANDO ELEMENTOS (muito parecido com CSS)

```
<View style={{
    flex: 1,
    backgroundColor: '#131016'
}}>
    O conteúdo da view...
</View>
```





