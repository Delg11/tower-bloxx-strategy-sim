# 🏙️ Tower Bloxx Strategy Simulator (EN-US)

An interactive simulator and optimization tool for the “Build City” mode of the classic game **Tower Bloxx**.

This project was created to help players test urban layout strategies, maximizing population without the time pressure or physics of the original game. It allows planning complex placements (such as setups for Diamond/Yellow towers) and sharing solutions with the community.

## ✨ Features

* **Real-Time Rule Validation:** The game prevents illegal moves and explains why (e.g., “Red requires a Blue neighbor”).
* **Timeline (Time Travel):** A slider lets you go back to any previous step and fix planning mistakes without restarting the board.
* **Compact Save System:** Export and share your entire board using a short hexadecimal code (e.g., `V1-07135C...`).
* **Smart Hints:** When selecting a tower, the board automatically highlights the cells where it can be built.
* **Tower Replacement:** Allows placing towers on top of existing ones (upgrades), as long as neighborhood rules are respected.
* **Internationalization:** Full interface in Portuguese (PT-BR) and English (EN-US).
* **Single File:** The entire project runs in a single HTML file, with no need to install dependencies (Node/NPM).

## 🎮 Game Rules

The goal is to maximize population by placing higher-value towers. However, better towers require specific neighbors (orthogonal only: up, down, left, right):

| Tower           | Color     | Points | Neighborhood Requirement                                     |
| :-------------- | :-------- | :----: | :----------------------------------------------------------- |
| **Residential** | 🔵 Blue   |    1   | None (Can be placed anywhere)                                |
| **Commercial**  | 🔴 Red    |    2   | Requires **1 Blue** adjacent                                 |
| **Office**      | 🟢 Green  |    3   | Requires **1 Blue** **and** **1 Red** adjacent               |
| **Luxury**      | 🟡 Yellow |    4   | Requires **1 Blue**, **1 Red**, **and** **1 Green** adjacent |

## 🚀 How to Use

No installation required! Since the project uses React via CDN:

1. Download the `index.html` file.
2. Open it in any modern browser (Chrome, Firefox, Edge, Safari).
3. Start planning!

### 💻 Development

If you want to edit the code:

1. Open `index.html` in a code editor (VS Code, Sublime, Notepad++).
2. The code uses **React 18** and **Tailwind CSS** (via CDN).
3. All logic lives inside the `<script type="text/babel">` tag.

## 📸 Screenshots

*(You can add a game screenshot here later)*

## 🤝 Contribution and Credits

This is a free and independent project.

* **Author:** Gabriel Silva Delgado
* **Co-authorship:** Developed with assistance from the Gemini AI (Google).

## 📄 License

This project is licensed under the **GNU GPL**. Feel free to use, study, and modify it.

---

*Liked the project? Consider making a donation via PIX: `g.delgado@unifesp.br`*


# 🏙️ Tower Bloxx Strategy Simulator (PT-BR)

Um simulador interativo e ferramenta de otimização para o modo "Build City" do clássico jogo **Tower Bloxx**.

Este projeto foi criado para ajudar jogadores a testarem estratégias de layout urbano, maximizando a população sem a pressão do tempo ou a física do jogo original. Ele permite planejar posicionamentos complexos (como o setup para torres de Diamante/Amarelas) e compartilhar soluções com a comunidade.

## ✨ Funcionalidades

* **Validação de Regras em Tempo Real:** O jogo impede jogadas ilegais e explica o motivo (ex: "Vermelho precisa de vizinho Azul").
* **Linha do Tempo (Time Travel):** Uma barra deslizante permite voltar no tempo para qualquer passo anterior e corrigir erros de planejamento sem reiniciar o tabuleiro.
* **Sistema de Saves Compactos:** Exporte e compartilhe seu tabuleiro inteiro usando um código hexadecimal curto (ex: `V1-07135C...`).
* **Dicas Visuais (Smart Hints):** Ao selecionar uma torre, o tabuleiro ilumina automaticamente as células onde é possível construir.
* **Substituição de Torres:** Permite colocar torres em cima de outras já existentes (upgrade), desde que as regras de vizinhança sejam respeitadas.
* **Internacionalização:** Interface completa em Português (PT-BR) e Inglês (EN-US).
* **Single File:** Todo o projeto roda em um único arquivo HTML, sem necessidade de instalação de dependências (Node/NPM).

## 🎮 Regras do Jogo

O objetivo é maximizar a população colocando torres de maior valor. No entanto, torres melhores exigem vizinhos específicos (apenas ortogonais: cima, baixo, esquerda, direita):

| Torre | Cor | Pontos | Requisito de Vizinhança |
| :--- | :--- | :---: | :--- |
| **Residencial** | 🔵 Azul | 1 | Nenhum (Pode ser colocada em qualquer lugar) |
| **Comercial** | 🔴 Vermelho | 2 | Precisa de **1 Azul** ao lado |
| **Escritório** | 🟢 Verde | 3 | Precisa de **1 Azul** E **1 Vermelho** ao lado |
| **Luxo** | 🟡 Amarelo | 4 | Precisa de **1 Azul**, **1 Vermelho** E **1 Verde** ao lado |

## 🚀 Como Usar

Não é necessário instalar nada! Como o projeto utiliza React via CDN:

1.  Baixe o arquivo `index.html`.
2.  Abra-o em qualquer navegador moderno (Chrome, Firefox, Edge, Safari).
3.  Comece a planejar!

### 💻 Desenvolvimento

Se quiser editar o código:
1.  Abra o `index.html` em um editor de código (VS Code, Sublime, Notepad++).
2.  O código utiliza **React 18** e **Tailwind CSS** (via CDN).
3.  Toda a lógica está dentro da tag `<script type="text/babel">`.

## 📸 Screenshots

*(Você pode adicionar um print do jogo aqui depois)*

## 🤝 Contribuição e Créditos

Este é um projeto livre e independente.

* **Autor:** Gabriel Silva Delgado
* **Co-autoria:** Desenvolvido com auxílio da IA Gemini (Google).

## 📄 Licença

Este projeto está licenciado sob a **GNU GPL**. Sinta-se livre para usar, estudar e modificar.

---
*Gostou do projeto? Considere fazer uma doação via PIX: `g.delgado@unifesp.br`*
