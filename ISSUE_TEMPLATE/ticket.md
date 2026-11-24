---
name: Ticket
about: Tarefa que um worker pode pegar sem perguntar nada
title: "<verbo no imperativo, sem repetir o tipo>"
labels: needs-triage
---

<!-- Troque todo PREENCHER; o lint reprova se sobrar um. Cada seção abaixo é obrigatória, menos as duas últimas. `scripts/issue_hygiene.py --check issue` falha se faltar uma ou se ficar vazia. Questão de design em aberto? Use `ready-for-human`, não `ready-for-agent`. -->

## Resultado

<!-- Uma frase: o que existe depois que o ticket fecha. -->

## Contexto

<!-- Até 5 linhas. Por que agora, e onde olhar (arquivo, issue, PR). Texto longo piora o resultado do worker. -->

## Arquivos permitidos

<!-- Lista fechada. O que não está aqui está fora de escopo. -->

## Fora de escopo

<!-- O que o worker NÃO pode mudar. -->

## Critérios de aceite

<!-- Um comando por item, que passa ou falha. Sem prosa. Função ou módulo novo: um item prova o chamador em código de produção (`grep -n "nome(" scripts/<arquivo>.py`), não só o teste. -->
<!-- Visto: #710 entregou `probe_cycle` com teste verde e nenhum `main()` o chamava; o cron instalaria a varredura antiga. -->
- [ ] `PREENCHER`

## Porta de mão única

<!-- Sim ou não. Sim = toca deploy, chaves, crontab, LiteLLM ou main sem auto-merge; o dono decide antes. -->

## Pai

<!-- Opcional: #N da spec. -->

## Blocked by

<!-- Opcional: #N, um por linha. -->
