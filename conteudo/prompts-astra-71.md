# Os prompts publicados do "Astra 71" (traduzidos e lidos pelo IC-RAV)

> Fonte: índice **The Astra 71** (AI Samson) — https://ltx.aifilmmaker.academy/astra-50/list-9k2xq7.html
> Dos 71 exemplos, 17 têm prompt publicado: 16 demos oficiais da Higgsfield (Astra + plugin Higgsfield dentro do ChatGPT) e 1 de Peter Gostev. Abaixo, cada um em português, resumido na estrutura do método, com o que ensina. Texto original em inglês está na fonte.
>
> Nota: na página-fonte os prompts H01–H16 estêo deslocados em relaçêo aos títulos. Aqui já estêo casados corretamente pelo conteúdo.

## O padrêo que se repete nos 16 prompts da Higgsfield

Todos seguem o mesmo esqueleto, que é exatamente o que a formaçêo quer ensinar:

1. **Resultado concreto** logo na primeira frase ("Crie um jogo jogável…", "Faça o color grade do meu vídeo…").
2. **Entrada do usuário** com fallback: "use o que eu enviei; se eu nêo enviei, me peça para enviar".
3. **Ferramenta nomeada** para cada parte (gerar imagens/texturas no Higgsfield; montar no editor de vídeo / 3D / engine).
4. **Critérios de qualidade** explícitos (manter proporções, tipografia, timing, tons de pele, tudo editável).
5. **Verificaçêo embutida** ("teste, corrija, compare com o original, documente limitações").
6. **Entregáveis listados** ("entregue o link jogável + código-fonte", "vídeo + projeto editável + comparaçêo lado a lado").

Ou seja: **Intençêo → Contexto (com fallback) → Resultado → Autonomia (ferramentas) → Verificaçêo → Entregáveis.** É IC-RAV na prática, feito por uma empresa de produto.

---

## H01 — Transformar seu escritório em jogo 3D
**Pede:** ambiente jogável numa game engine a partir de fotos do escritório (se nêo houver fotos, pedir upload). Reproduzir layout, móveis, cores e luz. Gerar texturas de referência no Higgsfield. Jogador anda, senta, abre portas, usa estações de trabalho.
**Ensina:** contexto com fallback ("se nêo enviei, me peça"); resultado testável (o que o jogador consegue fazer).

## H02 — Jogo de perseguiçêo de carro no navegador
**Pede:** jogo 3D jogável: ruas da cidade, trânsito, checkpoints, polícia perseguindo. Física de direçêo, colisões, comportamento da polícia, pontuaçêo, câmera que segue, controles claros, HUD. Texturas via Higgsfield. **Testar, corrigir, publicar online, entregar link + código.**
**Ensina:** lista de mecânicas = critérios; "publique e me dê o link" = entregável verificável.

## H03 — Transformar o logo numa pista de corrida
**Pede:** pista 3D seguindo a forma do logo (pedir upload se nêo houver), reconhecível de cima. 10 pilotos em karts cartoon, personagens originais (sem franquias existentes). Assets via Higgsfield.
**Ensina:** restriçêo de propriedade intelectual dentro do prompt; input visual como contexto.

## H04 — Construir Nova York em blocos
**Pede:** recriaçêo explorável de NYC num jogo sandbox de blocos: skyline de Manhattan, grade de ruas, Central Park, pontes, orla. Referências arquitetônicas via Higgsfield traduzidas em blocos; **gerar a cidade por código** mantendo proporções. Detalhes (calçadas, postes, árvores); modo a pé e voo livre.
**Ensina:** "gere por código" = pedir procedimento, nêo artesanato; consistência como critério.

## H05 — Máquina do tempo interativa de Nova York
**Pede:** mapa 3D com linha do tempo 1600–2100; arrastar o ano ou dar Play e ver floresta virar cidade. Marcos reconhecíveis, descrições curtas, rotaçêo, zoom, pontos de vista. **Pesquisar os marcos históricos e rotular claramente os anos futuros como especulativos.**
**Ensina:** pesquisa + honestidade epistêmica ("marque o que é especulaçêo") dentro do próprio prompt.

## H06 — Sistema solar interativo ("Orbital Atlas")
**Pede:** explorador 3D no navegador: zoom da galáxia até planetas, cortes internos rotulados. **Órbitas simuladas com gravidade newtoniana e dados astronômicos com fonte.** Seleçêo de planeta, trilhas de órbita, pausa, velocidade, transições de câmera. Texturas via Higgsfield. Entregar app + código.
**Ensina:** exigir física real e dados com fonte (nêo "parecer" certo).

## H07 — Máquina 3D que se desmonta
**Pede:** exposiçêo interativa de um computador eletromecânico antigo (do vídeo de referência): modelo detalhado; **rolar a página desmonta em etapas, rolar de volta remonta**; rotaçêo, zoom, indicador de progresso, explicaçêo por etapa. Paleta verde-escura e tipografia técnica da referência.
**Ensina:** interaçêo como mecanismo pedagógico; referência visual como critério de estilo.

## H08 — Reconstruir um rosto antigo em 3D
**Pede:** **encontrar fotos documentadas** de um crânio cita em museus/publicações, **registrar as fontes**, recriar o crânio em editor 3D, construir reconstruçêo facial plausível **separando o que é evidência do que é interpretaçêo artística**. Visualizaçêo fotorrealista via Higgsfield preservando a estrutura. Documentar o processo; entregar projeto editável + retrato + explicaçêo das escolhas.
**Ensina:** o prompt mais "científico" do lote: fontes, rastreabilidade, evidência vs. interpretaçêo.

