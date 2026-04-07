Overview

This project demonstrates a simplified DevOps pipeline using Python. It automates deployment, continuously monitors application health, detects failures, and performs automatic rollback to a stable version.

The system simulates real-world DevOps practices used to maintain application reliability during faulty deployments.

Objectives

-Automate application deployment
-Monitor application health in real-time
-Detect failures (HTTP errors or crashes)
-Trigger automatic rollback to stable version
-Maintain logs for all operations

Technologies Used
-Python
-Flask
-Requests library
-Logging module
-File handling (shutil, os)

Auto Rollback Flow
-Monitor checks app every 5 seconds
-If app returns error (500) or crashes
-Rollback is automatically triggered
-Stable version is restored

Failure Simulation
v1: Stable version (returns 200 OK)
v2: Buggy version (returns 500 error or crashes)

Output
-deploy.log (deployment logs)
-monitor.log (monitoring logs)
-rollback.log (rollback logs)
-Console messages showing failure and rollback


Learning Outcomes
-Understanding CI/CD pipeline basics
-Implementing monitoring systems
-Handling failures in production
-Automating rollback mechanisms

Conclusion
This project demonstrates core DevOps concepts like automation, monitoring, and fault recovery using a simple Python-based system.
