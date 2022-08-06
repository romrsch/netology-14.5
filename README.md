# Домашнее задание к занятию "14.5 SecurityContext, NetworkPolicies"

## Задача 1: Рассмотрите пример 14.5/example-security-context.yml

Создайте модуль

```
kubectl apply -f 14.5/example-security-context.yml
```
***Ответ:***

![Alt text](https://i.ibb.co/6P4SRL4/Screenshot-1.jpg)

![Alt text](https://i.ibb.co/hg1zmFX/Screenshot-3.jpg)

Проверьте установленные настройки внутри контейнера

![Alt text](https://i.ibb.co/vQJWMj1/Screenshot-23.jpg)
```
kubectl logs security-context-demo
uid=1000 gid=3000 groups=3000
```
***Ответ:***

![Alt text](https://i.ibb.co/KL1JJvF/Screenshot-2.jpg)

---
