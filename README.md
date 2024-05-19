# Crypto Prophet
## Дипломен проект
Проектът е на тема "Крипто телеграм бот".
# Изпълнение на проекта
## Ръководство за изпълнение на сървъра
За да изпълните сървърната част на проекта трябва да имате инсталирани следните програми: 
Java
MongoDB
Git
Stripe Client
Google Client
Освен това трябва да имате профил в Google Cloud и акаунт с включена Vertex AI услуга. 
### Инсталиране на програмата
Създайте нова директория на Вашия компютър. Отворете терминал в създадената директория и изпълнете тази команда:

git clone https://github.com/NikiKerezov/userHandlerBE2.git

### Конфигуриране и изпълнение на проекта
Отворете Google Client и влезте в своя акаунт. След това отворете Stripe Client и изпълнете следната команда:

stripe listen --forward-to localhost:8080/stripe/hook

Отворете файла src/main/resources/application.properties. Попълнете Вашите данни. След това изпълнете проекта. Вече успешно изпълнявате сървъра на адрес localhost:8080.
	

## Ръководство за изпълнение на клиента
За да изпълните клиентската част на проекта трябва да имате инсталирани следните програми: 
Git
NPM
### Инсталиране на програмата
Създайте нова директория на Вашия компютър. Отворете терминал в създадената директория и изпълнете тази команда:

git clone https://github.com/NikiKerezov/crypto-prophet-fronend.git

### Конфигуриране и изпълнение на проекта
Отворете терминал в папката на проекта и изпълнете следните команди:

npm install
npm start

Вече успешно изпълнявате клиента на адрес localhost:3000.

#Архитектура на проекта
Проектът е разделен на клиент и сървър.

Сървърът е написан на Java Spring Boot.
Клиентът е уеб приложение написано на React.js.

# Използвани технологии
#### Java Spring Boot
#### MongoDB
#### Stripe
#### Vertex AI
#### React.js
#### HTML
#### CSS

# Изработен от:
## Никола Керезов
## Дипломен ръководител:
### Валери Добрев
## Рецензент: 
### Теодора Йовчева
