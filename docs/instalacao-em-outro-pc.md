# Como montar esta equipe em qualquer PC

Este guia serve para baixar a equipe de agentes em outra maquina e usar os mesmos prompts em novos projetos.

## Opcao 1: Baixar pelo GitHub

Quando este projeto estiver em um repositorio publico, use:

```powershell
git clone https://github.com/RikThaylon/equipe-agentes-dev-ia.git
cd equipe-agentes-dev-ia
```

Depois abra a pasta no editor ou no Codex.

## Opcao 2: Baixar ZIP pelo GitHub

1. Abra o repositorio no GitHub.
2. Clique em `Code`.
3. Clique em `Download ZIP`.
4. Extraia a pasta.
5. Abra a pasta no Codex ou no seu editor.

## Requisitos recomendados

Para usar melhor em qualquer PC, instale:

- Git;
- GitHub CLI;
- VS Code ou outro editor;
- Node.js, se seus projetos forem web;
- Python, se seus projetos usarem ML/IA local.

## Instalar Git no Windows

Baixe em:

```text
https://git-scm.com/download/win
```

Depois confirme no terminal:

```powershell
git --version
```

## Instalar GitHub CLI no Windows

Baixe em:

```text
https://cli.github.com/
```

Depois confirme:

```powershell
gh --version
```

Faca login:

```powershell
gh auth login
```

## Criar um repositorio publico manualmente

Se ainda nao existir repositorio:

1. Entre no GitHub.
2. Clique em `New repository`.
3. Escolha um nome, por exemplo `equipe-agentes-dev-ia`.
4. Marque como `Public`.
5. Crie o repositorio.

## Subir esta pasta para o GitHub pelo terminal

Dentro desta pasta:

```powershell
git init
git add .
git commit -m "Cria equipe de agentes para desenvolvimento com IA"
git branch -M main
git remote add origin https://github.com/RikThaylon/equipe-agentes-dev-ia.git
git push -u origin main
```

## Atualizar depois de mudar arquivos

```powershell
git add .
git commit -m "Atualiza prompts e guias da equipe"
git push
```

## Usar em um novo projeto

1. Clone ou baixe esta equipe.
2. Copie a pasta `agents/` para o novo projeto ou mantenha este repositorio como referencia.
3. Preencha `templates/briefing-projeto.md`.
4. Comece com `docs/acionar-equipe.md`.
