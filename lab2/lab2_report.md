University: [ITMO University](https://itmo.ru/ru/)
Faculty: [FICT](https://fict.itmo.ru)
Course: [Cloud platforms as the basis of technology entrepreneurship](https://) ADD link
Year: 2024/2025
Group: U4225
Author: Gusev Dimitrii Ivanovich
Lab: Lab2
Date of create: 25.10.2024
Date of finished: 25.10.2024

# Лабораторная работа №2 "Исследование Cloud Run"

## Описание
Это вторая лабораторная работа "Исследование Cloud Run".

## Цель работы
Ознакомиться с работой Cloud Run.

## Ход работы

### 1. Создание сервиса Cloud Run
Для начала cоздаю сервис Cloud Run на основе дефолтного сервиса Hello. Использую минимальное количество ресурсов. 

![Screenshot1](https://github.com/user-attachments/assets/59d1c9ed-4996-49c0-b731-c5156d3963c5)

### 2. Тестирование сервиса
После создания сервиса, перехожу по предоставленной ссылке Cloud Run и тестирую его работу. Сервис успешно ответил на запросы.

### 3. Анализ логов и метрик
Затем перехожу в разделы логов и метрик. В логах вижу информацию о запросах, а в метриках — данные о производительности и использовании ресурсов.

![Screenshot 2024-10-28 at 18 28 34](https://github.com/user-attachments/assets/ff734c9b-4ab5-48b3-8768-b7e13aca993c)

![Screenshot 2024-10-28 at 18 28 51](https://github.com/user-attachments/assets/a4d7a5d9-0f0c-44c2-a6ec-7248f74a56fc)

### 4. Изменение порта
Изменяю конфигурацию Cloud Run, установив порт на 8090. После этого сервис перестал отвечать на запросы, так как он не слушал на этом порту.

![Screenshot 2024-10-28 at 18 32 26](https://github.com/user-attachments/assets/2ad055ff-7c6d-4e20-a612-f9b4b0f356a5)

![Screenshot 2024-10-28 at 18 32 39](https://github.com/user-attachments/assets/a222e956-8200-422f-b1bd-160580292050)

![Screenshot 2024-10-28 at 18 32 51](https://github.com/user-attachments/assets/9e3dad0b-9e00-4ec2-bd88-e2972158933f)

### 5. Переключение трафика между версиями
Создаю новую версию сервиса и переключаю трафик между версиями. Это позволяет мне сравнить результаты работы обеих версий.

### 6. Удаление сервисов
После завершения всех тестов и экспериментов, удаляю все созданные сервисы, чтобы не оставлять за собой ненужные ресурсы.



## Результаты лабораторной работы
В результате данной работы я ознакомился с работой Cloud Run, протестировал сервис, проанализировал логи и метрики, изменил конфигурацию и переключал трафик между версиями.

Отчет подготовлен с использованием скриншотов, которые иллюстрируют процесс выполнения лабораторной работы.
