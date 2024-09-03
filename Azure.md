## Thursday(22/08/2024)

## Introduction to Cloud Computing :

- ![alt text](image-48.png)
- ![alt text](image-49.png)
- Pay per use
- no maintenance and it will maintained by the cloud providers
- Autoscalling : increase/decrease the setup automattically based on requirement

## what is Cloud Computing :

- ![alt text](image-50.png)
- internet based computing
- ondemand resources delivered to your over the internet
- same resources shared by multiple clients
- Ex : Gmail , Netflix
- Set Budget :
- ![alt text](image-51.png)
- We can also go for " Pay as u go model "

## Benefits of Cloud Computing:

- ![alt text](image-52.png)
- ![alt text](image-53.png)
- ![alt text](image-54.png)

## Types of Cloud Services :

- ![alt text](image-55.png)
- Saas : we are using the buit in apps ,
- Pass :we are developing the application
- Iass : we have to take care of all the infras like installatonns , maintenance, code,

## IaaS vs PaaS vs SaaS :

- ![alt text](image-56.png)
- ![alt text](image-57.png)
- on premises : we have to take care of all the things
- Iaas : blank laptop , we have to install and code our own application, they will provide server , storage like PC
- Pass : ex : we need a python setup they will provide all , only thing is we have to develop or code our own applciation
- Saas : Every thing is readymade , we have to use only
- ![alt text](image-58.png)

## Types of Cloud Computing :

- ![alt text](image-59.png)
- ![alt text](image-60.png)
- Public Cloud : accessible to everyone , managed by 3rd party cloud providers , less control to users ,
- Private Cloud : not accessbile to general public , utilized by particular organization , strict security , control to users only.
- Hybrid Cloud : combination of public and private , expensive , complicate to maintain.
- ![alt text](image-61.png)
- ![alt text](image-62.png)
- ![alt text](image-63.png)
- ![alt text](image-64.png)
- ![alt text](image-65.png)
- ![alt text](image-66.png)
- ![alt text](image-67.png)
- ![alt text](image-68.png)

## Azure Regions :

- ![alt text](image-69.png)

## Azure Region Pairs :

- ![alt text](image-70.png)

## Availability Zones :

- ![alt text](image-71.png)
- Inside Availability Zone there are set of data centres
- set of data centres
- one data centres goes down , another data centre available all the time
- We will have a copy of data centres , azure will take care of all
- Availability Zones having independent powers
- Availability Zones should within the 100km to each one
  ![alt text](image-72.png)

## Resources :

- Instances created by us

## Resource Groups :

- ![alt text](image-73.png)
- resources are combine into resource groups
- 1 Resource having only 1 resource group
- we can switch from 1 resources to one resource group

## Subscriptions :

- User accounts , resources created by users , we will get subscription id we have to pay
- ![alt text](image-75.png)

## Management Groups :

- Organize Multiple Subscriptions as a single management entity
- Helps us to manage for multiple Subscriptions.Big companies uses it
- ![alt text](image-76.png)
- Each Management Groups[Parent] have many childs

## Azure Resource Manager[ARM] :

- ![alt text](image-74.png)
- We have template to create resources by automatically
- ARM template = JSON File[defines what do we want to deploy to Azure]
- Integrate with Azure, PowerShell, CLI , REST API Etc

## Azure Active Directory

- cloud based access management service
- ![alt text](image-77.png)
- ![alt text](image-79.png)
- Tenant : means Organization
- ![alt text](image-80.png)
- ![alt text](image-81.png)
- ![alt text](image-82.png)
- ![alt text](image-83.png)
- ![alt text](image-84.png)
- ![alt text](image-85.png)
- ![alt text](image-86.png)
- ![alt text](image-87.png)
- ![alt text](image-88.png)
- ![alt text](image-89.png)
- ![alt text](image-90.png)

## Azure Roll Based Access Control [ARBAC]

- ![alt text](image-91.png)
- ![alt text](image-92.png)
- ![alt text](image-93.png)
- ![alt text](image-94.png)
- ![alt text](image-95.png)
- ![alt text](image-96.png)

## Cost Management

- ![alt text](image-97.png)

## Azure Storage Service

- ![alt text](image-98.png)

## Azure Data Redundency :

