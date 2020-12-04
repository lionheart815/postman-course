
# This is the API for Postman Course

It is a simple version of an API builded with Django and Django Rest Framework
using Docker.

# How to run this project
- Install Docker and Docker Compose
- Execute `docker-compose up -d`: This command starts a local server with the API running over 8000 port.
- Get inside the docker container executing `docker exec -it postman-course_web_1 bash`
- Inside the docker container execute `source admin_info.sh`
- Run the migrations `python manage.py runscript migrations.admin_migration`
