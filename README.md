# TradeSports Knowledge Base

Fonte única da verdade da TradeSports para marca, design, marketing, produto, jurídico, analytics, crescimento, vendas e agentes de IA.

## Objetivo

Este repositório organiza apenas decisões oficiais, aprovadas e versionadas. Conversas, rascunhos e ideias descartadas não devem ser tratados como fonte oficial.

## Princípio central

> A IA nunca improvisa sobre a marca. Ela consulta a marca.

## Estrutura principal

- `specifications/` — regras e definições oficiais.
- `playbooks/` — processos operacionais.
- `assets/` — arquivos visuais oficiais.
- `prompts/` — prompts aprovados por função.
- `examples/` — exemplos validados.
- `agents/` — instruções dos agentes de IA.
- `templates/` — modelos de documentação.
- `decisions/` — registros formais de decisões.
- `glossary/` — termos oficiais.
- `archive/` — documentos substituídos ou descontinuados.

## Status permitidos

- `DRAFT`
- `REVIEW`
- `APPROVED`
- `DEPRECATED`

Somente documentos `APPROVED` devem orientar agentes de IA e decisões operacionais.

## Versionamento

- `1.0` — primeira versão aprovada.
- `1.1` — ajuste pequeno sem mudança estrutural.
- `2.0` — alteração relevante de regra, posicionamento ou processo.

## Convenção de nomes

Usar `snake_case` e extensão `.md`.

## Hierarquia documental

1. Brand Book
2. Especificações de marca
3. Design System / Creative System
4. Estratégia de marketing
5. Playbooks
6. Briefings e prompts
7. Exemplos

## Fluxo de aprovação

1. Criar como `DRAFT`.
2. Revisar e alterar para `REVIEW`.
3. Após aprovação de Gabriel Lima, alterar para `APPROVED`.
4. Registrar no `CHANGELOG.md`.
5. Nunca apagar versões relevantes; usar `DEPRECATED`.

## Uso por IA

Agentes devem consultar apenas documentos `APPROVED`, priorizar documentos de maior hierarquia, não inventar informações e informar conflitos ou lacunas.

## Responsável pela aprovação

Gabriel Lima
