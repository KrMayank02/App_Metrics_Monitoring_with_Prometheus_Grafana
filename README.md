# Application Metrics Monitoring using Prometheus and Grafana

**Objective:** To implement continuous monitoring of a Java application by collecting metrics with Prometheus and visualizing them in Grafana to automate feedback for faster issue detection and enhance build and monitoring processes.

**Real-time Scenario:** A retail company offering a wide range of products, including electronics, clothing, and groceries, is transitioning to a DevOps architecture. The company aims to automate continuous monitoring across its various online platforms and physical stores.
To achieve this, they have adopted Prometheus, a metrics-based monitoring tool that collects data such as website response times, stock levels, and sales performance. The collected metrics are visualized in Grafana, enabling time-based dashboards for tracking trends and improving operational efficiency.
By integrating Prometheus and Grafana, the company seeks to provide continuous feedback to their operations and development teams, improving system reliability, enhancing customer experience, and reducing the time between identifying and resolving issues.

----------------------------------------------------------------------------------------------------

## Major Tools, Environment Used in This Project:

- Prometheus
- Grafana
- AWS EC2 Instance: Ubuntu-24.04 (as Host Machine)
- Java: Version: open-jdk 17.0.15
- Maven: Version: Apache Maven 3.8.7
- GitHub Repo for Application Source Code

-----------------------------------------------------------------------------------------------------

## High Levels Tasks/Steps:

-	Install Java and Maven
-	Install and Configure Prometheus
-	Clone Java Application source code and Build the code using Maven
-	Install and Configure Grafana to visualize Metrics
-	Access Grafana and add Data Source as Prometheus
-	Create Grafana Dashboard with multi panels to Visualize Metrics

-------------------------------------------------------------------------------------------------------

## Output Result Screenshots:

<img width="928" height="305" alt="image" src="https://github.com/user-attachments/assets/340c7b9d-8515-4c95-bab9-d2fe59b6663d" />

----------------------------------------------------------------------------------------------------------------

Edit the Prometheus yml configuration file:

sudo vi /etc/prometheus/prometheus.yml

<img width="886" height="362" alt="image" src="https://github.com/user-attachments/assets/a23c20b1-a146-494f-b5b9-038e4a28fd92" />

------------------------------------------------------------------------------------------------------------------------------

<img width="941" height="442" alt="image" src="https://github.com/user-attachments/assets/0484ffdd-463e-4faa-a236-656dc6528d68" />

------------------------------------------------------------------------------------------------------------------------------

clone the Java app source code from git repository:

git clone https://github.com/simplilearn10/SpringBootPrometheusGrafana.git

<img width="947" height="206" alt="image" src="https://github.com/user-attachments/assets/5dffc240-fbbf-4a5d-ac46-133ca22ea066" />

---------------------------------------------------------------------------------------------------------------------------------

<img width="959" height="243" alt="image" src="https://github.com/user-attachments/assets/0c386fa6-163d-445e-8c74-00c3fa439798" />

-------------------------------------------------------------------------------------------------------------------------------
<img width="969" height="340" alt="image" src="https://github.com/user-attachments/assets/99cea53f-0cfe-4fc3-987f-c538e97392e8" />

--------------------------------------------------------------------------------------------------------------------------------

Install and Configure Grafana, then start the Grafana service

<img width="939" height="375" alt="image" src="https://github.com/user-attachments/assets/a88e0720-14b3-46e3-ba19-4efc2d43def4" />

---------------------------------------------------------------------------------------------------------------------------------

Access the Grafana web interface using the host/server’s IP address:  http://3.86.85.114:3000/

<img width="887" height="681" alt="image" src="https://github.com/user-attachments/assets/bf45b79e-a9c1-4fea-a116-8f3fd7ae0aca" />

--------------------------------------------------------------------------------------------------------------------------------

Configure Grafana web interface to add prometheus as Data source

<img width="909" height="555" alt="image" src="https://github.com/user-attachments/assets/33f9b332-547d-4815-896b-22c09bc52913" />

----------------------------------------------------------------------------------------------------------------------------

<img width="883" height="427" alt="image" src="https://github.com/user-attachments/assets/85472048-956a-41a7-8d1f-21f5a5a87d12" />

-------------------------------------------------------------------------------------------------------------------------------

Create Grafana Dashboard with multi panels to Visualize Metrics

<img width="953" height="667" alt="image" src="https://github.com/user-attachments/assets/acf0a8af-5c66-4096-a707-8d2fc197f806" />

-------------------------------------------------------------------------------------------------------------------------------

<img width="914" height="614" alt="image" src="https://github.com/user-attachments/assets/ca340b96-d219-4349-8a94-640c3bac84f5" />

-------------------------------------------------------------------------------------------------------------------------------

<img width="925" height="629" alt="image" src="https://github.com/user-attachments/assets/f16c92b0-7048-4620-a63f-128bcf291bc7" />

-------------------------------------------------------------------------------------------------------------------------------

<img width="956" height="628" alt="image" src="https://github.com/user-attachments/assets/9900b8c9-8ef6-43cb-9965-1a0329c38a47" />

-------------------------------------------------------------------------------------------------------------------------------

**We have successfully set-up Prometheus for continuous monitoring of application metrics, configured a Java application to expose custom metrics to Prometheus and set-up Grafana & configured Grafana Dashboard to visualize the collected metrics & API response data.**


