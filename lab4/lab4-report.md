University: ITMO University Faculty: FICT Course: Cloud platforms as the basis of technology entrepreneurship ADD link Year: 2024/2025 Group: U4225 Author: Gusev Dimitrii Ivanovich Lab: Lab2 Date of create: 01.11.2024 Date of finished: 01.11.2024
---------------------------------------------------------------------------------------------------------------------------------------------

# Лабораторная работа №4: Разработка инфраструктуры MVP AI приложения

## Описание
Это четвертая лабораторная работа, посвященная разработке инфраструктуры MVP AI приложения.

## Цель работы
Создать прототип AI-приложения с базовой функциональностью.

## Правила по оформлению
Правила по оформлению отчета по лабораторной работе можно изучить по [ссылке](#).

## Ход работы
В данной лабораторной работе не будет практической части создания каких-либо ресурсов в Cloud платформе. Вместо этого, необходимо накидать схему инфраструктуры приложения, используя draw.io. Также требуется рассчитать экономическую модель (расходы на содержание) и обосновать выбор тех или иных ресурсов.

### Состояния приложения
Приложение будет иметь три состояния:
1. **Начальное состояние** - базовая версия приложения, минимально необходимая для функционирования.
2. **Тестирование партнерами** - версия приложения, предназначенная для тестирования и сбора отзывов от партнеров.
3. **Продовое решение** - финальная версия приложения, готовая к массовому использованию.

### Оптимизация ресурсов
Необходимо заранее продумать, какое решение будет оптимальным исходя из предполагаемых нагрузок. Важно помнить, что не всегда самое дешевое решение на первом этапе является оптимальным в дальнейшем.

## Результаты лабораторной работы
В результате данной работы у вас должно быть:
- Схема инфраструктуры приложения, созданная в draw.io.
- Экономическая модель с расчетом расходов на содержание.
- Обоснование выбора ресурсов для каждого из состояний приложения.

### Пример схемы инфраструктуры
(Вставьте изображение схемы здесь или ссылку на файл)

### Экономическая модель
| Ресурс                 | Начальное состояние | Тестирование партнерами | Продовое решение |
|-----------------------|---------------------|-------------------------|------------------|
| Сервер                | $X                  | $Y                      | $Z               |
| Хранение данных       | $A                  | $B                      | $C               |
| Трафик                | $D                  | $E                      | $F               |
| Итого                 | $Total1             | $Total2                 | $Total3          |

### Обоснование выбора ресурсов
- **Сервер**: Выбор сервера зависит от предполагаемой нагрузки. На начальном этапе можно использовать виртуальный сервер с ограниченными ресурсами, а для продового решения стоит рассмотреть более мощные серверы или облачные решения.
- **Хранение данных**: Для начального состояния подойдет облачное хранилище с низкой стоимостью, а для тестирования и продового решения стоит выбрать более надежные и масштабируемые решения.
- **Трафик**: Необходимо учитывать предполагаемый объем трафика. На начальном этапе можно использовать тариф с ограниченным трафиком, а для продового решения — безлимитный тариф.

## Заключение
В данной лабораторной работе была разработана схема инфраструктуры MVP AI приложения, проведены расчеты экономической модели и обоснован выбор ресурсов для каждого из состояний приложения. Данная работа поможет в дальнейшем при реализации проекта и выборе оптимальных решений.