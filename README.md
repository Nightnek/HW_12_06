# 12_06 Стасенко Григорий Домашнее задание к занятию «Репликация и масштабирование. Часть 1» 12_06

---

## Задание 1
На лекции рассматривались режимы репликации master-slave, master-master, опишите их различия.

Ответить в свободной форме.

````
В режиме репликации master-slave, slave для пользователя доступен только для чтения. Записи туда ведет только master.
В режиме репликации master-master, читать и вести записи можно в обе БД, они же сами будут обмениваться изменениями.
````

## Задание 2
Выполните конфигурацию master-slave репликации, примером можно пользоваться из лекции.

Приложите скриншоты конфигурации, выполнения работы: состояния и режимы работы серверов.
![image](https://github.com/Nightnek/HW_12_5/assets/127677631/f9443d04-b824-475e-984b-a7499fba4efa)
![image](https://github.com/Nightnek/HW_12_5/assets/127677631/b71bbda5-0611-47f0-bf98-b4d6c0eec804)
![image](https://github.com/Nightnek/HW_12_5/assets/127677631/f51a1928-40fa-42d8-828c-689fdace3bda)
![image](https://github.com/Nightnek/HW_12_5/assets/127677631/a43fdfd7-6a21-4645-87a9-b9ddcab0416f)


---
## Задание 3*
Выполните конфигурацию master-master репликации. Произведите проверку.

Приложите скриншоты конфигурации, выполнения работы: состояния и режимы работы серверов.

![image](https://github.com/Nightnek/HW_12_5/assets/127677631/c8dc243b-0f2f-49fa-b2ed-b6ed7ae8ffaa)
![image](https://github.com/Nightnek/HW_12_5/assets/127677631/79a79cf6-0dfb-4d3d-80e1-ac2f1c3c9030)
![image](https://github.com/Nightnek/HW_12_5/assets/127677631/15869089-5951-4f43-b960-9c13ff43036f)

![image](https://github.com/Nightnek/HW_12_5/assets/127677631/5573ee5a-c804-4d05-b6b9-f48e0d54ea4e)
![image](https://github.com/Nightnek/HW_12_5/assets/127677631/36590361-dfb0-4bb3-b2c0-354e0197dc3e)
![image](https://github.com/Nightnek/HW_12_5/assets/127677631/a8d5cea0-089f-4f0a-978e-cce1302f0997)



---
