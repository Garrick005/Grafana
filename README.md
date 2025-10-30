# Домашнее задание к занятию 14 «Средство визуализации Grafana»

### Задание 1
![task1](https://github.com/user-attachments/assets/6610c81e-0b89-4576-8274-eeaa3e149ec4)

### Задание 2
![task2](https://github.com/user-attachments/assets/8a7e0c60-302c-4344-81d3-4f03b02dddd7)

1. Утилизация CPU (в процентах, 100 - idle)
100 - (avg by (instance) (rate(node_cpu_seconds_total{mode="idle"}[5m])) * 100)   
2. Load Average 1, 5, 15 (CPULA 1/5/15)
node_load1
node_load5
node_load15
3. Свободная оперативная память
node_memory_MemAvailable_bytes / (1024 * 1024 * 1024)
4. Свободное место на файловой системе
node_filesystem_avail_bytes{fstype!="tmpfs", fstype!="overlay"} / (1024 * 1024 * 1024)

### Задание 3
![task3](https://github.com/user-attachments/assets/d6079fb8-d600-4ec8-b734-71c16baea738)

monitoring/Node Exporter Monitoring-1761839883397.json
