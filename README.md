# 🚀 Day 07 – CloudWatch Monitoring & Alerts

---

## 📌 Overview

On Day 07, I explored **Amazon CloudWatch**, a monitoring and observability service in AWS used to track metrics, collect logs, create alarms, and automate actions.

---

# ☁️ What is Amazon CloudWatch?

Amazon CloudWatch is a monitoring service that helps users observe AWS resources and applications in real time.

It helps to:

* Monitor performance
* Collect logs
* Create alerts
* Trigger automated actions

---

# 🔑 Key Features

* Real-time monitoring
* Metrics collection
* Log management
* Alarm creation
* Dashboard visualization
* Automated notifications

---

# 🧱 CloudWatch Components

## 1. Metrics

Numerical performance data from AWS resources.

### Examples:

* CPU Utilization
* Memory Usage
* Disk Read/Write
* Network Traffic

---

## 2. Logs

Stores application and system logs.

### Uses:

* Troubleshooting
* Error tracking
* Application monitoring

---

## 3. Alarms

CloudWatch alarms monitor metrics and perform actions when thresholds are crossed.

### Example:

* CPU > 80% → Send notification

---

## 4. Dashboards

Custom monitoring dashboards with graphs and metrics.

---

## ⚙️ Workflow Diagram

![CloudWatch Workflow](diagram.png)

### (Text Version)

```plaintext id="pb2ezt"
AWS Resources
      ↓
CloudWatch
 ↓     ↓      ↓
Metrics Logs Alarms
      ↓
Notifications / Actions
```

---

# 🔔 Alarm Actions

* Send Email (SNS)
* Trigger Auto Scaling
* Restart EC2 Instance
* Invoke Lambda Function

---

# 🌍 Real-World Use Cases

1. Monitor EC2 CPU usage
2. Detect application failures
3. Centralized log monitoring
4. Auto scaling based on traffic
5. Server health monitoring
6. Security monitoring
7. Performance optimization
8. Troubleshooting production issues
9. Monitoring APIs
10. Tracking cloud costs

---

# 🧠 What I Learned

* CloudWatch fundamentals
* Metrics and logs
* Alarm configuration
* Monitoring dashboards
* Automated cloud monitoring

---

# 🚀 Next Step (Day 08)

* AWS Lambda (Serverless Computing)

---

# 📌 Author

**Sankar S**
Cloud & AI Learning Journey 🚀
