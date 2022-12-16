[< к содержанию](./readme.md)

[< предыдущая часть](./push.md)

## git status

Проверить состояние файлов в рабочем каталоге можно командой git status. После клонирования консоль выведет примерно такую информацию:

```
On branch master
Your branch is up to date with ‘origin/master’.

nothing to commit, working tree clean
```
Теперь отредактируем файлы и сравним статус:

```
>git status
On branch master
Your branch is up to date with ‘origin/master’.
Untracked files:
(use “git add <file>...” to include in what will be committed)
	Program.cs
	SomeConsoleApp.csproj
	SomeConsoleApp.sln
nothing added to commit but untracked files present (use “git add” to track)
```

Теперь зафиксируем изменения. В коммит войдут только те файлы, которые вы изменили и добавили командой git add. Остальные будут лишь дополнительными файлами в каталоге проекта.

[> следующая часть](end.md)

[> ссылки на источники](./links.md)