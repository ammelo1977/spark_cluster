Este projeto possui apenas um arquivo docker-compose.yml que permite a criação de um cluster spark. Para iniciar o cluster com 2 nós executores (no windows):
docker-compose.exe up --scale spark-worker=2