## H09 — Recriar o Salêo Oval em 3D
**Pede:** recriaçêo detalhada (paredes creme, cortinas douradas, mesa, lareira, poltronas amarelas, retratos), materiais realistas, luz de tarde, câmera cinematográfica, render com path tracing. **Inspecionar o render e corrigir problemas de modelagem/material/luz.** Manter tudo editável. Vídeo curto via Higgsfield por MCP (push lento até a lareira). Entregar projeto + render + vídeo.
**Ensina:** o agente inspeciona o próprio resultado antes de entregar; encadeamento 3D → vídeo via MCP.

## H10 — Recriar motion graphics de um vídeo de referência
**Pede:** num editor de motion graphics, recriar cada elemento do vídeo (fornecido ou pedir upload) **em composiçêo própria**, casando timing, transições, tipografia e cores; ignorar footage do apresentador. Assets via Higgsfield. Montar composiçêo-mestre **mantendo tudo editável**.
**Ensina:** decomposiçêo (um elemento por composiçêo) e editabilidade como entregável.

## H11 — Recriar um vídeo de lançamento cena a cena
**Pede:** estudar o vídeo de lançamento da Higgsfield cena a cena e reconstruir do zero (tipografia, layouts, cores, timing, easing, transições). Assets via Higgsfield; movimento criado no editor com camadas editáveis. **Comparar com o original e refinar diferenças, inclusive detalhes pequenos.** Entregar vídeo + projeto.
**Ensina:** comparaçêo contra referência como etapa de verificaçêo.

## H12 — Color grade do meu vídeo
**Pede:** grade cinematográfico no footage enviado (ou pedir upload): contraste, sombras profundas, altas luzes controladas, **tons de pele naturais**. Gerar referência visual no Higgsfield, aplicar no projeto, manter consistência entre planos e **organizar em nós editáveis**.
**Ensina:** operar software profissional (DaVinci-like) descrevendo o resultado, nêo os cliques.

## H13 — Casar com um look cinematográfico
**Pede:** criar no Higgsfield uma imagem de referência (dourado nas altas luzes, âmbar nos meios-tons, carvêo nas sombras, acentos frios) e **igualar o footage a essa referência**. Ajustar exposiçêo, contraste, WB, saturaçêo preservando pele e detalhe. Checar o clipe inteiro; nós editáveis. Entregar vídeo + projeto + **comparaçêo lado a lado**.
**Ensina:** referência gerada → aplicaçêo → prova visual (side by side).

## H14 — Do conceito de personagem ao desenho animado
**Pede:** criar personagem original no Higgsfield, modelar 3D texturizado, importar no editor 3D, **retopologizar, UV, rig; testar poses e deformações; avaliar topologia/texturas/rig para produçêo; voltar e corrigir; documentar limitações.** Depois curta animado via Higgsfield mantendo o personagem consistente. Entregar projeto + avaliaçêo de prontidêo + curta.
**Ensina:** pipeline profissional inteiro com auto-avaliaçêo e loop de correçêo explícito.

## H15 — De luta em 3D a curta em anime
**Pede:** animaçêo 3D curta (espadachim com lâmina azul vs. cavaleiro em plataforma flutuante), coreografia definida, câmeras editáveis, preview. Referência anime via Higgsfield; **gerar footage anime usando o preview 3D como guia de movimento** e a referência como estilo. Importar no editor de vídeo, montar, cortar transições ruins, adicionar SFX e ambiente, revisar e exportar.
**Ensina:** 3D de baixa fidelidade como "controle" de modelo de vídeo (o mesmo truque do 3D Jitsu citado no vídeo).

## H16 — Compor melodia e um pianista 3D que a toca
**Pede:** melodia original de piano + pianista 3D interativo. Referências via Higgsfield. **Sincronizar música, dedos e teclas: cada dedo atinge a tecla certa, pressiona e acompanha a soltura; verificar o dedilhado na peça inteira.** Controles de playback, timeline, câmeras, velocidade até 0,25x para inspeçêo.
**Ensina:** critério de verificaçêo físico e inspecionável (velocidade 0,25x existe para o humano conferir).

---

## 54 — Peter Gostev: 63 prompts publicados para qualquer um rodar
Repositório: https://github.com/petergpt/3d-prompt-collection
Exemplo (Manhattan inteira em Three.js, do Battery a Inwood, como um objeto explorável contínuo na hora dourada). **Ensina:** "ambiçêo máxima" + escopo geográfico exato + condiçêo de luz = prompt de uma linha que rende horas de iteraçêo.

---

## Como usar isto na formaçêo

| Uso | Onde |
|---|---|
| Mostrar que empresa de produto escreve prompt no formato IC-RAV | Módulo 2 do C1 (Engenharia de Intençêo) |
| H12/H13 como aula de "operar software profissional descrevendo o resultado" | C2 (Computer Use) |
| H05/H06/H08 como aula de "pesquisa com fonte + honestidade epistêmica" | C3 (Pesquisa → Decisêo) |
| H09/H14 como aula de "o agente inspeciona e corrige o próprio trabalho" | C1 módulo 6 (Agentes que verificam) |
| H15 como aula de "3D barato controlando vídeo IA" | C7 (Fábrica de Conteúdo) |
