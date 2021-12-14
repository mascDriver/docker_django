para executar o sistema, execute:
`docker-compose build`
`docker-compose run web python manage.py migrate`


em caso de falha da senha postgres rode `docker-compose down -v` e rode novamente `docker-compose up`