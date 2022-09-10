# office deployment tool

[![office deployment tool](gett-stateed.png)](https://github.com/softwarelaab/office.deployment.tool)


Office Deployment Tool is short for Office ODT which is a command-line tool used to download and deploy Microsoft 365 apps on Windows PCs. That is to say, you can download and configure Click-to-Run versions of Office utilities like Microsoft 365 apps for enterprise.

To be specific, the ODT tool gives you more control over an Office configuration file. You can configure which product, language, display, and property elements are installed, how to update them, whether or not to display the install experience to your users, etc. To know more details about configuration options for Office Deployment Tool, you can read this post.

Microsoft Office Deployment Tool package comes with 2 files: setup.exe and configuration.xml. The former is mainly used to install Office ODT. The latter can be used for the configuration file to define which options you want and run the setup.exe file from the command line.

## How to Download Office Deployment Tool

Step 1. Click here to open the Microsoft Download Center.
Step 2. Go to the Office Deployment Tool section and click on Download. Then select a location to save the download package.
Step 3. Locate the executable file you just placed, double click it and click on Yes to run the file.
Step 4. In the Microsoft Office Click-to-Run Administrator window, tick the checkbox for the Microsoft License Terms and click on Continue.
Step 5. In the pop-up window, select a location to save the extracted Microsoft Office 365 Deployment Tool package and click on OK.

## How to Install Office 365 with Office Deployment Tool

Step 1. Create and save the configuration file.
 * Click here to open the Office Configuration Tool page.
 * Input all required information like Architecture (32-bit or 64-bit), Office Suites, Language, and so on. For example, if you need an Office 365 plan that contains Office 365 ProPlus, select Office 365 ProPlus from the Office Suites.
 * Once you complete all required inputs, click on Export.
 * Select the Default File Format and click on OK. Here we take the Office Open XML formats for example. Of course, you can select the one according to your needs.
 * Click the checkbox for I accept the terms in the license agreement and input a name for the file, and click on Export. Then select a location to save the file.

Step 2. Run Microsoft Office Deployment Tool in Download Mode.
 * Type cmd in the Search box, and then right-click the Command Prompt app and select Run as administrator.
 * Change the directory of the Command Prompt to the ODT folder using the cd For example, the command in my case should be cd C:\Users\Administrator\Desktop\ODT. Here you need to replace the file path with your ODT folder.
 * Type the following command and hit Enter to run the ODT utility in Download mode.
 * The process may take you a while to complete depending on your internet speed. Once done, you will see a folder named Office inside the ODT Here you can verify the download is finished by checking the size of the Office folder. If the size has not increased, the download process should be complete.

Step 3. Run Office Deployment Tool in configure mode.
 * Open the elevated Command Prompt window again as we explain in Step 2.
 * Type the following command and hit Enter. Make sure you replace configuration.xmlwith the name of your XML file.
 * When the command runs successfully, you will see a pop-up window showing Office is being installed. Wait for the Office installation to complete.
