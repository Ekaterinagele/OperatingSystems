# Операционные системы
## Лабораторная работа 1
## Реализация функции для вычисления факториала на С++

## 1.Создаем заголовочный файл с функцией
<img width="546" height="184" alt="factorial" src="https://github.com/user-attachments/assets/a5142dd5-6f7f-465c-86c4-c4106019d13d" />

## Напишем реализацию функции
<img width="546" height="215" alt="factorial реализация" src="https://github.com/user-attachments/assets/b066d378-7a90-4a5d-a98a-86e377436d3e" />


## Напишем программу для проверки работы реализованной функции
<img width="546" height="215" alt="factorial проверка" src="https://github.com/user-attachments/assets/53ccd916-5954-4d48-8431-f70218a5f9db" />

## Откомпилируем файлы и проверим корректность работы
<img width="802" height="110" alt="трансляция main factorial" src="https://github.com/user-attachments/assets/c3173868-820b-43d1-a614-173b50d28815" />

## Проведем компиляцию в ассемблерный код:

### **1)** Без оптимизации

<img width="518" height="62" alt="без оптимизации" src="https://github.com/user-attachments/assets/93868e3e-63fe-423e-9866-dfcac1aa0a68" />

<img width="1102" height="709" alt="ассемблерный код без оптимизации" src="https://github.com/user-attachments/assets/e5d28f04-d82e-4f28-8a3e-8f6269c85764" />

### **2)** С оптимизацией -O3
<img width="518" height="51" alt="оптимизация O3" src="https://github.com/user-attachments/assets/cea949c5-aa7c-4067-8491-cd6ef34c27d9" />

<img width="1104" height="785" alt="ассемблерный код с оптимизацией -О3" src="https://github.com/user-attachments/assets/06e54e1f-2bda-443f-a0e1-9993280f815c" />

## Подключаем гит и создаем первый коммит
<img width="1311" height="287" alt="git" src="https://github.com/user-attachments/assets/c3e41806-0027-422b-b93f-1570643849c9" />

## Создаем и разрабатываем Makefile
<img width="810" height="432" alt="Makefile" src="https://github.com/user-attachments/assets/691f682d-2f5f-441f-8f5e-3e0f3fab0a77" />

## Запускаем Makefile

<img width="529" height="113" alt="запуск Makefile" src="https://github.com/user-attachments/assets/fc4a8c79-cecf-4dcf-b15b-f8bdc95d6b86"/>

## 2.Чтобы усовершенствовать программу, добавим параллельный поток вычислений и настроим передачу результата через общий файл с синхронным доступом
<img width="783" height="600" alt="усовершенствование программы" src="https://github.com/user-attachments/assets/e4bdc300-01b0-489f-baa4-b47ede71f771" />

<img width="783" height="443" alt="Makefile2" src="https://github.com/user-attachments/assets/61e93218-cbf5-4909-b6bb-e84d4f8d5269" />

## Коммиты
<img width="882" height="115" alt="image" src="https://github.com/user-attachments/assets/778804c1-5e39-41a1-a190-2e726e35c070" />

## Лабораторная работа 3a
## Вариант 4: "В текстовых файлах (. t x t ) найти заданную в параметре сценария строку, из найденных файлов составить список, сохранить"

## Запускаем Linux Bash
<img width="903" height="488" alt="bash" src="https://github.com/user-attachments/assets/b70fad23-dee8-4578-a5aa-a7121a6faae4" />

## Создаем папку, открываем ее и создаем три (.txt) файла
<img width="886" height="148" alt="создание файлов" src="https://github.com/user-attachments/assets/0dcd4780-befc-48f8-b209-72e698013c6b" />

## Проверяем список созданных файлов
<img width="406" height="113" alt="проверка списка созданных файлов" src="https://github.com/user-attachments/assets/1d696451-6f9d-4234-ba5c-29d1493f71e4" />

## Открываем аналог Блокнота windows nano и создаем файл сценария
<img width="280" height="28" alt="открываем файл" src="https://github.com/user-attachments/assets/99a3b95d-b70f-4509-b9a6-c212487aadf7" />
<img width="560" height="360" alt="создание ксрипта" src="https://github.com/user-attachments/assets/227b95d1-ca53-4d59-85b3-49065175ebb4" />

## Находим заданное слово "Bash" в созданных файлах и записываем результат поиска в файл *list.txt*
<img width="419" height="68" alt="результат" src="https://github.com/user-attachments/assets/5bdb3821-03fe-4937-8393-65260ae3c8c8" />

## Лабораторная работа 3b

## Вариант 4: "В текстовых файлах (. t x t ) найти заданную в параметре сценария строку, из найденных файлов составить список, сохранить"

## Запускаем Windows PowerShell
<img width="1183" height="284" alt="PowerShell" src="https://github.com/user-attachments/assets/814a2a77-86f6-4e11-8b36-bbc10448cfab" />

## Создаем папку, открываем ее и создаем три (.txt) файла
<img width="1233" height="507" alt="создаем файлы в PowerShell" src="https://github.com/user-attachments/assets/98f53c7a-df54-48d0-8129-154c5b774cee" />

## Проверяем список файлов
<img width="1233" height="287" alt="проверяем создание файлов PowerShell" src="https://github.com/user-attachments/assets/45c9f7bd-0356-4c9e-8832-a18286ec8efe" />

## Открываем Блокнот и создаем файл сценария 
<img width="425" height="42" alt="Открываем Блокнот и создаем файл" src="https://github.com/user-attachments/assets/81674a3a-8911-4a96-a5c3-e35e3cd3907b" />
<img width="1032" height="398" alt="скрипт" src="https://github.com/user-attachments/assets/5742ba8d-c10f-4d03-8195-bd32c9944c28" />

## Находим заданное слово "PowerShell" в созданных файлах и записываем результат поиска в файл *list.txt*
<img width="478" height="184" alt="результат" src="https://github.com/user-attachments/assets/33f1469c-ffdd-4701-848e-207cc7134623" />
