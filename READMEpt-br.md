# Desafio DIO Git/GitHub, este repositório também está disponível em [Português](https://github.com/PSRadavelli/dio-github-challenge/blob/develop/READMEpt-br.md)

Bem-vindo ao Desafio DIO Git/GitHub! Este projeto foi desenvolvido para aprimorar o seu entendimento sobre Git e GitHub, a dinâmica dupla de controle de versão e hospedagem de código. Este desafio é uma oportunidade fantástica para aprofundar seus conhecimentos, seja você um desenvolvedor experiente ou iniciante.

## Sobre o Git

O Git é mais do que apenas o GitHub! É uma poderosa ferramenta de controle de versão que capacita os desenvolvedores a rastrear alterações, colaborar de forma eficiente e gerenciar o histórico do projeto. Embora o GitHub seja uma plataforma popular para hospedar código usando o Git, é essencial explorar outros repositórios como GitLab e Bitbucket. Amplie seus horizontes e descubra a vasta paisagem do controle de versão.

### Recursos para Dominar o Git

- [Documentação Oficial do Git](https://git-scm.com/doc)
- [Guia Git da Microsoft](https://learn.microsoft.com/pt-br/devops/develop/git/what-is-git)
- [Tutoriais Git da Atlassian](https://www.atlassian.com/git/tutorials/what-is-git)
- [Introdução ao Git no W3Schools](https://www.w3schools.com/git/git_intro.asp?remote=github)

## Autenticação SSH

Garanta a segurança da sua conta no repositório configurando a Autenticação SSH. Isso adiciona uma camada extra de proteção, permitindo que você clone repositórios privados e envie alterações de forma segura usando chaves SSH.

### O que é SSH?

SSH (Secure Shell) é um protocolo criptográfico de rede para comunicação segura de dados. Saiba mais sobre isso [aqui](https://www.techtarget.com/searchsecurity/definition/Secure-Shell).

### Configurar SSH para o Seu Repositório

- [Configuração SSH no GitHub](https://docs.github.com/pt/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
- [Configuração SSH no GitLab](https://docs.gitlab.com/ee/user/ssh.html)
- [Configuração SSH no BitBucket](https://bitbucket.org/account/settings/ssh-keys/)

## Dicas e Truques Profissionais

Aprimore sua experiência com o Git com esses comandos e dicas úteis:

- **Editor Online do GitHub:** Pressione '.' no GitHub para acessar o editor online diretamente.
- **Magia do Gitkeep:** Crie um arquivo ".gitkeep" em uma pasta para fazer o Git reconhecer a pasta.
- **Alterar Comentário do Git:** Altere o comentário do seu último commit usando `git commit --amend -m "novo comentário git"`.
- **Revertendo Commits:** Use `git reset` para desfazer commits seletivamente com base no hash.
  - `--soft`: Mantém alterações na área de staging.
  - `--mixed`: Padrão, adiciona alterações aos arquivos rastreados.
  - `--hard`: Exclui alterações diretamente.
- **Remover do Rastreamento:** Deixe de rastrear alterações com `git restore <nome-do-arquivo>`.
- **Clonar Ramo Específico:** Clone apenas um ramo com `git clone -b nome-do-ramo --single-branch <URL-do-repositório>`.
  - Exemplo: `git clone -b develop --single-branch https://github.com/PSRadavelli/webpack-study`

## Adicionar, Commitar e Enviar

Agora, vamos mergulhar nos passos fundamentais para contribuir com um repositório Git:

- **Adicionar Alterações à Área de Staging:** Use `git add <nome-do-arquivo>` para colocar alterações na próxima confirmação. Você também pode usar `git add .` para adicionar todas as alterações.

- **Commitar Alterações:** Após colocar na área de staging, comite as alterações com `git commit -m "Sua mensagem de commit aqui"`. Isso registra suas alterações no histórico do projeto.

- **Enviar Alterações para o Repositório Remoto:** Finalmente, use `git push` para enviar suas alterações confirmadas para o repositório remoto, tornando-as acessíveis aos colaboradores.

## Guarde para Mais Tarde

Guarde suas alterações de código para uso futuro, especialmente após fusões ou operações semelhantes.

- Salve as alterações com `git stash`.
- Veja as alterações salvas com `git stash list`.
- Aplique as alterações salvas com `git stash apply`.
- Aplique de um índice específico do stash usando `git stash apply stash@{0}`.
- Aplique e remova da lista com `git stash pop stash@{0}`.

Feliz codificação, e que sua jornada com o Git seja tranquila e produtiva! 🚀✨
