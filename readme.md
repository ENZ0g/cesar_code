# Cesar_code

Это простое приложение, которе позоляет зашифровать сообщение алгоритмом, основанном на [шифре Цезаря](https://ru.wikipedia.org/wiki/%D0%A8%D0%B8%D1%84%D1%80_%D0%A6%D0%B5%D0%B7%D0%B0%D1%80%D1%8F) а так же расшифровать и взломать (брутфорсом) его.

Проект я делал для демонстрации своему ученику:
1. Принципа шифрования методом подстановки
2. Способа реализации шифра Цезаря на Python
3. Способа взлома грубой силой
4. Способа реализации проекта как веб приложения

Для возможности шифрования и русских, и английских текстов используется комбинированный алфавит (в веб версии).

Для локального запуска приложения воспользуйтесь инструкцией ниже.

### 1. Консольное приложение

Склонируйте репозиторий

`git clone https://github.com/ENZ0g/cesar_code.git`

Перейдите в склонированный репозиторий и далее в папку `local_cesar`

`cd ceasr_code/local_cesar`

Запустите приложение

`python3 local_cesar.py`

### 2. Веб приложение

![web interface img](web_cesar_interface.png)

Склонируйте репозиторий

`git clone https://github.com/ENZ0g/cesar_code.git`

Перейдите в склонированный репозиторий и далее в папку `web_cesar`

`cd ceasr_code/web_cesar`

Для работы приложения требуется фреймворк bottle. Установить можно командой:

`pip install -r requirements.txt`

Запустите сервер

`python3 server.py`

Перейдите в браузер по указанному адресу.
Для доступа к странице брутфорса необходимо дополнить адрес `/bruteforce`.
