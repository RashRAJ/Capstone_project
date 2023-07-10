## Architectural Diagram for the Capstone project ##
<img width="1030" alt=" Capstone Diagram" src="https://github.com/RashRAJ/Capstone_project/assets/108562214/eed0b340-c2bd-49cc-a77e-d074ed85809e">

## Breakdown of the Capstone_project ##

This project aims to deploy a highly sophisticated car rental platform using Kubernetes as the orchestration framework. The platform will adopt a decoupled architecture, with Node.js serving as the backend technology and React as the frontend. Kubernetes will enable the application to achieve exceptional scalability, maintainability, and resilience.

Users of the platform will benefit from a comprehensive range of features, including the ability to browse, add, and remove cars from the rental inventory, schedule, and book test drives, as well as manage their existing bookings seamlessly. 

## Project Overview 

To accomplish this, the project will heavily rely on Amazon Web Services (AWS) as the primary service provider, making use of various pertinent services and cutting-edge technologies offered by AWS. This selection allows for optimal utilization of resources and cost-efficiency, ensuring a streamlined and reliable deployment.

Overall, this project aims to deliver a technologically advanced car rental platform that harnesses Kubernetes's power, leverages AWS services' benefits, implements industry-standard practices, and prioritizes security. By doing so, it will provide an optimized, scalable, and user-friendly solution for the car rental industry.


## Implementation Process

### Stage 1
Set up the EKS infrastructure using infrastructure as code (Terraform)

### Stage 2
Containerize the car rental application services frontend and backend using Docker, create Docker images, push images to GCHR, and deploy them onto the Kubernetes cluster. 

### Stage 3
Configure Argo CD to automate the build, test, and deployment processes. Set up continuous integration to build and test the application codebase on each commit. Enable continuous deployment to automatically deploy new features or bug fixes to staging and production environments.

### Stage 4
Set up Prometheus as the monitoring tool to collect metrics from the application and Kubernetes cluster. Integrate Grafana for visualizing and analyzing the collected metrics. Configure alerting rules to notify the team about critical issues or anomalies. Set up signoz to collect logs, configure the uptime dashboard, and Slack alerting.

### Stage 5
Deloy Kubecost to the cluster, apply cost reduction recommendations. 

### Stage 6
Conduct knowledge transfer sessions with the operations and maintenance team to ensure a smooth handover and ongoing support.


## Installed Apps
### Argo CD 
argocd.octoarts.me

 <img width="1306" alt="Screenshot 2023-07-09 at 22 54 21" src="https://github.com/RashRAJ/Capstone_project/assets/56790407/a3ab74ff-e7ba-4087-ac99-296492b6e9c7">

### Kubecost

<img width="1306" alt="Screenshot 2023-07-09 at 22 55 44" src="https://github.com/RashRAJ/Capstone_project/assets/56790407/dbe8ac36-e319-4da7-8a55-72812d76ce9c">

### Grafana
grafana.octoarts.me

<img width="1306" alt="Screenshot 2023-07-09 at 22 57 05" src="https://github.com/RashRAJ/Capstone_project/assets/56790407/e39ff71b-02b2-452b-ad0a-919fe33729ca">

### Car-rental app
reantal.octoarts.me

<img width="1306" alt="Screenshot 2023-07-09 at 23 03 03" src="https://github.com/RashRAJ/Capstone_project/assets/56790407/98f67e89-51e8-4175-883b-ea2661eae696">

### Prometheus
prometheus.octoarts.me

<img width="1552" alt="Screenshot 2023-07-09 at 23 36 39" src="https://github.com/RashRAJ/Capstone_project/assets/56790407/8329e517-9180-4a59-ba5e-48ee0292f7d2">


