# rails-react-ts-docker

## build

```bash
docker-compose build
```

## db create

```bash
docker-compose run api rails db:create
```

## front app create

```bash
docker-compose run --rm front sh -c "yarn create react-app app --template typescript"
```

## start container

```bash
docker-compose up
```
