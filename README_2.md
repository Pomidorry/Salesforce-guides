00# Create HTTP Callouts and sending API response email with Flow Builder

## Short description
This project can be useful for beginners. In this tutorial you will learn how to work with Salesforce flows and how to implement API to you flow

## Precondition
You need to have your Salesforce org created. I'll use Trailhead Playgroung Org. It's good options for newbies cos it's free

## Let's start
1. You have you org opened. Now click gear icon and select **Setup** option
![image](https://github.com/user-attachments/assets/ec25b0a9-1e9b-4b85-abef-2040e17470e6)

2. In **Quick Find** field search and select **Named Credentials**
<br>![image](https://github.com/user-attachments/assets/e33fa28c-1de7-41ac-9684-474914a73995)</br>

3. Click **External Credentials** tab and we need to create credentials. Click **New** 
![image](https://github.com/user-attachments/assets/182db340-e7f1-43b1-8d3e-7b4d347df9b3)

4. Fill up **New External Credential** fields like on the screenshot. And then click **Save**
![image](https://github.com/user-attachments/assets/08e68cda-28e9-4c83-9bc0-00417527c4f3)

5. Then we need to create a principal. Click **New**
![image](https://github.com/user-attachments/assets/bd30f68a-4a0c-4bc5-9c76-bf1ecb5a589f)

6. Leave default field values but for **Parameter Name** enter **Animals API External**
![image](https://github.com/user-attachments/assets/98c240ab-a211-4a01-aa7c-459ec96c7416)

7. Let's come back to **Named Credentials**. Click **New**
![image](https://github.com/user-attachments/assets/a6a90e2c-625f-4ac4-b8c1-44c89b563b08)

8. You need to have configurations like on the screenshot. **Label**: Animals API Named. **Name**: Animals_API_Named. **URL**: https://th-apex-http-callout.herokuapp.com. For External Credential, select Animals API External. Then click **Save**
![image](https://github.com/user-attachments/assets/8a8c8e99-d288-44b3-a1d1-d8cbb179fb3d)

9. In **Quick Find** select Permission Sets. Then click **New**
![image](https://github.com/user-attachments/assets/9a8ed507-bafd-4177-acf3-1f4603b4aaae)

10. Enter Animals API for **Label** field.**API Name** will auto-filled with Animals_API value. Click **Save**
![image](https://github.com/user-attachments/assets/bfff5b2b-c9e8-4077-b31e-8068bf1c0493)

11. In the **Apps** section, select **External Credential Principal Access**
![image](https://github.com/user-attachments/assets/4db8e6e4-41e5-4d8b-94b9-1decbc665cff)

12. Click **Edit** 
![image](https://github.com/user-attachments/assets/26370ed8-bc71-4d29-8028-cba4fefc19f3)

13. Move the **Animals API External** option from **Available External Credential Principals** to **Enabled External Credential Principals** and click **Save**
<br>![image](https://github.com/user-attachments/assets/107b0bcc-5e7d-46a6-9bea-86a72e6cacbe)</br>

14. Now let's go to flow creating our flow. In **Quick Find** search and select **Flows** option. Then click **New Flow**
![image](https://github.com/user-attachments/assets/7d7069c8-60e8-4518-8932-ef62e8638862)

## Source
Inspired and modified idea from Trailhead [project](https://trailhead.salesforce.com/content/learn/projects/quick-start-create-http-callouts-with-flow-builder)
