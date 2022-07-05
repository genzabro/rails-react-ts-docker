# rails-react-ts-docker

## build

```bash
docker-compose build
```

## db create

```bash
docker-compose run api rails db:create
```

## start container

```bash
docker-compose up
```

#### backend app created

```bash
docker-compose run --no-deps api rails new . --force  -d mysql --api
```

#### frontend app created

```bash
docker-compose run --rm front sh -c "yarn create react-app app --template typescript"
```