- ![alt text](image-99.png)
- ![alt text](image-100.png)

## Blob Storage :

- ![alt text](image-101.png)
- ![alt text](image-102.png)

## Storage Access Tiers :

- ![alt text](image-103.png)
- Hot : we have to to use/access this by daily/Frequently
- Cool :once in a month , week
- Archive :Once in a year , rarely
- ![alt text](image-104.png)
- ![alt text](image-105.png)

## Azure Table Storage : Nosql Storage

- ![alt text](image-106.png)
- ![alt text](image-107.png)

## Azure File Storage : virtual , stored in storage account

- Cannot be shared acrooss data centres , only for particular data centres
- ![alt text](image-108.png)
- ![alt text](image-109.png)

## azure Disk Storage :virtual , stored in storage account

- ![alt text](image-110.png)

## Data Storage Authorization

- ![alt text](image-111.png)

## Shared Access Keys Authorization

- ![alt text](image-112.png)
- ![alt text](image-113.png)
- ![alt text](image-114.png)
- ![alt text](image-115.png)
- ![alt text](image-116.png)
- ![alt text](image-117.png)
- ![alt text](image-118.png)
- ![alt text](image-119.png)
- ![alt text](image-120.png)
- ![alt text](image-121.png)
- ![alt text](image-122.png)
- ![alt text](image-123.png)
- ![alt text](image-124.png)
- ![alt text](image-125.png)
- ![alt text](image-126.png)
- ![alt text](image-127.png)
- ![alt text](image-128.png)
- ![alt text](image-129.png)
- ![alt text](image-130.png)
- ![alt text](image-131.png)
- ![alt text](image-132.png)
- ![alt text](image-133.png)
- ![alt text](image-134.png)
- ![alt text](image.png)
- ![alt text](image-1.png)
- ![alt text](image-2.png)
- ![alt text](image-3.png)
- ![alt text](image-4.png)
- ![alt text](image-5.png)
- ![alt text](image-6.png)

## ARM

- ![alt text](image-7.png)
- ![alt text](image-8.png)
- ![alt text](image-9.png)
- ![alt text](image-10.png)

## Friday(23/08/2024)

## Azure App Service

- Enables you to build and host webapps, background jobs, mobile back ends and RESTFul API's
- ![alt text](image-11.png)
- AutoScalling
- High Avaialability : Never down
- Supports Windows and Linux only

## Types of App Service

- ![alt text](image-12.png)
- Web Apps :
- API Apps
- Web Jobs
- MObile Apps

## Azure App Service BackUp

- ![alt text](image-13.png)
- ![alt text](image-14.png)

## Deployment Settings

- ![alt text](image-15.png)
- ![alt text](image-16.png)

## App Service- Security

- ![alt text](image-17.png)

## Containers

- Wrap up an application into its own isolated package
- ![alt text](image-18.png)

## ACI[container Instance] vs AKI[Kubernet Instance]

- ![alt text](image-19.png)
- ![alt text](image-20.png)
- ![alt text](image-21.png)

## Virtual Machine vs COntainer

- ![alt text](image-22.png)
- spin up : refresh the system

## Docker & Azure Container Registry

- ![alt text](image-23.png)

## Docker

- ![alt text](image-24.png)
- ![alt text](image-25.png)
- ![alt text](image-26.png)
- ![alt text](image-27.png)
- ![alt text](image-28.png)
- ![alt text](image-29.png)
- ![alt text](image-30.png)

## Kubernetes

- ![alt text](image-31.png)
- ![alt text](image-32.png)
- ![alt text](image-33.png)
- ![alt text](image-34.png)
- ![alt text](image-35.png)

## Kubernetes architecure

- ![alt text](image-36.png)
- ![alt text](image-37.png)
- ![alt text](image-39.png)

## Azure Kubernetes Services

- ![alt text](image-40.png)
- ![alt text](image-41.png)
- ![alt text](image-42.png)
- ![alt text](image-43.png)
- Deployment : one or more identical pods
- ![alt text](image-44.png)
- ![alt text](image-45.png)
- ![alt text](image-46.png)

## Azure Networking Services

- ![alt text](image-47.png)
- ![alt text](image-136.png)
- ![alt text](image-137.png)
- ![alt text](image-138.png)
- ![alt text](image-139.png)

