# Описание функциональных и технических характеристик ПО TeamStorm

## Назначение документа <a href="#_toc110531995" id="_toc110531995"></a>

Документ описывает функциональные характеристики системы управления проектами и совместной работой TeamStorm.

## Описание системы <a href="#_toc110531996" id="_toc110531996"></a>

TeamStorm предоставляет возможность организовать совместную работу над проектами в едином цифровом пространстве, помогает обеспечить эффективное взаимодействие всех участников проекта, сфокусировать участников проекта на ключевые результаты и увеличить скорость принятия управленческих решений.

Структура TeamStorm состоит из следующих элементов:

* пространства;
* папки;
* расширения;
* задачи.

TeamStorm обеспечивает выполнение следующих функций:

* создание пространств для управления проектами и просмотр их структуры;
* декомпозиция пространств на папки;
* создание и редактирование задач;
* отслеживание выполнения задач, изменение статуса задач и исполнителя, связывание задач;
* выдача пользователям доступа на созданные пространства;
* фильтрация и поиск задач;
* переключение между представлениями для работы с задачами;
* настройка рабочих процессов с возможностью создавать пользовательские статусы;
* отслеживание списка задач пользователя на рабочем столе.

## Функциональные характеристики <a href="#_toc110531997" id="_toc110531997"></a>

### Главная страница <a href="#_toc110532004" id="_toc110532004"></a>

На главной странице пользователя отображается:

* список доступных ему пространств;
* список назначенных на него задач.

### Элементы управления <a href="#_toc110532005" id="_toc110532005"></a>

В системе доступны следующие элементы управления:

* поле поиска задач по идентификатору и наименованию с выпадающим списком задач;
* переключатели представления типа "Доска" и "Таблица";
* фильтры по наименованию задачи, исполнителю и статусу задачи;
* кнопка и окно создания задачи;
* панель изменения задачи.

### Работа с пространствами <a href="#_toc110531998" id="_toc110531998"></a>

В системе доступно создание/удаление пространств и просмотра их структуры. Пространство объединяет проекты и работы, которые влияют на общие целевые показатели организации. Пространство на системном уровне определяет модель доступа и базовые конфигурации содержимого. Принципы выделения пространства принимаются на уровне организации.

В пространстве для каждого типа задачи определен процесс по умолчанию.

На уровне пространства определяются рабочие процессы. В пространстве для каждого типа задачи определен процесс по умолчанию.

Владелец пространства (пользователь, создавший пространство) может предоставлять доступ к данному пространству другим пользователям.

### Работа с папками <a href="#_toc110531999" id="_toc110531999"></a>

В системе доступно создание/удаление папок внутри пространства. Папка объединяет задачи со схожими процессами и доступами (например, группировка работы по проектам, продуктам, командам).

Конфигурация рабочих процессов и типов для папки соответствует конфигурации пространства.

Пользователь может создавать вложенные папки.

### Работа с задачами <a href="#_toc110532000" id="_toc110532000"></a>

В системе доступно создание задач разных типов — структурированных элементов для управления проектом.

Пользователь может:

* вносить информацию о необходимых действиях для выполнения задачи;
* устанавливать исполнителя задачи;
* изменять статус по мере выполнения задачи и закрывать её;
* добавлять вложения (файлы);
* выстраивать иерархию задач, добавляя вложенные задачи;
* оставлять комментарии к задаче;
* создавать к задачам пользовательские атрибуты  типов «строка», «тег», «список», «дата», «число»;
* связывать задачи, выстраивая между ними отношения типа «зависимость», «блокирование», «дублирование»;
* указывать рабочий процесс, по которому должна проходить задача.

### Представления типа "Доска" и "Таблица" <a href="#_toc110532002" id="_toc110532002"></a>

Вся информация о выполнении задач отслеживается с помощью двух представлений — доска и таблица. Таблица представляет собой список задач с ее параметрами. Доска представляет из себя набор карточек задач, сгруппированных по статусам в колонках доски.

Через представления пользователь может:

* создавать задачи;
* переходить к карточке задачи;
* изменять статус задачи;
* редактировать атрибуты задачи;
* копировать ссылку на задачу;
* назначать исполнителя.

Пользователь может переключаться между представлениями в виде таблицы и доски. Представления отображают задачи выбранной папки или списка задач. В представлениях доступна фильтрация отображаемых задач по названию, статусу и исполнителю.

### Настройка рабочих процессов <a href="#_toc110532003" id="_toc110532003"></a>

В системе доступно создание настраиваемых рабочих процессов. Рабочий процесс определяет статусную модель отдельной задачи, которая служит для формализации и отражения этапов выполнения задачи.

В пространстве для каждого типа задачи определен процесс по умолчанию. Все процессы определены на уровне пространства и наследуются папками и задачами.

При конфигурировании рабочего процесса пользователь может:

* создавать новые статусы или добавлять существующие;
* удалять статусы из процесса.

## Технические характеристики <a href="#_toc110532006" id="_toc110532006"></a>

### Решения по комплексу технических средств, его размещению на объекте

Техническое обеспечение системы TeamStorm включает следующие технические средства:

* серверы;
* рабочие станции (для пользователей).

Требования к серверному оборудованию системы представлены в Таблице 1.

