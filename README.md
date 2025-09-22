# GitHub Actions Auto Commit

This repository demonstrates how to use **GitHub Actions** to automate daily commits.  
It runs a simple workflow that writes a timestamp to a file and commits the change once per day.

## Why?

- To explore **GitHub Actions** scheduling (`cron` jobs).  
- To learn how automated workflows can interact with a repository.  
- To keep my contribution activity grid consistently active.

## How it works

1. A workflow is defined in `.github/workflows/autocommit.yml`.  
2. Every day at midnight UTC, the workflow runs.  
3. It writes the current timestamp to a file and pushes the change.  

This provides a practical example of continuous automation in GitHub.

## Notes

- This project is for **educational purposes** (learning automation).  
- If you fork or reuse this, feel free to adapt it for your own workflows.  

---

📌 Example use cases beyond this demo:  
- Automatically update documentation.  
- Keep logs of build/test runs.  
- Generate daily reports.
