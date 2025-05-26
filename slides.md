# Comunicação Organizacional

> Apresentação do projeto

---

## Introdução
- Criação de **jogos de cartas autorais**, explorando e reinterpretando mecânicas clássicas.
- Inspirações:
    - Blackjack
    - Pôquer
    - Truco 
- Apresentação de **dois projetos distintos**:
    - **Blackjack Arcano:** releitura solo, estratégica e dinâmica do blackjack.
    - **Bravata:** jogo competitivo em duplas com foco em estratégia e risco.

--- 

## Objetivo

- Mostrar como elementos tradicionais podem ser reinventados:
    - ✅ Mantendo a familiaridade
    - ✅ Introduzindo inovação em novos contextos lúdicos

---

# Blackjack Arcano

---

## Introdução

- Jogo de cartas simples e estratégico:
    - Inspirado no **blackjack** e no **pôquer**.
    - Cartas com **efeitos especiais**.
    - Desktop (**Windows/Linux/Mac**).

---

## Objetivos

- Somar o mais próximo possível de **33 pontos**.
- Formar **combinações** para ganhar **bônus de pontuação**.
- Ganhar **apostas**.
- Usar os **efeitos especiais** das cartas a seu favor.

> A rodada termina quando:
>
> - O jogador decide "parar" (**stand**).
>
> - Ultrapassa 33 pontos (**estouro**).

---

## Diferenças

- **33 pontos**, em vez de **21**.
- **Combinações** também contribuem para a pontuação final.
- É possível:
    - **Apostar** em uma **combinação**.
    - **Devolver** um **número limitado de cartas**.
- Não é possível:
    - Opção **"Seguro"**.
    - Mais de cinco cartas na mão.
    - Ver cartas do dealer.
- Utiliza-se um **baralho de tarô**, em vez do tradicional **baralho francês**.

---

## Baralho de Tarô

- **Arcanos Menores**:
    - Cartas **numéricas** (2-10).
    - **Ás**.
    - **Valete**, **Cavaleiro**, **Rainha** e **Rei**.
- **Arcanos Maiores**:
    - **O Mago**, **A Morte**, **O Diabo**, etc.
    - Ativam **efeitos especiais**.

---

## Valor das Cartas

- Cartas **numéricas**:
    - Valor igual ao número que representam.
- **Ás**:
    - **1 ponto** ou **11 pontos**.
- **Valete**, **Cavaleiro**, **Rainha** e **Rei**:
    - **10 pontos** cada.
- **Arcanos Maiores**:
    - Sem valor

---

## Alguns Arcanos Maiores

| Nº    | Arcano Maior          | Efeito Especial                                                                                                                                                     | Ativação   |
| ----- | --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- |
| I     | **O Mago**            | Canalize sua vontade: escolha um valor entre 2 e 5 para receber um **buff** na pontuação.                                                                           | Voluntária |
| II    | **A Sacerdotisa**     | Com um olhar além do véu, revele as três cartas seguintes, vislumbrando o futuro.                                                                                   | Voluntária |
| III   | **A Imperatriz**      | Dissipe os **debuffs** e ignore o estouro desta rodada como um gesto de graça.                                                                                      | Voluntária |
| VIII  | **A Justiça**         | A balança da equidade pesa: se a diferença entre sua pontuação e a do dealer for de até 3 pontos, a vitória é compartilhada.                                        | Automática |
| X     | **A Roda da Fortuna** | O destino gira: dobre sua aposta em vitória, dobre-a em derrota ou sofra um **debuff** de 5 pontos.                                                                 | Automática |
| XII   | **O Enforcado**       | Em um sacrifício, receba 3 pontos de **debuff** e substitua toda a sua mão por duas novas cartas.                                                                   | Voluntária |
| XIII  | **A Morte**           | Devolva três cartas aleatórias da sua mão ao baralho, encerrando um ciclo. Se não houver cartas suficientes, receba um **debuff** de 5 pontos.                      | Voluntária |
| XV    | **O Diabo**           | Ousada escolha: dobre sua aposta em vitória, mas pague o triplo em derrota, ou receba um **buff** ou **debuff** aleatório entre -10 e +20 pontos.                   | Voluntária |
| XVIII | **A Lua**             | Sob o véu do mistério, repita o efeito do último Arcano Maior ativado. Se nenhum efeito anterior ocorreu, o destino decide: vitória ou derrota, guiados pela sorte. | Automática |

---

## Combinações

