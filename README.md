## Docker

Билд

```
docker build -t nginx-landing -f Dockerfile .
```

Запуск

```
docker run -d -p 80:80 nginx-landing
```
