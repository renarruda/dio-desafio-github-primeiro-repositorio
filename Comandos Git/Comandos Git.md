# **Comandos Git**

[Livro - Pro Git](https://git-scm.com/book/pt-br/v2/Appendix-C%3A-Git-Commands-Setup-and-Config)

### A documentação no [site](https://git-scm.com/doc) do Git é o melhor local para verificar os comandos básicos do Git, porém aqui trarei o comandos básicos para iniciar no mesmo:

- **Git init** - iniciar um repositório - lembre-se da pasta oculta ./git, é nela que seu projeto será iniciado.
- **Git add** - adicionar arquivos de uma máquina local para o servidor remoto do Github, e algumas variações desse código... Git add . / Git add -A ... colocando toda modificação em "stage" para ser comitado.
- **Git commit** - "Envelopar" criar um save (snapashot) com o estado atual do código - após isso, o arquivo é salvo em unmodified, permitindo alterações futuras o qual o levaria ao modo modified e seguindo um novo ciclo...
- **Git status** - traz informações sobre em que estágio o arquivo está!
- **Git commit -m "informação sobre modificações realizadas no arquivo"**  aqui comitamos o arquivo adicionado com o comando git add, criando um Objeto chamado ***commit***, no repositório local.
- **Git push** - ou melhor ***git push origin main***, enviado o arquivo modificado para o repositório no servidor.





