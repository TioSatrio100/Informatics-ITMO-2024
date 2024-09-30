# Отчет о лабораторной работе №1: Знакомство с терминалом Linux

## Введение
Я установил виртуальную машину на свой компьютер, вставил диск с linux ubuntu в виртуальную машину и запустил ее. Изучая linux ubuntu, я понял, что ubuntu имеет несколько преимуществ перед windows, например, полные встроенные приложения и полные драйверы.
Во время практики я познакомился с терминалом Linux, создал и запустил bash-скрипты. Цель данной работы - изучить основные команды терминала и работу с файлами.

## Шаги выполнения работы

1. **Создание файла `script.bash`:**<br>

В терминале выполнена команда для создания нового файла:
   ```bash
   touch script.bash
  ```

![touch](https://github.com/user-attachments/assets/8285a85b-c4a3-4ce6-a677-833072e4fa20)


2. **Редактирование файла:**<br>
Открыли файл для редактирования с помощью текстового редактора gedit:

```bash
    gedit script.bash
  ```
![gedit](https://github.com/user-attachments/assets/e174892f-0f7f-44d9-b1a8-5e3bef0ffddc)

В редакторе ввели следующий код:
   ```bash
#!/bin/bash  
echo "Welcome to ITMO University"
  ```
![welcome](https://github.com/user-attachments/assets/c67f1f23-6f1e-45f7-b643-e18d0ae78e1d)

3. **Запуск скрипта:**<br>
Выполнили скрипт в терминале:
   ```bash
     bash script.bash

![bash](https://github.com/user-attachments/assets/96d560fa-9485-4c3b-9596-759461fb1b90)

4. **Редактирование кода**<br>
      ```bash
     #!/bin/bash
     echo "Welcome, $"
   
5. **Выполнить**<br>
   Выполнили команду:
   ```bash
     bash script.bash Vasya Pupkin
   ```
   На экране отобразилось: "Welcome, Vasya Pupkin".
![result](https://github.com/user-attachments/assets/33e0d6a1-e703-481c-91f2-2af59c9603ff)
