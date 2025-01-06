# Ledor App 📸🔊

Ledor é um aplicativo de acessibilidade visual desenvolvido em React Native. Ele permite capturar ou selecionar uma imagem de texto e, através de uma API de OCR, converte o conteúdo da imagem em texto. Além disso, o aplicativo possui um interpretador de texto que narra o conteúdo extraído, proporcionando uma experiência de leitura inclusiva para pessoas com deficiência visual.

## 🎯 Objetivo
Promover a inclusão digital, ajudando pessoas com deficiência visual a acessar informações de forma prática ao transformar textos impressos em áudio, facilitando a compreensão e a interação com o conteúdo.

## 🛠️ Tecnologias Utilizadas
- React Native: Framework para o desenvolvimento de aplicativos móveis.
- Expo: Plataforma e conjunto de ferramentas para desenvolvimento com React Native.
- JavaScript (ES6+): Linguagem de programação principal.
- Expo ImagePicker: Biblioteca para seleção de imagens da galeria e captura de fotos.
- Fetch API: Utilizada para requisições HTTP.
- API apilayer (Image to Text): Serviço de OCR para extração de texto de imagens.
- React Hooks (useState): Para gerenciamento de estado.
- React Native Text-to-Speech: Biblioteca para converter texto em áudio.

## 📲 Funcionalidades
- Captura de imagens usando a câmera do dispositivo.
- Seleção de imagens diretamente da galeria.
- Conversão de imagens em texto utilizando a API apilayer.
- Narração automática do texto extraído por meio de um interpretador de voz.
- Interface simples e acessível, com navegação intuitiva.

## 🚀 Como Executar
1. Clone o repositório:
   ```bash
   git clone https://github.com/paulohenriquemendes/ledor-app.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd ledor
   ```
3. Instale as dependências:
   ```bash
   npm install
   ```
4. Execute o aplicativo:
   ```bash
   npx expo start
   ```

## 🤝 Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.
