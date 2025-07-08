# Suricata Alert and Log Analysis Lab

## 🔍 Objective

Analyze network traffic using Suricata IDS, write custom rules, and interpret alert logs (`fast.log` and `eve.json`).

## 🧪 Files

- `sample.pcap`: Sample captured network traffic
- `custom.rules`: Suricata rule triggering on `GET` HTTP method
- `fast.log`: Summary of alerts
- `eve.json`: JSON-format Suricata output (full events)

## ⚙️ Run Suricata

```bash
sudo suricata -r sample.pcap -S custom.rules -k none

