# Task 1: Create a Virtual Machine

1. Log in to the **Azure Portal** using the credentials provided:

   - **Email:** **<inject key="AzureAdUserEmail"></inject>**
   - **Password:** **<inject key="AzureAdUserPassword"></inject>**

     ![](./images/login.png)

     ![](./images/login1.png)

1. If you are prompted with **Stay signed in?** pop up then click on **No**.

   ![](./images/login2.png)

4. In the Azure Portal, select **Virtual Machines** under **Azure Services**.

   ![](./images/vm.png)
   
6. Click **Create** and select **Azure Virtual Machine**.

7. In the **Basics** tab, provide the following details:

   - **Subscription**: Choose **Default**.  
   - **Resource group**: Select the resource group named **ODL-Demo-<inject key="Deployment Id" enableCopy="false">-02**.  
   - **Virtual machine name**: Enter **labvm**.  
   - **Region**: Choose **west us 2**.  
   - **Availability options**: Select **No infrastructure redundancy required**.  
   - **Security type**: Select **Standard**.  
   - **Image**: Choose **Windows Server 2022 Datacenter** from the dropdown.  
   - **Size**: Select **Standard D2s_V3**.  
   - **Username**: Enter **labuser**.  
   - **Password**: Enter **Password.1!!**.  

8. Leave all other fields as **Default** and click **Review + create**.

9. Once the validation passes, click on **Create**.

10. Once the virtual machine is created click on submit button for below validation to verify that you have successfully completed the task.

# Validation 1: Create the virtual machine

<validation step="73f8cbf9-09fe-4b27-8951-ea93ee6f8e9a" />
