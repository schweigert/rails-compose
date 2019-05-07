# rails-compose

Um exemplo de aplicação rails com docker compose ou docker swarm.

## executar aplicação

Executar aplicação no terminal:

```bash
    docker-compose up --build
```

Executar aplicação sem bloquear terminal:

```bash
    docker-compose up -d
```

Executando tasks após executar sem bloquear:

```bash
    docker-compose exec web bash
```