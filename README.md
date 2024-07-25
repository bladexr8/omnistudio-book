## Installing Omnistudio into a scratch org
1. Visit the [Omnistudio Releases Page](https://help.salesforce.com/s/articleView?id=000394906&type=1) and locate the package you want to install.
2. Select the **Production Install** link for the package and extract the package id from the URL, e.g. from the Summer '24 install URL https://login.salesforce.com/?ec=302&startURL=%2Fpackaging%2FinstallPackage.apexp%3Fp0%3D04t4W000003ChfPQAS%26InstHostname%3Dlogin.salesforce.com **04t4W000003ChfPQAS** is the package id.
3. Construct a link in the following format and insert into a new browser tab https://*scratch org domain*.scratch.my.salesforce.com/packaging/installPackage.apexp?p0=*package id*
4. An example URL for installing the Summer '24 Omnistudio package - https://nosoftware-velocity-7865-dev-ed.scratch.my.salesforce.com/packaging/installPackage.apexp?p0=04t4W000003ChfPQAS

# Salesforce DX Project: Next Steps

Now that you’ve created a Salesforce DX project, what’s next? Here are some documentation resources to get you started.

## How Do You Plan to Deploy Your Changes?

Do you want to deploy a set of changes, or create a self-contained application? Choose a [development model](https://developer.salesforce.com/tools/vscode/en/user-guide/development-models).

## Configure Your Salesforce DX Project

The `sfdx-project.json` file contains useful configuration information for your project. See [Salesforce DX Project Configuration](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_ws_config.htm) in the _Salesforce DX Developer Guide_ for details about this file.

## Read All About It

- [Salesforce Extensions Documentation](https://developer.salesforce.com/tools/vscode/)
- [Salesforce CLI Setup Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_intro.htm)
- [Salesforce DX Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_intro.htm)
- [Salesforce CLI Command Reference](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference.htm)
