# GCP_lab-2

## ScreenShots :
-----------------------------------------------------------------
## Lab 2.1 :

1. From Cloud console, create a VPC named “auto-vpc” with auto-mode enabled,
How many subnets created?
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/1.1.0.png)
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/1.1.1.png)
-----------------------------------------------------------------
2. From Cloud console, create a VPC named “custom-vpc” with auto-mode disabled and create two subnets.
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/1.2.0.png)
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/1.2.1.png)
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/1.2.2.png)
-----------------------------------------------------------------
3. Using gcloud tool list all available VPCs and list subnets of each VPC.
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/1.3.0.png)
-----------------------------------------------------------------
4. Block internet access from you VPC using firewall rules.
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/1.4.0.png)
-----------------------------------------------------------------
5. Create a firewall rule to allow incoming SSH requests from internet to all instances in your vpc.
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/1.5.0.png)
-----------------------------------------------------------------
6. Modify the previous firewall rule to allow only ssh requests coming through Google’s IAP servers
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/1.6.0.png)
-----------------------------------------------------------------



## Lab 2.1 :

1. Create a VM with public ip then:
– In two different ways, SSH into this VM.
– Enforce SSH into this VM to be IAP protected
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/2.1.0.png)
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/2.1.1.png)
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/2.1.2.png)
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/2.1.3.png)
-----------------------------------------------------------------
2. Create a VM without public ip then:
– SSH into this vm.
– update system packages (is it possible?) >> will not be possible because vm don't have public ip to connect internte
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/2.2.0.png)
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/2.2.1.png)
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/2.2.2.png)
-----------------------------------------------------------------
3. Create a VM with public ip then:
– SSH into this vm 
– Update system packages.
– Setup Nginx Web Server and test your setup.
– Create a custom image from this VM named “custom-img-nginx”
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/2.3.0.png)
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/2.3.1.png)
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/2.3.2.png)
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/2.3.3.png)
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/2.3.4.png)
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/2.3.5.png)
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/2.3.6.png)
-----------------------------------------------------------------
4. Create MIG (min 3 and max 5) of a template using the custom image “custom-img-nginx”
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/2.4.0.png)
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/2.4.1.png)
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/2.4.2.png)
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/2.4.3.png)
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/2.4.4.png)
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/2.4.5.png)
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/2.4.6.png)
![agent](https://github.com/Badawi02/GCP/blob/lab-2/images/2.4.7.png)

