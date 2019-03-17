 В директорию site.local устанавливаем yii-advanced.  
 nano /etc/hosts   
 127.0.0.1 hello.dev  
 127.0.0.1 frontend.test  
 127.0.0.1 backend.test  
 sudo usermod -aG docker $USER  
 docker-compose exec php composer  
 docker-compose exec php composer create-project --prefer-dist yiisoft/yii2-app-advanced yii-application  
 sudo docker-compose exec php php site.local/yii-application/init  
 https://github.com/yiisoft/yii2-app-advanced/blob/master/docs/guide/start-installation.md  
