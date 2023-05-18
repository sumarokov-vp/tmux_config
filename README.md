[[tmux PurpleSchool configuration]]

### Команды bash

```bash
tmux new -s session1

tmux ls #sessions list
tmux attach
tmux attach -t session1

tmux kill-session -t session1

tmux kill-server

tmux list-commands
man tmux
```

### Sessions
>[!info]
Use sessionist plugin [[tmux PurpleSchool configuration]]

| Command|Keys|Plugin|
|-----------|-----|--|
|New session|^+B -> Shift+C |Sessionist
| Choose session                        | ^+B -> s            |
| Detach session             | ^+B -> d            |
| Rename session                 | ^+B -> $            |
|Next session|^+B -> )|Sessionist

### Rename window

```bash
vim ~/.tmux.conf

Создать строку в файле: set-option -g allow-rename off

Обновить настройки:
tmux source-file ~/.tmux.conf

Ctrl<B> ,
```



| Comand                               | Keys              |
| ------------------------------------ | ----------------- |
| Создать окно                         | ^+B, c            |
| Сменить окно                         | ^+B, 0; ^+B, 1    |
| Режим прокрутки scroll               | ^+B, \[ (q - exit)|
| Разбить панель вертикально           | ^+B, %            |
| Переход между вертикальными панелями | ^+B, ←            |
| Разбить панель горизонтально         | ^+B, "            |
| Отключиться от сессии                | ^+B, d            |
| Выбор сессии                         | ^+B, s            |
| Переименовать сессию                 | ^+B, $            |
| Переимновать окно                    | ^+B, ,            |
| Закрыть панель                       | exit              |

### Конфигурация

```bash
vim ~/.tmux.conf
```

| Comand                   | Description                               |
| ------------------------ | ----------------------------------------- |
| set-option -g prefix C-q | Сменить основной хоткей на ^+Q вместо ^+B |
| set -g mouse on          | Можно мышкой менять размер экрана         |
|                          |                                           |
|                          |                                           |
|                          |                                           |
|                          |                                           |
|                          |                                           |

```

```


