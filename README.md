# Equipe de Agentes para Desenvolvimento com ML e IA

Esta pasta contem uma equipe inicial de agentes para ajudar a planejar, construir, testar e evoluir sistemas com recursos de machine learning e inteligencia artificial.

## Estrutura

```text
agents/
  coordenador.md
  product-owner.md
  arquiteto.md
  desenvolvedor-fullstack.md
  engenheiro-ml-ia.md
  qa.md
  devops.md
  revisor-codigo.md

templates/
  briefing-projeto.md
  tarefa.md
  revisao.md
  decisao-tecnica.md

workflows/
  fluxo-desenvolvimento.md

projects/
  primeiro-projeto.md

docs/
  como-usar.md
```

## Como usar

1. Comece preenchendo `templates/briefing-projeto.md`.
2. Envie o briefing para o `agents/coordenador.md`.
3. O Coordenador decide quais agentes devem atuar.
4. Use `templates/tarefa.md` para cada atividade.
5. Use `agents/revisor-codigo.md` e `agents/qa.md` antes de considerar uma entrega pronta.

Guias importantes:

- `docs/acionar-equipe.md`: mostra exatamente como chamar cada agente.
- `docs/instalacao-em-outro-pc.md`: mostra como baixar, instalar e manter esta equipe em qualquer computador.
- `docs/como-usar.md`: explica o fluxo geral de trabalho.

## Ordem recomendada dos agentes

```text
Product Owner -> Arquiteto -> Coordenador -> Desenvolvedor/ML/DevOps -> QA -> Revisor
```

## Equipe minima para comecar

Se quiser comecar pequeno, use apenas:

- `coordenador.md`
- `arquiteto.md`
- `desenvolvedor-fullstack.md`
- `engenheiro-ml-ia.md`

Depois adicione QA, DevOps e Revisor conforme seus projetos ficarem mais serios.
