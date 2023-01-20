#  Cinema API

 API service for cinema management written on DRF

# Installing using CitHub

Install PostgreSQL and create db 
```
git clone https://github.com/InnaKushnir/docker-pro.git
cd cinema API
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```
# Run with docker

Docker should be installed
```
docker-compose build
docker-compose up
```
## Getting access
* create user via /api/user/register/
* get access token via /api/user/token/

## Features
* JWT authenticated
* Admin panel /admin/
* Documentation is located at /api/doc/swagger/
* Managing orders and tickets
* Creating movies with genres, actors
* Creating cinema halls
* Adding movie sessions
* Filtering movies and movie sessions

### Test user

* Email: `12345@gmail.com`

* Password: `12345user`
