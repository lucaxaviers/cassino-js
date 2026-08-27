<div align="center">

# 🎰 Cassino 2.0 — Caça-Níquel Web Interativo

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License" />
</p>

<p align="center">
  Um jogo de slot machine moderno e educativo construído inteiramente em <b>JavaScript Vanilla</b>, demonstrando manipulação dinâmica do DOM, gerenciamento de saldo em tempo real e animações temporizadas.
</p>

---

</div>

## 🎮 Regras e Mecânicas de Jogo

| Regra / Parâmetro | Valor | Descrição |
|---|---|---|
| 💰 **Saldo Inicial** | `100 créditos` | Crédito disponibilizado para iniciar a partida |
| 🕹️ **Custo por Rodada** | `10 créditos` | Debitado automaticamente a cada giro |
| 🏆 **Prêmio Jackpot** | `+50 créditos` | Concedido ao alinhar 3 símbolos idênticos |
| 🍒 **Símbolos Sorteados** | `🍒 🍋 🍉 ⭐ 7️⃣` | Sorteio randômico independente por rolo |

---

## ✨ Destaques de Implementação

```mermaid
flowchart LR
    A[Clique em Jogar] --> B{Saldo >= 10?}
    B -- Não --> C[Exibe Alerta F5]
    B -- Sim --> D[Debita 10 Créditos]
    D --> E[Desativa Botão & Inicia Rotação]
    E --> F[Sorteia 3 Símbolos]
    F --> G{3 Símbolos Iguais?}
    G -- Sim --> H[Adiciona +50 Créditos & Alerta Vitória]
    G -- Não --> I[Exibe Tente Novamente]
    H --> J[Reativa Botão]
    I --> J
```

- **Prevenção de Cliques Múltiplos:** Botão desabilitado (`disabled = true`) durante a rolagem dos rolos.
- **Manipulação Dinâmica:** Atualização visual imediata de saldos e mensagens coloridas.
- **Design Responsivo:** Centralização com Flexbox, sombras em relevo (`inset shadow`) e QR Code Pix integrado.

---

## 🚀 Como Executar Localmente

```bash
# Clonar o repositório
git clone https://github.com/lucaxaviers/cassino-js.git

# Acessar a pasta
cd cassino-js

# Abrir no navegador
start index.html
```

---

<div align="center">
  <sub>Desenvolvido no contexto de Engenharia de Software</sub>
</div>
