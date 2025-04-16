# Домашнее задание к занятию "`Система мониторинга Zabbix. Часть 2`" - `Лебедев Виктор`


### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или  https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
   2. Выполните клонирование данного репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите вверху название занятия и вашу фамилию и имя
      - в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
      - для корректного добавления скриншотов воспользуйтесь [инструкцией "Как вставить скриншот в шаблон с решением](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md)
      - при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md))
   4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`);
   5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
   6. Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.

---

### Задание 1

`Создайте свой шаблон, в котором будут элементы данных, мониторящие загрузку CPU и RAM хоста.`

1. `Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции`
2. `В веб-интерфейсе Zabbix Servera в разделе Templates создайте новый шаблон`
3. `Создайте Item который будет собирать информацию об загрузке CPU в процентах`
4. `Создайте Item который будет собирать информацию об загрузке RAM в процентах`

Решение 1
<img src = "img\img1.jpg" width = 100%>
<img src = "img\img1_1.jpg" width = 100%>
<img src = "img\img1_2.jpg" width = 100%>


---

### Задание 2

`Добавьте в Zabbix два хоста и задайте им имена <фамилия и инициалы-1> и <фамилия и инициалы-2>. Например: ivanovii-1 и ivanovii-2.`

1. `Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции`
2. `Установите Zabbix Agent на 2 виртмашины, одной из них может быть ваш Zabbix Server`
3. `Добавьте Zabbix Server в список разрешенных серверов ваших Zabbix Agentов`
4. `Добавьте Zabbix Agentов в раздел Configuration > Hosts вашего Zabbix Servera`
5. `Прикрепите за каждым хостом шаблон Linux by Zabbix Agent`
6. `Проверьте что в разделе Latest Data начали появляться данные с добавленных агентов`

Результат данного задания сдавайте вместе с заданием 3

---

### Задание 3

`Привяжите созданный шаблон к двум хостам. Также привяжите к обоим хостам шаблон Linux by Zabbix Agent.`

1. `Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.`
2. `Зайдите в настройки каждого хоста и в разделе Templates прикрепите к этому хосту ваш шаблон`
3. `Так же к каждому хосту привяжите шаблон Linux by Zabbix Agent`
4. `Проверьте что в раздел Latest Data начали поступать необходимые данные из вашего шаблона`

Решение 2-3
<img src = "img\img2-3.jpg" width = 100%>
<img src = "img\img2-3_1.jpg" width = 100%>

### Задание 4

`Создайте свой кастомный дашборд.`

1. `Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.`
2. `В разделе Dashboards создайте новый дашборд`
3. `Разместите на нём несколько графиков на ваше усмотрение.`

Решение 4
<img src = "img\img4.jpg" width = 100%>
<img src = "img\img4_1.jpg" width = 100%>
