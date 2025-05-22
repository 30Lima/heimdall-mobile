# HEIMDALL - Localização e Monitoramento de Motos no Pátio

## Integrantes

| Nome Completo               | RM       |
|-----------------------------|----------|
| Pedro Henrique Lima Santos  | 558243   |
| Vitor Gomes Martins         | 558244   |
| Leonardo Pimentel Santos    | 557541   |

## Descrição da Solução

O **HEIMDALL** é um aplicativo mobile desenvolvido em **React Native** com o objetivo de facilitar o processo de **localização e monitoramento de motocicletas dentro do pátio logístico da Mottu**. A proposta é que os gestores possam registrar zonas, vagas e motos, além de visualizar um mapa do pátio e acessar informações relevantes por meio de uma navegação intuitiva.

Este aplicativo simula a interface do sistema e oferece as seguintes funcionalidades:

- Tela de **Splash**, **Login** e **Cadastro**
- Navegação Drawer com páginas de **Home**, **Perfil** e **Sobre**
- Armazenamento local do nome de usuário usando `AsyncStorage`
- Design responsivo com foco em acessibilidade e boas práticas de UX

## Como Rodar o Projeto Localmente

### Pré-requisitos

- **Node.js** (versão recomendada: `18.x`)
- **Git**
- **Visual Studio Code** (ou outro editor de código de sua preferência)
- **Expo Go** instalado no celular

### Passo a passo

1. **Clone o repositório:**

- git clone https://github.com/30Lima/heimdall-mobile.git

2. **Acesse o diretório do projeto:**

- cd heimdall-mobile

3. **Instale as dependências:**

- npm install

4. **Instale as bibliotecas do projeto:**

- npx expo install @react-navigation/native
- npx expo install react-native-screens react-native-safe-area-context
- npx expo install react-native-gesture-handler react-native-reanimated
- npx expo install react-native-vector-icons
- npx expo install @react-navigation/native-stack
- npm install @expo/vector-icons
- npx expo install @react-native-picker/picker
- npm install @react-navigation/drawer
- npm install @react-native-async-storage/async-storage

5. **Inicie o servidor de desenvolvimento:**

- npx expo start

6. **Escaneie o QR code com o aplicativo Expo Go no seu celular para testar o app.**