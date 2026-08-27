# 🎰 Cassino 2.0 — Caça-Níquel Interativo Web

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
[![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)](LICENSE)

Uma aplicação web interativa de **Slot Machine (Caça-Níquel)** desenvolvida do zero em **JavaScript Vanilla**, **HTML5** e **CSS3**, com foco em manipulação dinâmica do DOM, gerenciamento de estado de saldo e animações visuais.

---

## 🎮 Mecânica do Jogo

- **Saldo Inicial:** O jogador inicia a partida com **100 créditos**.
- **Custo por Jogada:** Cada acionamento da alavanca consome **10 créditos**.
- **Regra de Vitória (Jackpot):** Ao alinhar 3 símbolos idênticos nos três rolos, o jogador recebe um prêmio bônus de **+50 créditos**.
- **Símbolos do Caça-Níquel:**
  ```
  🍒 Cereja  |  🍋 Limão  |  🍉 Melancia  |  ⭐ Estrela  |  7️⃣ Sete da Sorte
  ```
- **Controle de Bloqueio:** Durante a rotação dos rolos, o botão de jogar é desativado para evitar requisições concorrentes e garantir a sincronia da animação.
- **Fim de Créditos:** Caso o saldo chegue a zero, o sistema alerta o jogador para recarregar a página (`F5`).

---

## 🛠️ Tecnologias e Recursos

- **HTML5 Semântico:** Estrutura clara e acessível.
- **CSS3 Moderno:** Layout centralizado com Flexbox, sombras suaves (`box-shadow`), efeitos de profundidade nos rolos (`inset shadow`) e design limpo.
- **JavaScript ES6+:**
  - Sorteio pseudo-aleatório com `Math.random()`.
  - Manipulação de classes e atributos do DOM em tempo real.
  - Temporizadores (`setInterval` e `setTimeout`) para o efeito de rotação contínua antes da parada final.
- **QR Code Pix Integrado:** Área interativa para suporte ou demonstração de doações.

---

## 📁 Estrutura de Arquivos

```
.
├── index.html       # Estrutura visual da aplicação e dos rolos
├── script.js        # Lógica de jogo, regras de aposta e controle do DOM
├── style.css        # Estilização visual, layout responsivo e animações
├── image.png        # QR Code Pix demonstrativo
└── README.md
```

---

## 🚀 Como Executar Localmente

Basta abrir o arquivo `index.html` em qualquer navegador web moderno:

```bash
# Clonar o repositório
git clone https://github.com/lucaxaviers/cassino-js.git

# Acessar a pasta
cd cassino-js

# Abrir no navegador (Windows)
start index.html
```

---

> **Desenvolvido por Lucas Rodrigues Xavier**  
> *Projeto acadêmico e experimental com foco em front-end vanilla e lógica interativa.*
