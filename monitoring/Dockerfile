# Используем официальный образ Prometheus
FROM prom/prometheus:latest

# Копируем конфигурацию Prometheus
COPY prometheus.yml /etc/prometheus/prometheus.yml

# Копируем конфигурацию Blackbox Exporter
COPY blackbox.yml /etc/prometheus/blackbox.yml

# Открываем порт для Prometheus
EXPOSE 9090
