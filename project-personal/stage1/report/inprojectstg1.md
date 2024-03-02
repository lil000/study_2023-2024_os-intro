# Отчет по выполнению первого этапа индивидуального проекта

## **Markdown**

***Агаджанян Артур вячеславович***
***НКАбд-01-23***

## Цель работы:
Размещение на Github pages заготовки для персонального сайта.

### Теоретическое введение 

1. Установка программного обеспечения для Hugo 

    Ubuntu:

-sudo apt-get install go hugo

    Fedora:

-sudo dnf install go hugo

    Windows:

    - choco install hugo extended
    Ручная Утсановка:
Если устанавливаемая в системе версия hugo меньше необходимой,тогда следует установить программу вручную.

Версию Hugo можно посмотреть при помощи команды:

    - hugo version

Следует скачать архив с репозитория:

    -https://github.com/gohugoio/hugo/realeases

# Основные этапы выполнения работы

## 1. скачиваем Hugo на компьютер 
![1](https://github.com/lil000/study_2023-2024_os-intro/blob/master/project-personal/stage1/report/image/%D0%B8%D0%B7%D0%BE%D0%B1%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5_2024-03-02_164616005.png?raw=true)
рис.(1) Скачиваем нужную версию Hugo с github(а именно hugo_extended_0.123.7_Linux-64bit.tar.gz
)

&nbsp;
&nbsp;
&nbsp;
&nbsp;

## 2. Создаем папку для корректного использования Hugo

![2](https://github.com/lil000/study_2023-2024_os-intro/blob/master/project-personal/stage1/report/image/picin1.png?raw=true)

рис.(2)называем папку **bin**

## 3. С помощью шаблона создаем свой репозиторий на основе его же

![3](https://github.com/lil000/study_2023-2024_os-intro/blob/master/project-personal/stage1/report/image/picin2.png?raw=true)

рис.(3) Создание репозитория

## 4. Клонируем репозиторий в локальную папку **work**

![4](https://github.com/lil000/study_2023-2024_os-intro/blob/master/project-personal/stage1/report/image/picin3.png?raw=true)

рис.(4)с помощью команды git clone --recursive клонируем репозиторий.

## 5. Устанавливаем в локальный репозиторий Hugo 

![5](https://github.com/lil000/study_2023-2024_os-intro/blob/master/project-personal/stage1/report/image/picin4.png?raw=true)
рис.(5) Установка Hugo

## 6. Создаем локальный сервер с помощью Hugo

![6](https://github.com/lil000/study_2023-2024_os-intro/blob/master/project-personal/stage1/report/image/picin5.png?raw=true)
рис.(6) Создание локального сервера

## 7. Проверяем наш сайт через локальный домейн 

![7](https://github.com/lil000/study_2023-2024_os-intro/blob/master/project-personal/stage1/report/image/picin6.png?raw=true)
рис.(7) смотрим на наш сайт

## 8. Создаем новый репозиторий с помощью Github для Github pages 

![8](https://github.com/lil000/study_2023-2024_os-intro/blob/master/project-personal/stage1/report/image/picin7.png?raw=true)
рис.(8)Создаем новый репозиторий

## 9. Клонируем новый репозиторий локально в папку **work**

![9](https://github.com/lil000/study_2023-2024_os-intro/blob/master/project-personal/stage1/report/image/picin8.png?raw=true)
рис.(9) Клонируем новый репозиторий 

## 10. Создаем ветку Main и в ней же файл README.md

![10](https://github.com/lil000/study_2023-2024_os-intro/blob/master/project-personal/stage1/report/image/picin9.png?raw=true)
рис.(10)Создаем ветку и файл README.md

## 11.Подключаем новосозданный репозиторий к папке **public** внутри папки **work/blog**

![11](https://github.com/lil000/study_2023-2024_os-intro/blob/master/project-personal/stage1/report/image/picin10.png?raw=true)
рис.(11)Подключаем репозиторий к папке **public**

## 12. Отключаем игнорирование public в gitignore
Используем команду mc для нужного результата 

![12](https://github.com/lil000/study_2023-2024_os-intro/blob/master/project-personal/stage1/report/image/picin11.png?raw=true)
рис.(12)Отключили игнорирование,закомментив public - #public

## 13. Повторяем действия из пункта 11
Подключаем последний созданный репозиторий к папке public внутри папки **work/blog**

![13](https://github.com/lil000/study_2023-2024_os-intro/blob/master/project-personal/stage1/report/image/picin12.png?raw=true)
рис.(13)Подключаем репозиторий к папке public 

## 14. Используем Hugo для нового репозитория

![14](https://github.com/lil000/study_2023-2024_os-intro/blob/master/project-personal/stage1/report/image/picin13.png?raw=true)
рис.(14)Использовали Hugo на новом репозитории 

## 15. Проверяем подключение каталога к репозиторию и добавляем комментарий к коммиту

![15](https://github.com/lil000/study_2023-2024_os-intro/blob/master/project-personal/stage1/report/image/picin14.png?raw=true)
рис.(15)Проверяем подключение командой **git remote -v** и коммитим с комментарием 

## 16. Проверим наш репозиторий 

![16](https://github.com/lil000/study_2023-2024_os-intro/blob/master/project-personal/stage1/report/image/%D0%B8%D0%B7%D0%BE%D0%B1%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5_2024-03-02_171233818.png?raw=true)
рис.(16)Проверяем все ли загрузилось в репозиторий на github

## 17. Смотрим на наш сайт через ссылку (https://lil000.github.io)
по этой ссылке может пройти кто угодно

![17](https://github.com/lil000/study_2023-2024_os-intro/blob/master/project-personal/stage1/report/image/picin15.png?raw=true)
рис.(17) Все корректно 

## Вывод: 
У нас получилось создать сайт с помощью **Hugo** и команд в консоле **Linux** для **Github**,вместе с этим мы разместили заготовку сайта.