# [ToDoList](https://kilinskas19.thkit.ee/ToDoList)

## Вступление

ToDoList это многостраничное веб приложение которое представляет собой ежедневник из дел пользователя. В первую очередь пользователь может зарегистрироваться или войти в систему, после этого ему будет доступна возможность создавать списки дел которые можно разбивать на категории, а также для каждого списка добавлять, редактировать, удалять свои задачи. В приложении также присутствует хороший дизайн, рабочий и удобный интерфейс и многое другое.


## UML схемы проекта


### Диаграмма прецедентов

![Диаграмма прецедентов](https://kilinskas19.thkit.ee/ToDoList/images/precendentdiagram.png)

### Диаграмма базы данных

![Диаграмма прецедентов](https://kilinskas19.thkit.ee/ToDoList/images/databasediagram.png)

### Диаграмма активности

![Диаграмма прецедентов](https://kilinskas19.thkit.ee/ToDoList/images/activitydiagram.png)


## Подробное описание работы проекта

Представим себя в роли обычного пользователя, который попал на наш сайт.
Первым делом мы попадаем на страницу "Login".

![Страница логина](https://kilinskas19.thkit.ee/ToDoList/images/loginPage.png)

 На этой странице мы можем войти в аккаунт, но так как у нас его еще нет нажмем на кнопку "Haven`t account?" чтобы зарегистрироваться.

 Мы попадаем на страницу "Register", попробуем зарегистрироваться. Чтобы зарегистрироваться нужно ввести свою электронную почту и придумать пароль. Например зарегистрируемся введя такие данные: Электронная почта - nikita3255@gmail.com, Пароль: не скажу)

![Страница регистрации](https://kilinskas19.thkit.ee/ToDoList/images/regPage.png)


После успешной регистрации нас сразу же перекидывает на страницу списков, потому что мы вошли в систему. В противном случае нас бы перекинуло на страницу "Login"

![Страница списков](https://kilinskas19.thkit.ee/ToDoList/images/listsPage.png)

На странице списков мы можем добавлять и удалять списки, видеть все добавленные списки а также при нажатии на определенный список откроеться данный список с возможностью добавления задач к нему.
Давайте попробуем создать список, для этого нажимаем на кнопку "Add list of tasks".

![Создать список](https://kilinskas19.thkit.ee/ToDoList/images/createList.png)

У нас открылось всплывающее окно, в которое нужно ввести желаемое имя для списка. Давай введем например "Долги по учебе" и нажмем "Create list" чтобы создать список.

![Список добавился](https://kilinskas19.thkit.ee/ToDoList/images/listAdded.png)

Список успешно добавился и мы можем видеть его в таблице списков, давайте нажмем на него.

Мы попадаем на страницу этого списка, где можем добавлять ему задачи, а также удалять и редактировать их. Задача состоит из: названия задачи, темы задачи, начальнаой даты задачи, финальной даты задачи, описания задачи и картинки. Также на усмотрение пользователя задача может быть например только С названием и описанием или Названием и начальной датой, вариантов много но название задачи нужно ввести обязательно.

![Страница списка](https://kilinskas19.thkit.ee/ToDoList/images/listPage.png)

Давайте попробуем добавить первую задачу. Например добавим задачу с такими данными:

![Добавление задачи](https://kilinskas19.thkit.ee/ToDoList/images/addTask.png)

Теперь нажмем "Add task" чтобы добавить задачу в таблицу и вывести ее:

![Таблица с задачей](https://kilinskas19.thkit.ee/ToDoList/images/tableTask1.png)

Задача успешно добавилась и теперь нам доступны следуйщие функции: 
* Просматривать картинку задачи
* Ставить статус задачи (сделана или не сделана)
* Изменять задачу
* Удалить задачу 

Попробуем изменить задачу, для этого нажмем на кнопку карандашика, под столбцом "Edit" 
![Изменяемая задача](https://kilinskas19.thkit.ee/ToDoList/images/editTask.png)
Изменим ей например финальную дату: на 2020/06/09 15:30 и нажмем на карандашик в столбце "Save"

![Измененная задача](https://kilinskas19.thkit.ee/ToDoList/images/editedTask.png)

Задача успешно изменилась, теперь поставим ей статус "Сделана"

![Статус](https://kilinskas19.thkit.ee/ToDoList/images/StatusTask.png)

Добавим еще одну задачу.

![2 задачи](https://kilinskas19.thkit.ee/ToDoList/images/addTask2.png)

![Таблица с 2 задачами](https://kilinskas19.thkit.ee/ToDoList/images/2tasksTable.png)

Теперь так как задач несколько мы можем их сортировать по разным столбцам:
* Название задачи
* Тема задачи
* Начальная дата
* Финальная дата
* Статус задачи

Например отсортируем задачи по названию задачи в порядке убывания для этого наведемся на столбец "Task" и нажмем на него.

![Отсортированная таблица](https://kilinskas19.thkit.ee/ToDoList/images/sortedTable.png)

Теперь отсортируем таблицу по названию задачи в порядке возрастания, для этого еще раз нажмем на столбец "Task" 

![Отсортированная наоборот таблица](https://kilinskas19.thkit.ee/ToDoList/images/sortedTableInvert.png)

Теперь удалим задачу "Тест"

![Удаление задачи](https://kilinskas19.thkit.ee/ToDoList/images/deleteTask.png)

![Результат удаление задачи](https://kilinskas19.thkit.ee/ToDoList/images/deleteTaskResult.png)

Теперь добавим еще один список с названием "Домашние дела"

![2 списка](https://kilinskas19.thkit.ee/ToDoList/images/list2.png)

Нажмем на список "Долги по учебе" и увидим что справа появился раздел, позволяющий удобно переключаться между списков 

![Переключатель списков](https://kilinskas19.thkit.ee/ToDoList/images/otherLists.png)

## Используемые инструменты

* [PHP](https://www.php.net) - Язык программирования. В проекте используется для соединения с БД, вывод данных из БД, регистрации, логина, обработки всех действий пользователя, например: изменить задачу, удалить задачу, удалить список задач и тд.
* [Javascript](https://ru.wikipedia.org/wiki/JavaScript) - Язык программирования, в проекте используется для регистрации, логина, выбора даты и времени при добавлении задачи, а также добавляет некоторую динамику в страницы и фиксит некоторые баги.
* [HTML](https://ru.wikipedia.org/wiki/HTML) - Язык разметки. В проекте используется для составления карказа всех страниц.
* [CSS](https://ru.wikipedia.org/wiki/CSS) -  Формальный язык описания внешнего вида документа, написанного с использованием языка разметки. В проекте используется для стилизации всех страниц которые есть, например: добавление анимаций, подсвечивание выдранного элемента, строки и так далее.
* [MySQL](https://ru.wikipedia.org/wiki/MySQL) - Язык запросов. В проекте используется как основная база данных, благодаря базе данных действия пользователя сохраняются и ему не нужно делать все по новой. Например: Создание аккаунта, создание списка задач и так далее.
* [jQuery](https://ru.wikipedia.org/wiki/JQuery) - Javascript библиотека. В проекте используется для реализации выбора даты и времени.
* [LucidChart](https://www.lucidchart.com) - это инструмент для совместной работы над визуализацией, который делает рисование диаграмм быстрым и простым. В проекте используется для построения [UML диаграмм](https://ru.wikipedia.org/wiki/%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B0_(UML)), таких как: [диаграмма прецедентов](https://ru.wikipedia.org/wiki/%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B0_%D0%BF%D1%80%D0%B5%D1%86%D0%B5%D0%B4%D0%B5%D0%BD%D1%82%D0%BE%D0%B2), [диаграмма базы данных](https://ru.wikipedia.org/wiki/%D0%A1%D1%85%D0%B5%D0%BC%D0%B0_%D0%B1%D0%B0%D0%B7%D1%8B_%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85) и [диаграмма активности](https://flexberry.github.io/ru/fd_activity-diagram.html).
* [Kanban](https://ru.wikipedia.org/wiki/%D0%9A%D0%B0%D0%BD%D0%B1%D0%B0%D0%BD_(%D1%80%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B0)) - Гибкая методология разработки ПО. В проекте используется для назначения задач, разбитие их по группам, меткам и участникам. Также добавляется ожидаемая дата и время завершение задачи.
Для реализации данной методологии мы пользовались to do list`ом  [Trello](https://trello.com/b/GuDLSjlX/to-do-list).


## Управление версиями

Для управления версиями мы создали общую папку проекта на веб хостинге [Zone](https://www.zone.ee/) и выдали каждому разработчику права на подключение к папке, в итоге разработчик с помощью FTP соединения может подключаться к папке и работать в своем редакторе кода.

## Заключение 
В целом проект получился интересный, рабочий и удобный.
Благодаря этому проекту мы научились работать в команде, узнали очень много новых функций и фишек в используемых технологиях и также изучили пару новых технологий которые до этого не использовали. [Финальная версия проекта](https://kilinskas19.thkit.ee/ToDoList) ToDoList.

## Авторы

* **Витас Килинскас**  - [Портфолио](https://kilinskas19.thkit.ee/)
* **Никита Руднев**  - [Портфолио](https://rudnev19.thkit.ee/)
