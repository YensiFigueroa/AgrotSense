# AgrotSense
# 🐷 AgroSense IoT – Monitoreo Inteligente para Granjas Porcinas

Dashboard web en tiempo real para monitoreo ambiental de granjas porcinas, desarrollado como proyecto de grado en Ingeniería de Sistemas – UNAD, CIP La Dorada.

## 📡 ¿Qué hace?
Visualiza en tiempo real temperatura, humedad, amoniaco (NH₃) y metano (CH₄) capturados por sensores IoT distribuidos en sectores de una granja porcina. Incluye sistema de alertas, log MQTT simulado, histórico de 24 horas y configuración de umbrales personalizables.

## 🛠️ Stack tecnológico
- **Hardware:** ESP32 DevKit v1 · DHT22 · MQ-135 · MQ-4
- **Protocolo:** MQTT (Mosquitto)
- **Pipeline:** Node-RED → InfluxDB → Grafana
- **Dashboard:** HTML + CSS + JavaScript + Chart.js (archivo único, sin dependencias de servidor)

## 🌐 Demo en vivo
👉 [Ver dashboard](https://yensi-figueroa.github.io/iot-granja-porcina-caldas/)

