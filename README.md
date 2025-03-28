📊  Alert Notifications for CPU Utilization Monitoring

Grafana Alerting Monitoring
🔍 Overview

This project implements real-time alert notifications in Grafana to monitor CPU utilization. The system triggers alerts when CPU usage exceeds a defined threshold and sends notifications via configured contact points (e.g., Email, Telegram).
🚀 Features

✔ Alert Notifications – Monitor CPU usage and get instant alerts.
✔ Multi-Channel Notifications – Supports Email, Telegram, and more.
✔ Dynamic States – Alerts switch between 🔥 Firing and ✅ Normal based on conditions.
✔ Easy Setup – Simple configuration with Grafana’s intuitive UI.
⚙️ Workflow
📌 Creating an Alert Rule

    🔖 Name the Alert – E.g., "High CPU Usage Alert".

    📊 Define Query – Set up the query to fetch CPU metrics.

    ⚠️ Set Threshold – E.g., Trigger when CPU > 0.5.

    🗂 Organize – (Optional) Add to a folder/label.

    ⏱ Evaluation Interval – E.g., Check every 10s.

    📩 Configure Notifications – Select who gets alerts.

    📞 Select Contact Point – Choose Email/Slack/Telegram.

    ✏️ Add Context – Customize alert messages.

    💾 Save Rule – Done!

📧 Creating a Contact Point (Email Example)

    🏷 Name It – E.g., "Dev Team Email Alerts".

    📤 Choose Integration – Select Email.

    ✉️ Enter Email – Add recipient(s).

    🧪 Test – Send a test notification.

    💾 Save – Ready for use!

📸 Screenshots
Alert Triggered (Firing)	Alert Resolved (Normal)	Email Notification
Firing	Normal	Email
🛠 Usage

    Go to Grafana Alerting → Create a new alert rule.

    Follow the steps above to set up thresholds and notifications.

    Verify alerts by monitoring CPU spikes.


    📝 Best Practices

✔ Test alerts before production deployment
✔ Set meaningful thresholds for your workload
✔ Use multiple channels for critical alerts
✔ Review alert history periodically

📌 Notes

🔹 Ensure Grafana is properly configured to collect CPU metrics.
🔹 Test contact points before deploying in production.
🔹 For advanced setups, check Grafana’s Alerting Docs.
🔗 Related Badges

License Status

Made with ❤️ and Grafana! 🚀