| Combinação           | Requisitos                                      | Bônus de Pontuação | Multiplicador (em aposta) |
| -------------------- | ----------------------------------------------- | ------------------ | ------------------------- |
| **Par**              | Duas cartas do mesmo valor.                     | +1 pontos          | x1.25                     |
| **Trinca**           | Três cartas do mesmo valor.                     | +3 pontos          | x3                        |
| **Sequência**        | Três cartas em sequência.                       | +2 pontos          | x1.5                      |
| **Cor**              | Três cartas do mesmo naipe.                     | +2 pontos          | x1.5                      |
| **Sequência de Cor** | Três cartas em sequência do mesmo naipe.        | +4 pontos          | x4                        |

---

## Hierarquia para as combinações:

| Carta      | Valor ordinal (para combinações) |
| ---------- | -------------------------------- |
| Ás         | 1.                               |
| 2–10       | 2 a 10.                          |
| Valete     | 11.                              |
| Cavaleiro  | 12.                              |
| Rainha     | 13.                              |
| Rei        | 14.                              |
| Ás         | 15.                              |

---

## Apostas
- Aposte em uma única **combinação**:
    - **Antes** de completar a combinação.
    - Receba um **multiplicador de retorno**.
    - Acumulam com **A Roda da Fortuna** ou **O Diabo**.

---

## Como Jogar
1. O jogador realiza sua **aposta inicial**.
2. As cartas são **embaralhadas**.
3. O jogador e o dealer recebem **duas cartas** cada.

---

4. O jogador escolhe entre as seguintes opções:
    - **Bet**: Apostar em uma combinação de par, trinca, sequência, cor ou sequência de cor.
    - **Hit**: Comprar uma carta.
        - O jogador pode ter até cinco cartas na mão. 
    - **Drop**: Descartar uma carta.
        - O jogador pode descartar até cinco cartas por rodada. 
    - **Spell**: Usar um Arcano Maior de ativação voluntária.
        - A carta utilizada será devolvida ao baralho. 
        - É permitido usar no máximo três arcanos por rodada.
    - **Stand**: Manter a mão atual.

---

5. Se o jogador **estourar** (ultrapassar 33 pontos), sofrerá **derrota imediata**.
6. Se o jogador escolher **Stand**, o dealer continuará comprando cartas até atingir, no mínimo, 27 pontos.
7. Se o dealer **estourar**, o jogador conquista **vitória imediata**.
8. Caso contrário, as pontuações são comparadas e vence quem tiver a **maior pontuação**.

> O dealer **não** pode comprar **Arcanos Maiores**.

---

# Bravata

---

## Introdução

- Jogo de cartas com apostas, inspirado em **canastra**, **pôquer** e **truco paulista**.  
- Para **2 ou 4 jogadores** (mano a mano ou em duplas).  
- Disputado em **melhor de três rodadas**.  
- Público-alvo: geral (**classificação livre**).  
- Disponível para **desktop** e **dispositivos móveis**.

---

## Objetivo

- Vence a partida quem conquistar **duas rodadas**.  
- Vence a rodada quem acumular **1000 pontos de Prestígio**.  
- A rodada termina quando um jogador **bate** (fica sem cartas).  
  Em seguida, as cartas são redistribuídas e uma nova rodada começa.

---

## Como jogar

---

### Baralho utilizado

- Utiliza dois **baralhos de tarô europeu** (total: **156 cartas**):  
  - **Cartas comuns** (56 por baralho):  
    - Naipes: Paus, Copas, Espadas e Ouros.  
    - Cartas: Ás, 2–7, Cavaleiro, Valete, Dama e Rei.  
  - **Trunfos** (22 por baralho):  
    - Cartas: *Excuse* (O Louco, ou *Le Mat*), 1-21.  
- As cartas **8, 9 e 10** são **removidas**.

---

### Glossário
- **Prestígio** – Pontos obtidos pelas combinações.  
- **Mão** – Uma combinação de cartas.  
- **Morto** – 11 cartas extras reservadas para quem bate.  
- **Vira** – Primeira carta revelada após a distribuição.  
- **Manilha** – Carta seguinte à vira; vale mais Prestígio e funciona como coringa nas cartas comuns.  
- **Limpa** – Combinação sem manilha (cartas comuns) ou *excuse* (trunfos).  
- **Suja** – Combinação com manilha (cartas comuns) ou *excuse* (trunfos).

---

### Distribuição de cartas
1. Cada jogador recebe **11 cartas**.  
2. É separado um **morto** para cada jogador (1x1) ou dupla (2x2).  
3. A carta imediatamente após a distribuição é a **vira**, que define a **manilha**.
4. Caso a vira seja um trunfo, devolva-a ao baralho e revele uma nova vira, repetindo o processo até obter uma vira válida.
5. A próxima carta do baralho inicia a **pilha de descarte**.

> **Nota:** Em duplas, os parceiros **compartilham** combinações e Prestígio.

---

