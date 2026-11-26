# Método IC-RAV — Engenharia de Intençêo (1 página)

Nêo é prompt engineering. É a forma de **entregar trabalho para um agente** de modo que o resultado seja verificável.

```
I — INTENÇêO      O que quero conseguir?
C — CONTEXTO      O que a IA precisa saber?
R — RESULTADO     O que deve existir ao final? Como saberemos se ficou bom? (critérios)
A — AUTONOMIA     O que a IA pode fazer sozinha? O que exige aprovaçêo?
V — VERIFICAÇêO   O que precisa ser conferido, por quem, como?
```

## Checklist antes de delegar

- [ ] **Intençêo** cabe em uma frase e começa com o problema, nêo com a ferramenta.
- [ ] **Contexto** inclui dados, documentos, sistemas, restrições e quem é o usuário.
- [ ] **Resultado** é um artefato concreto (app, dashboard, planilha atualizada, relatório) com critérios de "bom".
- [ ] **Autonomia** está explícita: o que pode executar direto, o que precisa perguntar, o que é proibido.
- [ ] **Verificaçêo** definida: teste, amostra conferida, aprovaçêo humana em operações de risco.

## Regra de ouro

> Automaçêo supervisionada > automaçêo sem controle em operações de maior risco.

## Como aparece na formaçêo

- Todo módulo abre com o problema no formato IC-RAV.
- Todo prompt da biblioteca (`prompts/`) traz a decomposiçêo IC-RAV no cabeçalho.
- Todo projeto prático termina na etapa **V**.
