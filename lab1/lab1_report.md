University: ITMO University Faculty: FICT Course: Cloud platforms as the basis of technology entrepreneurship ADD link Year: 2024/2025 Group: U4225 Author: Gusev Dimitrii Ivanovich Lab: Lab2 Date of create: 25.10.2024 Date of finished: 25.10.2024

# Лабораторная работа №1: Обзор Google Cloud и исследование основных сервисов

## Описание
Это первая лабораторная работа "Обзор Google Cloud и исследование основных сервисов."

## Цель работы
Ознакомиться с основными возможностями и преимуществами облачной платформы Google Cloud.

## Ход работы

1. **Заполнение гугл формы**
   - Заполняю гугл форму, указав свою Gmail почту, получаю доступ к Google Cloud.

2. **Создание Service Account**
   - Захожу в вкладку IAM.
   - Создаю service account с ролью Storage Admin.
   - Нейминг: dgusev-sa-lab1.
  
<img width="736" alt="Screenshot 2024-10-28 at 17 41 55" src="https://github.com/user-attachments/assets/79180bde-1067-4a68-820b-4d0adff373a2">


3. **Создание виртуальной машины**
   - Создал минимальный Compute Engine (виртуальную машину) с Machine type e2-micro в режиме spot.
   - Нейминг: dgusev-vm-lab1.
     
<img width="541" alt="Screenshot 2024-10-28 at 17 44 30" src="https://github.com/user-attachments/assets/76214fee-d84a-4409-93d4-73b670d248b0">


4. **Копирование файлов с использованием gsutil**
   - С помощью утилиты gsutil нахожу бакет lab1-bucket-itmo копирую 3 файла в локальную папку на VM (gsutil cp -r gs:/ /lab1-bucket-itmo/
./).
   - Выполняю команду ls -lah для отображения файлов на VM.

 <img width="619" alt="Screenshot 2024-10-28 at 18 01 09" src="https://github.com/user-attachments/assets/6b07b3de-63b1-43a7-9115-7de419813a8a">


5. **Изменение прав доступа Service Account**
   - Меняю права доступа для моего service account с Storage Admin на Compute Viewer.
   - Повторяю пункт с копированием данных и замечаю, что возникла ошибка доступа.
     
<img width="250" alt="Screenshot 2024-10-28 at 18 02 37" src="https://github.com/user-attachments/assets/f31096e3-04d1-46aa-a90b-421b58b0f61f">
![Screenshot 2024-10-28 at 18 10 10](https://github.com/user-attachments/assets/93681397-9805-4f8b-a17e-04cab1ebbfee)


   **Выводы:** Изменение роли с Storage Admin на Compute Viewer ограничивает доступ к хранилищу, что подтверждает важность правильного назначения ролей в Google Cloud.

6. **Удаление созданных сервисов**
   - Удаляю все созданные сервисы, включая виртуальную машину и service account.

## Результаты лабораторной работы
В результате данной работы был получен доступ к Google Cloud, созданы необходимые сервисы, выполнены операции по копированию файлов и сделаны выводы о роли прав доступа в системе.

**Отчет по лабораторной работе составлен успешно.**
