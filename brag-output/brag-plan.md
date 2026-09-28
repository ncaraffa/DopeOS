# Brag Plan: DopeOS

## What is this app?
Um jogo mobile em Flutter em que o celular é o próprio jogo: um sistema operacional fictício com feed de vídeos (Loop), chat com personagens, economia virtual e um algoritmo adaptativo que aprende com o jogador.

## The angle
O vídeo É o celular do DopeOS ligando e, cena a cena, disputando a sua atenção: boot → tela de bloqueio lotada de notificações → home → rolagem no Loop → um personagem que lembra do que você curtiu → o Screen Time revelando o que o algoritmo aprendeu. Fecha com a frase do projeto: "O celular é o jogo. A sua atenção move o mundo."

## Hook (first 2-3 seconds)
Tela preta-roxa, a cápsula do logo acende com brilho e uma barra de boot enche; a frase "O celular é o jogo." aparece embaixo.

## Key moments (the middle)
- Notificações empilhando uma a uma na tela de bloqueio (Loop, Chat, Loja, Screen Time).
- Um dedo toca no app Loop; o feed rola sozinho e um coração de curtida estoura.
- Chat: a personagem digita e comenta um vídeo que "você" curtiu — memória e contexto.
- Screen Time: "O que o algoritmo aprendeu" com barras de uso.

## Outro / punchline
Logo oficial + "O celular é o jogo. A sua atenção move o mundo." + "Em desenvolvimento · Android".

## User flow worth showing
Boot → bloqueio → home → Loop → Chat → Screen Time (a sequência de uso descrita no README). O código do app não é público: as telas são recriadas a partir das descrições do README.

## Tone
- Preset: polished (revisão: o usuário pediu um tom mais sério)
- Creative direction: "o celular que disputa a sua atenção" — sóbrio, levemente inquietante, roxo escuro
- Interpretation: movimentos sem quique, brilho contido, ícones em roxo escuro, música mais calma (vol-12) e poucos sons.

## Format: vertical — 1080x1920
## Duration: 22.4s

## Visual identity (from the project)
- Background: #100629 / #17083d (roxo quase preto do logo)
- Accent: #8335f1 (cápsula), luz #a97bff para texto sobre fundo escuro
- Text: #f7f4f9 (branco da cápsula), #e7e1f3 (lavanda)
- Display font: Space Grotesk (geométrica, "digital")
- Body font: Inter
- Strongest visual element: a cápsula roxa e branca com brilho neon (logo oficial `assets/brand/dopeos_logo.png`)

## Share copy (draft)
E se o celular fosse o jogo? DopeOS: um sistema operacional fictício com feed infinito, personagens que lembram de você e um algoritmo que aprende seus hábitos. A sua atenção move o mundo.

## Audio direction
- Role: dense-ish rhythmic layer, punchy
- Music: `happy-beats-business-moves-vol-12-by-ende-dot-app.mp3` (109.96 BPM)
- Music treatment: ~0.34, fade-out no último 1.2s
- Music cue guidance: preset vol-10. Strong cue 18.55s → logo final. Beat grid: notificações em 3.55 / 4.64 / 5.19(… a cada 2 batidas para leitura), cortes de cena em 3.01, 6.28, 8.73, 12.56, 15.82.
- Audio-reactive treatment: subtle; brilho roxo da cápsula e do fundo respira com o grave.
- SFX posture: moderate — "plin" de notificação, toque, swipe, digitação, sino no logo.
- Restraint rule: sons curtos e baixos; nada estridente repetido.

## Storyboard
1. Boot — 0–3.01 — cápsula acende, barra de boot, "O celular é o jogo."
2. Bloqueio — 3.01–6.28 — relógio 21:47, 4 notificações chegam; legenda "Um sistema operacional inteiro. Dentro do jogo."
3. Home — 6.28–8.73 — grade de apps, dedo toca no Loop.
4. Loop — 8.73–12.56 — feed de vídeos rola 2x, curtida; legenda "Um feed que nunca acaba."
5. Chat — 12.56–15.82 — personagem (fictícia, "Luna") digita e lembra do vídeo curtido; legenda "Personagens com memória e rotina."
6. Screen Time — 15.82–18.55 — "O que o algoritmo aprendeu" + barras; legenda "O sistema aprende com você."
7. Outro — 18.55–22.4 — logo, tagline, "Em desenvolvimento · Android".

