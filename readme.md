# Создание виртуального окружения

## Обращаемся к python, модулю venv и называем local_venv. Программа скопирует python в папку проекта.
![](for_md/1.png)
![](for_md/2.png)
## Активируем python.
Для VS Code нажимаем ctrl+shift+p и выбираем интерпретатор python.
![](for_md/3.png)
![](for_md/4.png)

Команда для windows:
* .\local_venv\Scripts\activate.bat - для запуска с CMD!
* .\local_venv\Scripts\Activate.ps1 - для запуска с PowerShell, терминад VS Code

![](for_md/5.png)
![](for_md/6.png) - для того, чтобы узнать от куда запускается python в PowerShell

# Установка зависимостей

Создаём requirements.txt с перечислением в столбик необходимых библиотек
![](for_md/7.png)\
Запускаем установку пакетов командой:\
**pip install -r requirements.txt**
![](for_md/8.png)

*pip show имя_библиотеки* - информация о библиотеке: версия, описание, автор, лицензия и тп