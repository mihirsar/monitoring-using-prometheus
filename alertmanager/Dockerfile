# Use the official Alertmanager image
FROM prom/alertmanager:latest

# Copy the Alertmanager configuration file
COPY alertmanager.yml /etc/alertmanager/alertmanager.yml

# Expose Alertmanager ports (default is 9093)
EXPOSE 9093

# Start Alertmanager with custom configuration
CMD ["--config.file=/etc/alertmanager/alertmanager.yml"]
