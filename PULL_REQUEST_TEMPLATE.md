<!-- Título: <tipo>(<escopo>): <verbo no imperativo>. Seções obrigatórias; `scripts/issue_hygiene.py --check pr` falha se faltar uma. -->

## Resumo

<!-- Uma frase: o quê e por quê. -->

Closes #

<!-- Um `Closes #N` por linha, um por issue resolvida. Sem issue: escreva `Sem issue` no lugar. -->

## O que mudou

<!-- Arquivos e comportamento, em lista. -->

## O que NÃO mudou

<!-- Uma linha: o que o título ou o resumo poderia sugerir e não foi feito. -->

## Prova

<!-- Troque todo PREENCHER; o lint reprova se sobrar um. Comando e saída colada, com exit code. Resumo do agente não vale. Se havia teste falhando, mostre antes e depois. Cada item marcado leva a evidência depois do `|`: `- [x] afirmação | comando`. -->

- [x] PREENCHER afirmação | PREENCHER comando que prova

```
# antes
$ PREENCHER
exit 1

# depois
$ PREENCHER
exit 0
```

## Merge Danger

**Door:** PREENCHER (one-way ou two-way)

**Blast Radius:** PREENCHER (uma palavra)

**Rollback:** PREENCHER (`git revert` ou o passo extra)

<!-- One-way = não dá para desfazer: deploy, dado de produção, chaves, crontab. Veja "One-way Doors" no AGENTS.md. -->
