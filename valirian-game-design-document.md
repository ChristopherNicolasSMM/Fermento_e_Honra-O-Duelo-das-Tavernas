# Fermento & Honra — O Duelo das Tavernas
## Game Design Document (GDD) — v1.0
### Cervejaria Valirian · Para Aprovação e Início de Desenvolvimento

---

## Sumário de Navegação

- [1. Visão Executiva](#1-visão-executiva)
- [2. Conceito e Posicionamento](#2-conceito-e-posicionamento)
- [3. Ficha do Produto](#3-ficha-do-produto)
- [4. Narrativa e Universo](#4-narrativa-e-universo)
- [5. Os Seis Personagens-Deck](#5-os-seis-personagens-deck)
  - [5.1 Pacto das Sombras — Porter](#51-pacto-das-sombras--porter)
  - [5.2 Sangue de Druida — Irish Red Ale](#52-sangue-de-druida--irish-red-ale)
  - [5.3 Elixir da Dríade — Session Juice IPA](#53-elixir-da-dríade--session-juice-ipa)
  - [5.4 Orvalho de Valirian — Witbier](#54-orvalho-de-valirian--witbier)
  - [5.5 Juramento do Aventureiro — Amber Ale](#55-juramento-do-aventureiro--amber-ale)
  - [5.6 Tempestade de Trigo — Weiss](#56-tempestade-de-trigo--weiss)
- [6. Regras Completas do Jogo](#6-regras-completas-do-jogo)
  - [6.1 Objetivo e Preparação](#61-objetivo-e-preparação)
  - [6.2 Estrutura do Turno](#62-estrutura-do-turno)
  - [6.3 Tipos de Cartas](#63-tipos-de-cartas)
  - [6.4 Habilidades Passivas](#64-habilidades-passivas)
  - [6.5 Regras Especiais](#65-regras-especiais)
  - [6.6 Condição de Vitória](#66-condição-de-vitória)
  - [6.7 Glossário](#67-glossário)
- [7. Deck Completo — MVP Pacto das Sombras](#7-deck-completo--mvp-pacto-das-sombras)
- [8. Deck Completo — MVP Sangue de Druida](#8-deck-completo--mvp-sangue-de-druida)
- [9. Comparação e Balanceamento — Análise dos Decks MVP](#9-comparação-e-balanceamento--análise-dos-decks-mvp)
- [10. Modos de Jogo](#10-modos-de-jogo)
- [11. Direção Visual do Jogo](#11-direção-visual-do-jogo)
- [12. Componentes e Box Colecionador](#12-componentes-e-box-colecionador)
- [13. Alinhamento com a Identidade Valirian](#13-alinhamento-com-a-identidade-valirian)
- [14. Estratégia de Lançamento](#14-estratégia-de-lançamento)
- [15. Estimativa de Custos](#15-estimativa-de-custos)
- [16. Roteiro de Desenvolvimento](#16-roteiro-de-desenvolvimento)
- [17. MVP — Plano de Testes e Validação](#17-mvp--plano-de-testes-e-validação)
- [18. Próximos Passos para Aprovação](#18-próximos-passos-para-aprovação)

---

## 1. Visão Executiva

**Fermento & Honra — O Duelo das Tavernas** é o card game oficial da Cervejaria Valirian.

O projeto transforma os rótulos do portfólio Valirian em personagens jogáveis de um card game competitivo. Cada deck representa uma cerveja com identidade, mecânica e narrativa únicas — alinhadas ao estilo cervejeiro e à arte do rótulo correspondente.

O jogo existe para **aprofundar o ecossistema da marca**, criando um produto colecionável que recompensa quem já conhece a Valirian e convida novos consumidores a descobrir o portfólio através do jogo.

### Premissa central

> *"O jogo não existe sem a cerveja. O deck não existe sem o rótulo. Cada partida é uma celebração da experiência Valirian — nunca um produto separado."*

### O que este documento é

Este GDD é o documento de referência para aprovação do conceito, alinhamento da equipe e início do desenvolvimento. Ele cobre regras completas, decks do MVP, direção visual, estratégia de lançamento e roteiro de desenvolvimento fase a fase.

---

## 2. Conceito e Posicionamento

### Referência de mecânica

O jogo é inspirado no **Dungeon Mayhem** (Wizards of the Coast) — um card game ágil, rápido e altamente acessível para 2 a 6 jogadores, onde cada personagem tem um deck único com habilidade passiva e mecânica central próprias. Partidas duram 15 a 30 minutos.

A escolha por essa referência é estratégica: Dungeon Mayhem tem fórmula provada, curva de aprendizado suave e alta rejogabilidade. A Valirian traz sua identidade narrativa e visual para esse molde, criando algo familiar na mecânica mas único no universo.

### Proposta de valor do produto

| Dimensão | Proposta |
|----------|----------|
| **Para fãs da Valirian** | Um produto colecionável que aprofunda o vínculo com a marca e o portfólio |
| **Para jogadores de card games** | Um card game bem balanceado com identidade visual forte e história |
| **Para o mercado de cerveja artesanal** | Um produto diferenciado que cria experiência além da garrafa |
| **Para a marca Valirian** | Expansão do ecossistema, geração de receita adicional e visibilidade em eventos |

### Diferencial competitivo

Não existe hoje no mercado brasileiro de cerveja artesanal um card game vinculado a um portfólio real de cervejas com essa qualidade de identidade visual e profundidade mecânica. O produto cria uma categoria nova para a Valirian.

---

## 3. Ficha do Produto

| Atributo | Especificação |
|----------|---------------|
| **Nome** | Fermento & Honra — O Duelo das Tavernas |
| **Tipo** | Card Game Competitivo |
| **Jogadores** | 2 a 6 |
| **Tempo por partida** | 15–30 minutos |
| **Faixa etária** | 14+ |
| **Total de cartas (box completo)** | 180 cartas (6 decks × 30 cartas) |
| **Linha** | Edição Limitada / Colecionável |
| **Licença** | Produto oficial Cervejaria Valirian |

---

## 4. Narrativa e Universo

### Ambientação

O jogo se passa na **Taverna Valirian** — um lugar lendário onde aventureiros de todos os reinos se reúnem após batalhas, missões e jornadas. A tradição sagrada da Taverna é o **Torneio do Barril**: um duelo realizado toda lua cheia, onde cada cerveja do portfólio se manifesta como uma entidade personificada e disputa o título de **Mestre da Taverna**.

O vencedor do Torneio garante o direito de ser a primeira a ser servida no novo lote — o maior dos honrarias no mundo da Valirian.

### Texto de abertura (manual)

> *"Nas terras de Valirian, diz-se que toda cerveja carrega uma alma. Não a alma do mestre cervejeiro — embora a dele esteja lá também — mas a alma de tudo o que ela representa: a floresta de onde vieram os lúpulos, a montanha que filtrou a água, o fogo que tostou o malte. Quando a lua cheia banha o barril sagrado, essas almas ganham forma. E disputam. Não com espadas, não com magias — com cartas, estratégia e a honra do seu estilo. Que o melhor Mestre da Taverna vença. E que todos brindem ao final."*

### Coerência com os rótulos

Cada personagem-deck é uma extensão direta do universo narrativo já estabelecido nos rótulos físicos da Valirian. O personagem do jogo deve ser reconhecível por quem já conhece o rótulo — são o mesmo mundo, a mesma história, apenas com poses e contexto de combate.

---

## 5. Os Seis Personagens-Deck

Cada deck representa uma cerveja do portfólio Valirian com **30 cartas**, **habilidade passiva única** e **mecânica central** que remete às características do estilo cervejeiro e à narrativa do rótulo.

---

### 5.1 Pacto das Sombras — Porter

| Campo | Definição |
|-------|-----------|
| **Estilo Cervejeiro** | Porter |
| **Arquétipo de Jogo** | Controlador / Sombrio |
| **Estilo de Jogo** | Controla o jogo, força descartes, brilha no fim da partida |
| **Habilidade Passiva** | *Manto das Trevas* — no início do turno, se você tiver 3 ou menos cartas na mão, compre 1 |
| **Mecânica Central** | Cartas que ganham força quando o jogador está em desvantagem (mão baixa, vida baixa) |
| **Dificuldade** | Intermediário |

**Lore:**
> *"Há magias que não deveriam ser invocadas. Há pactos que custam mais do que se imagina. O Pacto das Sombras é uma Porter encorpada e escura — como os segredos que ela guarda. Quem bebe, aceita o acordo."*

**Coerência com o estilo:** O Porter é escuro, encorpado e intenso — um estilo que "guarda segredos" no malte. A mecânica de controle e a explosão no late game refletem a profundidade que se revela gradualmente ao beber uma boa Porter.

---

### 5.2 Sangue de Druida — Irish Red Ale

| Campo | Definição |
|-------|-----------|
| **Estilo Cervejeiro** | Irish Red Ale |
| **Arquétipo de Jogo** | Equilibrado / Conector |
| **Estilo de Jogo** | Conecta ações, ganha bônus por sequências, recompensa consistência |
| **Habilidade Passiva** | *Ciclo da Natureza* — se você jogar 2 ou mais cartas no mesmo turno, cure 1 de vida |
| **Mecânica Central** | Combos e sequências de cartas que se potencializam mutuamente |
| **Dificuldade** | Avançado |

**Lore:**
> *"Nas florestas antigas, os druidas conhecem o fluxo da vida. Sangue de Druida é uma Irish Red Ale que celebra esse equilíbrio — terrosa, encorpada, com alma de madeira e raízes profundas. Cada gole é um lembrete: a natureza recompensa quem respeita seu ritmo."*

**Coerência com o estilo:** A Irish Red Ale é equilibrada, consistente e confiável — exatamente como o estilo de jogo que recompensa sequências bem executadas. O loop de cura reflete a natureza cíclica e regenerativa da cerveja e do personagem druida.

---

### 5.3 Elixir da Dríade — Session Juice IPA

| Campo | Definição |
|-------|-----------|
| **Estilo Cervejeiro** | Session Juice IPA |
| **Arquétipo de Jogo** | Curativo / Protetor |
| **Estilo de Jogo** | Cura aliados e a si mesmo, protege, tem mecânicas de "presente" |
| **Habilidade Passiva** | *Essência da Floresta* — no final do turno, se você curou alguém, compre 1 carta |
| **Mecânica Central** | Curas que também geram outros benefícios — cada ato de cura tem retorno |
| **Dificuldade** | Iniciante–Intermediário |

**Lore:**
> *"Dizem que dríades nascem das árvores mais antigas, guardiãs da vida que floresce entre raízes e musgo. O Elixir da Dríade carrega esse dom — suave, refrescante, com uma profundidade que só quem prova entende. É o conforto da floresta em forma líquida."*

**Coerência com o estilo:** Session Juice IPA é suave, refrescante e fácil de beber — o estilo "entry point" para o mundo das IPAs. O deck espelha isso com uma mecânica generosa e de fácil aprendizado.

---

### 5.4 Orvalho de Valirian — Witbier

| Campo | Definição |
|-------|-----------|
| **Estilo Cervejeiro** | Witbier |
| **Arquétipo de Jogo** | Ágil / Surpresa |
| **Estilo de Jogo** | Cartas baratas, ataques pequenos e rápidos, alta mobilidade |
| **Habilidade Passiva** | *Primeiro Orvalho* — a primeira carta jogada no turno não conta como ação principal, permitindo uma carta adicional |
| **Mecânica Central** | Muitas jogadas pequenas por turno; velocidade como vantagem estratégica |
| **Dificuldade** | Iniciante |

**Lore:**
> *"Nas primeiras horas da manhã, quando o sol ainda não rompeu a névoa, o orvalho se forma. Dizem que quem prova esse líquido ao amanhecer ganha agilidade e clareza. O Orvalho de Valirian é uma Witbier leve e cristalina — o primeiro gole do dia, o começo de uma nova jornada."*

**Coerência com o estilo:** Witbier é leve, efervescente e rápida — características que se traduzem diretamente na agilidade e no volume de jogadas por turno do deck.

---

### 5.5 Juramento do Aventureiro — Amber Ale

| Campo | Definição |
|-------|-----------|
| **Estilo Cervejeiro** | Amber Ale |
| **Arquétipo de Jogo** | Versátil / Adaptável |
| **Estilo de Jogo** | Deck com cartas de todos os tipos, bônus por "missões" (sequências), adapta-se ao oponente |
| **Habilidade Passiva** | *Código do Aventureiro* — no início do jogo, escolha um tipo de carta; cartas desse tipo têm +1 de efeito durante toda a partida |
| **Mecânica Central** | Adaptação — o jogador define seu estilo de jogo na configuração e otimiza em torno dele |
| **Dificuldade** | Intermediário |

**Lore:**
> *"Todo aventureiro sabe: o mundo não espera você se preparar. É preciso versatilidade, coragem e, acima de tudo, um juramento. Juramento do Aventureiro é uma Amber Ale que celebra quem ousa sair da taverna — equilibrada, confiável, pronta para qualquer desafio."*

**Coerência com o estilo:** Amber Ale é o estilo mais equilibrado e versátil — nem muito leve, nem muito encorpado. O deck reflete isso com cartas de todos os tipos e a habilidade de adaptar o foco durante o jogo.

---

### 5.6 Tempestade de Trigo — Weiss

| Campo | Definição |
|-------|-----------|
| **Estilo Cervejeiro** | Weiss |
| **Arquétipo de Jogo** | Explosivo / Imprevisível |
| **Estilo de Jogo** | Efeitos aleatórios, cartas poderosas com risco embutido |
| **Habilidade Passiva** | *Fúria dos Ventos* — no início do turno, role um dado: 1–2 = 1 dano próprio; 3–4 = compre 1 carta; 5–6 = 1 dano em oponente escolhido |
| **Mecânica Central** | Aleatoriedade controlada — efeitos fortes com possibilidade de falha ou risco |
| **Dificuldade** | Intermediário (aleatoriedade exige adaptação constante) |

**Lore:**
> *"O trigo balança com o vento, mas quando a tempestade chega, até as montanhas tremem. Tempestade de Trigo é uma Weissbier imprevisível — refrescante como a brisa, mas com um trovão escondido. Quem prova, sente a energia do céu aberto."*

**Coerência com o estilo:** Weiss é efervescente, com perfil aromático variado dependendo do lote e temperatura — uma cerveja com "surpresas". A aleatoriedade mecânica do deck captura essa imprevisibilidade.

---

### Resumo rápido dos decks

| Deck | Estilo Cervejeiro | Arquétipo | Habilidade Passiva | Dificuldade |
|------|------|-----------|-------------------|-------------|
| Pacto das Sombras | Porter | Controlador | *Manto das Trevas* — compra se mão ≤ 3 | Intermediário |
| Sangue de Druida | Irish Red Ale | Conector | *Ciclo da Natureza* — cura 1 se jogar ≥ 2 cartas | Avançado |
| Elixir da Dríade | Session Juice IPA | Curativo | *Essência da Floresta* — compra 1 se curou no turno | Iniciante–Interm. |
| Orvalho de Valirian | Witbier | Ágil | *Primeiro Orvalho* — ação extra na 1ª carta | Iniciante |
| Juramento do Aventureiro | Amber Ale | Versátil | *Código do Aventureiro* — escolhe tipo com +1 | Intermediário |
| Tempestade de Trigo | Weiss | Imprevisível | *Fúria dos Ventos* — efeito aleatório no turno | Intermediário |

---

## 6. Regras Completas do Jogo

### 6.1 Objetivo e Preparação

**Objetivo:** Ser o último jogador com Pints de Glória acima de zero.

**Preparação:**
1. Cada jogador escolhe um deck (personagem) e o embaralha
2. Cada jogador compra 5 cartas da mão inicial
3. Todos os jogadores começam com **20 Pints de Glória** (marcados no contador de barril)
4. Determine a ordem dos turnos (sugestão: rolar o D20 Valirian — maior vai primeiro)

**Variação para Duelo (2 jogadores):** Cada jogador começa com **25 Pints de Glória** para partidas mais longas.

---

### 6.2 Estrutura do Turno

Cada turno segue esta sequência obrigatória:

**Passo 1 — Comprar**
No início do seu turno, compre 1 carta do seu baralho e adicione à mão.

**Passo 2 — Verificar Habilidade Passiva (pré-turno)**
Verifique se a condição da sua habilidade passiva foi atendida. Se sim, resolva-a agora.

**Passo 3 — Jogar Cartas**
Jogue 1 carta da mão (sua ação principal). Algumas habilidades permitem jogadas adicionais no mesmo turno. Você deve jogar pelo menos 1 carta por turno. Se a mão estiver vazia, compre 2 cartas imediatamente e jogue 1 delas.

**Passo 4 — Verificar Habilidade Passiva (pós-turno)**
Algumas habilidades se verificam no final do turno (ex.: Elixir da Dríade). Resolva-as agora.

**Passo 5 — Ajustar Mão**
Descarte cartas da mão até ter no máximo 5. Em seguida, compre cartas até atingir 5 na mão.

**Passo 6 — Passar a Vez**
O próximo jogador inicia seu turno.

---

### 6.3 Tipos de Cartas

O jogo possui 5 tipos de cartas, identificados por cor de borda:

#### 💥 Ataque — Borda Âmbar (#C8840A)
Causam dano (reduzem Pints de Glória do alvo). O jogador escolhe um alvo ao jogar. Se o alvo tiver Defesas ativas, o dano atinge as Defesas primeiro.

| Símbolo | Significado |
|---------|-------------|
| 💥 N | Causa N pontos de dano ao alvo escolhido |

#### 🛡️ Defesa — Borda Aço (#6B8FA8)
Ao jogar, a carta é colocada na mesa à frente do jogador (virada para cima). Ela permanece em jogo absorvendo dano até ser destruída. Use fichas para marcar os pontos de defesa consumidos. Quando todos os pontos forem consumidos, a carta vai para o descarte. Múltiplas defesas podem estar ativas simultaneamente — o jogador escolhe a ordem de absorção.

| Símbolo | Significado |
|---------|-------------|
| 🛡️ N | Absorve N pontos de dano antes de ser destruída |

**Dano excedente:** Se o dano superar a defesa ativa, o excedente passa para a próxima defesa (se houver) ou diretamente para os Pints de Glória do jogador.

#### 🌿 Cura — Borda Floresta (#1E3D1E)
Recuperam Pints de Glória. O limite máximo é sempre 20 Pints (ou 25 no modo Duelo). Cura não pode ultrapassar o máximo. Salvo indicação da carta, cura é aplicada ao próprio jogador.

| Símbolo | Significado |
|---------|-------------|
| 🌿 N | Recupera N Pints de Glória |

#### ✨ Habilidade — Borda Ouro (#C8A028)
Cartas com efeitos especiais que não se encaixam nas outras categorias. Podem comprar cartas, forçar descartes nos oponentes, manipular a pilha de descarte, causar dano em área, entre outros.

#### ⚡ Especial — Borda Chama (#D4520E)
Versões poderosas das outras categorias, sempre com custo ou condição especial para ser jogada. Exemplos: descarte adicional, dano próprio ao usar, só pode ser jogada com vida baixa. O custo deve ser pago mesmo se o efeito for menos útil do que o esperado.

#### 🔄 Permanentes
Algumas cartas têm o símbolo 🔄, indicando que ficam em campo além do turno em que foram jogadas (como as Defesas). A exceção é expressa no texto da carta.

---

### 6.4 Habilidades Passivas

Toda habilidade passiva:
- **Sempre ativa automaticamente** quando a condição é atendida
- Não pode ser ignorada ou escolhida pelo jogador — se a condição foi cumprida, o efeito acontece
- A verificação ocorre nos momentos especificados (início do turno, final do turno, após jogar uma carta específica)

| Personagem | Habilidade | Verificação |
|------------|------------|-------------|
| Pacto das Sombras | *Manto das Trevas*: se mão ≤ 3 cartas, compre 1 | Início do turno (Passo 2) |
| Sangue de Druida | *Ciclo da Natureza*: se jogou ≥ 2 cartas no turno, cure 1 | Final do turno (Passo 4) |
| Elixir da Dríade | *Essência da Floresta*: se curou alguém no turno, compre 1 | Final do turno (Passo 4) |
| Orvalho de Valirian | *Primeiro Orvalho*: a 1ª carta jogada não é a ação principal | Ao jogar a 1ª carta (Passo 3) |
| Juramento do Aventureiro | *Código do Aventureiro*: 1 tipo de carta escolhido tem +1 de efeito | Configuração (antes da partida) |
| Tempestade de Trigo | *Fúria dos Ventos*: role o dado e aplique o efeito correspondente | Início do turno (Passo 2) |

---

### 6.5 Regras Especiais

**Baralho vazio:** Se você precisar comprar uma carta e o baralho estiver vazio, embaralhe a pilha de descartes para formar um novo baralho e continue a compra normalmente.

**Mão cheia:** Você não pode ter mais de 5 cartas na mão antes do Passo 5. Se um efeito forçar a compra com a mão cheia, compre e descarte imediatamente até 5.

**Múltiplos alvos:** Cartas de área afetam todos os oponentes simultaneamente. O dano de área é calculado e aplicado a cada alvo separadamente, considerando as defesas individuais de cada um.

**Reações:** Cartas com indicação de "Reação" (bordas roxas, quando incluídas) podem ser jogadas fora do turno em resposta a ações adversárias. O texto da carta especifica quando a reação pode ser ativada.

**Interação entre Defesas:** Com múltiplas Defesas ativas, o jogador defensor escolhe qual absorve o dano primeiro. Essa escolha é feita no momento em que o dano é aplicado.

---

### 6.6 Condição de Vitória

O jogo termina quando apenas um jogador ainda tem Pints de Glória acima de zero. Esse jogador é declarado **Mestre da Taverna Valirian**.

**Empate:** Se uma carta causar dano suficiente para eliminar todos os jogadores restantes simultaneamente, a partida termina em empate. Todos brindam e preparam uma nova partida.

---

### 6.7 Glossário

| Termo | Definição |
|-------|-----------|
| **Pints de Glória** | Os pontos de vida/prestígio do jogador (máximo 20, ou 25 no Duelo) |
| **Nocauteado** | Quando um jogador chega a 0 Pints de Glória e é eliminado |
| **Mestre da Taverna** | Título do vencedor da partida |
| **Pilha de Descarte** | Onde cartas usadas são depositadas, viradas para cima |
| **Defesa Ativa** | Carta de Defesa em campo, aguardando dano para absorver |
| **Mão** | Cartas que o jogador segura; máximo de 5 |
| **Ação Principal** | A carta obrigatória jogada por turno (Orvalho de Valirian pode jogar uma anterior sem consumir a ação principal) |
| **Reação** | Carta jogada fora do próprio turno em resposta a uma ação adversária |

---

## 7. Deck Completo — MVP Pacto das Sombras

**Personagem:** Pacto das Sombras | **Estilo:** Porter | **Habilidade Passiva:** *Manto das Trevas*

### Lista de cartas (30 cartas)

#### 💥 Ataques — 14 cartas

| Qtd. | Nome | Efeito |
|------|------|--------|
| 3× | *Sombra Cortante* | Cause 2 de dano. Se você tiver 3 ou menos cartas na mão, cause +2 (total 4) |
| 3× | *Toque Sombrio* | Cause 3 de dano |
| 2× | *Dreno de Alma* | Cause 2 de dano. Cure 2 de vida |
| 2× | *Crepúsculo* | Cause 2 de dano em todos os oponentes |
| 2× | *Lâmina das Sombras* | Cause 4 de dano. Descarte 1 carta da mão após o uso |
| 2× | *Espectro Voraz* | Cause 3 de dano. Se o oponente tiver 10 ou menos de vida, cause +2 (total 5) |

#### 🛡️ Defesas — 5 cartas

| Qtd. | Nome | Efeito |
|------|------|--------|
| 2× | *Manto da Noite* | 🛡️×3 (absorve 3 dano). No próximo turno, compre 1 carta |
| 2× | *Abismo* | 🛡️×2 (absorve 2 dano). Se você tiver 10 ou menos de vida, absorve +2 (total 4) |
| 1× | *Escuridão Protetora* | 🛡️×4 (absorve 4 dano). Quando destruída, cause 1 de dano ao atacante |

#### 🌿 Curas — 3 cartas

| Qtd. | Nome | Efeito |
|------|------|--------|
| 2× | *Regeneração Sombria* | Cure 3 de vida. Se você tiver 3 ou menos cartas na mão, cure +2 (total 5) |
| 1× | *Pacto de Sangue* | Cure 5 de vida. Você sofre 1 de dano |

#### ✨ Habilidades — 6 cartas

| Qtd. | Nome | Efeito |
|------|------|--------|
| 2× | *Pacto Selado* | Compre 2 cartas. Depois, descarte 1 carta da mão |
| 2× | *Sussurros* | Olhe a mão de um oponente. Escolha 1 carta para ele descartar |
| 1× | *Necromancia* | Pegue 1 carta da sua pilha de descartes e coloque na mão |
| 1× | *Espiral das Sombras* | Todos os oponentes descartam 1 carta |

#### ⚡ Especiais — 2 cartas

| Qtd. | Nome | Efeito |
|------|------|--------|
| 1× | *Eclipse* | Cause 4 de dano em todos os oponentes. Descarte sua mão após o uso |
| 1× | *Último Pacto* | Cause 6 de dano. Você sofre 2 de dano. Só pode usar se tiver 5 ou menos de vida |

### Distribuição por tipo

| Tipo | Qtd. | % |
|------|------|---|
| Ataque | 14 | 47% |
| Defesa | 5 | 17% |
| Cura | 3 | 10% |
| Habilidade | 6 | 20% |
| Especial | 2 | 6% |

### Guia de estratégia

**Início do jogo (20–15 Pints):** Estabeleça controle. Use *Sussurros* para forçar descartes nos oponentes. *Pacto Selado* ajuda a filtrar a mão enquanto ativa a passiva se você ficar com 3 ou menos cartas.

**Meio do jogo (14–8 Pints):** Mantenha a mão propositalmente baixa para ativar *Manto das Trevas*. *Dreno de Alma* sustenta sua vida enquanto ataca. Construa vantagem de mão sobre os adversários.

**Fim do jogo (7–0 Pints):** Guarde *Eclipse* para quando múltiplos oponentes estiverem vulneráveis. *Último Pacto* é o golpe final definitivo — use apenas com vida baixa, pois o custo de 2 de dano próprio pode ser fatal se mal calculado.

---

## 8. Deck Completo — MVP Sangue de Druida

**Personagem:** Sangue de Druida | **Estilo:** Irish Red Ale | **Habilidade Passiva:** *Ciclo da Natureza*

### Lista de cartas (30 cartas)

#### 💥 Ataques — 10 cartas

| Qtd. | Nome | Efeito |
|------|------|--------|
| 3× | *Garra do Lobo* | Cause 2 de dano. Se você já jogou outra carta neste turno, cause +1 (total 3) |
| 3× | *Investida do Urso* | Cause 3 de dano. Se você já jogou 2 ou mais cartas neste turno, cause +2 (total 5) |
| 2× | *Toque da Vida* | Cause 2 de dano. Cure 1 de vida |
| 2× | *Eco da Floresta* | Cause 2 de dano em todos os oponentes. Cure 1 de vida |

#### 🛡️ Defesas — 5 cartas

| Qtd. | Nome | Efeito |
|------|------|--------|
| 2× | *Escudo de Casca* | 🛡️×3 (absorve 3 dano). Ao ser destruído, cure 1 de vida |
| 2× | *Muralha de Espinhos* | 🛡️×2 (absorve 2 dano). Ao ser destruído, cause 1 de dano ao atacante |
| 1× | *Raiz Anciã* | 🛡️×4 (absorve 4 dano). Permanente até ser destruído |

#### 🌿 Curas — 7 cartas

| Qtd. | Nome | Efeito |
|------|------|--------|
| 2× | *Seiva Curativa* | Cure 3 de vida |
| 2× | *Círculo de Renovação* | Cure 2 de vida em si mesmo e em um aliado (se em modo multiplayer) |
| 2× | *Bênção da Floresta* | Cure 1 de vida. Compre 1 carta |
| 1× | *Espírito da Floresta* | Cure 5 de vida |

#### ✨ Habilidades — 6 cartas

| Qtd. | Nome | Efeito |
|------|------|--------|
| 2× | *Ciclo das Estações* | Compre 2 cartas. Depois jogue 1 carta adicional neste turno |
| 2× | *Comunhão com a Natureza* | Olhe as 3 cartas do topo do baralho. Coloque 1 na mão e as demais de volta em qualquer ordem |
| 1× | *Pacto Druídico* | Recupere 1 carta do descarte e jogue-a imediatamente |
| 1× | *Lamento da Floresta* | Todos os oponentes perdem 1 carta da mão. Você compra 1 carta |

#### ⚡ Especiais — 2 cartas

| Qtd. | Nome | Efeito |
|------|------|--------|
| 1× | *Fúria Primal* | Jogue mais 1 carta neste turno. Todos os seus ataques neste turno causam +1 de dano |
| 1× | *Despertar da Floresta* | Cause 3 de dano a um oponente. Cure 3 de vida. Compre 1 carta |

### Distribuição por tipo

| Tipo | Qtd. | % |
|------|------|---|
| Ataque | 10 | 33% |
| Defesa | 5 | 17% |
| Cura | 7 | 23% |
| Habilidade | 6 | 20% |
| Especial | 2 | 7% |

### Guia de estratégia

**Início do jogo:** Estabeleça o ritmo de jogo. Tente jogar 2 cartas por turno para ativar *Ciclo da Natureza* desde cedo. *Comunhão com a Natureza* ajuda a filtrar o baralho para encontrar as peças dos combos.

**Meio do jogo:** Com a passiva ativando consistentemente, você terá uma recuperação constante de vida. Use *Fúria Primal* com cuidado — é o "multiplicador" do deck quando você tem 3 cartas úteis na mão.

**Fim do jogo:** Seu deck não tem os "one-shot killers" do Pacto das Sombras, mas sua consistência garante chegada ao final em melhor estado. *Despertar da Floresta* é o encerramento ideal — ataque, cure e recarregue a mão em uma jogada.

---

## 9. Comparação e Balanceamento — Análise dos Decks MVP

| Aspecto | Pacto das Sombras | Sangue de Druida |
|---------|-------------------|------------------|
| **Arquétipo** | Controlador | Conector |
| **Estilo Cervejeiro** | Porter | Irish Red Ale |
| **Foco principal** | Controle de mão, descartes | Combos, sequências, cura |
| **Habilidade passiva** | Compra se mão ≤ 3 | Cura se jogar ≥ 2 cartas |
| **Ataque médio** | 2–4 de dano | 2–3 dano base (com bônus de combo) |
| **Cura total** | 3 cartas (fraca) | 7 cartas (forte) |
| **Defesa total** | 5 cartas (média) | 5 cartas (média) |
| **Controle** | Alto — força descartes | Baixo — pouca interação direta |
| **Complexidade** | Média (gestão de mão baixa) | Alta (gestão de sequências) |
| **Dificuldade** | Intermediário | Avançado |

### Análise de matchup (1v1)

| Cenário | Análise |
|---------|---------|
| Sangue de Druida ataca | Precisa de 2 cartas/turno para ativar a cura. Se Pacto usar *Sussurros* para forçar descartes, os combos são quebrados antes de começarem |
| Pacto das Sombras ataca | Força descartes e controla o ritmo. Sangue de Druida precisa manter mão cheia para combos — perder cartas-chave é fatal |
| Equilíbrio geral | Partida estrategicamente equilibrada. Pacto controla o ritmo; Druida precisa ignorar o controle e manter o loop de combos. Quem impuser seu ritmo primeiro tende a vencer |

### Pontos fortes e fracos

**Pacto das Sombras:**
- Forte em controle de mão adversária e late game explosivo
- Fraco em cura e sustento — poucos recursos de recuperação

**Sangue de Druida:**
- Forte em cura constante e versatilidade de combos
- Fraco contra controle de mão — quebrar o combo desorganiza todo o deck

---

## 10. Modos de Jogo

### 10.1 Duelo — 2 Jogadores

O modo clássico 1v1. Cada jogador começa com **25 Pints de Glória** para partidas mais longas. O primeiro a nocautear o oponente vence. Ideal para testar estratégias e aprender os decks em profundidade.

### 10.2 Batalha da Taverna — 3 a 4 Jogadores

Todos contra todos. Último de pé vence. Todos começam com **20 Pints de Glória**.

**Regra adicional — Favor da Taverna:** Ao ser nocauteado, o jogador pode escolher um sobrevivente e dar a ele 1 carta aleatória da mão como "favor". Isso mantém os jogadores eliminados engajados e cria alianças táticas informais.

### 10.3 Festa da Colheita — 5 a 6 Jogadores

Jogo rápido com todos contra todos. Todos começam com **20 Pints de Glória**.

**Regra adicional — Recompensa do Caçador:** Ao nocautear um oponente, o jogador vencedor cura **2 Pints de Glória**. Incentiva agressividade e turnos rápidos.

### 10.4 A Ira do Barril Amaldiçoado — Modo Cooperativo (Expansão Futura)

Todos os jogadores contra um "Chefão" controlado por um deck especial. A cada rodada, o Chefão executa uma ação pré-programada que afeta todos os jogadores. Vitória se o grupo sobreviver por **10 rodadas** ou se causar dano coletivo suficiente para zerar os Pints do Chefão.

Este modo é indicado como expansão após a validação do jogo base, pois exige desenvolvimento de um deck separado para o Chefão.

---

## 11. Direção Visual do Jogo

### Identidade visual aplicada ao jogo

| Elemento | Especificação |
|----------|---------------|
| **Ilustração dos personagens** | Versão de combate dos personagens dos rótulos; mesmo estilo *Realismo Narrativo com influência fantástica* da linha de cervejas |
| **Verso das cartas** | Logo Valirian central, fundo Tinta das Sombras (#120E06), borda Âmbar (#C8840A) |
| **Bordas por tipo** | 💥 Ataque: Âmbar / 🛡️ Defesa: Aço Encantado / 🌿 Cura: Floresta Profunda / ✨ Habilidade: Ouro da Coroa / ⚡ Especial: Chama da Forja |
| **Tipografia** | Títulos de cartas: Cinzel Decorative / Textos de efeito: Lora / Microtextos: Cinzel |
| **Arte da caixa** | Os 6 personagens sentados ao redor de uma mesa de taverna, cada um com sua caneca — arte panorâmica no estilo épico-narrativo |
| **Manual** | Diagramado com a identidade visual da marca, com linguagem narrativa em todo o texto de regras |

### Paleta de cores do jogo

| Cor | Hex | Uso |
|-----|-----|-----|
| Âmbar do Mestre | #C8840A | Bordas de ataque, destaques principais |
| Chama da Forja | #D4520E | Bordas de cartas especiais |
| Floresta Profunda | #1E3D1E | Bordas de cura |
| Aço Encantado | #6B8FA8 | Bordas de defesa |
| Ouro da Coroa | #C8A028 | Bordas de habilidade |
| Pergaminho | #F5E6C8 | Textos principais nas cartas |
| Tinta das Sombras | #120E06 | Fundo das cartas, caixa |

### Brief para ilustradores — Estilo das cartas

Cada carta deve seguir o mesmo padrão visual dos rótulos: **Realismo Narrativo com influência fantástica**. As artes de cartas são cenas em miniatura — não ícones ou símbolos, mas momentos dramáticos do universo do personagem. Iluminação realista, textura rica, composição com profundidade. O fantástico aparece como detalhe, não como protagonista visual.

---

## 12. Componentes e Box Colecionador

### Conteúdo do Box Edição do Aventureiro

| Item | Descrição | Qtd. |
|------|-----------|------|
| Decks de cartas | 30 cartas por personagem, em sleeves individuais | 6 decks |
| Cartas (total) | 180 cartas | 180 |
| Marcadores de Pints | Formato de barril de madeira miniatura, 20 posições | 6 |
| Manual Ilustrado | 32 páginas, regras + lore de cada personagem + galeria de cartas | 1 |
| D20 Valirian | Dado de vinte faces temático com logo Valirian | 1 |
| Cartas de Referência | Resumo de regras por personagem, frente e verso | 6 |
| Box externo | Caixa rígida com fecho magnético, arte épica da taverna | 1 |

### Estrutura interna da caixa

```
[BOX EXTERNO]
├── Tampa: arte panorâmica da Taverna Valirian com os 6 personagens
├── Corpo: 6 compartimentos para decks individuais
├── Espaço central para componentes (marcadores, dado, cartas de referência)
└── Fecho magnético lateral

[CONTEÚDO INTERNO]
├── 6 Decks (cada um em sleeve com arte do personagem)
├── 6 Marcadores de Barril (com trilho de 20 posições)
├── 1 D20 Valirian
├── 1 Manual Ilustrado (32 páginas)
└── 6 Cartas de Referência Rápida
```

### Estrutura do Manual Ilustrado (32 páginas)

| Seção | Páginas | Conteúdo |
|-------|---------|----------|
| Abertura | 2 | "Bem-vindo à Taverna Valirian" — introdução narrativa e contextualização |
| Regras Básicas | 6 | Como jogar com diagramas visuais e exemplo de turno ilustrado |
| Os Personagens | 12 | 2 páginas por personagem: lore + arte + tabela de cartas especiais |
| Galeria de Cartas | 4 | As cartas mais icônicas de cada deck com arte em tamanho maior |
| Modos de Jogo | 4 | Explicação visual de cada modo (Duelo, 3–4, 5–6, Cooperativo) |
| Créditos | 2 | Ilustradores, equipe, agradecimentos, número de versão |
| Fichas de Feedback | 2 | Para jogadores registrarem experiências (edições de lançamento) |

---

## 13. Alinhamento com a Identidade Valirian

O jogo é uma extensão de produto — não um produto separado. Cada decisão de design do jogo deve ser avaliada contra os pilares da marca.

| Pilar Valirian | Como o Jogo Atende |
|----------------|-------------------|
| **Técnica** | Mecânica testada, balanceada e divertida — o jogo em si é um produto de qualidade |
| **Narrativa** | Cada deck tem lore própria, coerente com o rótulo e o estilo cervejeiro |
| **Exclusividade** | Edição limitada, produto colecionável que valoriza quem já tem as cervejas |
| **Cerveja em Primeiro** | O jogo existe para celebrar os rótulos — nunca para substituí-los ou eclipsá-los |
| **Realismo Narrativo** | A direção visual das cartas segue o mesmo conceito "Fantasia Ancorada no Real" dos rótulos |

### Regra de ouro do projeto

> *"O deck não existe sem o rótulo. Cada partida é uma celebração das cervejas Valirian — nunca um produto separado ou concorrente."*

---

## 14. Estratégia de Lançamento

### Edições

| Edição | Conteúdo | Tiragem | Preço Sugerido |
|--------|----------|---------|----------------|
| **Edição do Aventureiro** | Box completo com 6 decks + todos os componentes | 500 unidades | R$ 249–299 |
| **Decks Avulsos** | Cada deck individual (para completar ou testar) | 200 por deck | R$ 49–59 |

### Público-alvo e canais

| Segmento | Canal | Estratégia |
|----------|-------|------------|
| Clientes Valirian | Direto (eventos, loja online) | Pré-venda exclusiva para comunidade |
| Colecionadores de card games | Grupos de board games, BGG Brasil | Demonstrações e resenhas |
| Público de RPG e fantasia | Lojas especializadas, feiras de RPG | Parceria com distribuidores |
| Eventos de cerveja artesanal | Festivais, degustações | Demonstração ao vivo do jogo |

### Expansões futuras (após validação)

- **Novos personagens:** Cervejas do portfólio ainda não incluídas (Fafnir, Nefertari, Elixir da Dríade expandido, etc.)
- **Modo Cooperativo:** Deck do Chefão — "A Ira do Barril Amaldiçoado"
- **Edições Sazonais:** Decks temáticos vinculados a lançamentos especiais da cervejaria
- **Cartas Promo:** Distribuídas em eventos e com compra de cervejas — incentivo de colecionabilidade

---

## 15. Estimativa de Custos

| Item | Descrição | Custo Estimado (R$) |
|------|-----------|---------------------|
| Arte | 6 ilustrações principais de personagens + artes de cartas | 3.000–6.000 |
| Design Gráfico | Layout de cartas, manual, box, cartas de referência | 2.000–3.500 |
| Produção (500 unidades) | Cartas, box rígido, manual, componentes (marcadores, dado) | 15.000–25.000 |
| Frete e Armazenamento | Distribuição inicial | 2.000–4.000 |
| Marketing | Material promocional, eventos, vídeos | 1.500–3.000 |
| **Total Estimado** | | **23.500–41.500** |

> *Nota: Produção menor (100–200 unidades) eleva o custo unitário mas reduz o investimento inicial. Recomendado como opção de validação antes de escalar.*

### Break-even estimado

Com tiragem de 500 unidades e preço médio de R$ 270 (Edição do Aventureiro):
- Receita potencial: R$ 135.000
- Investimento: ~R$ 32.000 (ponto médio)
- Margem potencial: ~76%

---

## 16. Roteiro de Desenvolvimento

### Fase 1 — Validação do Conceito (Semanas 1–2)
- Aprovação deste GDD
- Prototipagem física dos 2 decks MVP (impressão caseira ou gráfica rápida)
- Primeiros playtest internos com equipe e amigos próximos
- Coleta de feedback inicial sobre regras e mecânicas

### Fase 2 — Ajuste e Expansão dos Decks (Semanas 3–6)
- Refinamento dos 2 decks MVP com base no feedback
- Confirmação definitiva das regras
- Desenvolvimento dos outros 4 decks (Elixir da Dríade, Orvalho, Juramento, Tempestade)
- Teste com 3–4 jogadores para validar dinâmica de grupo

### Fase 3 — Arte e Design (Semanas 7–14)
- Contratação de ilustrador (brief baseado neste GDD, seção 11)
- 6 ilustrações principais de personagens
- Design de todas as cartas (tipografia, bordas, ícones, efeitos)
- Diagramação do manual ilustrado
- Arte da caixa (cena panorâmica da taverna)

### Fase 4 — Produção (Semanas 15–20)
- Orçamento e negociação com gráficas/produtores de jogos
- Produção dos boxes, cartas, marcadores e dado
- Revisão final do material antes da impressão
- Aprovação de amostra física antes da tiragem completa

### Fase 5 — Lançamento (Semanas 21–24)
- Pré-venda para membros da comunidade Valirian (2 semanas antes)
- Lançamento com evento temático (degustação + jogo ao vivo)
- Distribuição para canais parceiros
- Campanha de redes sociais com unboxings e partidas ao vivo

### Cronograma resumido

| Fase | Atividade | Prazo |
|------|-----------|-------|
| 1 | Aprovação + prototipagem MVP | 2 semanas |
| 2 | Ajuste de mecânicas + 6 decks completos | 4 semanas |
| 3 | Arte, design e diagramação | 7 semanas |
| 4 | Produção física | 6 semanas |
| 5 | Lançamento | 2 semanas |
| **Total** | | **~21 semanas (~5 meses)** |

---

## 17. MVP — Plano de Testes e Validação

O MVP consiste nos **2 decks definidos neste GDD** (Pacto das Sombras e Sangue de Druida). Com eles, é possível validar as mecânicas centrais antes de comprometer recursos com os outros 4 decks.

### O que testar

| Área | Perguntas de validação |
|------|----------------------|
| **Equilíbrio** | Os 2 decks estão balanceados? Quem vence mais? As partidas são equilibradas ou um deck domina? |
| **Mecânicas** | As habilidades passivas ativam com frequência adequada? Os combos de Sangue de Druida são funcionais? O controle de Pacto das Sombras é relevante mas não frustrante? |
| **Clareza** | As regras são claras sem o manual? As cartas são autoexplicativas? |
| **Tempo** | As partidas duram 15–30 minutos como projetado? |
| **Identidade** | O deck captura a personalidade da cerveja correspondente? Um conhecedor da Valirian reconhece a coerência? |
| **Diversão** | Os jogadores querem jogar novamente? Há sensação de "mais uma partida"? |

### Ficha de feedback para testadores

| Pergunta | Pacto das Sombras | Sangue de Druida |
|----------|-------------------|------------------|
| Partidas jogadas | | |
| Vitórias | | |
| O deck pareceu equilibrado? | Sim / Não | Sim / Não |
| A habilidade passiva ativou com frequência? | | |
| Alguma carta pareceu forte demais? | | |
| Alguma carta pareceu fraca demais? | | |
| O deck captura a essência da cerveja? | Sim / Não | Sim / Não |
| Qual deck foi mais divertido de jogar? | | |
| Sugestões de ajuste | | |

### Critérios de aprovação do MVP

Para avançar para a Fase 2 (desenvolvimento dos outros 4 decks), os critérios mínimos são:
- Equilíbrio: nenhum deck vence mais de 65% das partidas em testes com 10+ jogadores
- Clareza: menos de 20% dos jogadores têm dúvidas de regras durante a partida
- Tempo: 90% das partidas duram entre 15 e 35 minutos
- Diversão: 80%+ dos testadores querem jogar novamente

---

## 18. Próximos Passos para Aprovação

Este documento está pronto para revisão e aprovação. Os próximos passos após aprovação são:

| Etapa | Ação | Responsável |
|-------|------|-------------|
| 1 | Aprovação deste GDD — conceito, decks, regras e escopo | Equipe Valirian |
| 2 | Prototipagem física dos 2 decks MVP para playtest | Equipe |
| 3 | Execução de sessões de teste com 6–10 jogadores | Equipe + comunidade |
| 4 | Revisão de equilíbrio e regras com base no feedback | Equipe |
| 5 | Desenvolvimento dos 4 decks restantes | Equipe |
| 6 | Brief e contratação de ilustrador para as 6 artes principais | Equipe + Ilustrador |
| 7 | Finalização de design gráfico e diagramação do manual | Designer |
| 8 | Orçamento com fornecedores (cartas, box, componentes) | Equipe |
| 9 | Campanha de pré-venda para comunidade Valirian | Marketing |
| 10 | Lançamento oficial | Todos |

---

*Documento preparado para aprovação e início de desenvolvimento.*
*Fermento & Honra — O Duelo das Tavernas*
*Cervejaria Valirian · contato@valirian.com.br · @nanocervejariavalirian*
