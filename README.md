# Домашнее задание к занятию 13.1. «Уязвимости и атаки на информационные системы» - Ковбаса Анна

------

### Задание 1

Скачайте и установите виртуальную машину Metasploitable: https://sourceforge.net/projects/metasploitable/.

Это типовая ОС для экспериментов в области информационной безопасности, с которой следует начать при анализе уязвимостей.

Просканируйте эту виртуальную машину, используя **nmap**.

Попробуйте найти уязвимости, которым подвержена эта виртуальная машина.

Сами уязвимости можно поискать на сайте https://www.exploit-db.com/.

Для этого нужно в поиске ввести название сетевой службы, обнаруженной на атакуемой машине, и выбрать подходящие по версии уязвимости.

Ответьте на следующие вопросы:

- Какие сетевые службы в ней разрешены?
![1-1]()

- Какие уязвимости были вами обнаружены? (список со ссылками: достаточно трёх уязвимостей)
[Multiple Vendor Telnet Client - Env_opt_add Heap Buffer Overflow] [id]
[id]: https://www.exploit-db.com/exploits/25303
https://www.exploit-db.com/exploits/47956 Pachev FTP Server 1.0 - Path Traversal
https://www.exploit-db.com/exploits/48038 OpenSMTPD - MAIL FROM Remote Code Execution (Metasploit)
  


### Задание 2

Проведите сканирование Metasploitable в режимах SYN, FIN, Xmas, UDP.

Запишите сеансы сканирования в Wireshark.

Ответьте на следующие вопросы:

- Чем отличаются эти режимы сканирования с точки зрения сетевого трафика?
- Как отвечает сервер?

*Приведите ответ в свободной форме.*
