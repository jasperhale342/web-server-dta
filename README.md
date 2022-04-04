To start server:
cd AppServer
python manage.py runserver

to scale:
docker-compose up — scale web=3 -d