Nota de privacidade: nomes, horários e números são ilustrativos da interface do jogo; nenhum dado real.

---

## Revisão 3 — corte misterioso (substitui o storyboard acima)

Pedido: mais misterioso, animação com movimento de câmera de verdade, exaltar o lema "Welcome to a more fun version of the world."

- Tom: cinematic / misterioso — quase preto (#07030f), roxo só como luz, grão e vinheta.
- Técnicas (hyperframes-animation): `3d-camera-flight` (lente de perspectiva fixa, um único objeto de câmera, pousos em power4.out e voos em power3.inOut), `depth-of-field-blur` (troca de foco entre as telas), `hacker-flip-3d` (o lema se decifra letra a letra), `chromatic-glitch` (glitch RGB travado na batida forte de 17.47s).
- 0–3.3 Sinal: cápsula acende no escuro, "SINAL DETECTADO", câmera mergulha na cápsula.
- 3.1–12.9 Voo 3D entre as telas flutuando sobre um piso em grade: "Um sistema inteiro." → "Um feed que não termina." → "Alguém lembra de você." → "E tudo aprende com você."; recua para o vazio e escurece.
- 12.9–19.66 O lema se decifra em 4 linhas; glitch em 17.47s; "fun" acende em roxo.
- 19.66–23 Logo surge do escuro (beat-locked 19.66s) com o lema embaixo.
- Música: vol-12 a 0.26, fade-in e fade-out; SFX mínimos (glitch, deslizes, teclas baixas, sino grave no logo).

---

## Revisão 4 — estilo do pin de referência (substitui a revisão 3)

Pedido: refazer no estilo do pin https://br.pinterest.com/pin/774124931963319/ (reel de motion design com tipografia animada), mantendo o lema "Welcome to a more fun version of the world." no final e o "fun" acendendo em roxo alguns segundos depois.

- Linguagem visual do pin: serifa itálica (Playfair Display 400/700/900 italic), rótulo em caixa roxa (Oswald), fundos alternando branco / roxo vivo #7209b7 / creme / lavanda, grade sutil, palavra-fantasma gigante atravessando o fundo, estrelas brancas nos cantos, objetos "recortados" com sombra, cursor roxo, palavras entrando com blur, cortes secos na batida.
- Objetos (feitos em CSS/SVG, sem imagens externas): a cápsula do DopeOS, o celular na tela de bloqueio, cards do feed Loop, balão de chat da Luna, um olho que observa, o gráfico neon do Screen Time.
- Cortes a cada 4 batidas (~110 BPM, 1ª batida em 0.28s):
  1. 0–2.46 "JÁ PENSOU NISSO?" / "E se o celular fosse o jogo?" — cursor clica na cápsula.
  2. 2.46–4.64 roxo: "não é um app. Sistema inteiro." — celular sobe, 3 notificações.
  3. 4.64–6.83 "Loop" vertical + "um feed que nunca acaba." — feed rola, coração.
  4. 6.83–9.01 creme: "Personagens com memória" — Luna digita e lembra do vídeo curtido.
  5. 9.01–11.19 roxo: "O algoritmo observa cada toque e aprende." — olho procurando.
  6. 11.19–13.37 lavanda: "Screen Time sem segredos" — linha neon + contador; "a sua atenção move o mundo".
  7. 13.37–15.55 "não é só distração." / faixa roxa "é um mundo inteiro." — cápsula sobe.
  8. 15.55–23 o lema, palavra por palavra na batida; em 19.66s (cue forte) o "fun" acende em roxo com brilho, estrela e fantasma "fun" tingido; logo + "Em desenvolvimento · Android" em 20.5s. O lema fica na tela até o fim.
- Música: vol-12 a ~0.3–0.34, fade-out no último 1.4s. SFX: clique, deslizes nos cortes, notificações, digitação, "plin" de vidro no "fun", sino no logo.
