# 🪨 Stone Portal

**Stone Portal** é um jogo **2D de plataforma** desenvolvido no **Construct 3**, focado em **exploração e evasão**, ambientado em um mundo fantástico repleto de mistérios, ruínas e criaturas perigosas.

---

## 🎮 Sobre o Jogo

O jogador controla um **explorador** que, durante uma de suas expedições, encontra uma **pedra misteriosa** que o transporta para um mundo desconhecido. Esse local é habitado por **animais fantásticos** e pelos vestígios de uma **civilização antiga que foi extinta por algo misterioso**.

Sem meios de combate, o explorador precisa usar sua **agilidade, precisão e estratégia** para evitar inimigos e coletar artefatos antigos que o ajudem a encontrar o caminho de volta para casa.

---

## 🗺️ Estrutura das Fases

- **Total de fases:** 7  
  - 🟢 **6 fases normais**
  - 🔴 **1 fase final (Boss)**

- Para avançar em cada fase, o jogador deve:
  - Coletar **3 runas**
  - Abrir o **portal** para a próxima fase

- Algumas fases possuem:
  - 🔑 **Chave**, usada para abrir um **baú**
  - 💰 **Baú com moedas extras**

---

## ❤️ Sistema do Jogador

- **Vida:** 3 corações
- **Combate:** ❌ Não existe combate
- **Mecânica principal:** Evitar inimigos
- **Coletáveis:**
  - 🪙 **Moedas** (pontuação do jogo)
  - 🔮 **Runas** (progressão das fases)

---

## 👾 Inimigos

O jogo conta com **3 tipos de inimigos**, todos causam **1 ponto de dano** ao jogador.  
Como não há combate, o objetivo é **desviar e evitar o contato**.

### 🐍 Snake
- Primeiro inimigo do jogo
- Movimento terrestre
- Dano: 1

### 🦂 Scorpion
- Segundo inimigo do jogo
- Dano: 1
- Efeito especial: **paralisa o jogador por 2 segundos**

### 🦅 Vulture
- Inimigo aéreo
- Dano: 1
- Habilidade especial: **voa e pode arrastar o jogador**

---

## 🐢 Boss Final – Mother Turtle

Na fase final, o jogador enfrenta o boss:

- **Nome:** Mother Turtle
- **Ataque:** Mísseis teleguiados
- **Dano:** 3 pontos (**Hit Kill**)
- Exige atenção máxima, já que **um único ataque pode ser fatal**

---

## 🌲 Ambientação

- Estilo **2D Plataforma**
- Mapas ambientados em:
  - 🌳 Florestas
  - 🌉 Pontes de madeira antigas
- Atmosfera de mundo perdido, antigo e misterioso

---

## 📖 Lore do Jogo

> Durante uma de suas explorações, um aventureiro encontra uma pedra antiga que o transporta para um mundo fantástico.  
>  
> Esse mundo é habitado por criaturas incríveis e pelos vestígios de uma civilização que foi extinta por algo desconhecido.  
>  
> Perdido nesse lugar, o explorador precisa encontrar **runas ancestrais** espalhadas pelas fases para ativar portais que possam guiá-lo de volta para casa.

---

## 🎮 Controles

O jogo utiliza apenas o teclado:

- ⬅️ **Seta Esquerda** — Move o jogador para a esquerda  
- ➡️ **Seta Direita** — Move o jogador para a direita  
- ⬆️ **Seta para Cima** — Pulo  
- 🤚🏻 **Tecla E** — Interação  

### 🔄 Mecânica Especial
- O jogador possui **pulo duplo**, permitindo um segundo salto no ar.

---

## 🕹️ Modo de Jogar

Para executar o jogo localmente, siga os passos abaixo:

1. **Clone o repositório**
   ```bash
   https://github.com/DevJoaoVitorB/stone-portal-game.git
   ```

2. **Abra o projeto no Visual Studio Code**

3. **Instale a extensão Live Server**
   - Acesse a aba de extensões no VSCode
   - Procure por **Live Server**
   - Instale a extensão

4. **Execute o jogo**
   - Abra o arquivo `index.html`
   - Clique com o botão direito
   - Selecione **"Open with Live Server"**

O jogo será aberto automaticamente no navegador.

---

## 🛠️ Tecnologias Utilizadas

- **Engine:** Construct 3  
- **Plataforma:** Web / PC  
- **Gênero:** Plataforma 2D / Aventura
