# How_srat_raylib_ubuntu
c++,ubuntu
Как скачать рэйлиб на убунту,используя vscode

Пошаговая инструкция:

Шаг 1: Установите raylib и необходимые зависимости

Откройте терминал и выполните следующие команды:


sudo apt-get update

sudo apt-get install build-essential git libasound2-dev libx11-dev libxrandr-dev libxi-dev libgl1-mesa-dev libglu1-mesa-dev


Затем склонируйте репозиторий raylib и перейдите в его каталог:


git clone https://github.com/raysan5/raylib.git


cd raylib/src


Соберите и установите библиотеку:


make PLATFORM=PLATFORM_DESKTOP


sudo make install


Шаг 2: Cкачайте зип файл и распакуйте его в пустой каталог,используя vscode,чтоб открыть этот каталог как проект.
Затем измените файл таскс на тот который был в зипке




Шаг 3: Соберите проект

Нажмите Ctrl + Shift + B (или выберите Build Task в меню Terminal), чтобы запустить задачу построения. Это создаст исполняемый файл main в каталоге вашего проекта.

Шаг 4: Запустите проект

Откройте терминал и перейдите в каталог вашего проекта. Затем запустите исполняемый файл:


./main


Это все! Теперь вы можете создавать свои собственные игры и приложения с помощью raylib в VSCode на Ubuntu.
