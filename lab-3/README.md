# GCP_lab-3

## ScreenShots :
-----------------------------------------------------------------
## Lab 3.1 :

## 1. In previous lab you created the VPC “auto-vpc”, How many routes created for this VPC? Can you delete any of these routes?
    - answer : we have number of subnet+1 . no, we can not delete any one of them because it is managing by GCP
![agent](https://github.com/Badawi02/GCP/blob/main/lab-3/images/3.1.1.0.png)
-----------------------------------------------------------------
-----------------------------------------------------------------
## 2. In previous lab you created a VPC named “custom-vpc” How many routes created for this VPC?
    - answer : number of subnet + 1 
![agent](https://github.com/Badawi02/GCP/blob/main/lab-3/images/3.1.2.0.png)
-----------------------------------------------------------------
-----------------------------------------------------------------
## 3. How would you block internet access from you vpc using routes?
    - answer : by deleteing the route contain internet getway
![agent](https://github.com/Badawi02/GCP/blob/main/lab-3/images/3.1.3.0.png)
-----------------------------------------------------------------
-----------------------------------------------------------------
## 4. Add a NAT gateway on any of the subnets in your VPC.
![agent](https://github.com/Badawi02/GCP/blob/main/lab-3/images/3.1.4.0.png)

-----------------------------------------------------------------
-----------------------------------------------------------------

## Lab 3.2 :

## 1. In previous lab you created an MIG of a template using the custom image “custom-img-nginx”,
- Create a Global (or Regional) HTTP Load balancer to access your MIGs Nginx setup.
![agent](https://github.com/Badawi02/GCP/blob/main/lab-3/images/3.2.1.0.png)
![agent](https://github.com/Badawi02/GCP/blob/main/lab-3/images/3.2.1.1.png)
![agent](https://github.com/Badawi02/GCP/blob/main/lab-3/images/3.2.1.2.png)
![agent](https://github.com/Badawi02/GCP/blob/main/lab-3/images/3.2.1.3.png)

-----------------------------------------------------------------
-----------------------------------------------------------------


## Lab 3.3 :

## 1.Create a private standard GKE cluster.
![agent](https://github.com/Badawi02/GCP/blob/main/lab-3/images/3.3.1.0.png)
![agent](https://github.com/Badawi02/GCP/blob/main/lab-3/images/3.3.1.1.png)
![agent](https://github.com/Badawi02/GCP/blob/main/lab-3/images/3.3.1.2.png)
![agent](https://github.com/Badawi02/GCP/blob/main/lab-3/images/3.3.1.3.png)
![agent](https://github.com/Badawi02/GCP/blob/main/lab-3/images/3.3.1.4.png)
-----------------------------------------------------------------
-----------------------------------------------------------------
## 2.Deploy Nginx as a deployment using latest Nginx docker image on Docker Hub.
![agent](https://github.com/Badawi02/GCP/blob/main/lab-3/images/3.3.2.0.png)
-----------------------------------------------------------------
-----------------------------------------------------------------
## 3.Expose your Nginx deployment using Kubernetes LoadBalancer Service.
![agent](https://github.com/Badawi02/GCP/blob/main/lab-3/images/3.3.3.0.png)
-----------------------------------------------------------------
-----------------------------------------------------------------
## 4.What is the type of GCP Load Balancer that is created for your LB service?
![agent](https://github.com/Badawi02/GCP/blob/main/lab-3/images/3.3.4.0.png)
-----------------------------------------------------------------
-----------------------------------------------------------------
## 5.Use kubectl to view container logs.
![agent](https://github.com/Badawi02/GCP/blob/main/lab-3/images/3.3.5.0.png)
-----------------------------------------------------------------
-----------------------------------------------------------------
## 8.Create an autopilot GKE cluster with public control plane.
![agent](https://github.com/Badawi02/GCP/blob/main/lab-3/images/3.3.8.0.png)
-----------------------------------------------------------------
-----------------------------------------------------------------
## 9.Enforce the cluster’s control plane to accept only connections from your local machine.
![agent](https://github.com/Badawi02/GCP/blob/main/lab-3/images/3.3.9.0.png)
![agent](https://github.com/Badawi02/GCP/blob/main/lab-3/images/3.3.9.1.png)