# Application Metrics Monitoring using Prometheus and Grafana

**Objective:** To implement continuous monitoring of a Java application by collecting metrics with Prometheus and visualizing them in Grafana to automate feedback for faster issue detection and enhance build and monitoring processes.

**Real-time scenario:** A retail company offering a wide range of products, including electronics, clothing, and groceries, is transitioning to a DevOps architecture. The company aims to automate continuous monitoring across its various online platforms and physical stores.
To achieve this, they have adopted Prometheus, a metrics-based monitoring tool that collects data such as website response times, stock levels, and sales performance. The collected metrics are visualized in Grafana, enabling time-based dashboards for tracking trends and improving operational efficiency.
By integrating Prometheus and Grafana, the company seeks to provide continuous feedback to their operations and development teams, improving system reliability, enhancing customer experience, and reducing the time between identifying and resolving issues.

**Major Tools, Environment Used in This Project:**

- Prometheus
- Grafana
- AWS EC2 Instance: Ubuntu-24.04 (as Host Machine)
- Java: Version: open-jdk 17.0.15
- Maven: Version: Apache Maven 3.8.7
- GitHub Repo for Application Source Code

**High Levels Tasks/Steps:**

-	Install Java and Maven
-	Install and Configure Prometheus
-	Clone Java Application source code and Build the code using Maven
-	Install and Configure Grafana to visualize Metrics
-	Access Grafana and add Data Source as Prometheus
-	Create Grafana Dashboard with multi panels to Visualize Metrics

# Output Result Screenshots:
----------------------------------------------------------------------------------------------------------------------
Edit the Prometheus yml configuration file:

sudo vi /etc/prometheus/prometheus.yml

<img width="886" height="362" alt="image" src="https://github.com/user-attachments/assets/a23c20b1-a146-494f-b5b9-038e4a28fd92" />
------------------------------------------------------------------------------------------------------------------------------

<img width="941" height="442" alt="image" src="https://github.com/user-attachments/assets/0484ffdd-463e-4faa-a236-656dc6528d68" />

------------------------------------------------------------------------------------------------------------------------------

clone the Java app source code from git repository:

git clone https://github.com/simplilearn10/SpringBootPrometheusGrafana.git

<img width="947" height="206" alt="image" src="https://github.com/user-attachments/assets/5dffc240-fbbf-4a5d-ac46-133ca22ea066" />
-------------------------------------------------------------------------------------------------------------------------------

<img width="939" height="375" alt="image" src="https://github.com/user-attachments/assets/a88e0720-14b3-46e3-ba19-4efc2d43def4" />




