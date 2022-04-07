# Introdução ao Git e GitHub

Abaixo terão anotações de comandos do curso.

### Comandos novos aprendidos sobre terminal Windows

 - Deletar arquivos no Windows: del "nome do diretório onde fica arquivos ou nome do arquivo"
 - Deletar diretórios no Windows: rmdir "nome do diretório" /Q /S

### Comandos para gerar SSH para GitHub

 - Gerar Chave SSH: ssh-keygen -t ed25519 -C "e-mail"
 - Ir na pasta .ssh e dar comando: cat id_ed25519.pub
 - Executar entidade que lida com chaves: eval $(ssh-agent -s)
 - Passar chave ao agente: ssh-add id_ed25519

### Comandos do Git

- Configurar parametro na config do Git: git config --global "parametro"
- Resetar algum parametro da config do Git: git config --global --unset "parametro"