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

   ![Создание Service Account](screenshot1.png)

3. **Создание виртуальной машины**
   - Создал минимальный Compute Engine (виртуальную машину) с Machine type e2-micro в режиме spot.
   - Нейминг: dgusev-vm-lab1.

   ![Создание Виртуальной Машины](screenshot2.png)

4. **Копирование файлов с использованием gsutil**
   - С помощью утилиты gsutil нахожу бакет lab1-bucket-itmo копирую 3 файла в локальную папку на VM.
   - Выполняю команду ls -lah для отображения файлов на VM.

   bash
   gsutil cp gs://lab1-bucket-itmo/* /path/to/local/folder/
   ls -lah /path/to/local/folder/

   ![Копирование файлов](screenshot3.png)

5. **Изменение прав доступа Service Account**
   - Меняю права доступа для моего service account с Storage Admin на Compute Viewer.
   - Повторяю пункт с копированием данных и замечаю, что возникла ошибка доступа.

   ![Ошибка доступа](screenshot4.png)

   **Выводы:** Изменение роли с Storage Admin на Compute Viewer ограничивает доступ к хранилищу, что подтверждает важность правильного назначения ролей в Google Cloud.

6. **Удаление созданных сервисов**
   - Удаляю все созданные сервисы, включая виртуальную машину и service account.

   ![Удаление сервисов](screenshot5.png)

## Результаты лабораторной работы
В результате данной работы был получен доступ к Google Cloud, созданы необходимые сервисы, выполнены операции по копированию файлов и сделаны выводы о роли прав доступа в системе.

**Отчет по лабораторной работе составлен успешно.**
