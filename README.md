# gcp-cloud-monitoring-alerting
Hands-on Google Cloud Monitoring project demonstrating dashboards, alerting policies, uptime checks, and resource grouping.
#  GCP Cloud Monitoring & Alerting

##  Project Overview
This project demonstrates hands-on experience with Google Cloud Monitoring, including creating custom dashboards, configuring alerting policies, setting up uptime checks, and organizing resources using groups.

---

##  Tools & Technologies
- Google Cloud Platform (GCP)
- Cloud Monitoring
- Compute Engine (VM Instances)
- Uptime Checks
- Alerting Policies

---

## ⚙️ Tasks Performed

### Task 1: Monitoring Overview
- Explored Cloud Monitoring interface
- Reviewed metrics and resource usage

---

###  Task 2: Custom Dashboard
- Created a custom dashboard named My Dashboard
- Added a line chart to monitor CPU utilization
- Used Metrics Explorer to analyze resource metrics

---

###  Task 3: Alerting Policies
- Created an alert policy with two conditions:
  - CPU usage > 20%
  - CPU utilization > 20%
- Configured multi-condition trigger: All conditions are met
- Added email notification channel

---

###  Alerting Best Practice
Avoid excessive alert noise. Alerts should be meaningful and actionable.

---

###  Task 4: Resource Groups
- Created a group named VM instances
- Filtered instances using:
  - Contains: nginx
- Automatically generated monitoring dashboard for the group

---

###  Task 5: Uptime Monitoring
- Created an uptime check with:
  - Protocol: HTTP
  - Resource type: Instance
  - Group: VM instances
  - Frequency: 1 minute
- Verified connectivity using test feature
- Configured alert notifications

---

###  Task 6: Disable Alert Policy
- Disabled the alert policy after creation
- Ensured proper cleanup of monitoring configuration

---

## 📸 Screenshots

| Step | Image |
|------|------|
| Dashboard Created | images/dashboard.png |
| CPU Utilization Chart | images/cpu-chart.png |
| Alert Policy Created | images/alert-policy.png |
| Notification Channel | images/notification-channel.png |
| Resource Group | images/resource-group.png |
| Uptime Check | images/uptime-check.png |
| Alert Disabled | images/alert-disabled.png |

---

##  Key Learnings
- Building custom monitoring dashboards
- Creating alerting policies with multiple conditions
- Configuring notification channels
- Monitoring service availability using uptime checks
- Organizing resources using groups

---



##  Notes
This project represents practical hands-on experience with Google Cloud Monitoring and reflects real-world cloud operations and observability practices.
