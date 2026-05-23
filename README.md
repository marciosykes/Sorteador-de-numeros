# Sorteador de Números

Uma aplicação web robusta e animada para sortear números aleatórios. Ideal para sorteios, jogos ou qualquer situação que exija a geração de números dentro de um intervalo específico, com a opção de evitar repetições.

## 🚀 Funcionalidades

* **Sorteio Múltiplo:** Capacidade de sortear vários números de uma só vez.
* **Intervalo Personalizado:** O utilizador pode definir o valor mínimo e máximo para o sorteio.
* **Controlo de Repetição:** Um *toggle switch* (interruptor) personalizado permite escolher se os números sorteados se podem repetir ou se devem ser únicos.
* **Animações Dinâmicas:** A exibição dos resultados conta com animações avançadas criadas em CSS (`@keyframes`), proporcionando um efeito visual rotativo e de escala à medida que cada número é revelado.
* **Revelação Assíncrona:** Utilização de temporizadores (`setTimeout` no JavaScript) para revelar os números sorteados de forma faseada, aumentando a expectativa.
* **Design Responsivo:** Interface moderna (Dark Mode) que se adapta perfeitamente a dispositivos móveis e desktops.

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação da página e formulários.
* **CSS3:** * Estrutura altamente modular (ficheiros separados para `button`, `container`, `switch`, animações de resultados, etc.).
  * Uso intensivo de CSS Custom Properties (variáveis globais).
  * Animações complexas utilizando `@keyframes` para criar efeitos de gradiente nos botões e interações rotativas nos resultados.
* **JavaScript (Vanilla):** * Lógica matemática com `Math.random()`.
  * Manipulação avançada do DOM e listas de arrays para garantir números únicos (quando o switch está ativo).
  * Controlo de fluxo assíncrono com `setTimeout` para a exibição faseada dos resultados.

## 📁 Estrutura de Ficheiros

* `index.html`: Ficheiro principal da interface.
* `script.js`: O motor da aplicação, gerindo o algoritmo de sorteio e a manipulação dos elementos visuais.
* `styles/`: Diretório contendo a estilização fragmentada e organizada (ex: `global.css`, `index.css`, `button.css`, `switch.css`).
* `assets/`: Imagens, ícones (SVG) e o logótipo do projeto.

## 💻 Como Executar o Projeto

1. Faça o clone deste repositório para a sua máquina local ou descarregue o código-fonte.
2. Navegue até à pasta do projeto (`Sorteador-de-numeros`).
3. Abra o ficheiro `index.html` no seu navegador web (browser) preferido.
4. Defina a quantidade de números, o intervalo pretendido, e clique em "Sortear" para ver a magia acontecer!

---
*Projeto focado no aprimoramento de animações em CSS puro e lógica assíncrona em JavaScript.*