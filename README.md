# dz4 Инфраструктурные паттерны

Для запуска проекта использовать команды

```bash
helm dependency build
helm install dz4 ./
```

Также необходимо заполнить данные для подключения postgresql
в файле values.yaml в секции global.postgresql.auth