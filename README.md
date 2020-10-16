# srm
## Command description
The srm command was created for careful file deletion, files and directories are deleted by the `srm file name` command,
after executing the command, the script checks if the ~/RECYCLE directory exists, if not, it creates it,
then the files are moved to the ~/RECYCLE directory, then automatically compressed with the gzip command,
then the command checks for old files in the directory deleted 7 days ago,
if there are any, then in ~/RECYCLE all files and directories deleted 7 days ago are deleted.

# Command setup

- Download the srm file to your home directory
- Run the command `mkdir ~/bin`
- Then execute `echo export PATH="${PATH}:~/bin" >> ~/.bash_profile`
- Next, move the previously downloaded srm file to the bin directory, you can do this with the command `mv ~/srm ~/bin`
- Run the command `chmod +x ~/bin/srm`
- Reconnect to server

Everything is ready! You can use

# srm
## Описание команды
Команда srm создана для бережного удаление файлов, файлы и директории удаляются командой `srm имя файла`,
после выполнения команды, скрип проверяет существует ли директория ~/RECYCLE, если нет то создает ее,
далее файлы перемещаются в директорию ~/RECYCLE, затем автоматически сжимаются командой gzip,
далее команда проверяет на наличие старых файлов в директории удаленных 7 дней назад, 
если такие имеются то в ~/RECYCLE удаляются все файлы и директории удаленные 7 дней назад.

# Установка команды

- Скачайте файл srm в домашнюю директорию 
- Выполните команду `mkdir ~/bin`
- Далее выполните `echo export PATH="${PATH}:~/bin" >> ~/.bash_profile`
- Далее переместите ранее скаченый файл srm в директорию bin можно сделать это командой `mv ~/srm ~/bin`
- Выполните команду `chmod +x ~/bin/srm`
- Переподключить к серверу

Все готово! Можно пользоваться
