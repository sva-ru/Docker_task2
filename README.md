## Команды для запуска контейнера c backend-сервером
1) Создаем образ на основе джанго проекта, коммандой: 

   docker build -t my_django_project:v1 .

3) Затем запускаем образ:

   docker run -d -p 8000:8000 my_django_project:v1
