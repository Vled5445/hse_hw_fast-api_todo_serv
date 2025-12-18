# hse_hw_fast-api_todo_serv

Для выполнения данного задания нам необходимо создать файлы, которые требуются для работы нашего сервиса. Далее, необходимо выполнить следующие шаги для проверки его работоспособности:
Соберем наш докер образ 
<img width="1401" height="340" alt="image" src="https://github.com/user-attachments/assets/d25caa0e-2a90-461f-b7ca-baa0917eaced" />


Запустим докер <br>
<img width="778" height="33" alt="image" src="https://github.com/user-attachments/assets/aedd94b1-2e0b-4e1c-aced-9b0a9603c207" />


Запушим образ на dockerhub <br>:
<img width="702" height="159" alt="image" src="https://github.com/user-attachments/assets/813b4fc8-ac15-4ddc-b589-09396c3f36ce" />


Проверим работоспособность сайта  <br>
<img width="1438" height="851" alt="image" src="https://github.com/user-attachments/assets/27a9d59c-18b1-42db-819f-e17f93e89623" />


Для того, чтобы запустить данный сервис локально, можно воспользовать докер-контейнером, который размещен на dockerhub с помощью команды

<i>docker run -d -p 8000:80 --name todo-app vled5445/todo-app:latest</i>
