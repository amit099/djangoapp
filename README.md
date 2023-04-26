# djangoapp

Commands used in docker


docker build -t djangoapp .
docker images
docker run -d --name djandocontainer -p 8080:8080 djangoapp
docker login
docker tag djangoapp amit099/djangoapp
docker push amit099/djangoapp


running in development mode in 8080 port

python3 manage.py runserver 0.0.0.0:8080
