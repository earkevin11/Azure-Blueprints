# Azure-Blueprints

# What are Azure Blueprints?
- Blueprints give admins the ability to orchestrate the deployment of artifacts to Azure


# How to use Blueprints?
- Blueprints will be used to automate using IaaS to deploy resources 
- First admins must define a blueprint and then assign it to a management group or a subscription
- Only can be assigned to management group or a subscription. NOT A resource group


# Stages of Azure Blueprint
- Define Blueprint -> Publish Blueprint -> Assign the Blueprint

# Blueprints Artifacts
- 1. Role Assignments - if you need specific roles to be assigned
- 2. Policy assignments - if you need specific policies to be applied
- 3. Resource groups - if you need certain resource groups to be in place
- 4. ARM templates - if there are resources that need to be deployed

# Working with Azure Blueprints
- Define the Blueprint, create some artifacts, publish the blueprint, and then assign the blueprint at a management group level to one subscription.


# Define a Blueprint and link it to the scope of the Azure subscription

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/175796294-29bab869-ebca-4c73-af76-c6d2f7321b88.png" height="75%" width="75%" alt="Azure LAW"/>

<p/>

# Create a an artifact within the Blueprint - Role Assignment
<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/175796391-11eed999-3c21-467e-8d1b-feff51e0b8c5.png" height="165%" width="165%" alt="Azure LAW"/>

<p/>


# Publish the Blueprint
<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/175796430-d7a7af13-438c-4ddf-8280-60194596d7b9.png" height="165%" width="165%" alt="Azure LAW"/>

<p/>
- Artifact - Role Assignment
- Artifact - Resource group


# Assign the Blueprint
- This will ensure that resources within Azure subscription 1 has
- 1. Contributor role - appuserA
- 2. resourcegroupA in the subscription

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/175796611-85b4d60f-89ee-475d-afbe-e877423d3a8e.png" height="75%" width="75%" alt="Azure LAW"/>

<p/>

# Check to see if the Blueprints created resourcegrpA
<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/175796804-26f62f65-08c8-4151-ac23-63c1c48b64b4.png" height="75%" width="75%" alt="Azure LAW"/>

<p/>


# Check to see if then Blueprints created appuserA 
<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/175796847-7643fd0a-0f40-4b2f-8201-26a9ce9c9c55.png" height="75%" width="75%" alt="Azure LAW"/>

<p/>
