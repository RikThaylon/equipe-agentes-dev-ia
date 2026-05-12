# Como acionar a equipe de agentes

Voce aciona a equipe copiando o prompt de um agente e dando uma tarefa para ele. O jeito mais simples e sempre comecar pelo Coordenador.

## Acionamento rapido

Use este comando inicial:

```text
Atue como meu Agente Coordenador usando as instrucoes do arquivo agents/coordenador.md.

Meu objetivo e:
[descreva aqui o sistema, problema ou funcionalidade]

Monte o plano de execucao, escolha os agentes necessarios, organize as tarefas e diga qual e o primeiro passo.
```

## Quando usar cada agente

Use o `Product Owner` quando precisar transformar uma ideia em requisitos:

```text
Atue como meu Agente Product Owner usando agents/product-owner.md.
Transforme esta ideia em MVP, historias de usuario e criterios de aceite:
[sua ideia]
```

Use o `Arquiteto` quando precisar definir stack, banco, modulos e APIs:

```text
Atue como meu Agente Arquiteto usando agents/arquiteto.md.
Com base nestes requisitos, proponha a arquitetura do sistema:
[requisitos]
```

Use o `Desenvolvedor Full Stack` quando ja existir uma tarefa tecnica clara:

```text
Atue como meu Agente Desenvolvedor Full Stack usando agents/desenvolvedor-fullstack.md.
Implemente esta tarefa:
[tarefa]
```

Use o `Engenheiro de ML e IA` quando o sistema tiver modelo, RAG, embeddings, classificacao, previsao ou agentes:

```text
Atue como meu Agente Engenheiro de ML e IA usando agents/engenheiro-ml-ia.md.
Projete a solucao de IA para este caso:
[caso de uso]
```

Use o `QA` para validar a entrega:

```text
Atue como meu Agente QA usando agents/qa.md.
Crie um plano de testes para esta funcionalidade:
[funcionalidade]
```

Use o `DevOps` para ambiente, deploy e CI/CD:

```text
Atue como meu Agente DevOps usando agents/devops.md.
Monte o plano de ambiente, deploy e observabilidade para:
[sistema]
```

Use o `Revisor de Codigo` antes de aprovar uma entrega:

```text
Atue como meu Agente Revisor de Codigo usando agents/revisor-codigo.md.
Revise esta entrega com foco em bugs, seguranca, performance e testes:
[descricao ou diff]
```

## Fluxo recomendado

```text
1. Coordenador entende o objetivo.
2. Product Owner cria requisitos e criterios de aceite.
3. Arquiteto define a solucao tecnica.
4. Coordenador quebra em tarefas.
5. Desenvolvedor, ML/IA e DevOps executam.
6. QA testa.
7. Revisor de Codigo avalia.
8. Coordenador decide o proximo ciclo.
```

## Exemplo completo

```text
Atue como meu Agente Coordenador usando agents/coordenador.md.

Quero criar um sistema web para pequenas empresas controlarem atendimentos de clientes.
O sistema deve ter cadastro de clientes, historico de conversas, painel de tarefas e uma IA para sugerir proximas acoes.

Monte:
1. MVP;
2. agentes que devem participar;
3. arquitetura inicial;
4. backlog de tarefas;
5. primeira tarefa para comecar.
```

