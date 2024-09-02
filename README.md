# SIEM-Setup

### To set up Geo IP Data Ingestion with Log Analytics and Microsoft Sentinel (SIEM), you can follow these steps, which you can use for your 

# Create a Log Analytics Workspace
In the Azure Portal, go to Log Analytics.
![Screen Shot 2024-09-02 at 4 31 00 AM](https://github.com/user-attachments/assets/31b5a01e-32e0-4f3e-aac5-f91fc7dda7d5)


Create a new workspace, providing the relevant details (name, region, and resource group).
Ensure that the workspace is linked to Microsoft Sentinel later.
![Screen Shot 2024-09-02 at 5 51 44 AM](https://github.com/user-attachments/assets/4814ac67-6418-459b-b8c6-f22919be7cd4)

# Enable Microsoft Sentinel
Navigate to Microsoft Sentinel in Azure.
![Screen Shot 2024-09-02 at 6 35 50 AM](https://github.com/user-attachments/assets/dbb69ac0-78a2-4cc2-bc72-7887afef26c4)

Click on Add and select the Log Analytics Workspace created earlier.
![Screen Shot 2024-09-02 at 7 19 57 AM](https://github.com/user-attachments/assets/9918a20c-d25c-48fb-8cfa-22446b27cc39)
Sentinel will be deployed to the workspace, allowing it to monitor logs and alerts.
