# Método IC-RAV — Engenharia de Intenção (1 página)

Não é prompt engineering. É a forma de **entregar trabalho para um agente** de modo que o resultado seja verificável.

```
I — INTENÇÃO      O que quero conseguir?
C — CONTEXTO      O que a IA precisa saber?
R — RESULTADO     O que deve existir ao final? Como saberemos se ficou bom? (critérios)
A — AUTONOMIA     O que a IA pode fazer sozinha? O que exige aprovação?
V — VERIFICAÇÃO   O que precisa ser conferido, por quem, como?
```

## Checklist antes de delegar

- [ ] **Intenção** cabe em uma frase e começa com o problema, não com a ferramenta.
- [ ] **Contexto** inclui dados, documentos, sistemas, restrições e quem é o usuário.
- [ ] **Resultado** é um artefato concreto (app, dashboard, planilha atualizada, relatório) com critérios de "bom".
- [ ] **Autonomia** está explícita: o que pode executar direto, o que precisa perguntar, o que é proibido.
- [ ] **Verificação** definida: teste, amostra conferida, aprovação humana em operações de risco.

## Regra de ouro

> Automação supervisionada > automação sem controle em operações de maior risco.

## Como aparece na formação

- Todo módulo abre com o problema no formato IC-RAV.
- Todo prompt da biblioteca (`prompts/`) traz a decomposição IC-RAV no cabeçalho.
- Todo projeto prático termina na etapa **V**.
