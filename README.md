# Aplicativo de Gestão de Uso de Veículos 🚗

![Imagem do Figma](url-da-sua-imagem-ou-logo.jpg)

Este é um aplicativo desenvolvido em React Native que oferece recursos para **registrar e gerenciar a utilização de veículos em empresas**. O aplicativo permite que os colaboradores registrem o uso de veículos da empresa, além de fornecer recursos de autenticação e integração com APIs de mapas e bancos de dados.

## Conteúdo

- [Instalação](#instalação)
- [Configuração](#configuração)
- [Funcionalidades](#funcionalidades)
- [Documentação](#documentação)
- [Bibliotecas e Tecnologias Utilizadas](#bibliotecas-e-tecnologias-utilizadas)
- [Licença](#licença)

## Instalação 🛠️

Antes de começar, certifique-se de ter o ambiente de desenvolvimento React Native configurado em sua máquina. Você pode seguir as [instruções de instalação](https://reactnative.dev/docs/environment-setup) na documentação oficial do React Native.

1. **Clone este repositório:**

   ```
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   ```

2. **Navegue até o diretório do projeto:**

   ```
   cd nome-do-repositorio
   ```

3. **Instale as dependências do projeto:**

   ```
   npm install
   ```

4. **Inicie o aplicativo:**

   ```
   npm start
   ```

   Isso iniciará o Metro Bundler e fornecerá opções para executar o aplicativo em emuladores ou dispositivos físicos.

## Configuração ⚙️

Para usar o aplicativo, é necessário configurar algumas variáveis de ambiente e integrar serviços externos. Siga os passos abaixo:

### Variáveis de Ambiente 🔑

O aplicativo utiliza variáveis de ambiente para configurar informações sensíveis, como chaves de API e URLs. Crie um arquivo `.env` na raiz do projeto e configure as seguintes variáveis:

```
API_BASE_URL=https://sua-url-da-api.com
GOOGLE_MAPS_API_KEY=sua-chave-da-api-do-google-maps
```

### Autenticação OAuth 2.0 📝

O aplicativo utiliza o protocolo OAuth 2.0 para autenticação. Consulte a documentação sobre como configurar a autenticação OAuth 2.0 para obter mais informações.

### Configuração do Banco de Dados 🗄️

O aplicativo utiliza o RealmDB para armazenar dados. Certifique-se de que o RealmDB esteja instalado no projeto e configure os esquemas de banco de dados conforme necessário.

## Funcionalidades 🚀

O aplicativo oferece as seguintes funcionalidades principais:

- Registro de Utilização de Veículos 📋
- Autenticação de Usuários 🔐
- Integração com APIs de Mapas (Google Maps) 🗺️
- Armazenamento de Dados no RealmDB 🏦
- Geocodificação de Endereços 🌍
- Exibição de Mapas Interativos 🗺️
- Customização de Marcadores no Mapa 📍
- Background Tasks ⏲️

## Documentação 📚

Para obter informações detalhadas sobre como usar o aplicativo, consulte a documentação disponível no diretório `docs` deste repositório. A documentação inclui guias passo a passo, exemplos de código e informações sobre a integração com serviços externos.

## Bibliotecas e Tecnologias Utilizadas 📦

O aplicativo foi desenvolvido utilizando as seguintes bibliotecas e tecnologias:

- React Native
- Styled Components
- React Navigation
- Expo Location
- React-Native-Maps
- OAuth 2.0
- RealmDB

Consulte o arquivo `package.json` para obter a lista completa de dependências do projeto.

## Licença 📜

Este projeto é licenciado sob a Licença MIT. Consulte o arquivo `LICENSE` para obter mais informações.

---
