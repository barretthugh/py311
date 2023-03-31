FROM barretthugh/py311

RUN apt-get update \
    && apt-get install -y cron --allow-unauthenticated

CMD ["cron", "-f"]
