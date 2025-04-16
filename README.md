# bash
Команды для работы с файлами и папками

```bash

~                                     # Открыть домашнюю директорию через терминал 
pwd                                   # Определить имя папки, в которой вы находитесь
mkdir test1                           # Создать внутри этой папки каталог с именем test1
cd test1                              # Перейти в папку test1
touch file{1,2,3}.txt.                # Создать файл 1,2 и 3 внутри каталога test1
ls                                    # Проверить содержимое каталога test1 
cd                                    # Перейти в домашнюю директорию 
mkdir test2                           # Создать папку test2 внутри домашней директории
rmdir test2                           # Удалить папку test2
rm file2.txt                          # Удалить файл 2 из папки test1
mkdir test3                           # Создать папку в домашней директории test3 и добавить в нее два файла
touch file{4,5}.txt                   # и добавить в нее два файла
rmdir -rf test3                       # Удалить папку test3 
mkdir test4                           # Создать папку test4 в домашней директории
mv ~/test1/file{1,3}.txt ~/test4      # Переместить файлы 1 и 3 из папки test1 в папку test4
echo line11 >> file1.txt              # Добавить в файл 1 три строки со словами line
echo line12 >> file1.txt            
echo line13 >> file1.txt
cat file1.txt                         # Посмотреть содержимое файла 1
echo line31 >> file3.txt              # Добавьте в файл 3 три строки со словами line
echo line32 >> file3.txt
echo line33 >> file3.txt
cat file1.txt file3.txt               # Просмотрите содержимое двух файлов (1 и 3) сразу
nano file1.txt + manual replacement   # Используя один из редакторов замените все строки в файле 1
nano file3.txt + manual replacement 

```

