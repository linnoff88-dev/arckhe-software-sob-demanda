# DESAFIO: 30 AGENTES EM 30 DIAS

> Todo dia você entrega um problema pequeno para um agente. Não precisa ser grande. Precisa ser **seu** e precisa **funcionar no fim do dia**.
>
> No dia 1 você pergunta "qual IA devo aprender?". No dia 30 você pergunta **"qual problema vou entregar para um agente hoje?"**.

## Como funciona

| Regra | Detalhe |
|---|---|
| **Tempo** | 30 a 60 minutos por dia. Se passar disso, o escopo estava grande demais. |
| **Entrega** | Algo que abre e funciona: uma página, uma planilha atualizada, um relatório, uma tarefa executada. |
| **Ferramenta** | Qualquer uma. ChatGPT, Claude, Gemini, Claude Code, Codex. Os dias marcados 🖥️ pedem um agente que use o computador. |
| **Formato padrão** | Um único arquivo HTML, salvo no seu computador. Ver `../conteudo/como-criar-do-zero.md`. |
| **Prova** | Print ou tela gravada do resultado funcionando. É isso que você posta. |
| **Regra de ouro** | Se você não conseguir **conferir** que está certo, não conta como entregue. |

Todo dia usa o mesmo esqueleto (IC-RAV, em `../metodo/IC-RAV.md`):

```
INTENÇÃO · CONTEXTO · RESULTADO · AUTONOMIA · VERIFICAÇÃO
```

---

## Semana 1 — Ferramentas para você (dias 1 a 7)

Objetivo da semana: descobrir que dá para ter software feito sob medida.

| Dia | Problema | Você entrega | Como conferir |
|---|---|---|---|
| 1 | **Organizar documentos** | Página que lista seus arquivos por tipo/assunto e sugere onde arquivar | Rodar em 20 arquivos reais e discordar de no máximo 3 |
| 2 | **Pesquisa que vira página** | Uma decisão pequena pesquisada, com fontes e comparativo | Todo dado tem link clicável que confirma o número |
| 3 | **Formulário chato** | Formulário que você preenche toda semana, agora com preenchimento assistido | Preencher um de verdade e submeter |
| 4 | **Dashboard** | Painel de um número que você acompanha (gasto, peso, vendas, horas) | Lançar 5 registros e o gráfico bater com a conta na mão |
| 5 | **Indicadores** | Pegar dados soltos e virar 3 indicadores com explicação em português | Conferir 1 indicador na calculadora |
| 6 | **Comparar fornecedores** | Tabela com critérios, pesos e nota final ajustável | Mudar um peso e a ordem mudar de forma que faz sentido |
| 7 | **Sua agenda** | Página que lê sua semana e aponta conflitos e buracos | Comparar com a agenda real do celular |

**Prompt-base da semana:**
```text
Quero uma ferramenta pessoal, não uma resposta em texto.
INTENÇÃO: [o incômodo de hoje]
CONTEXTO: [quem usa, que dados tenho, onde estão]
RESULTADO: [o que deve existir no fim e como saberei que ficou bom]
Entregue como UM ÚNICO arquivo HTML, com CSS e JavaScript dentro, sem
dependências externas, funcionando offline, guardando dados no navegador.
Não invente funcionalidades além do que pedi.
```

---

## Semana 2 — A IA operando o computador (dias 8 a 14) 🖥️

Objetivo da semana: parar de fazer os cliques.

| Dia | Problema | Você entrega | Como conferir |
|---|---|---|---|
| 8 | **Atualizar o CRM / uma planilha** 🖥️ | Agente abre a planilha e atualiza 5 linhas | Abrir a planilha e ver as 5 linhas |
| 9 | **Financeiro** | Extrato bagunçado vira categorias + total + 3 alertas | Somar as categorias e bater com o extrato |
| 10 | **Contratos** | Um contrato vira lista de riscos, prazos e responsáveis | Achar no PDF cada item que ele citou |
| 11 | **Pesquisar um fornecedor** 🖥️ | Agente pesquisa na web e traz ficha com fontes | Abrir 3 fontes e confirmar |
| 12 | **Baixar e ler um documento** 🖥️ | Agente entra no site, baixa o PDF e resume o que interessa | Ler o trecho original que ele citou |
| 13 | **Preencher um cadastro** 🖥️ | Agente preenche o formulário e **para antes de salvar** | Ele parou? Se salvou sozinho, o prompt falhou |
| 14 | **Relatório semanal** | O que você faz toda sexta, feito por um agente | Comparar com o relatório da semana passada |

