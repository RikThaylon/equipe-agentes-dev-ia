# Equipe Figma / UX UI para GitHub Copilot

Esta pasta contem os Custom Agents reconhecidos pelo GitHub Copilot/VS Code.

## Agente principal
- `analista-figma.agent.md` — orquestrador e ponto de entrada recomendado.

## Especialistas subordinados
- `ux-ui-strategist.agent.md` — UX, fluxos, arquitetura da informacao e usabilidade.
- `visual-director.agent.md` — direcao de arte, tipografia, grid, cor e composicao.
- `design-system-architect.agent.md` — tokens, variables, components, variants e Auto Layout.
- `figma-mcp-operator.agent.md` — operacao e inspecao do Figma via MCP.
- `motion-threejs-director.agent.md` — GSAP, ScrollTrigger, Three.js, parallax e storytelling cinematografico.
- `accessibility-auditor.agent.md` — WCAG, contraste, foco, teclado e reduced motion.

## Fluxo recomendado

```text
Pedido do usuario
      |
      v
Analista Figma
      |
      +--> UX UI Strategist
      +--> Visual Director
      +--> Design System Architect
      +--> Figma MCP Operator
      +--> Motion Three.js Director
      +--> Accessibility Auditor
      |
      v
Solucao consolidada
```

## Uso
No VS Code com GitHub Copilot, abra o seletor de agentes e escolha `Analista Figma` para tarefas completas. Use um especialista diretamente quando a tarefa estiver claramente limitada ao seu dominio.

Quando o Figma MCP estiver configurado no ambiente, o `Figma MCP Operator` e o `Analista Figma` devem preferir dados reais do arquivo em vez de estimativas visuais.
