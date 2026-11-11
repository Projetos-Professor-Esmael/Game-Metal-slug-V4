# 🪖 Metal Commando V4 — Run & Gun

**Metal Commando V4** é um jogo de ação 2D estilo *Run & Gun* desenvolvido em HTML5 Canvas, CSS3 e JavaScript puro em um único arquivo autossuficiente (`metal_commando_v4.html`), compatível com navegadores **Desktop** e **Mobile**.

---

## 🚀 Principais Recursos

* **HUD e Barras de Atributos:** Indicadores visuais em tempo real para **Vida**, **Ataque (`A`)**, **Defesa (`D`)** e **Habilidade (`H`)**.
* **Sistema de Airdrops (Quedas Aéreas):** Ao derrotar uma sequência de inimigos ou vencer um chefe, caixas com paraquedas caem do céu contendo melhorias de atributos ou novas armas.
* **Arsenal Dinâmico (Troca em Tempo Real):** Alterne livremente entre as armas desbloqueadas durante o combate:
  * **`A1` — Pistola:** Disparo padrão rápido e preciso.
  * **`A2` — Bazuca:** Projétil pesado de alto impacto e dano elevado.
  * **`A3` — Metralhadora:** Dispara 3 feixes contínuos simultâneos em leque.
* **Progressão Sequencial de Dificuldades:** O jogo inicia apenas com o nível **Fácil** desbloqueado. Ao completar todas as fases de uma dificuldade, a próxima é liberada (**Fácil → Médio → Difícil**).
* **Salvar e Importar Progresso:** Exporte seus dados de progresso (dificuldades liberadas, armas e níveis de atributos) em formato `.json` e importe-os a qualquer momento no menu inicial.
* **Suporte Multiplataforma:** Interface responsiva com aviso automático de modo paisagem (horizontal) e controles virtuais dedicados para dispositivos móveis.

---

## 🎮 Controles

### 💻 Computador (PC)
| Tecla / Ação | Função |
| :--- | :--- |
| **`W` / `A` / `S` / `D`** ou **Setas** | Mover o personagem |
| **`Espaço`** ou **`W` / `▲`** | Pular |
| **Mouse + Clique Esquerdo** | Mirar livremente e atirar |
| **`G`** | Lançar granada |
| **`Q`** | Ativar Habilidade Especial (requer barra `H` em 100%) |
| **`1` / `2` / `3`** | Alternar entre Pistola (`A1`), Bazuca (`A2`) e Metralhadora (`A3`) |

### 📱 Dispositivos Móveis (Touch)
* **Direcional (D-Pad):** Movimentação no canto inferior esquerdo.
* **Botões de Ação:** **ATIRAR**, **PULO**, **BOMBA** e **SKILL [Q]** no canto inferior direito.
* **Barra de Armas na HUD:** Toque nos botões `A1`, `A2` ou `A3` no topo da tela para trocar de arma.

---

## 📦 Como Executar

1. Baixe ou salve o arquivo **`metal_commando_v4.html`**.
2. Dê um duplo clique no arquivo para abri-lo diretamente em qualquer navegador moderno (Google Chrome, Microsoft Edge, Firefox, Safari ou Brave).
3. Não requer instalação de servidores, dependências ou conexão com a internet.

---

## 💾 Sistema de Save (`.json`)

No menu inicial do jogo:
* Clique em **💾 Salvar Progresso** para baixar o arquivo `metal_commando_v4_save.json` no seu dispositivo.
* Clique em **📂 Importar Progresso** e selecione o arquivo `.json` salvo anteriormente para restaurar suas conquistas e níveis.
