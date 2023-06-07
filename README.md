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

| Command           |Keys                   |Plugin
|-------------------|-------------------    |--------
| New session       | PREFIX -> Shift+C     |Sessionist
| Choose session    | PREFIX -> s           |
| Detach session    | PREFIX -> d           |
| Rename session    | PREFIX -> $           |
| Next session      | PREFIX -> )           |Sessionist
| Kill session      | PREFIX -> X           |Sessionist

###  Windows
| Comand                               | Keys
| ------------------------------------ | -----------
| Создать окно                         | PREFIX -> c
| Сменить окно                         | PREFIX -> 0
| Режим прокрутки scroll               | PREFIX -> \[ (q - exit)
| Переимновать окно                    | PREFIX -> ,
| Kill window                          | Ctrl + d

### Panes
| Comand                               | Keys 
| ------------------------------------ | -----------------
| Разбить панель горизонтально         | PREFIX -> " 
| Разбить панель вертикально           | PREFIX -> % 
| Изменить размеры панели              | PREFIX -> hjkl (нажимать быстро для повтора) 
| Закрыть панель                       | PREFIX -> x

### Конфигурация
[[tmux PurpleSchool configuration]]

```bash
vim ~/.tmux.conf
```

