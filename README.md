# Azure-Real-Time-Data-Stream-IoT-Project

In this lab, we Real-Time Sonar Sensor Data Streaming from Raspberry Pi to Azure

# Prerequisites
We first create IoT Hub and IoT Hub Device in Azure. 

## Creating an IoT Hub:

* Go to [Microsoft Azure official website](https://portal.azure.com/) and sign in/ sign up to your Azure account.
* Once logged in, type "IoT Hub" in the search bar and select it from the search results.

![Screenshot 2024-04-25 013218](https://github.com/mehrab-abrar/Azure-Real-Time-Data-Stream-IoT-Project/assets/42034831/28d083c9-915b-49e3-84fa-d943476adff5) <br>
<br>

![Screenshot 2024-04-25 013301](https://github.com/mehrab-abrar/Azure-Real-Time-Data-Stream-IoT-Project/assets/42034831/b93e7ce8-8c40-4761-a320-846a6f83b254)

* Click on "Create" to create an IoT hub.
  - Choose your Azure subscription (Free trial/ Azure subscription 1).
  - Create a new resource group or select an existing one.
  - IoT Hub Name: Enter a unique name for your IoT Hub.
  - Choose the region where you want your IoT Hub to be located.
  - Select the desired tier and Daily message limit based on your requirements (You can select Free)
 
![Screenshot 2024-04-25 015003](https://github.com/mehrab-abrar/Azure-Real-Time-Data-Stream-IoT-Project/assets/42034831/cce388d1-99d3-4351-ba0e-e2f5233ff872)

* Click on the "Next: Networking>" button.

![Screenshot 2024-04-25 020016](https://github.com/mehrab-abrar/Azure-Real-Time-Data-Stream-IoT-Project/assets/42034831/9fa6d060-f8a9-4871-bf26-f941fa00768e)

* Configure the size and scale settings according to your needs. You can choose the number of partitions, units, and other options. Once done, click on the "Review + create" button.
![Screenshot 2024-04-25 020052](https://github.com/mehrab-abrar/Azure-Real-Time-Data-Stream-IoT-Project/assets/42034831/f66c2c1e-c327-45e2-9d13-d3aaada85897)

* It may take a few minutes for the deployment to complete. Once complete, you will receive a notification of deployment completion. You can then navigate to your IoT Hub from the Azure portal dashboard or by searching for its name.


## Creating an IoT Hub Device:

Navigate to IoT Devices:
In the Azure portal, go to your newly created IoT Hub. You can find it by searching for its name or navigating through the resource groups.
