Скачать и запустить Docker. 
Скачать образы для докера Node.js, mysql, postgresql.

1. Открыть терминал
2. Выполнить в терминале команду `docker-compose up`
3. Открыть новую консоль.
4. Выполнить в терминале команду `cd gate-simulator`
5. Выполнить в терминале команду `docker-compose up`
6. Открыть новую консоль.
7. Выполнить в терминале команду 
   `java -jar artifacts/aqa-shop.jar`
8. Запустить тесты (команда `./gradlew test` либо нажать run)

После завершения тестов, в последнем терминале остановить 
работу приложения сочетанием клавиш ctrl + C.
1. В файле `application.properties` раскомментировать 3 строку 
и закомментировать 4 строку. 
2. В файле `AppTest` переменной `database` присвоить значение `mysql`.
3. Запустить тесты.
