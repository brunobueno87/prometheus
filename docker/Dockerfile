# Use a imagem oficial do Prometheus
FROM prom/prometheus:latest

# Copia um arquivo de configuração personalizado (opcional)
# Substitua "prometheus.yml" pelo caminho do seu arquivo de configuração
COPY prometheus.yml /etc/prometheus/

# Expõe a porta padrão do Prometheus
EXPOSE 9090

# Comando para rodar o Prometheus
CMD ["--config.file=/etc/prometheus/prometheus.yml"]

