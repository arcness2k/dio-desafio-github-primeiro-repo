# Download Git

https://git-scm.com/downloads

- SHA1 - Chave 40 caracteres (alterado por modificações no texto)
- Objetos Fundamentais
  - BLOBS
  - TREES
  - COMMITS (principal)
- Sistema distribuido seguro



1) Chave SSH: Publica x Privada
   1) Criar chave no Bash:
      1) ssh-keygen -t ed25519 -C <email>
   2) Exibir chave no Bash:
      1) cat id_ed25519.pub
   3) Inicia processo no Bash:
      1) eval $(ssh-agent -s)
   4) Entregar chave no Bash:
      1) ssh-add id_ed25519
2) Clone de acesso pessoal
   1) Gerar token (verificação em duas etapas)
      1) git clone by https
3) Iniciar Repo Git = git init
4) Adicionar Repo = git add (*/./<name>)
5) Subir commit = git commit
6) git status
7) git push origin master/main
8) git pull origin master/main
9) git clone <url>
10) mkdir = novo diretório
11) ls = listar diretórios