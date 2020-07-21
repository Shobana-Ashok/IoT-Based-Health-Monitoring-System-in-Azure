# IOT Based Smart Health Monitoring and Notifications with Azure Logic Apps

### Summary
The purpose of this project is to monitor vital signs such as heart-rate and temperature. The system automatically send alerts to the healthcare if there is any abnormality in the telemetry value. The IoT device is simulated using the Python code, which generates the Heartrate and Temperatute. The values are sent to the Azure IoT Hub. Using Stream Analytics Job the data from the Iot Hub is sent to the PowerBI to generate meaningful insights (Visualization). The notification is send using Azure Logic Apps by connecting IoT hub and mailbox. 

### Requirements
* Simulated Device - Python Code
* Microsoft Azure Subscription
* Iot Hub
* Stream Analytics Job
* PowerBI
* Azure Logic Apps
### Simulated Device Sending Telemetry Values
![alt text](https://github.com/Shobana-Ashok/IoT-Based-Health-Monitoring-System-in-Azure/blob/master/Screenshot%20(1660).png?raw=true)
### IoT-Hub Events Monitor
![alt text](https://github.com/Shobana-Ashok/IoT-Based-Health-Monitoring-System-in-Azure/blob/master/Screenshot%20(1662).png?raw=true)
### Generated Report in PowerBI
![alt text](https://github.com/Shobana-Ashok/IoT-Based-Health-Monitoring-System-in-Azure/blob/master/Screenshot%20(1659).png?raw=true)



 
