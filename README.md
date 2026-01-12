### Домашнее задание к занятию 3 «Использование Ansible».

### Подготовка к выполнению:

1.Подготовьте в Yandex Cloud три хоста: для clickhouse, для vector и для lighthouse.

2.Репозиторий LightHouse находится по ссылке.

### Основная часть.

1.Допишите playbook: нужно сделать ещё один play, который устанавливает и настраивает LightHouse.

2.При создании tasks рекомендую использовать модули: get_url, template, yum, apt.

3.Tasks должны: скачать статику LightHouse, установить Nginx или любой другой веб-сервер, настроить его конфиг для открытия LightHouse, запустить веб-сервер.

4.Подготовьте свой inventory-файл prod.yml.

5.Запустите ansible-lint site.yml и исправьте ошибки, если они есть.

6.Попробуйте запустить playbook на этом окружении с флагом --check.

7.Запустите playbook на prod.yml окружении с флагом --diff. Убедитесь, что изменения на системе произведены.

8.Повторно запустите playbook с флагом --diff и убедитесь, что playbook идемпотентен.

9.Подготовьте README.md-файл по своему playbook. В нём должно быть описано: что делает playbook, какие у него есть параметры и теги.

10.Готовый playbook выложите в свой репозиторий, поставьте тег 08-ansible-03-yandex на фиксирующий коммит, в ответ предоставьте ссылку на него.

### Как оформить решение задания.

Выполненное домашнее задание пришлите в виде ссылки на .md-файл в вашем репозитории.

### Решение.
<img width="1494" height="361" alt="Задание 1(1)" src="https://github.com/user-attachments/assets/4917e02b-f25c-4331-ae3e-b0bbb6ae9e2f" />
<img width="551" height="347" alt="Задание 1(2)" src="https://github.com/user-attachments/assets/e7eab5cd-bd49-4277-b458-0ef3ec3f8c3d" />
<img width="649" height="355" alt="Задание 1(3)" src="https://github.com/user-attachments/assets/198b48be-5a9e-4662-8981-5d00fe4daa6d" />
<img width="843" height="60" alt="Задание 1(4)" src="https://github.com/user-attachments/assets/93b3b7d2-c9cb-42db-bdfc-9e2402333d1f" />
<img width="887" height="558" alt="Задание 1(5)" src="https://github.com/user-attachments/assets/0026ab04-a337-4d21-826d-db9dfe5f39ce" />
<img width="900" height="541" alt="Задание 1(6)" src="https://github.com/user-attachments/assets/0c351a15-64a6-4796-9f9d-f5e14c7e2152" />
<img width="886" height="542" alt="Задание 1(7)" src="https://github.com/user-attachments/assets/c96260b3-5ac3-42e9-bfbb-73735b1ffe41" />
<img width="1531" height="400" alt="Задание 1(8)" src="https://github.com/user-attachments/assets/76e4b49c-6ee9-4b38-97bc-c140d50e78c1" />






