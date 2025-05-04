# Monitoring-stack
Prometheus + Grafana + Alertmanager

# Monitoring Stack: Prometheus + Grafana + Alertmanager

Небольшой DevOps-проект, демонстрирующий настройку мониторинга и алертинга в Docker-среде.

## Стек технологий

- **Prometheus** — сбор и хранение метрик
- **Node Exporter** — метрики ОС (CPU, RAM, диски и т.д.)
- **Grafana** — визуализация метрик
- **Alertmanager** — отправка алертов (на email/Slack и др.)
- **Docker Compose** — управление сервисами

## Цель проекта

Показать умение:
- Настраивать мониторинг системных метрик
- Работать с alerting-правилами Prometheus
- Использовать Grafana для визуализации
- Работать с Docker Compose для локальной среды

## Как запустить

1. Установите [Docker Desktop](https://www.docker.com/products/docker-desktop)
2. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/yourname/monitoring-stack.git
   cd monitoring-stack
