# Suricata Custom Rules for Home Threat Detection

This repository houses custom Suricata rules designed for home networks using Corelight @home sensors. These include signatures for smart appliances, IoT devices, NAS, routers, printers, gaming consoles, and endpoint activity.

## 🔄 Rule Deployment (e.g., via cron)

```bash
curl -o /etc/suricata/rules/custom.rules https://raw.githubusercontent.com/your-username/suricata-custom-rules/main/rules/custom_iot_monitoring.rules && \
suricatasc -c reload-rules