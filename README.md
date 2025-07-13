# 📅 ENTERPRISE-NETWORK-MONITORING
ENTERPRISE NETWORK MONITORING WITH PROMETHEUS AND GRAFANA <br>
## Day 1: Kiến thức cơ bản & tổng quan

✅ **Monitor hạ tầng trong doanh nghiệp là gì?**  
Giám sát tài nguyên, trạng thái, hiệu suất hạ tầng IT.  
Lợi ích: phát hiện lỗi sớm, giảm downtime, đảm bảo SLA.

✅ **Những công cụ monitor phổ biến hiện tại**  
- Open-source: Prometheus, Grafana, Zabbix, Nagios, ELK Stack.  
- Thương mại: SolarWinds, PRTG, ManageEngine, Datadog, Dynatrace.

✅ **Metric là gì?**  
Chỉ số đo lường như CPU usage, memory usage, disk I/O, network throughput, response time.

✅ **Các giao thức monitor thiết bị mạng**  
- SNMP: thiết bị mạng, switch, router.  
- WMI: máy chủ Windows.  
- ICMP: ping, kiểm tra connectivity.  
- API: dịch vụ cloud, SaaS.

✅ **So sánh các hệ thống monitor phổ biến**  
So sánh license, giao thức, tính năng, ưu nhược điểm, scalability.

---

## Day 2: Thực hành Prometheus & Grafana

✅ **Cài đặt Prometheus, Grafana, agent**  
- Prometheus server  
- Exporter (Linux, Windows, network device)  
- Grafana kết nối Prometheus

✅ **Thêm thiết bị monitor vào Prometheus**  
- Chỉnh `prometheus.yml`  
- Kiểm tra target UP/DOWN

✅ **Câu lệnh PromQL**  
- Viết query: `node_cpu_seconds_total`, `rate()`, `sum() by ()`  
- Filter, aggregation, grouping

✅ **Các hàm của Prometheus**  
`rate()`, `irate()`, `increase()`, `sum()`, `avg()`, `max()`, `min()`

---

## Day 3: Grafana nâng cao & dashboard thực tế

✅ **Hướng dẫn dùng Grafana**  
- Tạo dashboard, chart, line, gauge, table  
- Thiết lập panel, threshold, alert

✅ **Dashboard mẫu**  
- Cisco (interface traffic, error rate)  
- VMware (CPU, memory, datastore)  
- Firewall (sessions, throughput, drops)  
- Network device (latency, packet loss)  
- Linux (CPU, memory, load, disk)  
- Windows (CPU, memory, services, event log)

---
