[к содержанию](/readme.md)

## git diff
---
Команда git diff используется для вычисления разницы между любыми двумя Git деревьями. Это может быть разница между вашей рабочей копией и индексом (собственно git diff), разница между индексом и последним коммитом (git diff --staged), или между любыми двумя коммитами (git diff master branchB).

**Пример**	&#128161;

*Следующие команды можно запускать для сравнения изменений в конкретном файле:*

```
    git diff HEAD <file_name>
    git diff <file_name>
    git diff --staged <file_name> или git diff --cached <file_name>
    git diff <branch_name1> <branch_name2> <file_name>
    git diff <commit_hash> <commit_hash> <file_name>
```
[&#11013;](/pages/commit.md) |  [&#10145;](/pages/difftool.md)