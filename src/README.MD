# Simulador de Teclado Virtual 🎹

## Descrição

Keyboard Simulator é uma aplicação web de interface simples e intuitiva que permite aos usuários tocar um teclado musical utilizando o mouse ou o teclado do computador.

## Tecnologias Usadas

- **HTML5**: Para estruturar a página e o layout do teclado musical.
- **CSS3**: Para estilizar a interface, incluindo cores, fontes e efeitos visuais.
- **Vanilla JavaScript**: Para adicionar interatividade, como tocar notas ao clicar nas teclas ou pressionar as teclas do teclado.

## Estrutura do Projeto

- `index.html`: Contém a estrutura da página e a interface do teclado musical.
- `styles/`: Diretório contendo os arquivos CSS para estilização.
  - `reset.css`: Reinicia estilos padrão do navegador.
  - `main.css`: Contém os estilos principais da aplicação.
- `scripts/`: Diretório contendo o arquivo JavaScript para lógica.
  - `engine.js`: Contém a lógica para tocar as notas e manipular a interface.
- `src/tunes/`: Diretório contendo os arquivos de áudio para cada nota musical.
- `src/fav-icon/`: Diretório contendo o ícone da aplicação.

## Funcionamento

### 1. Layout

O teclado musical é representado como uma série de teclas brancas e pretas. Cada tecla possui um evento de clique que, quando acionado, toca uma nota correspondente.

### 2. Interatividade

- **Clique em Teclas**: O usuário pode tocar as notas clicando nas teclas do teclado musical. Cada tecla ativa um som específico.
- **Teclado**: O usuário pode usar as teclas do teclado ("a", "w", "s", "e", "d", "f", "t", "g", "y", "h", "u", "j", "k", "o", "l", "p", ";") para tocar as notas.
- **Controle de Volume**: Um controle deslizante permite ajustar o volume do áudio.
- **Mostrar/Ocultar Teclas**: Uma checkbox permite que o usuário oculte ou mostre as teclas do teclado musical.

### 3. Código JavaScript

O arquivo `engine.js` contém a lógica principal da aplicação. Aqui estão alguns pontos-chave:

- **Seleção de Elementos**: Utiliza `document.querySelector` e `document.querySelectorAll` para acessar elementos do DOM.
- **Manipulação de Eventos**: Adiciona listeners para eventos de clique e pressionamento de teclas.
- **Controle de Áudio**: Utiliza a classe `Audio` para carregar e reproduzir arquivos de áudio.
- **Animações**: Adiciona e remove classes para criar efeitos visuais ao tocar as notas.

## Exemplos de Uso

1. **Tocar uma Nota**: Clique em uma tecla ou pressione a tecla correspondente no teclado.
2. **Ajustar o Volume**: Use o controle deslizante para aumentar ou diminuir o volume.
3. **Mostrar/Ocultar Teclas**: Use a checkbox para ocultar ou mostrar as teclas do teclado musical.

