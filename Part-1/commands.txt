docker build --tag python-django .
docker run --publish 8000:8000 python-django