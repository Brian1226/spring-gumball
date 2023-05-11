# Lab #10 Notes - DevOps CI/CD

## CI Workflow (Part 1)
Created gradle.yml </br>
[![Screen-Shot-2023-05-10-at-4-08-12-PM.png](https://i.postimg.cc/Mp8d5zd5/Screen-Shot-2023-05-10-at-4-08-12-PM.png)](https://postimg.cc/crXR4Gqt)

Using the Gradle starter workflow (successful build) </br>
[![Screen-Shot-2023-05-10-at-4-08-48-PM.png](https://i.postimg.cc/jqpXqs0T/Screen-Shot-2023-05-10-at-4-08-48-PM.png)](https://postimg.cc/xqPHtV1p)

[![Screen-Shot-2023-05-10-at-4-09-08-PM.png](https://i.postimg.cc/BnsBDMnw/Screen-Shot-2023-05-10-at-4-09-08-PM.png)](https://postimg.cc/QH47Zg5p)

[![Screen-Shot-2023-05-10-at-4-09-42-PM.png](https://i.postimg.cc/s2gPHxSY/Screen-Shot-2023-05-10-at-4-09-42-PM.png)](https://postimg.cc/RW2nNMgh)

## CD Workflow (Part 2)
Created google.yml </br>
[![Screen-Shot-2023-05-10-at-4-29-32-PM.png](https://i.postimg.cc/Y9J1SxPR/Screen-Shot-2023-05-10-at-4-29-32-PM.png)](https://postimg.cc/gXHwS3mL)

Successfully created GKE Cluster </br>
[![Screen-Shot-2023-05-10-at-6-08-10-PM.png](https://i.postimg.cc/501m5ggt/Screen-Shot-2023-05-10-at-6-08-10-PM.png)](https://postimg.cc/LqCf2zrd)

Enabled the Kubernetes Engine and Container Registry APIs </br>
[![Screen-Shot-2023-05-10-at-6-11-59-PM.png](https://i.postimg.cc/Qdh5yC56/Screen-Shot-2023-05-10-at-6-11-59-PM.png)](https://postimg.cc/1f7fg9v6)

Getting Project ID </br>
[![Screen-Shot-2023-05-10-at-6-14-32-PM.png](https://i.postimg.cc/kXb6mXZd/Screen-Shot-2023-05-10-at-6-14-32-PM.png)](https://postimg.cc/VdzL91m7)

Successfully created Service Accounts </br>
[![Screen-Shot-2023-05-10-at-9-16-37-PM.png](https://i.postimg.cc/Y0fSvhw4/Screen-Shot-2023-05-10-at-9-16-37-PM.png)](https://postimg.cc/YL07V20k)

IAM showing specified permissions </br>
[![Screen-Shot-2023-05-10-at-9-16-45-PM.png](https://i.postimg.cc/prZ224Dz/Screen-Shot-2023-05-10-at-9-16-45-PM.png)](https://postimg.cc/8f784yXz)

Successfully got JSON Key </br>
[![Screen-Shot-2023-05-10-at-9-19-30-PM.png](https://i.postimg.cc/8543sS0p/Screen-Shot-2023-05-10-at-9-19-30-PM.png)](https://postimg.cc/zbLpP9N6)

The content of the service account JSON file </br>
[![Screen-Shot-2023-05-10-at-9-27-37-PM.png](https://i.postimg.cc/mkqmF2Ns/Screen-Shot-2023-05-10-at-9-27-37-PM.png)](https://postimg.cc/K3PP6bHq)

Successfully Configured Github Secrets </br>
[![Screen-Shot-2023-05-10-at-9-26-41-PM.png](https://i.postimg.cc/pXbGxyTf/Screen-Shot-2023-05-10-at-9-26-41-PM.png)](https://postimg.cc/K4frDGtj)

Trigger a CD Deployment by successfully creating a new GitHub Release </br>
[![Screen-Shot-2023-05-10-at-9-43-12-PM.png](https://i.postimg.cc/LsGffCnr/Screen-Shot-2023-05-10-at-9-43-12-PM.png)](https://postimg.cc/Tyqpvcj9)

Bulding and Deploying to GKE </br>
[![Screen-Shot-2023-05-10-at-9-44-18-PM.png](https://i.postimg.cc/3x4xpKmx/Screen-Shot-2023-05-10-at-9-44-18-PM.png)](https://postimg.cc/18SS11vk)

Successful workflow of the Release </br>
[![Screen-Shot-2023-05-10-at-9-53-53-PM.png](https://i.postimg.cc/V6NTrN07/Screen-Shot-2023-05-10-at-9-53-53-PM.png)](https://postimg.cc/wtSFngVJ)

All workflow are successful </br>
[![Screen-Shot-2023-05-10-at-9-54-22-PM.png](https://i.postimg.cc/284DfVQv/Screen-Shot-2023-05-10-at-9-54-22-PM.png)](https://postimg.cc/F7sqyFns)

Workloads (deployment successful) </br>
[![Screen-Shot-2023-05-10-at-9-55-24-PM.png](https://i.postimg.cc/rs1Y7RBw/Screen-Shot-2023-05-10-at-9-55-24-PM.png)](https://postimg.cc/GTpQyt3W)

Services & Ingress (service successful) </br>
[![Screen-Shot-2023-05-10-at-10-04-12-PM.png](https://i.postimg.cc/v8thFy1T/Screen-Shot-2023-05-10-at-10-04-12-PM.png)](https://postimg.cc/BttHHdBf)

Creating a Kubernetes Ingress </br>
[![Screen-Shot-2023-05-10-at-10-12-51-PM.png](https://i.postimg.cc/hjCzS2VJ/Screen-Shot-2023-05-10-at-10-12-51-PM.png)](https://postimg.cc/FdLspgWm)

Services & Ingress (successful load balancer) </br>
[![Screen-Shot-2023-05-10-at-10-20-25-PM.png](https://i.postimg.cc/bNnxTjQ3/Screen-Shot-2023-05-10-at-10-20-25-PM.png)](https://postimg.cc/kBnRJzYb)

Gumball Spring App Web UI successfully come up on Load Balancer's External IP </br>
[![Screen-Shot-2023-05-10-at-10-21-26-PM.png](https://i.postimg.cc/JzcF4Fz4/Screen-Shot-2023-05-10-at-10-21-26-PM.png)](https://postimg.cc/Yv0RdbFJ)