## Public Vs Private IP Address

- ![alt text](image-140.png)
- ![alt text](image-141.png)

## Virtual net[Vnet]

- ![alt text](image-142.png)
- ![alt text](image-143.png)
- ![alt text](image-144.png)
- ![alt text](image-145.png)
- ![alt text](image-146.png)
- ## Subnet masking
- ![alt text](image-147.png)
- ![alt text](image-148.png)
- ![alt text](image-149.png)

## NIC Network Interface card : generated automatically whenever a vn is created

- ![alt text](image-150.png)

## User Defined Route [UDR]

- ![alt text](image-151.png)
- ![alt text](image-152.png)

## Network peering

- ![alt text](image-153.png)
- ![alt text](image-154.png)

## Virtual Private Network[VPN]

- ![alt text](image-155.png)
- ![alt text](image-156.png)
- ![alt text](image-157.png)

## Service Chaining

- ![alt text](image-158.png)
- ![alt text](image-159.png)
- ![alt text](image-160.png)

## Domain Name System

- ![alt text](image-161.png)
- ![alt text](image-162.png)

## Azure DNS

- ![alt text](image-163.png)
- ![alt text](image-164.png)
- ![alt text](image-165.png)
- ![alt text](image-166.png)
- ![alt text](image-167.png)
- ![alt text](image-168.png)
- ![alt text](image-169.png)
- ![alt text](image-170.png)
- ![alt text](image-171.png)
- ![alt text](image-172.png)
- ![alt text](image-173.png)
- ![alt text](image-174.png)
- ![alt text](image-175.png)
- ![alt text](image-176.png)
- ![alt text](image-177.png)
- ![alt text](image-178.png)
- ![alt text](image-179.png)

## Azure Load Balancer

- ![alt text](image-180.png)
- ![alt text](image-181.png)
- ![alt text](image-182.png)
- ![alt text](image-183.png)
- ![alt text](image-184.png)
- ![alt text](image-185.png)

## Load Balancer

- ![alt text](image-186.png)

## Application GateWay

- ![alt text](image-187.png)

## URL path based routing

- ![alt text](image-188.png)

## Multi site Routing

- ![alt text](image-189.png)
  ##V web application FireWall[WAF]
- ![alt text](image-190.png)

## Application Gateway Components

- ![alt text](image-191.png)

## Virutual WAN

![alt text](image-192.png)

## Express Route

- ![alt text](image-193.png)
- ![alt text](image-194.png)
- ![alt text](image-195.png)
- ![alt text](image-196.png)
- ![alt text](image-197.png)
- ![alt text](image-198.png)
- ![alt text](image-199.png)
- ![alt text](image-200.png)
- ![alt text](image-201.png)

## Azure Monitor

- ![alt text](image-202.png)
- ![alt text](image-203.png)
- ![alt text](image-204.png)

## Powershell cli commands

- ![alt text](image-205.png)

## Wednesday(28/08/2024)

## Azure Training

## Cloud Computing : take features from onpremises[server] to cloud[serverless]

- physically we can see a server
- ![alt text](image-206.png)
- Pay as you go[Costing]
- server less computing[cloud]
- infinite storage

## Shared Responsibilty Module :

- avaialability zone , resource group , services of azure etc.
- Avaialabilty zone : avaialability high , region can contains multiple avaialability zones/one AZ
- Resource Group :

## SAAS

- ![alt text](image-207.png)
- ![alt text](image-214.png)
- Scalability : Use as you go
- Accessibility : How much we access
- Auto Scaling group : automatically increse/decrease based on requirement
- Cost-effectiveness :
- Active Directory :user credentiALS ARE STORED her

## IAAS

- ![alt text](image-208.png)

## PAAS

- ![alt text](image-209.png)
- Develpement -->Testing[SIT, UAT,Integration Testing] --->Production[pre, production]
- Hybrid Cloud
- Both features of IAAS and SAAS
  ![alt text](image-210.png)
- ![alt text](image-211.png)
- Abstraction : data Hiding
- ![alt text](image-212.png)
- Paramters : for compute
- No of users
- turn around time
- Space /storage
- ![alt text](image-213.png)

## Azure

- ![alt text](image-215.png)
- cloud platform

