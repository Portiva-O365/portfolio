# How to use the repository

In order to further expand or adjust the repository itself, the repository must be locally cloned. The description below shows how to do this with Visual Studio Code.

## Clone in Visual Studio Code

1. Open the repository you want to clone
2. Select `Clone or Download` in the repository
3. Copy the Url in the dropdown
4. Open Visual Studio Code and choose `Ctrl + Shift + P` and type `git clone`, press `Enter`
5. Paste the copied Url from GitHub into the command line and press `Enter`
6. Choose a local storage folder

The repository is copied locally. Of course you you're not allowed to update the repo on GitHub, but you can adjust the repo to your needs.

## Build the repository

1. In Visual Studio Code, go to the command window using `Ctrl + '`
2. Build the repository using `npm install`
3. Compile the repository with `gulp serve`

After the `gulp serve` command, the browser automatically starts in the local workbench.

## Helpful links
- [SPFx Getting Started](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/web-parts/get-started/build-a-hello-world-web-part)
- [SharePoint Development](https://docs.microsoft.com/en-us/sharepoint/dev/)
- [SharePoint Framework Reference](https://docs.microsoft.com/en-us/javascript/api/overview/sharepoint?view=sp-typescript-latest)
- [Release Notes for SPFx Package Version 1.5.1](https://github.com/SharePoint/sp-dev-docs/wiki/Release-Notes-for-SPFx-Package-Version-1.5.1)
