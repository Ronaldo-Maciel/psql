# Como rodar

Verifique o IP do docker:

```bash
 ifconfig
```

Geralmente: 172.17.0.1

```bash
  docker-compose up -d postgres
  docker-compose run --rm  postgres bash
```