## Azure Services

- ![alt text](image-216.png)
- 1. Computation :trying to execute on server less machine
- 2. Storage : files , queues , tables and disks
- Container : place to store
- Virtual machine : is on cloud , to host application , server less machine
- ![alt text](image-217.png)
- 3. Networking
- 4. Security
- 1. Azure Computation
- ![alt text](image-218.png)
- virtual machine
- container
- Severless computing
- 2. Azure Storage
- ![alt text](image-219.png)
- 3. Networking
- ![alt text](image-220.png)

## Thursday(29/08/2024)

- 4. Azure Security : stores passwords , important data
- ![alt text](image-221.png)
- Identity management : gives access to users , and provides services after verifying user credentials , having 2 methods
- Azure Active Directory for authentication[ checking user credentials] and authorization[giving access]
- Data Encryption
- Threat Protecion
- 5. Azure Monitoring : monitors the billing , costs of users , sends alerts to users through sms, mails regarding how much we have used on azure
- ![alt text](image-222.png)

## Web Jobs: Background tasks that are run in azure

- ![alt text](image-223.png)
- Background tasks that are run in azure
- Run by processor manager
- It automates the various tasks like processing , sending mails , monotoring our applications
- Azure monitoring beacause of webjibs

## Benefits of Webjobs

- ![alt text](image-224.png)

## Types of Webjobs

- ![alt text](image-225.png)
- 1. continuous wejobs : It runs continuously as long as they are active , ideal for longtime-running tasks like monitoring and data processing.
- 2. Triggered webjobs : Activated for specific tasks/events such as new files in a storage acount or messages in a queue
- 3. Scheduled webjobs : Executed according to a defined schedule , such a daily , weekly , or monthly for tasks requiring regular execution

## Deploying Webjobs

- ![alt text](image-226.png)

## Monotoring and Debugging Webjobs

- ![alt text](image-227.png)
- ![alt text](image-228.png)

## Introduction to Container and Docker

### Container

- ![alt text](image-229.png)
- lightweight , package it includes everything needed to run on an application

## Benefits of Containerization

- ![alt text](image-230.png)
- Docker :
- ![alt text](image-231.png)
- ![alt text](image-232.png)

## Docker Architecuture

- ![alt text](image-233.png)
- Docker Clients : commands
- Docker Daemon : Server/host machine
- Docker Image : Instructions to create a contaner
- Registry : stores images
- Design a docker image for any aplication deployment

## Azure Resource manager : Is in json format

## Docker Images

- ![alt text](image-234.png)
- ![alt text](image-235.png)
- ![alt text](image-236.png)
- Cosmos DB : Azure self developed Data base

## Friday(30/08/2024)

## Rivison on Previous Topics :

- Resouce Group : A resource group is a container that holds related resources for an Azure solution. The resource group can include all the resources for the solution, or only those resources that you want to manage as a group.
- stores metadata about the resources.
- Virtual Machine : Service

### Devops : Done Manually

- Developement Operations
- It having branches
- Repository : place where all codes are available
- Source Code Management : tool to maintain codes
- main branch : Production Environment
- Ops : Production
- ITSM : Information technology service management
- 3 parts :Source code management, Staging , Deplyoment -->Deployment Life cycle /PipeLine
- Continuous Integration :
- Continuous Developement:

## ARM :

- Azure Resource Manager (ARM) is a Microsoft Azure service that helps users manage and deploy resources for their Azure account
- ARM uses resource providers to create, update, delete, or retrieve resources in an Azure environment.
- ARM template :
- A JavaScript Object Notation (JSON) file that defines one or more resources to deploy to a resource group, subscription etc...
- 1 Project have 1 ARM , ARM creates Automatically

## Container :

- contains zip , files , codes , all
- Container Engine :Docker
- CICD : automtatically dones the tasks like releases, tags , versions etc..
- Vm - can create os, files
- azure will deploy the container

## Resource vs Services :

- A service is a set of features in Azure
- A resource is the product or object of a service.
- ![alt text](image-237.png)

## Choosing Azure Regions

