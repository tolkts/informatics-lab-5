# Лабораторная работа 5

## Задание 1 - Автоматизация проверки формата файлов при коммите

Создаем новый файл с проверкой в `.git/hooks`:

![image](https://github.com/user-attachments/assets/155a4533-30bb-4468-acae-a80d9570923a)

Наполняем его содержимым например проверкой на пустоту файла:

![image](https://github.com/user-attachments/assets/db1f98f2-d39e-44ec-859f-7be578c1173a)

Пробуем добавить пустой текстовый файл:

![image](https://github.com/user-attachments/assets/e656ce65-d953-4317-8e0c-6a8c37a30c9c)
В коммите отказано.

Заполняем файл и коммитим снова:

![image](https://github.com/user-attachments/assets/4fe67f7c-31db-478b-8036-9d641e884622)
Коммит удался.

__Вывод: скрипт работает__

## Задание 2 - Использование Git Flow в проекте

## Feature
Инициализируем создаем фичу git-flow:

![image](https://github.com/user-attachments/assets/57b158e4-ad57-4c81-be72-f77e81aa3977)

Теперь наполняем ее содержимым и соединяем обратно с нашей веткой `develop`:

![image](https://github.com/user-attachments/assets/debaac9a-7ca3-4a9c-a057-31975e3d5076)

## Release

Создаем релиз:

![image](https://github.com/user-attachments/assets/a95ea45d-6cb5-4304-9cba-9ea67a507f49)

Выпускаем релиз:

![image](https://github.com/user-attachments/assets/accdb14d-e6c3-480b-9e23-6039b4fc8986)

## Hotfix

Делаем хотфикс:

![image](https://github.com/user-attachments/assets/7b08fa7f-8387-431e-ad9b-aae01bd95184)

Завершаем работу над хотфиксом:

![image](https://github.com/user-attachments/assets/48e8b4cf-4d9c-4527-a280-2027cca99f31)

## Push

Пушим изменения на репозиторий:

![image](https://github.com/user-attachments/assets/c21f6f35-3aed-4d77-bfca-779f785bf32c)
