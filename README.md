# 2FA-Symfony

We have here an simple exemple that use Symfony 5 with the bundle scheb/2fa (bundle provides two-factor authentication). 

Install the project

### Pré-requis

* PHP 7.3
* Composer
* Symfony CLI
* Docker
* Docker-compose

### Lancer l'environnement de développement 
```bash
composer install
docker-compose up -d
symfony server:start -d
symfony open:local
```
* Open your navigateur : https://127.0.0.1:NUM_PORT/register (fill with the right port), then https://127.0.0.1:NUM_PORT/login
* For having the code, open the mailCatcher http://127.0.0.1:49155/ (change the port)

