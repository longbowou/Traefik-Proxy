# Traefik

![Traefik](https://doc.traefik.io/traefik/assets/img/traefik-architecture.png)

Traefik is an open-source Edge Router that makes publishing your services a fun and easy experience. It receives
requests on behalf of your system and finds out which components are responsible for handling them.

## Getting Started

[Documentation](https://doc.traefik.io/traefik)

Create traefik proxy external network:

```
docker network create traefik-proxy
```

Create acme file:

```
touch acme.json && chmod 600 acme.json
```

Start Traefik

```
docker compose up -d
```

## License

This project is licensed under the [MIT License](LICENSE).

