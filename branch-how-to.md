# Создать новую ветку
git branch имя_ветки
# Например:
git branch feature-новая-функция

# Переключиться на ветку
git checkout имя_ветки
# Или короче:
git switch имя_ветки
# Например:
git checkout feature-новая-функция

# Перед созданием ветки убедитесь, что вы находитесь в актуальной основной ветке
git checkout main
git pull origin main

# Внести изменения, зафиксировать их
git add .
git commit -m "Описание изменений"

# Отправить ветку на сервер
git push origin имя_ветки
# Например:
git push origin feature-новая-функция
