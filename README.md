# Azure-Real-Time-Data-Stream-IoT-Project

In this lab, we Real-Time Sonar Sensor Data Streaming from Raspberry Pi to Azure

# Prerequisites
We first create IoT Hub and IoT Hub Device in Azure. 

## Creating an IoT Hub:

* Go to [Microsoft Azure official website](https://portal.azure.com/) and sign in/ sign up to your Azure account.
* Once logged in, type "IoT Hub" in the search bar and select it from the search results.
* 
* ![Screenshot 2024-04-25 013218](https://github.com/mehrab-abrar/Azure-Real-Time-Data-Stream-IoT-Project/assets/42034831/28d083c9-915b-49e3-84fa-d943476adff5)>br
* >br
* ![Screenshot 2024-04-25 013301](https://github.com/mehrab-abrar/Azure-Real-Time-Data-Stream-IoT-Project/assets/42034831/b93e7ce8-8c40-4761-a320-846a6f83b254)



Configure IoT Hub:


In the "Basics" tab, provide the following information:
Subscription: Choose your Azure subscription.
Resource Group: Create a new resource group or select an existing one.
Region: Choose the region where you want your IoT Hub to be located.
IoT Hub Name: Enter a unique name for your IoT Hub.
Pricing and Scale Tier: Select the desired tier based on your requirements.
Click on the "Next: Size and scale" button.
Size and Scale:
Configure the size and scale settings according to your needs. You can choose the number of partitions, units, and other options. Once done, click on the "Review + create" button.
Review and Create:
Review the configuration details of your IoT Hub. If everything looks good, click on the "Create" button to create your IoT Hub. It may take a few minutes for the deployment to complete.
Deployment Complete:
Once the deployment is complete, you will receive a notification. You can then navigate to your IoT Hub from the Azure portal dashboard or by searching for its name.
