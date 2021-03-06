# JavaScript Extensions and API Tutorial

Banana does allow to have Extensions  that are embedded within a Banana File.
We have prepared tutorial files that include samples code for most API.
- You can see how the API works and experiment with it.
- Just downaload and open a tutorial file in Banana.


## Download template files

1. Start Banana Accounting
2. Click on menu **File** -> **New**
3. On the Search section digit "Tutorial"
4. On the right side select **JavaScript Tutorial 1** or **JavaScript Tutorial 2** from the templates
5. The selected tutorial template is now ready to be used

![search_tutorial_template](https://raw.githubusercontent.com/BananaAccounting/General/master/TutorialApps/images/search_tutorial_templates.png)

### Tutorial as an embedded BananaApp
Extensions can be embedded in the accounting file.
Embedded script run only for the specific file, but don't need to be installed. 
A  tutorial is a  Banana accounting file that includes many BananaApps that show how to construct the BananaApp and let  experiment by changing the code. 

### Use the JavaScript Tutorial Extensions:
1. Start Banana Accounting
2. Open the ac2 tutorial file 
3. Move to the table **Documents**
4. Select cell of the column **Attachments**
   * Choose the **first icon** to start the scripts
   * Choose the **second icon** to edit and experiment with the script 

![manage_tutorial_apps](https://raw.githubusercontent.com/BananaAccounting/General/master/TutorialApps/images/manage_tutorial_app.png)

By clicking the first icon the ExtensionChange is executed and returns a report like the following:

![report_example](https://raw.githubusercontent.com/BananaAccounting/General/master/TutorialApps/images/report_example.png)

By clicking the second icon, an editor is opened and it is possible to see and modify the JavaScript code:

![javascript_editor](https://raw.githubusercontent.com/BananaAccounting/General/master/TutorialApps/images/javascript_editor.png)

## Tutorial available
[embedded_javascript_tutorial1.ac2](https://github.com/BananaAccounting/General/blob/master/TutorialApps/embedded_javascript_tutorial1.ac2?raw=true) let you try the basic functionalities, starting with a "Hello World" example

[embedded_javascript_tutorial2.ac2](https://github.com/BananaAccounting/General/blob/master/TutorialApps/embedded_javascript_tutorial2.ac2?raw=true) let you try the complete examples, starting with a formatted "Account statement"
 
## Tutorial javascript codes
[embedded_javascript_tutorial1.js](https://raw.githubusercontent.com/BananaAccounting/General/master/TutorialApps/embedded_javascript_tutorial1.js) contains all the javascript codes used for the [embedded_javascript_tutorial1.ac2](https://github.com/BananaAccounting/General/blob/master/TutorialApps/embedded_javascript_tutorial1.ac2?raw=true).

[embedded_javascript_tutorial2.js](https://raw.githubusercontent.com/BananaAccounting/General/master/TutorialApps/embedded_javascript_tutorial2.js) contains all the javascript codes used for the [embedded_javascript_tutorial2.ac2](https://github.com/BananaAccounting/General/blob/master/TutorialApps/embedded_javascript_tutorial2.ac2?raw=true).

## Other tutorials
[ch.banana.tutorial.tablewidget.js](https://raw.githubusercontent.com/BananaAccounting/General/master/TutorialApps/ch.banana.tutorial.tablewidget.js) shows how to interact with a QTableWidget. The user interface is found in file [ch.banana.tutorial.tablewidget.ui](https://raw.githubusercontent.com/BananaAccounting/General/master/TutorialApps/ch.banana.tutorial.tablewidget.js). This tutotial is also found in file embedded_javascript_tutorial1.ac2 at code 740.

## Documentation
* See the [BananaApps Documentation](https://www.banana.ch/doc9/en/node/4065) to discover all the available features that allow you to create your own BananaApps.
