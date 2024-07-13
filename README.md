# EV-olution

## Introdução
EV-olution é um projeto de frontend desenvolvido com React que apresenta uma interface interativa com um fundo dinâmico, uma barra de navegação e uma seção heroica que alterna entre diferentes mensagens e imagens.

## Instalação
Para instalar e executar este projeto localmente, siga os passos abaixo:

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/ev-olution.git
    ```
2. Navegue até o diretório do projeto:
    ```bash
    cd ev-olution
    ```
3. Instale as dependências:
    ```bash
    npm install
    ```
4. Inicie o servidor de desenvolvimento:
    ```bash
    npm start
    ```

## Uso
Após iniciar o servidor de desenvolvimento, você pode visualizar o projeto acessando `http://localhost:3000` no seu navegador. A interface exibe um vídeo ou imagens que mudam automaticamente a cada 3 segundos e uma barra de navegação no topo.

## Funcionalidades
- Exibição de fundo dinâmico (vídeo ou imagens).
- Navegação entre diferentes seções.
- Mensagens heroicas alternando automaticamente.
- Controle de reprodução de vídeo.

## Dependências
- React
- CSS (para estilização)
- Vídeo e imagens estáticas

## Estrutura do Projeto
src/
|-- assets/
| |-- video1.mp4
| |-- image1.png
| |-- image2.png
| |-- image3.png
| |-- arrow_btn.png
| |-- play_icon.png
| |-- pause_icon.png
|
|-- Components/
| |-- Background/
| | |-- Background.js
| | |-- Background.css
| |
| |-- Hero/
| | |-- Hero.js
| | |-- Hero.css
| |
| |-- Navbar/
| |-- Navbar.js
| |-- Navbar.css
|
|-- App.js

## Contribuidores
- [Seu Nome](https://github.com/FernandoZuchi)

## Licença
Este projeto está licenciado sob a Licença MIT. Consulte o arquivo LICENSE para obter mais informações.
