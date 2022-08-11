# WAF Monitoring

In order to control the performance of a project and maintain its status, it is necessary to monitor different layers of the project. One of the most important part of network hardwares is web application firewalls that must be controlled instantly and the device information displayed on the dashboard.

It should be noted that the SNMP V3 protocol has been used to monitor these devices over Grafana platform.

The mentioned dashboard includes the following item:
- Hostname
- OS Version
- Uptime
- Operation Mode
- HA Mode
- Number of CPU
- RAM Capacity
- Disk Capacity
- CPU Usage
- CPU Frequency
- Memory Utilization
- Disk Usage
- Send / Receive Rate
- Port Summary (Name, Index, Alias, Status, Bandwidth, Type, In Errors, Out Errors)


In the pictures below, you can see the dashboard visualizations:

![image](https://user-images.githubusercontent.com/43276746/184242698-ff611e39-d8e6-4ffb-ae47-db8a6823d8ca.png)
![image](https://user-images.githubusercontent.com/43276746/184243211-8ae8ae3a-bce2-404e-a201-e1c96b09bc66.png)
![image](https://user-images.githubusercontent.com/43276746/184243414-5d95a060-ce14-4948-8c67-663f76974b52.png)



Requirements:
- Grafana: https://grafana.com/grafana/download
- InfluxDB & Telegraf: https://portal.influxdata.com/downloads/

Remember:
- At first you need to apply your informations in both of dashoboard and configuration (YOUR-IP, YOUR-NAME, USERNAME, YOUR-AUTH-PASSWORD, YOUR-PRIV-PASSWORD)
- To use snmp configurations you need to load their mib files
