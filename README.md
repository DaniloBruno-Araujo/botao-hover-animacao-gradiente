# Botão com Animação de Gradiente em Hover

## 🖼️ Preview

<img width="957" height="945" alt="image" src="https://github.com/user-attachments/assets/52535b12-614a-493d-baf2-da2269748853" />


## 💻 Tecnologias Utilizadas

* **HTML5:** Utilizado para a estrutura do botão, que consiste em um elemento `<div>` como container e um link `<a>` com um `<span>` interno para o texto.
* **CSS3:** Responsável por toda a estilização e pela animação. A borda é criada com a propriedade `background: linear-gradient` no container externo. O efeito de "botão vazado" é obtido com um `<span>` interno que tem a cor de fundo da página. A animação é ativada no estado `:hover` e utiliza `@keyframes` para animar a propriedade `filter: hue-rotate()`, o que gera a transição de cores.
