# Task 1: Create a Virtual Machine

1. Open your browser and navigate to the Azure Portal using this link: [Azure Portal](https://portal.azure.com/).

2. Log in to the **Azure Portal** using the credentials provided:

   - **Email:** **<inject key="AzureAdUserEmail"></inject>**
   - **Password:** **<inject key="AzureAdUserPassword"></inject>**

3. In the Azure Portal, select **Virtual Machines** under **Azure Services**.

4. Click **Create** and select **Azure Virtual Machine**.

5. In the **Basics** tab, provide the following details:

   - **Subscription**: Choose **Default**.  
   - **Resource group**: Select the resource group named **ODL-Test-Spektra-02**.  
   - **Virtual machine name**: Enter **labvm**.  
   - **Region**: Choose **Central US**.  
   - **Availability options**: Select **No infrastructure redundancy required**.  
   - **Security type**: Select **Standard**.  
   - **Image**: Choose **Windows Server 2022 Datacenter** from the dropdown.  
   - **Size**: Select **Standard D2s_V3**.  
   - **Username**: Enter **labuser**.  
   - **Password**: Enter **Password.1!!**.  

6. Leave all other fields as **Default** and click **Review + create**.

7. Once the validation passes, click **Create**.

8. Once the virtual machine is created click on submit button for below validation to verify that you have successfully completed the task.

# Validation 1: Create the virtual machine

<validation step="11ea4ebd-6966-4f62-82a3-86834ea408f6" />
