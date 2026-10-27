# Piscine Hack
Полезные команды для прохождения бассейна в Tomorrow School


## Настройка Git на только что запущенном компьютере
Все команды нужно ввести в Terminal

1. Сохраняет username и password, чтобы не вводить постоянно

```sh 
git config --global credential.helper store
```



2. Клонируем репозиторий:

```sh 
git clone 
```

3. Сохраняем автора коммитов 

*измените файл README и вставьте свои значения, чтобы каждый раз не вводить вручную, а просто копировать отсюда:
```sh
git config --global user.name "Your name"
git config --global user.email "email@example.com"
```

## Основные Linux команды

4. После клонирования должна появиться папка piscinego. Чтобы увидеть нужно

Посмотреть содержимое текущей папки:
```sh
ls
```

Зайти в папку через терминал: 
```sh
cd piscinego
```

Открыть папку в кодовом редакторе VS Code:
```sh
code . 
```

Чтобы выйти из папки на уровень вверх:
```sh
cd ..
```

## Как проверить статус файлов в системе Git
```sh 
git status
```

## Как отправить изменения в Gitea
1. Добавить файлы в Git

Добавить отдельные файлы:
```sh 
git add hello.go file2 file3
``` 

Добавить все файлы:
```sh 
git add . 
```

2. Сделать commit, в кавычках написать любой текст с описанием изменений
```sh 
git commit -m "" 
```

3. Отправить изменения в репозиторий Gitea
```sh 
git push 
```



## Golang

### Запуск Go файлов

```sh
go run .
```


```sh
go run main.go
```

### Go ошибки форматирования
Проверить Go файл на ошибки и форматирование

```bash
gofumpt -d .
```

Автоматическое исправление форматирования
```bash
gofumpt -w .
```

### Ресурсы

Вводное видео:
https://www.youtube.com/playlist?list=PLIb1whG82v48

Quest 2, Урок 1:
https://www.youtube.com/watch?v=5pweJaeWnwc

Quest 2, Урок 2:
https://www.youtube.com/watch?v=vG2w-NC8Bew

typist.online

