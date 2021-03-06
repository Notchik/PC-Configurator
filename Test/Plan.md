### Содержание
  1. [Введение](#1)
  2. [Объект тестирования](#2)
  3. [Риски](#4)
  4. [Аспекты тестирования](#5)<br>
5. [Подходы к тестированию](#6)
6. [Представление результатов](#7)
7. [Выводы](#8)


<a name="1"></a>
### 1. Введение
Содержание данного документа описывает план тестирования разрабатываемого приложения. Более подробную информацию о приложении можно найти в документе [SRS.md](https://github.com/Notchik/PC-Configurator/blob/master/SRS.md).  
Данный план предназначен для тестирования приложения "PC-Configurator". Цель проведения тестирования - проверка работоспособности и пригодности приложения для практического использования.

<a name="2"></a>
### 2. Объект тестирования

1. Функциональность:
	+ функциональная полнота: приложение должно выполнять все заявленные функции
	+ функциональная корректность: приложение должно выполнять все заявленные функции корректно
	+ функциональная целесообразность: отсутствуют не заявленные ранее функции, которые могут помешать приложению выполнять первоначально поставленные задачи

Данные атрибуты были взяты с учётом специфики приложения.

<a name="3"></a>
### 3. Риски

Вмешательство в конфигурационные файлы приложения. 

<a name="4"></a>
### 4. Аспекты тестирования

#### Аспекты, подвергаемые тестированию:

В ходе тестирования планируется проверить реализацию основных функций приложения, провести позитивные и негативные тесты, а также проверить нефункциональные требования.
К основным функциям можно отнести следующие пункты:
* возможность выбрать комплектующие в любой категории;
* возможность сохранить конфигурацию;
* возможность загрузить конфигурацию;
* возможность получить информацию о программе;
* возможность получить уведомление об информации, с которой ведётся работа;

##### Возможность выбрать комплектующие в любой категории
Этот вариант использования небходимо протестировать на:
* Наличие списка комплектующих во всех категориях;
* Выставление цены на соответствующее комплектующее;
* Изменение общей стоимости в зависимости от цены комплектующего;

##### Возможность сохранить конфигурацию 
Этот вариант использования небходимо протестировать на:
* Наличие сохранённого файла;

##### Возможность загрузить конфигурацию;
Этот вариант использования небходимо протестировать на:
* Верный список комплектующих;
* Отображения статуса информации, с которой идёт работа;

##### Возможность получить информацию о программе;
Этот вариант использования небходимо протестировать на:
* Предоставление информации о продукте;
* Предоставление информации о состоянии файлов приложения;

##### Возможность получить уведомление об информации, с которой ведётся работа;
Этот вариант использования небходимо протестировать на:
* Изменение статуса приложения в зависимости от информации, с которой работает пользователь; 

<a name="5"></a>
### 5. Подходы к тестированию
Для тестирования приложения необходимо вручную проверить каждый аспект тестирования.

<a name="6"></a>
### 6. Представление результатов

Результаты тестирования представлены в документе ["Представление результатов"](https://github.com/Notchik/PC-Configurator/blob/master/Test/Results.md).

<a name="7"></a>
### 7. Выводы
Данный тестовый план позволяет протестировать основной функционал приложения. Успешное прохождение всех тестов позволяет полагать, что данное программное обеспечение работает корректно.

