[к содержанию](/readme.md)

## git rm
---
Команда git rm используется в [Git](/pages/aboutgit.md) для удаления файлов из индекса и рабочей копии. Она похожа на [git add](/pages/add.md) с тем лишь исключением, что она удаляет, а не добавляет файлы для следующего коммита.

**Пример**	&#128161;

*Для того чтобы удалить файл из Git, вам необходимо удалить его из отслеживаемых файлов (точнее, удалить его из вашего индекса) а затем выполнить коммит. Это позволяет сделать команда git rm, которая также удаляет файл из вашего рабочего каталога, так что в следующий раз вы не увидите его как «неотслеживаемый».
Если вы просто удалите файл из своего рабочего каталога, он будет показан в секции «Changes not staged for commit» (измененные, но не проиндексированные) вывода команды git status:*

```
 rm PROJECTS.md
$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        deleted:    PROJECTS.md

no changes added to commit (use "git add" and/or "git commit -a")
```