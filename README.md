# Отчёт о тестировании "KeyValidator" и "OpenJDK11"

## Краткое описание

06.07.2020 - 06.07.2020 было проведено тестирование установки,   приложения "KeyValidator" и "OpenJDK11".

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:

* https://github.com/KristinaPelevina/KeyValidator/issues/3#issue-651571184

* https://github.com/KristinaPelevina/KeyValidator/issues/1#issue-651568335


## Описание процесса тестирования

### В процессе тестирования использовались следующие артефакты:

* чек-лист: 
> https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md

* баг-репорт (ссылки выше)


### В качестве тестовых данных использовались данные:

> https://github.com/netology-code/javaqa-homeworks/tree/master/intro (задача 1)

> https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md 

>https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md

* программа "OpenJDK11" установилась согласно инструкции, запускается и совместима с Java 11
* Список валидных ключей, при проверке которых результат должен был быть ОК
* Список невалидных ключей, при проверке которых результат должен был быть FAIL

### Тестирование производилось в следующем окружении:

> Microsoft Windows 7 Домашняя расширенная х64-based PC

> Java 11.0.7