- ![alt text](image-238.png)
- Latency : when any user requesting a service , it will takes time to respond i.e "Latency"[Delay]
- Data Sovereignty : mainatenace of data
- Pricing : Cost
- Avaialability Zones : utilizing zones for resources by deploying our application across physically seperated data centre[Backup] within a region
- ![alt text](image-239.png)
- Disaster Recover[DR]
- Azure Content Delivary Networ[CDN]
- Resource manAGER - RESOURCES\_\_>ALL

## Microservices :

- ![alt text](image-240.png)
- Independent Deployment : releasing versions one after another
- Technology Diversity : Different services can use different technologies , allowing teams to choose the best tool for the job.
- Improved scalability : based on demand it allows scaling
- Resilience and Fault Tolerance : Failures in one service are less likely to impact other services , improving application resilience
- ![alt text](image-241.png)
- Consistency : maintaining same data by not decreasing
- Increased Complexity :
- Distributed Complexity:

## Microservices Architecture

- ![alt text](image-242.png)
- ![alt text](image-243.png)

## Git

- Git is an open-source distributed version control in DevOps
- ![alt text](image-244.png)

## Question 1 : C&D

The development teams that support the Agile approach to DevOps must include staff from the operations teams to ensure:

- A) That stability is prioritised over creativity
- B) Operational considerations are prioritised over stability
- C) Operational considerations are taken into account
- D) The resultant designs of the systems will fit nicely into the business as usual environment

## Question 2 : C

Which statement best describes the relationship between DevOps and Continuous Delivery?

- A) DevOps and Continuous Delivery are the same thing.
- B) DevOps and Continuous Delivery are not related and are mutually exclusive.
- C) DevOps and Continuous Delivery share a background in Agile methods and LEAN thinking.
- D) DevOps and Continuous Delivery share common processes.

## Monday (02/09/2024)

## Microservices Solid Principles :

- ![alt text](image-245.png)
- Single Responsibility : Each module or a class should have a one and only one reason to change
- Open/Closed :Instead of modifying resources we can change services
- Liskov Substitution: pay as you go like procedure, This means that objects of the child class should be able to substitute objects of the parent class without causing any issues or breaking the application's integrity.
- Ex : ![alt text](image-246.png)
- Interface Segregation :Azure uses logical isolation to segregate each customer’s data from the data of others. Segregation provides the scale and economic benefits of multi-tenant services while rigorously preventing customers from accessing one another’s data.
- Dependency Inversion/injection : Technique to achieve Inversion of Control (IoC) between classes and their dependencies. Dependency injection in Azure Functions is built on the.NET Core Dependency Injection features.
- Ex : ![alt text](image-247.png)

## Monolithic Application vs MicroService :

- ![alt text](image-248.png)

## Tuesday(03/09/2024)

- ![alt text](image-249.png)
- ![alt text](image-250.png)
- Branch Policy :who can access to which branch .

## Kubernetes :

- ![alt text](image-251.png)
- ![alt text](image-252.png)
- Pods : container
- Cluster : summation of Pods

## Architecture :

- ![alt text](image-253.png)
- Master Node : It manages all the slave nodes
- Slave Node : Contains Pods[is equals to container]
- Cluster made up of : Master node + Many Slave nodes
- ![alt text](image-254.png)
- Etcd : used to store the configuration ans state of the cluster
- Kubelet[Processor] :runs on each slave node and manage the pods running on that node
- ![alt text](image-255.png)
- kube-apiserver: The core component server that exposes the Kubernetes HTTP API
- etcd : Consistent and highly-available key value store for all API server data
- kube-scheduler : Looks for Pods not yet bound to a node, and assigns each Pod to a suitable node.
- kube-controller-manager
  Runs controllers to implement Kubernetes API behavior.
- cloud-controller-manager (optional)
  Integrates with underlying cloud provider(s).
- Kubernetes Pods : ![alt text](image-256.png)

## cloud Shell commands

- 1.To create Aplication NAme : az group create --name myapp-rg --location eastus
- 2. To create Resource group :
- az acr create --resource-group myapp-rg --name mycontainerregistry --sku Basic
- az aks create\
- ![alt text](image-257.png)

## physical devices that connect to and exchange information with a computer network

- Kubernetes Deployment :
- ![alt text](image-258.png)
- Kubernetes Services :
- ![alt text](image-259.png)

## Network Policy

- ![alt text](image-260.png)
