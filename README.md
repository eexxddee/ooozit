1:
systemctl start nginx
systemctl enable nginx

2:

3:
docker build -t task3 .
docker run -d -p 80:80 task3 task3

вопросы
1. update - получение информации о новых пакетах, upgrade - установка новых пакетов
2. ss, netstat, lsof
3. ping, curl, ss, netstat, traceroute,
