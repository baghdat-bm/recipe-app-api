# recipe-app-api
Recipe API project

alias dc='docker-compose'

# comit
git commit -am "Desciption..."

# push
git push origin

# run test
docker-compose run --rm app sh -c "python manage.py test"

# run lint
docker-compose run --rm app sh -c "flake8"
