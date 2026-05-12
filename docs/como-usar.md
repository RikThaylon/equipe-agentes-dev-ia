# Como usar sua equipe de agentes

## 1. Descreva o projeto

Abra `templates/briefing-projeto.md` e preencha:

- problema;
- publico-alvo;
- funcionalidades desejadas;
- dados disponiveis;
- restricoes;
- objetivo de IA/ML, se existir.

## 2. Passe para o Coordenador

Use o conteudo do briefing com o agente `agents/coordenador.md`.

Peca algo como:

```text
Atue como meu Agente Coordenador. Leia este briefing e monte o plano de execucao.
```

## 3. Gere requisitos com o Product Owner

Depois do plano inicial, use `agents/product-owner.md` para transformar a ideia em MVP, historias de usuario e criterios de aceite.

## 4. Defina a arquitetura

Use `agents/arquiteto.md` para decidir stack, banco, APIs, modulos e riscos tecnicos.

## 5. Divida em tarefas

Cada tarefa deve seguir `templates/tarefa.md`.

Uma boa tarefa tem:

- objetivo claro;
- agente responsavel;
- entrada;
- saida esperada;
- criterio de aceite;
- testes.

## 6. Desenvolva e valide

Use:

- `agents/desenvolvedor-fullstack.md` para implementacao geral;
- `agents/engenheiro-ml-ia.md` para IA, ML, RAG, prompts, embeddings e avaliacao;
- `agents/devops.md` para ambiente, deploy e observabilidade;
- `agents/qa.md` para testes;
- `agents/revisor-codigo.md` para revisao final.

## 7. Trabalhe por ciclos

Nao tente construir tudo de uma vez. Use ciclos curtos:

```text
Planejar -> Implementar -> Testar -> Revisar -> Publicar -> Melhorar
```

