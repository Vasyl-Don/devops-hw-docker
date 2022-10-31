# devops-hw-docker
  
  АВТОРИЗАЦІЯ <br />
docker login <br /><br />
  СТВОРЕННЯ КОНТЕЙНЕРА <br />
docker build -t vasyldon/devops_hw . <br /><br />
  ЗАВАНТАЖЕННЯ НА DOCKER <br />
docker push vasyldon/devops_hw <br /><br />
  ЗАПУСК <br />
docker run -p 80:80 --name my-container --cpu-period=50000 --cpu-quota=25000 --memory=512m vasyldon/devops_hw