Допускается установка на программную и/или аппаратную систему, эмулирующую аппаратное обеспечение некоторой платформы (виртуальная машина).

**Таблица 1 - Требования к серверному оборудованию системы на момент её развёртывания**

| Имя сервера      | Процессор                                                                              | Оперативная память | Объем жесткого диска | Операционная система                                                    | Сетевые интерфейсы |
| ---------------- | -------------------------------------------------------------------------------------- | ------------------ | -------------------- | ----------------------------------------------------------------------- | ------------------ |
| Server Тeamstorm | 8 ядер серверного класса с поддержкой виртуализации и тактовой частотой 2.2 ГГц и выше | 12 Гб              | 100 Гб               | CentOS или любая другая с возможностью установки Docker, Docker compose | TCP/IP             |

Требования к оборудованию рабочих станций пользователей приведены в Таблице 2

**Таблица 2 - Требования к оборудованию рабочих станций пользователей**

| Компонент                   | Рекомендуемая конфигурация                                                                   |
| --------------------------- | -------------------------------------------------------------------------------------------- |
| Процессор                   | Intel Core 2 Duo 2.3 Ггц или аналог                                                          |
| Оперативная память          | 2 Гб SDRAM                                                                                   |
| Жесткий диск                | 50 Гб                                                                                        |
| Сетевая плата               | Ethernet 10 Мбит                                                                             |
| Дополнительное оборудование | Монитор, клавиатура, мышь                                                                    |
| Операционная система        | Windows, MacOS или Linux                                                                     |
| Общесистемное ПО            | Веб-браузер Google Chrome, Яндекс.Браузер, Opera, Mozilla Firefox, Microsoft Edge или Safari |

### Решения по составу программных средств, языкам деятельности, алгоритмам процедур и операций и методам их реализации

Система TeamStorm представляет собой клиент-серверное приложение. Для развертывания и запуска системы используются средства docker-контейнеризации.

Система TeamStorm разработана с помощью следующих программных средств и языков программирования:

* C# – для реализации серверной части;
* TypeScript – для реализации клиентской части и пользовательского интерфейса;
* PostgreSQL – в качестве базы данных;
* Minio – в качестве файлового хранилища;
* RabbitMQ – для организации обмена данными между сервисами системы;
* Elasticsearch – в качестве подсистемы логирования;
* Nginx – для маршрутизации запросов.

### Перечень программного обеспечения

Перечень программного обеспечения представлен в Таблице 3.

**Таблица 3 - Перечень программного обеспечения**

| Сервер/Компонент | Системное программное обеспечение                                                  | Прикладное программное обеспечение                         |
| ---------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------- |
| Server TeamStorm | Рекомендуемая ОС CentOS, или любая с возможностью установки Docker, Docker compose | Docker Engine 17.09.0 и выше, Docker Compose 1.17.0 и выше |

Перечень необходимых лицензий представлен в Таблице 4.

**Таблица 4 - Перечень необходимых лицензий**

| Программное обеспечение | Число и тип лицензий                                                                                                                                    |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| TeamStorm               | Временная лицензия по количеству пользователей системы на время пилотирования. Коммерческая лицензия по количеству пользователей на время использования |

## Термины и определения <a href="#_toc110532007" id="_toc110532007"></a>

**Таблица 5 - Перечень терминов, используемых в ПО TeamStorm и документации на него**

| Термин                   | Определение                                                                                                                                                                                     |
| ------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Agile расширение         | Расширение с настройками очередей типа "бэклог" и "спринт"                                                                                                                                      |
| Бэклог                   | Бэклог содержит нерешенные задачи, над которыми работает команда                                                                                                                                |
| Спринт                   | Отрезок времени, в течение которого команда решает определенную задачу или группу задач                                                                                                         |
| Расширение               | Модуль, расширяющий функциональность пространства                                                                                                                                               |
| Пространство             | Пространство, которое объединяет типы работ по сходим критерием. Определяет модель доступа и базовые конфигурации содержимого. Принципы выделения пространств принимаются на уровне организации |
| Задача                   | Объект, который можно отслеживать, планировать, описывать, обсуждать или согласовывать (задача/документ/файл)                                                                                   |
| Папка                    | Раздел в пространстве, который объединяет похожие типы задачи со схожими доступами и процессами (проект/продукт/команда)                                                                        |
| Атрибут задачи           | Атрибут определенного типа, значение которого может хранить задача. Описывает или категорирует задачу                                                                                           |
| Пользовательский атрибут | Атрибут, добавляемый пользователем, специфичный для типа задачи и/или папки или пространства                                                                                                    |
| Статус задачи            | Определяет возможные состояния задачи                                                                                                                                                           |
| Категория статуса        | Определяет возможные категории статусов для группировки статусов. На уровне системы определены категории To Do, In Progress, Done, Cancelled                                                    |
| Рабочий процесс, процесс | Определяет набор статусов для задачи и правила перехода между ними                                                                                                                              |
| Процесс по умолчанию     | Процесс, присваеваемый задаче при ее создании                                                                                                                                                   |
| Тип задачи               | Определяет шаблон создания задачи, с каким процессом или атрибутом она создается                                                                                                                |
| Комментарий              | Комментарий к задаче                                                                                                                                                                            |
| Вложение                 | Вложение в виде файла, добавляемое к задаче или комментарию                                                                                                                                     |