# Como publicar este projeto no GitHub

Repositorio destino:

```text
https://github.com/RikThaylon/equipe-agentes-dev-ia
```

## Situacao atual

O repositorio ja existe, esta publico e ja possui a licenca MIT.

Nesta maquina, o terminal nao encontrou `git` nem `gh`, entao a publicacao local precisa de uma destas opcoes:

- instalar Git e GitHub CLI;
- ou liberar a integracao do GitHub com permissao de escrita para este repositorio.

## Opcao recomendada: publicar pelo terminal

Instale o Git:

```text
https://git-scm.com/download/win
```

Instale o GitHub CLI:

```text
https://cli.github.com/
```

Depois abra o PowerShell nesta pasta e rode:

```powershell
git --version
gh --version
gh auth login
```

Em seguida, publique:

```powershell
git init
git add .
git commit -m "Cria equipe de agentes para desenvolvimento com IA"
git branch -M main
git remote add origin https://github.com/RikThaylon/equipe-agentes-dev-ia.git
git pull origin main --allow-unrelated-histories
git push -u origin main
```

Se o Git pedir para resolver conflito no `LICENSE`, mantenha o arquivo que ja esta no GitHub.

## Atualizar depois

Quando fizer mudancas:

```powershell
git add .
git commit -m "Atualiza equipe de agentes"
git push
```

## Clonar em outro PC

```powershell
git clone https://github.com/RikThaylon/equipe-agentes-dev-ia.git
cd equipe-agentes-dev-ia
```

