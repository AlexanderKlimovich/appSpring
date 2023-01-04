appSpring
Описание
Необходимо реализовать web CRUD приложение, которое имеет следующие сущность 

Person
Person имеет поля: id, name, age, email


В качестве хранилища данных необходимо использовать postgresql

Пользователь  должен иметь возможность создания, получения, редактирования и удаления данных.
Перед записью данных в базу проводится валидация.

Слои:
main.java.klymovych.model - POJO клаcс
main.java.klymovych.dao - класс, реализующий доступ к базе данных
main.java.klymovych.controllers - обработка запросов от пользователя
main.java.klymovych.util - валидация данных 
main.java.klymovych.config - конфигурация приложения
