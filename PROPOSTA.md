# PROPOSTA — Linha de formação "Software sob Demanda com IA"

> Origem: vídeo *"50+ Usos INSANOS do GPT-6 Astra"* (https://www.youtube.com/watch?v=l5cuD72R8MU)
> e o material de referência reunido em `~/projetos/astra-auto/doc/` (Astra Computer-Use Kit, Field Guide, "5 Coisas Para Fazer") — repo separado, não copiado para cá.
>
> Status: **proposta v0.1 — 2026-09-07**. Nada aqui é curso pronto; é o mapa do que dá para construir.

---

## 0. Resumo executivo

O vídeo não deveria virar um curso "50 coisas legais do Astra". Ele aponta para uma **mudança na relação com software**:

| ANTES | AGORA |
|---|---|
| Problema → procurar software → comprar → aprender → configurar → operar | Problema → descrever resultado → IA pesquisa → cria/opera software → testa → entrega |

A competência a ensinar sobrevive ao modelo (Astra, Fable, Gemini, o próximo):

**enxergar problema → definir intenção → fornecer contexto → delegar → dar ferramentas → acompanhar execução → validar resultado.**

Slogan da linha:

> **DE USUÁRIO DE IA → GESTOR DE AGENTES**

Do vídeo + material de referência dá para extrair: **6 a 10 cursos, 20+ projetos práticos, biblioteca de 50–100 prompts orientados a trabalho real, um método próprio (IC-RAV) e um desafio de 30 dias.**

---

## 1. Tese central

# SOFTWARE SOB DEMANDA COM IA
### Pare de apenas usar ferramentas. Aprenda a mandar a IA criar, operar e integrar as ferramentas que você precisa.

Três estágios que o aluno atravessa:

1. **Pergunta → Resposta** (usar IA para responder)
2. **Objetivo → Pesquisa → Plano → Execução → Verificação** (usar IA para trabalhar)
3. **Problema → Software/Agente → Resultado** (usar IA para criar e operar ferramentas)

Insight-chave do vídeo: quando o custo de criar software tende a zero, **software deixa de precisar de mercado**. Pode ser pessoal, temporário, descartável, feito numa tarde para um problema de uma pessoa só.

---

## 2. Os 8 blocos de conteúdo

| # | Bloco | O aluno aprende | Exemplos do vídeo |
|---|---|---|---|
| 1 | Software sob demanda | Criar pequenas aplicações específicas para um problema | Todo-list pessoal com "coach", dashboard patrimonial, app de citometria que substituiu licenças caras |
| 2 | Computer Use | Fazer agentes operarem programas existentes | Astra operando DaVinci Resolve, KiCad (PCB em < 3 min), Blender |
| 3 | Pesquisa + decisão | Transformar pesquisa em dashboards e sistemas de decisão | Pesquisa de cidade para morar 1 mês → página com notas, custos e comparativo |
| 4 | Simulações | Modelar cenários antes de decidir | Simulador de cidade, modelagem de enchente em cidade costeira |
| 5 | Agentes | Criar agentes que trabalham, verificam e colaboram | Agentes Astra em mundo Unreal cooperando para sobreviver |
| 6 | Conteúdo | Vídeo, apresentações, imagens, experiências interativas | Vídeo de 5 min sobre células T, brand guidelines animado, site a partir de uma camisa polo |
| 7 | Dados e indicadores | Dados empresariais → ferramentas de gestão | Patrimônio consolidado de várias fontes → tarefas acionáveis |
| 8 | Gestão por agentes | Definir, delegar, supervisionar e validar trabalho de IA | Reality check do vídeo: OSWorld 72,6% — ainda erra, precisa supervisão |

---

## 3. Método próprio: IC-RAV

Não ensinar "prompt engineering". Ensinar **Engenharia de Intenção**:

```
INTENÇÃO     → O que quero conseguir?
CONTEXTO     → O que a IA precisa saber?
RESULTADO    → O que deve existir ao final?
CRITÉRIOS    → Como saberemos se ficou bom?
AUTONOMIA    → O que a IA pode fazer sozinha?
VERIFICAÇÃO  → O que precisa ser conferido?
```

**IC-RAV** = **I**ntenção · **C**ontexto · **R**esultado · **A**utonomia · **V**erificação (critérios entram dentro de Resultado/Verificação).

Cada aula, projeto e prompt da linha é estruturado nesse esqueleto. Vira a marca metodológica do INEMA nessa área, combinando com o trabalho já em andamento de Engenharia de Intenção + Contexto + Agentes.

---

## 4. Trilha completa (6 níveis)

```
NÍVEL 1 — IA como ASSISTENTE      prompt + contexto + pesquisa
      ↓
NÍVEL 2 — IA como CRIADORA        sites + apps + dashboards + conteúdo
      ↓
NÍVEL 3 — IA como OPERADORA       computer use + navegador + softwares
      ↓
NÍVEL 4 — IA como AGENTE          objetivo → planejamento → ferramentas → execução
      ↓
NÍVEL 5 — SISTEMAS DE AGENTES     agentes especializados trabalhando juntos
      ↓
NÍVEL 6 — EMPRESA ORIENTADA POR AGENTES   processos redesenhados para humanos + agentes
```

---

## 5. Catálogo de cursos propostos

| # | Curso | Nível | Público | Prioridade |
|---|---|---|---|---|
| C1 | **Do Prompt ao Software — Crie Sistemas com Agentes de IA** (curso-âncora) | 1→4 | Geral / PRO | 🔴 primeiro |
| C2 | **Agentes que Usam o Computador** (Computer Use) | 3 | Geral / empresas | 🔴 primeiro |
| C3 | **Pesquisa → Análise → Decisão → Aplicação** (pesquisa que vira software) | 2–4 | Geral | 🟠 |
| C4 | **Agentes para Empresas** (fornecedores, segurança, indicadores, formulários) | 4–6 | Empresas / B2B | 🟠 |
| C5 | **Engenharia de Intenção — Método IC-RAV** (curso curto, transversal) | 1 | Todos | 🟠 |
| C6 | **Simuladores e Decision Labs** | 2–4 | Gestores | 🟡 |
| C7 | **Fábrica de Conteúdo com Agentes** (vídeo, site, marca, 3D) | 2 | Criadores | 🟡 |
| C8 | **Sistemas de Agentes** (multi-agente, verificação cruzada) | 5 | Avançado | 🟡 |
| C9 | **Empresa Orientada por Agentes** (redesenho de processos) | 6 | Direção / consultoria | 🟢 depois |
| C10 | **Desafio 30 Agentes em 30 Dias** (formato desafio, não curso) | 1–4 | Comunidade | 🔴 marketing |

### C1 — Do Prompt ao Software (esboço de módulos)

1. **A nova relação com software** — usar IA para responder vs. usar IA para trabalhar; os 3 estágios.
2. **Engenharia de Intenção (IC-RAV)** — o método aplicado a um problema real do aluno.
3. **Software sob demanda** — primeiro app descartável numa tarde; dashboard pessoal.
4. **Pesquisa que vira sistema** — Deep Research + Vibe Coding num só fluxo.
5. **A IA operando o computador** — introdução ao Computer Use (aprofunda em C2).
6. **Agentes que verificam** — testar, corrigir, validar; o "reality check".
7. **Gestão por agentes** — delegar, supervisionar, aprovar; automação supervisionada.
8. **Projeto final** — resolver um problema real com um software/agente próprio.

### C2 — Agentes que Usam o Computador (roteiro de projetos)

Objetivo: não ensinar Excel, SAP, ERP, navegador ou CRM — ensinar **como fazer um agente usar esses sistemas por você**.

1. entrar em um sistema
2. pesquisar um fornecedor
3. copiar informações
4. preencher cadastro
5. preencher formulário
6. baixar documento
7. analisar documento
8. atualizar planilha
9. produzir relatório
10. avisar o responsável

Base já disponível em `~/projetos/astra-auto/doc/`: `Astra-Computer-Use-Kit.zip` (8 prompts, CLI de busca de voos com runbooks de browser) e `Computer-Use-Field-Guide.pdf`.

### C4 — Agentes para Empresas (casos)

| Caso | Entrada | Saída |
|---|---|---|
| Gestão de fornecedores | contratos + preços + entregas + atrasos + qualidade + reclamações | score + risco + recomendação + ações |
| Segurança do trabalho | incidentes + inspeções + procedimentos + registros | dashboard → riscos → pendências → responsáveis → alertas |
| Indicadores | dados dispersos | interpreta → consolida → calcula → gráficos → anomalias → explica → recomenda |
| Formulários | "Cadastre esse fornecedor" | processo executado ponta a ponta com aprovação humana |

---

## 6. Projetos práticos (cada um vira uma aula)

| Projeto | Resultado | Curso |
|---|---|---|
| Meu CFO IA | Dashboard financeiro pessoal/empresarial | C1 |
| Fornecedor 360 | Sistema de avaliação de fornecedores | C4 |
| Safety Copilot | Gestão de segurança do trabalho | C4 |
| Decision Lab | Simulador de decisões | C6 |
| Research Agent | Pesquisa profunda transformada em aplicativo | C3 |
| KPI Copilot | Indicadores + análise automática | C4 |
| Form Agent | Agente preenchendo formulários | C2 |
| Browser Worker | Agente executando tarefas na web | C2 |
| Video Factory | Roteiro → voz → imagem → vídeo | C7 |
| Learning Studio | Conteúdo transformado em aula interativa | C7 |
| Personal Coach | IA analisando tarefas e produtividade | C1 |
| Contract Analyzer | Contratos → riscos → ações | C4 |
| Meeting Agent | Reunião → decisões → responsáveis | C4 |
| Sales Copilot | Leads → pesquisa → proposta | C4 |
| CRM Agent | Atualização automática do CRM | C2 |
| Site Generator | Produto → marca → site | C7 |
| 3D Product Studio | Produto → experiência 3D | C7 |
| Scenario Simulator | Simulação empresarial | C6 |
| Operations Copilot | Operação diária da empresa | C9 |
| Executive Cockpit | Painel completo para direção | C9 |

---

## 7. Biblioteca de prompts (mudança de paradigma)

Em vez de *"Faça um dashboard."*, ensinar *"Resolva este problema e crie a ferramenta necessária para isso."*

Os 5 prompts-mestre da formação (texto completo em `prompts/`):

| Arquivo | Prompt | Uso |
|---|---|---|
| `prompts/01-software-sob-demanda.md` | Prompt Mestre — Software sob demanda | Arquiteto + dev + executor em 10 passos |
| `prompts/02-nao-me-de-resposta-crie-ferramenta.md` | "Não me dê uma resposta, crie uma ferramenta" | Converte pergunta em app/simulador |
| `prompts/03-agente-empresarial.md` | Agente empresarial | Divide processo em autônomo / ferramenta / computador / dados / aprovação humana |
| `prompts/04-pesquisa-vira-sistema.md` | Pesquisa → sistema de decisão | Deep Research + critérios + pesos + dashboard |
| `prompts/05-oportunidades-na-empresa.md` | Identificar oportunidades de automação | Mapeia área da empresa e escolhe as 3 melhores |

Meta: chegar a **50–100 prompts** organizados por bloco (seção 2) e por nível (seção 4).

---

## 7b. Conteúdo prático: como criar do zero (leigo)

A proposta só tem valor se o aluno **sair criando**. O guia `conteudo/como-criar-do-zero.md` cobre:

- ferramentas mínimas (sem instalar nada para começar);
- o formato "um arquivo HTML só" que roda em qualquer navegador;
- passo a passo de 30 minutos para a primeira ferramenta, com prompt pronto;
- como as pessoas do vídeo estão criando (padrões reutilizáveis, não mágica);
- escada de 7 degraus, cada degrau = 1 aula;
- prompts de bolso e limites que precisam ser ditos ao aluno.

Referência completa dos exemplos do vídeo: `conteudo/catalogo-astra-71.md` (71 itens, 33 abríveis) e `conteudo/prompts-astra-71.md` (17 prompts publicados, traduzidos). Fonte: índice *The Astra 71* de AI Samson.

## 8. Desafio: 30 AGENTES EM 30 DIAS

Formato de comunidade / marketing de entrada. Todo dia um pequeno problema entregue a um agente:

| Dia | Tema | Dia | Tema |
|---|---|---|---|
| 1 | organizar documentos | 6 | fornecedores |
| 2 | pesquisa | 7 | agenda |
| 3 | formulário | 8 | CRM |
| 4 | dashboard | 9 | financeiro |
| 5 | indicadores | 10 | contratos |

(dias 11–30 escalam para os projetos da seção 6)

Resultado esperado: a pessoa deixa de perguntar *"Qual IA devo aprender?"* e passa a perguntar **"Qual problema vou entregar para um agente hoje?"**

---

## 9. Reality check (obrigatório em todo curso)

- Astra não é funcionário autônomo perfeito. Erra, entende errado, trava, precisa de correção.
- OSWorld (benchmark de computer use): **72,6%**. Enorme avanço, longe de perfeito.
- Regra da linha: **automação supervisionada > automação sem controle** em operações de risco.
- Todo projeto termina com etapa de **VERIFICAÇÃO** (o V do IC-RAV).

---

## 10. Plano de execução proposto

### Fase 1 — Fundação (2–3 semanas)
- [x] Fechar o método IC-RAV (`metodo/IC-RAV.md`).
- [x] Prompts-mestre (`prompts/01` a `05`).
- [x] Catálogo de casos reais (`conteudo/catalogo-astra-71.md`, `conteudo/prompts-astra-71.md`).
- [x] Guia para leigo (`conteudo/como-criar-do-zero.md`).
- [x] Escrever o **Desafio 30 Agentes em 30 Dias** (`desafio-30-dias/`).
- [ ] Produzir os 30 vídeos curtos (1 por dia) e abrir a inscrição.
- [ ] Biblioteca de prompts: chegar a 25 (5 mestres + 20 derivados dos dias do desafio).

### Fase 2 — Curso-âncora (4–6 semanas)
- [ ] **C1 — Do Prompt ao Software** em `/formato-curso-v5` (decisão 2), alimentado pelos casos reais do desafio.
- [ ] 8 módulos, cada módulo com 1 projeto da seção 6.
- [ ] Publicar no portal (inema.club) via `/atualiza-portal`.

### Fase 3 — Computer Use (3–4 semanas)
- [ ] **C2 — Agentes que Usam o Computador** aproveitando o Kit em `astra-auto/doc/`.
- [ ] 10 projetos guiados (seção 5, C2).

### Fase 4 — Empresas (paralelo, sob demanda)
- [ ] **C4 — Agentes para Empresas** como treinamento in-company (decisão 5), com o prompt 05 abrindo o diagnóstico.

### Fase 5 — Expansão
- [ ] C3, C5, C6, C7, C8, C9 conforme tração.

---

## 11. Decisões tomadas (2026-09-07)

| # | Decisão | Escolha | Por quê |
|---|---|---|---|
| 1 | Nome da linha | **GESTOR DE AGENTES** é a linha; **Do Prompt ao Software** é o curso-âncora | "Software sob demanda" descreve a tecnologia, que muda; "gestor de agentes" descreve a competência, que fica |
| 2 | Formato do curso-âncora | **`/formato-curso-v5`** (INEMA.PRO, público 40+ leigo) | O guia "como criar do zero" foi escrito para leigo; o curso tem que falar a mesma língua. Confirmar na hora de construir |
| 3 | Ferramenta de referência | **Neutra** — Astra, Claude Code, Codex e Gemini como intercambiáveis | A tese do vídeo é que a competência sobrevive ao modelo. Amarrar o curso a um modelo o faz vencer em meses |
| 4 | Por onde começar | **Desafio 30 Agentes em 30 Dias** antes do curso C1 | Gera audiência, prova social e casos reais que viram material do curso. Custo de produção baixo |
| 5 | B2B (C4 e C9) | **Consultoria / treinamento in-company**, não curso aberto | O valor está no diagnóstico da área específica (prompt 05). Curso aberto viria depois, feito dos casos |

### O que isso implica na prática

- A marca da linha é **GESTOR DE AGENTES**; "Software sob Demanda com IA" vira o subtítulo explicativo.
- O primeiro entregável é `desafio-30-dias/`, não um curso.
- Nenhuma aula pode depender de ter Astra. Todo projeto precisa de caminho em pelo menos duas ferramentas.
- C4/C9 viram uma oferta comercial, com o prompt 05 como porta de entrada do diagnóstico.

---

## 12. Estrutura sugerida deste repo

```
software-sob-demanda/
├── README.md              ← entrada
├── PROPOSTA.md            ← este documento
├── prompts/               ← biblioteca de prompts (5 mestres + derivados)
├── conteudo/              ← guias práticos (como criar do zero, padrões do vídeo)
├── metodo/                ← IC-RAV: diagrama, 1-pager, checklist
├── cursos/
│   ├── c1-do-prompt-ao-software/
│   ├── c2-computer-use/
│   └── ...
├── projetos/              ← 20 projetos práticos (spec + prompt + critérios)
└── desafio-30-dias/       ← 30 problemas, 1 por dia

(material bruto de referência continua em `~/projetos/astra-auto/doc/`)
```
