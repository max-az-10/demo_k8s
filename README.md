Deploying the Swiggy clone app with Terraform, Kubernetes, and Jenkins CICD.

Test200

DevOps Pipeline Architecture Diagram (Concept)
[GitHub Repository]
         |
         v  (Webhook trigger)
    [Jenkins EC2 Instance]
    |  - Pipeline
    |  - SonarQube Scanner
    |  - Docker Build & Push
    |
    v
 [Docker Hub]  <-- Docker images
    |
    v
 [AWS EKS Cluster]
    |  - 3 Worker Nodes
    |  - Kubernetes Deployment
    |  - Service (LoadBalancer)
    v
 [Live Application in Browser]

Legend / Notes:

CI/CD Flow: GitHub → Jenkins → EKS
Containerization: Jenkins builds Docker images → Docker Hub
Code Quality: SonarQube integrated in Jenkins
Deployment: EKS runs Docker images as pods, exposed via LoadBalancer


# demo_k8s
