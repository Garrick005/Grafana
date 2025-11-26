# Домашнее задание к занятию «Микросервисы: масштабирование»

## Задача 1: Кластеризация

Оптимальное решение это Kubernetes-кластер как основная платформа

Основой решения является кластер Kubernetes (k8s), дополненный:

- Container Registry (Docker Registry / Harbor / GitLab Registry / ECR / GCR)
- Ingress-контроллером (Nginx Ingress / Traefik / Istio Gateway)
- Системой сервис-мэш (опционально): Istio / Linkerd
- Автоматическим масштабированием: Horizontal Pod Autoscaler (HPA)
- Секрет-хранилищем: Kubernetes Secrets или HashiCorp Vault
- Мониторингом и логированием: Prometheus + Grafana, Loki / ELK