### Dinâmica dos turnos
1. No início do turno, o jogador **compra uma carta**.
2. Durante o turno, o jogador pode executar as seguintes ações:
  - **a) Jogar combinações.**  
  - **b) Bravata!**  
  - **c) Correr!**  
3. Ao final do turno, o jogador **descarta uma carta**, encerrando seu turno.

> O jogador pode comprar cartas do baralho ou da pilha de descarte.

---

#### a) Jogar combinações
- Pode jogar até **três mãos** no turno. 
    - Deve **comprar uma carta** para cada mão jogada (exceto ao **bater**).
    - No máximo **uma mão com trunfo** (trunfos ativam efeitos especiais).
- Pode utilizar **cartas altas de turnos anteriores** para compor uma mão.

---

#### b) Bravata!
- Faz a próxima rodada valer **1,5×** para quem declarou.
- Caso o jogador (ou a dupla) perca a rodada, o bônus é transferido ao adversário.  
- O jogador (ou a dupla) fica impedido de bravatear na rodada seguinte.

---

#### c) Correr!
- Faz a próxima rodada valer **0,5×** para quem declarou.

---

## Cartas comuns: ordem e valor

- A ordem das cartas comuns segue a do truco, com a adição do **Cavaleiro**.  
- A **Manilha** funciona como um coringa — portanto, sua posição na ordem não importa.

---

| Cartas                       | Prestígio |
|------------------------------|-----------|
| 4, 5, 6, 7                   | +5        |
| Cavaleiro, Dama, Valete, Rei | +10       |
| Ás, 2, 3                     | +15       |
| **Manilha**                  | +20       |

---

## Combinações: cartas comuns

- As combinações válidas com cartas comuns seguem as regras do pôquer.

---

| Combinação      | Limpa | Suja |
|-----------------|-------|------|
| Carta Alta      | 0     | 0    |
| Par             | +5    | 0    |
| Dois Pares      | +10   | +5   |
| Trinca          | +15   | +10  |
| Sequência       | +20   | +15  |
| Flush           | +25   | +20  |
| Full House      | +30   | +25  |
| Quadra          | +40   | +35  |
| Straight Flush  | +45   | +40  |
| Royal Flush     | +50   | +45  |

---

## Trunfos: efeitos e valor

- Cada trunfo tem um efeito especial e um valor em Prestígio.

---

| Carta                  | Efeito Especial                                                    | Prestígio |
|------------------------|--------------------------------------------------------------------|-----------|
| 0 (Excuse)             | Anule o efeito de Bravata! ou Correr! nessa rodada.                | 0         |
| 1 (O Mago)             | Anule o Prestígio de uma combinação do adversário.                 | +5        |
| 2 (A Sacerdotisa)      | Espie as três primeiras cartas do baralho.                         | +5        |
| 3 (A Imperatriz)       | Compre três cartas.                                                | +5        |
| 4 (O Imperador)        | Impeça o adversário de usar trunfos no próximo turno.              | +5        |
| 5 (O Papa)             | Permite jogar mais duas mãos com trunfo nesse turno.               | +5        |
| 6 (Os Amantes)         | Troque uma carta com seu parceiro.                                 | +5        |
| 7 (O Carro)            | Jogue outro turno.                                                 | +5        |
| 8 (A Justiça)          | Ganhe +50 de Prestígio se a pontuação do adversário for superior.  | +10       |
| 9 (O Eremita)          | Espie a mão de um oponente.                                        | +10       |
| 10 (A Roda da Fortuna) | Efeito aleatório: +100 Prestígio ou -100 Prestígio.                | +10       |
| 11 (A Força)           | Permite jogar uma mão a mais.                                      | +10       |
| 12 (O Enforcado)       | Descarte três cartas.                                              | +10       |
| 13 (A Morte)           | Troque suas cartas pelas do morto. Sem efeito se não houver morto. | +10       |
| 14 (A Temperança)      | Troque três cartas de sua mão.                                     | +10       |
| 15 (O Diabo)           | Roube três cartas do adversário.                                   | +15       |
| 16 (A Torre)           | Todos descartam três cartas aleatórias.                            | +15       |
| 17 (A Estrela)         | Adicione um multiplicador de 1,5× para as combinações nesse turno. | +15       |
| 18 (A Lua)             | Ativa um efeito de um trunfo aleatório.                            | +15       |
| 19 (O Sol)             | Espie a mão de seu parceiro.                                       | +15       |
| 20 (O Julgamento)      | Desmonte uma combinação em cartas altas.                           | +15       |
| 21 (O Mundo)           | Revive o morto.                                                    | +15       |

---

## Combinações: trunfos

- A única combinação permitida com trunfos é **carta alta**.

---

Obrigado pela atenção!
