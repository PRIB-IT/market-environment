# Market Environment

## Clone

Clone the repository with `--recurse-submodules` flag so it will clone all the repositories needed to run the full application.

## Configuration

It repository may have a different configuration that are needed to run the application. To make that happen, follow the instructions provided on each repository.

- [market-gateway](https://github.com/PRIB-IT/market-gateway)
- [market-BFF](https://github.com/PRIB-IT/market-BFF)
- [market-UI](https://github.com/PRIB-IT/market-UI)
- [market-client-service](https://github.com/PRIB-IT/market-client-service)
- [market-products-service](https://github.com/PRIB-IT/market-products-service)
- [market-authorization-service](https://github.com/PRIB-IT/market-authorization)
- [market-suggestion-service](https://github.com/PRIB-IT/market-suggestion-service)

## Deploying

1. To start up the environment
```cmd
  docker-compose up --build -d
```

2. To stop the environment
```cmd
  docker-compose down
```