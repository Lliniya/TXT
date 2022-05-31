# TXT
Homework

1. Создать внешний репозиторий c названием TXT.

	`Repositories -> New -> Repository name: TXT -> Create repository`

2. Клонировать репозиторий TXT на локальный компьютер.

	`git clone https://github.com/Lliniya/TXT.git

3. Внутри локального TXT создать файл “new.txt”.
	```
	cd txt
	touch new.txt
	```
4. Добавить файл под гит.

	`git add new.txt`

5. Закоммитить файл.

	`git commit -m "add first new.txt file"`

6. Отправить файл на внешний GitHub репозиторий.

	`git push`

7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
	```
	ФИО: Корягина Алина Александровна
	Возраст: 24
	Домашние животные: нет
	Будущая желаемая зарплата: $3000
	```
8. Отправить изменения на внешний репозиторий.
	```
	git status
	git checkout main
	git add new.txt
	git commit -m "edit the new.txt file"
	git push
	```
9. Создать файл preferences.txt

	`touch preferences.txt`

10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
```
Любимый фильм - "Лучшее предложение".
Любимый сериал - "Увивительная мисис Мэйзел".
Любимая еда - йогурты.
Любимое время года - лето.
Страна, которую хочу посетить - Исландия.
```

11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
	```
1. Базовая теория (Что такое тестирование, багрепорты, документаци, виды, методы, направления тестирования и т.п.) SDLC, STLC.
2. Что такое клиент-серверная архитектура.
3. HTTP Методы запросов на сервер.
4. Коды ответов HTTP сервера.
5. Структуры HTTP запросов и ответов.
6. Что такое JSON, XML. Их структура.
7. Тестирование API через Postman (JS, автотесты API).
8. Снятие и чтение логов c внешнего сервера.
9. Снифинг http web трафика через Charles и Fiddler.
10. Dev Tools веб браузеров (Google Chrome, FireFox).
11. VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)
12. Мобильное тестирование.
13. Особенность iOS, Android, гайдлайны.
14. Сборка iOS приложений на XCode. 
15. Сборка Android приложений на Android Studio.
16. ADB (управление андройд девайсами).
17. Настройка прокси и vpn на iOS и Android.
18. Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android.
19. Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)
20. Основы bash скриптинг, автоматизация рутинных задач на сервере.
21. Доступ к удалённым серверам.
22. Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).
23. База данных Postgres (установка, настройка и использование).
24. Нереляционная база данных Redis (установка, настройка и использование).
25. Нагрузочное тестирование в Jmeter.
26. Методология разработки Scrum.
	```
12. Сделать коммит в одну строку.

	`git add preferences.txt sklls.txt; git commit -m "add preferences.txt, sklls.txt"`

13. Отправить сразу 2 файла на внешний репозиторий.

	`git push`

14. На веб интерфейсе создать файл bug_report.txt.

	`Repositories -> TXT -> Add file -> Create new file -> "Name your file": bug_report.txt`

15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
	```
	Блок "Commit new file"
	В поле заголовка: create bug_report.txt
	В поле описания: create my first bug_report.txt
	Нажать на кнопку "Commit changes"
	```
16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
	```
	Repositories -> TXT -> bug_report.txt -> Edit this file 
	Приступить к редактированию файла в поле "Edit file"
	```
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
	```
	В поле заголовка: можно оставить пустым, а можно указать Update bug_report.txt
	В поле описания: "added first bug report"
	Нажать на кнопку "Commit changes"
	```
18. Синхронизировать внешний и локальный репозиторий TXT

	`git pull`
