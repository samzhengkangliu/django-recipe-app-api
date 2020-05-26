# Django Recipe App API

This is a personal learning project for Django and Django REST Framework.

## Requirements
- Python 3.8.3
- Django 3.0.6
- Django REST Framework 3.11.0
- flake8 3.8.2
- Docker
- Travis CI

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install Django.

```bash
docker-compose build
```

## Run & Test
```bash
docker-compose run app sh -c "python manage.py runserver 8000"
```

```bash
docker-compose run app sh -c "python manage.py test"
```

Enable linting: 
```bash
docker-compose run app sh -c "python manage.py test && flake8"
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)