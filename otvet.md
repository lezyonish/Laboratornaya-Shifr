# Новицкая Елизавета Максимовна К3162 
# Отчет по созданной лабораторной работе 

1) Я установила gpg через homebrew по примеру в отчете:


<img width="500" src="3.png"/>


2) Проверка:


<img width="500" src="4.png"/>


3) Далее создала текстовый файл `tekst.txt`


<img width="500" src="5.png"/>


4) Открыла терминал и набрала указанную в задании команду `gpg -c tekst.txt` , чтобы зашифровать файл, далее система потребовала придумать пароль, моим паролем было мое имя - Елизавета. 


<img width="500" src="6.png"/>


5) Затем я ввела команду `nano tekst.txt.gpg` чтобы проверить шифровку


<img width="500" src="7.png"/>
 
Текст зашифрован

6) Я расшифровала файл, используя команду из задания, система вновь попросила пароль


<img width="500" src="8.png"/>

7) Я создала каталог, файлы, а так же текст в них.

<img width="500" src="10.png"/>

<img width="500" src="11.png"/>

<img width="500" src="9.png"/>



8) Затем архив, по указанной команде


<img width="500" src="12.png"/>

9) Далее зашифровала его через  `gpg -c test_directory.tar`, появился файл `test_directory.tar.gpg`, который я разархивировала через `gpg test_directory.tar.gpg`, где находились зашифрованные файлы



**Таким образом я закончила лабораторную работу, обучившись новым знаниям в этой сфере**