**Prompt-base da semana:**
```text
Objetivo: [o que precisa acontecer].
Faça o passo a passo no navegador/no programa.
Antes de qualquer ação que SALVE, ENVIE, APAGUE ou PAGUE, pare e me
mostre exatamente o que vai fazer, e espere eu confirmar.
No fim, entregue: o que foi feito, o que não conseguiu, e onde ficou em dúvida.
```

> ⚠️ Semana da supervisão. Em benchmark de uso de computador o estado da arte acerta cerca de 3 em 4 tarefas. O "pare antes de salvar" não é frescura, é o que torna isso utilizável.

---

## Semana 3 — Trabalho de verdade (dias 15 a 21)

Objetivo da semana: sair do pessoal e entrar no profissional.

| Dia | Problema | Você entrega | Como conferir |
|---|---|---|---|
| 15 | **Reunião → decisões** | Transcrição vira decisões, responsáveis e prazos | Mandar para quem estava lá e ninguém corrigir |
| 16 | **Pendências** | Painel do que está parado, há quanto tempo e com quem | Achar 1 pendência que você tinha esquecido |
| 17 | **Proposta comercial** | Lead pesquisado vira proposta rascunhada | Você mandaria essa proposta? |
| 18 | **Segurança / qualidade** | Registros de incidente viram riscos + ações + responsáveis | Um responsável real concordar com a ação |
| 19 | **Simulador de decisão** | Uma decisão difícil com variáveis que você pode mexer | Mexer numa variável e o resultado virar |
| 20 | **Um relatório que ninguém lê** | O mesmo relatório, agora como página que responde perguntas | Alguém abrir e achar o que queria em 30 segundos |
| 21 | **Refaça só a parte que você usa** | Substituir 1 função de um software caro pelo seu caso específico | Rodar com dados reais e bater com o software original |

**Prompt-base da semana (o do dia 21 é o mais forte do desafio):**
```text
Uso o software [X] só para uma coisa: [a função].
Meus dados são assim: [formato/exemplo].
Construa uma ferramenta que faça exatamente essa parte, para o meu caso,
e mais nada. Depois rode com os dados de exemplo, compare com o resultado
que o software original me dá, e me diga onde diverge.
```

---

## Semana 4 — Delegar de verdade (dias 22 a 30)

Objetivo da semana: parar de operar e começar a gerir.

| Dia | Problema | Você entrega | Como conferir |
|---|---|---|---|
| 22 | **Agente que se testa** | Agente constrói algo, usa, acha os próprios erros e corrige | Ele achou pelo menos 1 erro sozinho |
| 23 | **Aba "coach"** | Sua ferramenta do dia 4 ganha uma aba onde a IA comenta seu uso | Ele apontar algo que você não tinha visto |
| 24 | **Dois agentes** | Um faz, outro confere e reprova | O revisor reprovou pelo menos uma vez |
| 25 | **Rotina automática** | Algo que roda toda segunda sem você pedir | Chegar na segunda e estar feito |
| 26 | **Diagnóstico de uma área** | Rodar o prompt 05 na sua área e listar oportunidades | As 3 escolhidas fazem sentido para quem trabalha lá |
| 27 | **Vídeo/aula** | Um assunto seu vira material visual | Alguém entender sem você explicar |
| 28 | **Documente seu agente** | Instruções para outra pessoa usar o que você fez | Outra pessoa usar sem te perguntar nada |
| 29 | **Conserte o pior deles** | Volte no dia que deu mais errado e resolva | Agora funciona |
| 30 | **Seu maior incômodo** | O problema que você vem adiando desde o dia 1 | Está resolvido, ou tem plano com data |

---

## Ao final

Você tem 30 provas de que consegue transformar um incômodo em ferramenta. Falta escolher qual das 30 merece virar coisa séria.

Continua em: **Do Prompt ao Software** (curso-âncora da linha GESTOR DE AGENTES).

## Material de apoio

- `../conteudo/como-criar-do-zero.md` — passo a passo da primeira ferramenta
- `../metodo/IC-RAV.md` — o esqueleto de todo pedido
- `../prompts/` — os 5 prompts-mestre
- `../conteudo/catalogo-astra-71.md` — 71 exemplos reais para roubar ideia
