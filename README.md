# 🔁 Cron URL Pinger

This repository contains a GitHub Actions workflow that **pings a specified endpoint every minute**, using a secure cron job. It is ideal for triggering scheduled tasks like background jobs, queue processing, or webhook-based automation.

---

## 🚀 Features

- ⏱ Runs **every minute** using GitHub Actions scheduled workflows
- 🔁 Automatically retries up to 3 times on failure
- ✅ Logs HTTP status and response body for visibility
- 🔒 Uses **GitHub Secrets** to protect the cron URL and token
- 🆓 Runs from a **public repo** to benefit from free GitHub Actions minutes


