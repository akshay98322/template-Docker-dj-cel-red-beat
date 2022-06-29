# Template-Docker-dj-cel-red-beat
This is a template project in Docker for Django-Celery-Redis-CeleryBeat


## Run Locally

Clone the project

```bash
  git clone https://github.com/akshay98322/template-Docker-dj-cel-red-beat.git
```
Go to the project directory

```bash
  cd template-Docker-dj-cel-red-beat
```

To run this project, you will need to rename the .env.dev-sample to .env.dev and add the environment variables to your .env.dev file.

Start the server

```bash
  docker-compose up --build
```

Migrate the tables

```bash
  docker-compose exec web python manage.py migrate --noinput
```

Check at http://localhost:8000/ for the app

Stop the server

```bash
  docker-compose down
```

