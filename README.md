## Описание

Цель курса:
- Сформировать понимание этапов разработки приложений и познакомить с подходами и практиками, которые для этого применяются
- Познакомить с архитектурой веб-сервисов и бэкенд-приложениями

У каждой лабораторной свой репозиторий. В репозитории с лабораторной есть README с условием и структура проекта, которой желательно воспользоваться. Вопросы по лабораторным можно задавать в репозиториях во вкладке Issues.

В рамках лабораторных мы итерационно разработаем бэкенд-приложение. Выбор варианта в первой лабораторной повлияет на следующие. Можно предложить свой вариант для первой лабораторной.

Выполнение всех лабораторных оценивается в 8 баллов. Для получения оценки выше, нужно выполнить дополнительные задания (каждое из заданий добавляет +1 балл к итоговой оценке):
- Контейнеризировать приложение в Docker
- Провести код-ревью приложения однопоточника
- Подключить аутентификацию OAuth 2 через Google или GitHub API
- Логировать запросы и настроить логирование в stdout и файл через фасад Slf4j
- Для SQL баз данных наливать схему данных миграциями 
- Добиться 90% покрытия кода тестами
- Доработать проект до полноценного MVP, который бы решал какую-то задачу
- Разработать простенький фронтенд для написанного бэкенд-приложения
- Добавить документацию кода в формате Javadoc, создать README файл проекта с инструкцией по запуску и перечислением возможностей, делать логичные коммиты с понятным описанием (можно опираться на [конвенцию](https://www.conventionalcommits.org/en/v1.0.0/))  

## Лабораторные

1. Бизнес-логика и структуры данных: https://github.com/RSOI-2023/lab-1
2. Перенос приложения в Spring Context: https://github.com/RSOI-2023/lab-2
3. Spring Data JPA, персистентность данных: https://github.com/RSOI-2023/lab-3
4. Реализация контроллеров: https://github.com/RSOI-2023/lab-4
5. Добавление нового функционала, тестирование (в работе): https://github.com/RSOI-2023/lab-5ƒ

## Полезные материалы
- Курс лекций по Java Core от Тагира Валиева (Java Tech Lead в разработке IntelliJ IDEA): https://youtube.com/playlist?list=PLlb7e2G7aSpTCB2OxGlezpgOXwq4xer7Z
- Spring-построитель, доклад Евгения Борисова: https://youtu.be/rd6wxPzXQvo
- Spring-потрошитель, доклад Евгения Борисова: https://youtu.be/BmBr5diz8WA
