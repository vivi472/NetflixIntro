# 🎥 Animação de Introdução do NETFLIX (HTML & CSS Puros)

Este projeto é uma réplica da animação de introdução icônica da Netflix. O foco foi em replicar o efeito de "pincelada de luz" e o zoom final utilizando apenas HTML semântico e CSS, explorando recursos avançados de animação e transformações.

## 🚀 Funcionalidades

* **Animação de Pincelada:** Efeito de varredura (brush-moving) na cor vermelha, que simula a luz.
* **Efeito de Luminescência:** Uso de `box-shadow` e múltiplos elementos (classes `.lamp-xx`) para criar o brilho característico.
* **Zoom Final:** Animação de escala (`zoom-in`) para o efeito de transição.
* **Reaproveitamento de Componentes:** Estrutura modular (classes `.helper-1` a `.helper-4`) para renderizar todas as letras do nome "NETFLIX" através de um único arquivo CSS.

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Descrição |
| :--- | :--- |
| **HTML5** | Estrutura base com tags personalizadas (`<netflixintro>`) para facilitar o CSS. |
| **CSS3** | Utiliza `@keyframes`, `transform` (para rotação e escala), `linear-gradient` e `box-shadow` para os efeitos visuais e animações. |

## 💡 Como Configurar e Testar

1.  **Estrutura do Projeto:**
    * `index.html`: Arquivo principal contendo a estrutura da letra (incluindo os elementos `.helper-x` e `.fur-xx`).
    * `style.css`: Contém todas as regras de estilo e definições de `@keyframes` para as animações.

2.  **Mudar a Letra:**
    Para alternar a letra exibida, modifique o atributo `letter` na tag `<netflixintro>` dentro do `index.html`.
    
    Exemplo (para a letra T):
    ```html
    <netflixintro letter="T"> 
    ```

## 🔗 Inspiração e Créditos

Este projeto foi criado como uma demonstração de habilidades em CSS3.

* **Créditos Originais:** Programador Designer Pro
    * Instagram: [@programadordesignerpro](https://www.instagram.com/programadordesignerpro/)
    * Telegram: [programadordesignerpro](https://t.me/programadordesignerpro)