# Kittygram_backend

## Описание
Этот проект служит бэкенд приложением для интернет-прлощадки Kittygram. Где владельцы своих котов могут выставлять их на показ включая имя, цвет, дату рождения и даже фото, а так же отмечать достижения питомца. Благодаря данному ресурсу хозяева кошачих смогут создать реестр своих питомцев.

**Инструменты и стек:** #Python #Django #API #Pillow #Djoser #Djangorestframework #Python-dotenv #JSON #Postman #PyCharm

## Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:
```bash
git clone https://github.com/yandex-praktikum/kittygram_backend.git
```
```bash
cd kittygram_backend
```

Cоздать и активировать виртуальное окружение:
```bash
python3 -m venv env
```

* Если у вас Linux/macOS
    ```bash
    source env/bin/activate
    ```

* Если у вас windows
    ```
    source env/scripts/activate
    ```
Обновить установщик пакетов:
```bash
python3 -m pip install --upgrade pip
```

Подготовить .env файл:
```bash
nano .env
```
```nano
SECRET_KEY=<секретный ключ проекта Django>
DEBUG=False
```

Установить зависимости из файла requirements.txt:
```bash
pip install -r requirements.txt
```

Выполнить миграции:
```
python3 manage.py migrate
```

Запустить проект:
```
python3 manage.py runserver
```

## Примеры запросов
Добавить питомца: POST `/cats/add` \
Редактировать питомца: PUTCH `/cats/edit` \
Просмотр питомца: GET `/cats/{cat_id}`

## Об авторе
Python-разработчик
> [AxeUnder](https://github.com/AxeUnder/).
