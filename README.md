# Задача работа с директориями:

 1. Имя получил абсолютное, корневой каталог обозначается / --- 2,3,4 на одном скриншоте

 <img width="733" height="320" alt="image" src="https://github.com/user-attachments/assets/b4d04af7-0c4b-4a0d-8c2c-113add7761e7" />

 5. Вывел man `ls, cd` ругается говорит нет man

 <img width="1009" height="521" alt="image" src="https://github.com/user-attachments/assets/e657d421-6033-4414-89f8-e360c3baf03d" />

 6. `Whatis` - выдает краткую справку по команде, apropos - ищет по ключевому слову во всех man

 7. `info` - выводит развернутую документацию

 8. Создал каталоги

 <img width="488" height="206" alt="image" src="https://github.com/user-attachments/assets/3930e491-1d3d-40af-9010-28fd1f54fd2a" />

 9. Первые 13 `head -n`, последние 13 `tail -n`

 <img width="520" height="583" alt="image" src="https://github.com/user-attachments/assets/e56b58b1-e14c-4f57-87a3-e8fd3e15c8fc" />

 10. Расширение раздела (P.s - 10-2 он ошибочный я при работе с `fdisk` ввёл в `last sector +5G` это решение оказалось не верное потом я просто тапнул `enter` и он расширил на все `40G`, а скриншот не сделался или я его не сделал)

  - Добавил в `wmWare 5 GB`

  - `lsblk` имя диска

  - `sudo fdisk /dev/sda` удалил старый раздел `d`, создал новый `n` с того же сектора назвал sda2, сохранил `w`

  - `sudo partprobe /dev/sda` - перечитал таблицу разделов

  - Перезагрузил OC

  - `df -h` проверил результат

 <img width="522" height="309" alt="image" src="https://github.com/user-attachments/assets/24a4a8cc-5e8d-40af-ac1c-29090a3d8dd6" />

 <img width="1084" height="738" alt="image" src="https://github.com/user-attachments/assets/129f87aa-8caf-446d-a595-283c934f43b5" />

 <img width="654" height="262" alt="image" src="https://github.com/user-attachments/assets/5013423d-5939-4f4c-9318-f5013d2adc97" />


