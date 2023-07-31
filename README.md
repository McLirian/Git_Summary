# Основы работы с Git (Яндекс Практикум)

VCS - Version Control System (система контроля версий) <br>
SCM - Source Control Managment (система управления исходным кодом) <br>
Одно изменение или группу изменений в VCS называют ревизией или версией. <br>

## Работа с командной строкой

pwd      - выводит путь к текущей директории (print working directory) <br>
cd       - сменить директорию (change directory) <br>
cd ~     - перейти к домашней директории <br>
cd ..    - перейти на уровень выше <br>
cd .     - обратиться к текущей директории <br>
ls       - отобразить содержимое директории (list directory content) <br>
ls -a    - отобразить расширенный список содержимого директории <br>
touch    - создать файл в текущей директории <br>
mkdir    - создать директорию <br>
mkdir -p - создать структуру директорий <br>
cp       - копировать (принимает 2 параментра "что копируем" и "куда копируем") <br>
mv       - переместить файл или папку (синтаксис аналогичен команде **cp**) <br>
cat      - прочитать файл (concatenate and print). Работает только с текстовыми файлами <br>
rm       - удалить файл <br>
rmdir    - удалить папку (если она пуста) <br>
rm -r    - удалить папку со всем содержимым <br>

## Инициализация репозитория

git init - сделать папку репозиторием <br>
rm -rf .git - "разгитить" папку <br>
git status - показать текущее состояние репозитория <br>
git add - подготовить файлы к сохранению <br>
git commit - сделать коммит <br>
git commit -m - сделать коммит и присвоить ему сообщение <br>

## SSH

SSH - Secure Shell Protocol. Сетевой протокол, обеспечивающий безопасный обмен данными.


SSH использует паруключей: <br>
*приватный ключ* - хранится только на компьютере и используется для расшифровки данных <br>
*публичный ключ* - доступен всем и используется для шифрования данных <br>
ssh-keygen - генерация SSH gfhs <br>