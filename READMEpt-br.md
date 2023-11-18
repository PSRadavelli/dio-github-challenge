# Desafio DIO
# This description is also avaiable in [English](https://github.com/PSRadavelli/dio-github-challenge/blob/develop/README.md)
Desafio de projeto sobre Git/Github

Referencias para se informar sobre git:

Seja sábio! Git não significa apenas GitHub. Git é uma ferramenta de controle de versão, e o GitHub é um site para hospedar código que utiliza a ferramenta Git. Existem muitos repositórios de código diferentes na internet, como GitLab e BitBucket.

https://git-scm.com/doc

https://learn.microsoft.com/pt-br/devops/develop/git/what-is-git

https://www.atlassian.com/git/tutorials/what-is-git

https://www.w3schools.com/git/git_intro.asp?remote=github

## SSH Authentication

Apos fazer seu registro em algum Hub de codigos seja o GitHub, GitLab ou Bitbucket é sempre interessante se autenticar de forma com SSH, por questoes de segurança, apenas voce ou pessoas com permissao poderao clonar seus repositorios privados, e enviar o codigo para o seu HUB pelas autenticações feitas por SSH


O que é SSH:
https://resultadosdigitais.com.br/marketing/ssh/

Github SSH: https://docs.github.com/pt/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

GitLab SSH: https://docs.gitlab.com/ee/user/ssh.html

BitBucket SSH: https://bitbucket.org/account/settings/ssh-keys/

### Alterar comentário do git com amend

Para modificar o comentário do git, utilize o comando amend:

```bash
git commit --amend -m "novo comentário do git"
```

Se você não adicionar o sufixo '-m "comentário" ', ele entrará no modo editor VIM para que você possa editá-lo.

### Redefinir Commits

Obtenha o hash do commit com o comando `git log`:

```bash
git reset --soft <hashdoCommit>
```

Remove os commits posteriores e os adiciona à área de preparação (staging).

```bash
git reset --mixed <hashdoCommit>
```

O comando padrão de reset do git, adiciona os commits posteriores aos nossos arquivos rastreados.

```bash
git reset --hard <hashdoCommit>
```

Exclui diretamente todos os arquivos de commit posteriores.

### Remover do Rastreamento

Utilize o comando `git restore` para remover do rastreamento:

```bash
git restore <nomeDoArquivo>
```

### Clonar Apenas um Ramo do Repositório

Clone apenas um ramo do repositório usando o seguinte comando:

```bash
git clone -b nome_do_ramo --single-branch <URLdoRepositório>
```

Exemplo:

```bash
git clone -b desenvolvimento --single-branch https://github.com/PSRadavelli/webpack-study
```

### Aplicar Stash

Aplique o stash para salvar as diferenças no ramo para uso posterior:

```bash
git stash apply
```

