## Для информации:
1. билдим:  			    **docker build -t antuanuran/api .**
2. заливаем на Hub:   		**docker push antuanuran/api**
3. спуливаем:               **docker pull antuanuran/api**
4. docker-compose:          **docker-compose up -d**

5. Устанавливаем Docker и Docker-compose:  
### Установка Docker:
curl -fsSL https://get.docker.com -o get-docker.sh  
sh get-docker.sh

### Установка Докер-композ:
sudo curl -L "https://github.com/docker/compose/releases/download/1.26.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose  
sudo chmod +x /usr/local/bin/docker-compose
