    Как создать ключ:
пишем в терминал ssh-keygen -t ed25519 -C "shakhzadov.kd@phystech.edu"
нажимаем enter, чтобы пропустить пароль
    Как добавить ключ на ГитХаб:
Открываем ГитХаб
открываем settings(настройки)
Нажимаем SSH and GPG keys
Нажимаем new SSH key
Копируем туда содержимое публичного ключа
    Как использовать приватный ключ:
ssh-add ~/.ssh/id_ed25519
    Как склонировать репозиторий:
git clone git@github.com:username/repository.git
меняем username и repository на свои
    Как добавить файл:
git add file.txt