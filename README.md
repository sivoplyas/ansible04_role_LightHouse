# Роль Lighthouse (08-ansible-04-role-lighthouse)
Описание: устанавливает Lighthouse

### Платформa
ubuntu: [22.04]

### Минимальная верия ansible
2.10

### Переменные роли

|Имя|Значение по умолчанию|Описание|
|---|---|---|
|lighthouse_web_user|www-data|Пользователь|
|lighthouse_web_port|8080|Порт|		 
|lighthouse_repository|https://github.com/VKCOM/lighthouse.git|Статическая переменная указывающая repository| 
|vector_directory|/opt|Статическая переменная указывающая каталог установки|

### Автор
ssa

### Лицензия
MIT
