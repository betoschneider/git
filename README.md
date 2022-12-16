# GIT: Comandos, links e tutoriais

## tutorial git Github
### primeiros passos (esse video me ajudou muito!)
* https://www.youtube.com/watch?v=UBAX-13g8OM
### git com arquivos binários (pbix e xlsx por exemplo)
* https://www.youtube.com/watch?v=6OokP-NE49k&t=1020s (minuto 24:48)
### acertando commits
* https://www.youtube.com/watch?v=6OokP-NE49k&t=1020s (minuto 3:10)

## Links úteis:
### Configurar acesso bash Github
* https://blog.cod3r.com.br/autenticacao-no-github-pela-linha-de-comando/
* https://www.alura.com.br/artigos/nova-exigencia-do-git-de-autenticacao-por-token-o-que-e-o-que-devo-fazer
* https://www.horadecodar.com.br/2022/02/17/como-remover-remote-origin-de-repositorio-em-git/
* https://stackoverflow.com/questions/19730565/how-to-remove-files-from-git-staging-area
* https://www.horadecodar.com.br/2021/10/26/como-desfazer-um-git-reset-no-repositorio/
* https://www.atlassian.com/br/git/tutorials/undoing-changes

## download do lfs
https://git-lfs.github.com/

## principais comandos
* verificar versão instalada: git --version
* iniciar git: git init
* alterar nome do branch: git branch -M "main"
* adicionar arquivo na stage: git add nome_do_arquivo
* remover arquivo da stage: git reset -- nome_do_arquivo
* remover todos os arquivos da stage: git reset --
* adicionar diferentes modificações de um arquivo em commits diferentes: git add -p (no menu, digitar s de split e depois y ou n para adicionar ou não no commit)
* verificar arquivos na stage: git status
* enviar arquivos: git commit -m "comentário do commit"
* empurrar arquivos para o respositório do Github: git push -u origin main
* puxar atualizações remotas: git pull
* sair do editor de mensagem commit pull: :qa!
* criar nova branch: git checkout -b "nova_branch"
* trocar de branch: git checkout branch_desejada
* merge entre as branch: checkout para a nova branch e depois executar: git merge branch_anterior
* binário lfs - iniciar lfs: git lfs install
* binário lfs - adicionar tipos de arquivos ao lfs: git lfs track "*.extensao"
* ver o pach completo de alterações: git diff
* retornar versões anteriores mantendo as alterações: git reset --soft HEAD~n
* retornar versões anteriores mantendo as alterações (no stage): git reset --soft HEAD~n
* retornar versões anteriores e apagar as alterações (CUIDADO): git reset --hard HEAD~n
* excluir um arquivo da pasta (repositório): git rm nome_do_arquivo e depois dar um commit
