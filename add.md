[< к содержанию](./readme.md)

[< предыдущая часть](./Git_init.md)
## git add


**git add *[файл]*** — добавляет файл в индекс.

Чтобы добавить все файлы в каталоге в индекс (кроме игнорируемых), используйте команду:


```bash-
git add .
```

Конечно добавлять всё сразу удобнее, чем прописывать каждую позицию отдельно. Однако, тут надо быть внимательным, чтобы не добавить по ошибке ненужные элементы. Если же такое произошло изъять оттуда ошибочный файл можно при помощи команды

``` bash-
git reset:

git reset (название файла)/(файл).(расширение файла)
```

[> следующая часть](./commit.md)