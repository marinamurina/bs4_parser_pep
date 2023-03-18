# Проект парсинга для документации Python.

Парсер дает возможность получить актуальную информацию о нововведениях в языке Python, данные о версиях, скачать документацию, узнать о статусах PEP.

## Установка:
* склонируйте репозиторий 
* в папке проекта создайте и активируйте виртуальное окружение:
    * python3 -m venv venv
    * source venv/bin/activate (Linux, MacOS), venv/Scripts/acrivate (Win)
* установите необходимые пакеты:
    * pip install --upgrade pip
    * pip install -r requirements.txt

## Функции:
Запуск производится из командной строки - python main.py <имя команды>.

Команды (парсеры):

* whats_new - cобирает ссылки на статьи о нововведениях в Python. 

Формат вывода: Ссылка на статью, Заголовок, Редактор, Aвтор.

* latest_versions - собирает информацию о версиях Python. 

Формат вывода: Ссылка на документацию, Версия, Статус.

* download - скачивает архив с документацией Python.

* pep - собирает информацию о количестве PEP в каждом статусе.

## Выбор форматов для вывода:
-o {pretty,file}, --output {pretty,file}
* pretty - таблица в терминале
* file - файл .csv
* вывод по умолчанию - терминал, построчно

## Дополнительно:
-c, --clear-cache Очистка кеша

## Автор:

Марина Мурина https://github.com/marinamurina