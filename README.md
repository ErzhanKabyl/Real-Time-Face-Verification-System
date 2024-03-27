Этот проект представляет собой систему верификации лиц в реальном времени, которая использует веб-камеру для захвата изображений и сравнивает лица на них с изображениями в базе данных.

Функциональные возможности:

Создание базы данных лиц из изображений в заданной папке.
Верификация лиц в реальном времени с помощью веб-камеры.
Оповещение о неизвестных лицах с отправкой фото в Telegram.
Требования:

Python 3.7+
Библиотеки: requests, cv2, numpy, os, insightface, datetime, dotenv.
Telegram bot с API токеном и chat ID.

Использование:

Создайте .env файл и добавьте в него:

TOKEN: Telegram bot API token.
CHAT_ID: Telegram chat ID.

Установите библиотеки:
pip install requests
pip install opencv-python
pip install numpy
pip install insightface
pip install datetime
pip install dotenv

Запустите скрипт:
python main.py

Дополнительные сведения:

faces: Папка с изображениями для создания базы данных лиц.
unknown_face: Папка для сохранения изображений неизвестных лиц.
main.py: Главный файл проекта.
requirements.txt: Файл с описанием зависимостей.
