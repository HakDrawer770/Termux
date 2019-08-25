#  Termux основы
apt update  -y && apt upgrade && pkg update -y && pkg upgrade - обновление пакетов.
termux-setup-storage - предоставление доступа к файловой системе устройства.
Установка пакетов.
Основные команды
apt list-all – вывод всех доступных пакетов.
apt list-installed – вывод установленных пакетов.
apt install [ имя пакета ]  – установка пакета [ ]. 
apt uninstall [ имя пакета ] – удаление пакета [ ].  
apt reinstall [ имя пакета ] – переустановка пакета [ ].
Полезные пакеты
nnn  –файловый менеджер  для терминала
tree – пакет для отображения графического дерева текущей директории и её поддиректорий.
python, python2 – пакет для работы с языком Python.
git – пакет для работы с серверами GitHub.
wget – пакет для скачивания файлов из интернета.
man – пакет для вывода мануала по командам.
vim, vim-python, neovim – редактор текста, дополнение к Python и более яркий редактор vim.
php – пакет для работы с языком php.
openssh – пакет для работы с ssh-соединениями.
play-audio – пакет для воспроизведения аудио файлов в терминале.
file – пакет для вывода подробной информации о файле.
