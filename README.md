# AWS-cloudwatch-monitoring
Monitoring EC2 using AWS Cloudwatch, Alarms, SNS and dashboards.
#Project Overview-
This is the basic project that demonstrates how to launch EC2 instance, monitor cloud applications, alarm setup, SNS notification system and visulizing metrics dashboards.
##Services used
--Amazon EC2
--AWS Cloudwatch
--Amazon SNS

## Implementation Steps
### 1. Launched EC2 Instance
- Created an EC2 instance to simulate a cloud-based application.
- Used default CloudWatch metrics provided by AWS.

### 2. CloudWatch Monitoring
- Monitored EC2 metrics such as:
  - CPUUtilization
  - NetworkIn
  - NetworkOut

### 3. CloudWatch Alarm
- Created a **High CPU Utilization Alarm**
- Threshold: CPU > 70%
- Evaluation period: 5 minutes
- Alarm state change triggers notification

### 4. SNS Notification
- Integrated Amazon SNS
- Configured email notification for alarm state changes
- Received alert when CPU usage crossed the threshold

### 5. Time Zone Awareness
- Learned the importance of correct time zone selection
- Ensured accurate metric evaluation and alert timing

### 6. CloudWatch Dashboard
- Created a dashboard to visualize:
  - CPUUtilization
  - Network traffic
- Enabled centralized monitoring view

## Outcome
- Successfully triggered alarm by increasing CPU usage
- Received real-time email alerts
- Visualized metrics using CloudWatch dashboard

## 🏁 Conclusion
This project provided hands-on experience with AWS monitoring, alerting, and observability using CloudWatch and SNS.
