# Parcel Tracker CI/CD

Проект посылочного трекера с настроенным CI/CD через GitHub Actions.

## Workflow

- **test** — запускает юнит-тесты и проверку кода (go vet) при каждом push
- **deploy** — собирает Docker-образ и публикует в GitHub Container Registry (ghcr.io)
