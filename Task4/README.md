# Задание 4. Автоматизация развёртывания (локально через Docker)

## Диаграмма

![Диаграмма развёртывания](./diagram.svg)

## Как запустить

```bash
   terraform init
   terraform plan
   terraform apply
```

Приложение будет на `http://localhost:8080/` ручки - `/health` или `/info`

```bash
   terraform destroy
```

![Приложение](./tf-apply.png)
![Приложение](./curl.png)
![Приложение](./tf-destroy.png)
