# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #1 выполнил(а):
- Русакова Анна Алексеевна
- РИ-230947
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | * | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 1.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 2.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 3.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Выводы.
- ✨Magic ✨

## Цель работы
Установить необходимое программное обеспечение, которое пригодится для создания интеллектуальных моделей на Python. Рассмотреть процесс установки игрового движка Unity для разработки игр.

## Задание 1
### Написать программу Hello World на Python с запуском в Jupiter Notebook.

Ход работы:
- Установить Anaconda - дистрибутив языков программирования Python, включающий набор популярных свободных библиотек, объединенных проблематиками науки о данных и машинного обучения.
- Открыть установившийся Anaconda-Navigator, найти в нём инструмент Jupyter Notebook и запустить.
- В открывшемся дереве файлов создать папку "UrFU" и в ней - файл "HelloWorld.ipynb".
- Открыть файл и написать команду `print('HelloWorld')`.

![image](https://github.com/user-attachments/assets/d97d867d-5572-45f6-a85f-d06dfea821b4)


## Задание 2
### Написать программу Hello World на C# с запуском на Unity. 

- Установить Unity Hub, после чего в нём выбрать для скачивания последнюю актуальную версию Unity.
- Установить IDE для работы с C#.
- Создать новый 3D-проект.
- Настроить синхронизацию Unity и Visual Studio с помощью вкладки Edit -> Preferences -> External Tools -> External Script Editor -> Visual Studio.
- Написать программу Hello World на C# с запуском на Unity. Для этого переходим в Assets -> Create -> C# Script. Открываем скрипт в VS и меняем его содержимое на желаемую программу:
```c#
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class HelloWorld : MonoBehaviour
{
    void Start()
    {
        Debug.Log("Hello World");
    }
}
```
- Создать пустой объект в меню Hierarchy -> + -> Create Empty и перетащить на него HelloWorld.
- Нажать "запустить". В консоль выведется Hello World.

![image](https://github.com/user-attachments/assets/e2412851-e4fe-45d1-9a6c-19f99201d9c9)
![image](https://github.com/user-attachments/assets/226bf1ee-e34d-48db-948e-136162130e92)
![image](https://github.com/user-attachments/assets/7a4dfc9c-e4ac-436c-b556-281e8c53dcd7)
![image](https://github.com/user-attachments/assets/4c70d9b0-b1c2-4e9e-9084-2185195ca824)


## Задание 3
### Оформить отчет в виде документации на github (markdown-разметка).

- Авторизоваться на GitHub.
- Создать репозиторий.
- Составить отчёт по шаблону.
- ???
- Profit


## Выводы
Я установила программы Jupyter и Unity и немного ознакомилась с их базовым функционалом.


| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
