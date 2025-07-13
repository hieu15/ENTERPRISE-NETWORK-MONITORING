# 📅 ENTERPRISE-NETWORK-MONITORING
ENTERPRISE NETWORK MONITORING WITH PROMETHEUS AND GRAFANA <br>

## Day 1: Kiến thức cơ bản & tổng quan
- Monitor hạ tầng trong doanh nghiệp: khái niệm, lợi ích
- Công cụ phổ biến
- Metric là gì
- Giao thức: SNMP, WMI, ICMP, API
- So sánh hệ thống monitor

## Day 2: Thực hành Prometheus & Grafana
- Cài Prometheus, Grafana
- Thêm thiết bị vào Prometheus (`prometheus.yml`)
- Viết query PromQL

## Day 3: Grafana nâng cao & dashboard
- Tạo dashboard, chart, gauge, table, panel
- Dashboard mẫu: Cisco, VMware, Firewall, Network device, Linux, Windows

## Day 4: Giám sát thiết bị qua SNMP
- SNMP: version, MIB, OID, community, trap
- Cài snmp_exporter, cấu hình snmp.yml
- Kiểm tra thiết bị (snmpwalk, snmpget)
- Hiển thị dữ liệu SNMP trên Grafana

## Day 5: Giám sát VMware & Blackbox
- Giám sát VMware: vmware_exporter, kết nối vCenter, metric cluster, host, VM
- Hiển thị VMware trên Grafana
- Giám sát Blackbox: HTTP, ICMP, TCP check, cấu hình probe, monitor website/API
- Dashboard Blackbox: latency, status code, response time

## Day 6: Alert trong Monitoring
- Khái niệm Alert: phát hiện sự cố, giảm downtime
- Alertmanager: cài đặt, rule alert, kết nối email/Slack/webhook
- Alert Grafana: thiết lập alert, notification channel, trạng thái alert
- Best Practices: tránh alert noise, ngưỡng hợp lý
