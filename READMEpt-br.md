# Desafio Git/GitHub da DIO

Bem-vindo ao Desafio Git/GitHub da DIO! Este projeto foi criado para aprimorar seu conhecimento sobre Git e GitHub, a dinâmica dupla de controle de versão e hospedagem de código. Seja você um desenvolvedor experiente ou iniciante, este desafio é uma oportunidade fantástica para aprofundar seus conhecimentos.

## Sobre o Git

Git é mais do que apenas o GitHub! É uma poderosa ferramenta de controle de versão que capacita os desenvolvedores a rastrear alterações, colaborar de forma eficiente e gerenciar o histórico do projeto. Enquanto o GitHub é uma plataforma popular para hospedar código usando o Git, é essencial explorar outros repositórios de código, como GitLab e Bitbucket. Expanda seus horizontes e descubra a vasta paisagem do controle de versão.

### Recursos para Dominar o Git

- [Documentação Oficial do Git](https://git-scm.com/doc)
- [Guia Git da Microsoft](https://learn.microsoft.com/pt-br/devops/develop/git/what-is-git)
- [Tutoriais Git da Atlassian](https://www.atlassian.com/git/tutorials/what-is-git)
- [Introdução ao Git do W3Schools](https://www.w3schools.com/git/git_intro.asp?remote=github)

## Autenticação SSH

Garanta a segurança da sua conta no repositório de código configurando a Autenticação SSH. Isso adiciona uma camada extra de proteção, permitindo que você clone repositórios privados e envie alterações com segurança usando chaves SSH.

### O que é SSH?

SSH (Secure Shell) é um protocolo criptográfico de rede para comunicação segura de dados. Saiba mais sobre isso [aqui](https://www.techtarget.com/searchsecurity/definition/Secure-Shell).

### Configurando SSH para seu Repositório

- [Configuração SSH no GitHub](https://docs.github.com/pt/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
- [Configuração SSH no GitLab](https://docs.gitlab.com/ee/user/ssh.html)
- [Configuração SSH no BitBucket](https://bitbucket.org/account/settings/ssh-keys/)

## Dicas e Truques Profissionais

Aprimore sua experiência com o Git com esses comandos e dicas úteis:

- **Editor Online do GitHub:** Pressione '.' no GitHub para acessar o editor online diretamente.
- **Magia do Gitkeep:** Crie um arquivo ".gitkeep" em uma pasta para forçar o Git a reconhecer a pasta.
- **Alterar Comentário do Git:** Altere o comentário do seu último commit usando `git commit --amend -m "novo comentário do git"`.
- **Redefinir Commits:** Use `git reset` para desfazer commits seletivamente com base no hash.
  - `--soft`: Mantém alterações na área de preparação.
  - `--mixed`: Padrão, adiciona alterações aos arquivos rastreados.
  - `--hard`: Exclui alterações diretamente.
- **Remover do Rastreamento:** Desfaça o rastreamento de alterações com `git restore <nome_do_arquivo>`.
- **Clonar Ramo Específico:** Clone apenas um ramo com `git clone -b nome_do_ramo --single-branch <URL_do_repositório>`.
  - Exemplo: `git clone -b develop --single-branch https://github.com/PSRadavelli/webpack-study`

## Guarde para Depois com o Stash

Guarde suas alterações de código para uso futuro, especialmente após merges ou operações semelhantes.

- Salve as alterações com `git stash`.
- Visualize as alterações salvas com `git stash list`.
- Aplique as alterações salvas com `git stash apply`.
- Aplique de um índice específico com `git stash apply stash@{0}`.
- Aplique e remova da lista com `git stash pop stash@{0}`.

Feliz codificação, e que sua jornada com o Git seja suave e produtiva! 🚀✨
