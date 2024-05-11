# Прочитайте в первую очередь
* Данный проект является одним из под-проектов в рамках курса "Docker и K8S глазами разработчика".
* В данном проекта мы рассматриваем простейший клиент, который отображает одну страницу и хранит состояние в памяти.

# Getting Started
* Для локального старта (без использования Docker) вам потребуется установленный node
* Необходимо выполнить команды
<br/>`npm install`
<br/>`npm start`
<br/>Открыть ссылку
<br/>`http://localhost:4200/`
* Для старта с использованием Docker необходимо:
* Установить Docker
* Создать образ
<br/>`docker build . --tag=nodeapp:latest`
* Запустить контейнер
<br/>`docker run -p 4200:4200 nodeapp:latest`

### Дополнительные ссылки
* [GitHub repository](https://github.com/proselytear/usersapi)
* [Proselyte Community TG](https://t.me/pse_club)

