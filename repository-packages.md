# Using the Repository Packages

## Before you start!
- To use a web part package in the SharePoint environment, you must be a *__Tenant Administrator__*. If you re not a Tenant Administrator...
    - Then carry out *Step 1 - Download a package*
    - Find a Tenant Administrator! She can perform step 2 with the downloaded package
    - Execute Steps 3 and 4 yourself 
- The web parts must be added in the *App Center* or *App Catalog*. This is a SharePoint site collection created from the admin portal. If there is no App Center in your tenant yet, it must be created. [More information on app site collections.](https://docs.microsoft.com/en-us/sharepoint/use-app-catalog)

## Step 1 - Download the package

To use a web part package, you must first download it from GitHub:
1. Open the repository
2. Open the folder `sharepoint/solution`, always take the latest version in the folder name
3. Click on the `.sppkg` file and then select the **Download** button in GitHub.
4. Save the file locally 

## Step 2 - Install the package

1. Open your tenant and go to the App Center
2. Upload the local `.sppkg` file in the App Center
3. If the file is already present, select **Replace**
4. SharePoint asks if you trust this file, choose *Yes*

After this last step, the `.sppkg` file is installed and can be used in the sites on the tenant.

## Step 3 - Add web part to site

1. Open the site where you want to use the web part
2. On the home page of the site you select *New > App*
3. The *Site Contents > Apps* page opens, click on the icon of the app you want to add
4. The app is added to the site

## Step 4 - Add web part to the page

1. Open on the site where the app has been added and create a new page
2. In a web part zone, click on the `+` icon and choose the web part that you have added
3. If necessary, adjust the configuration of the web part
