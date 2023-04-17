# **G2P-Csv-Import**

## **Introduction:**

  This is a feature which helps to import many registrants at a time by using importing csv/excel

## **Technologies Used**:
Following technologies have used:

  - xml: Used for creating the views.
  - JavaScript: Used for adding wizard and Added action functionality of importing csv/excel
  - Odoo: Used for provides a range of features and functionalities
  - Python: Used for implementing business logic 


## **Installation**
- Add module to addon path and run odoo.
- Go to settings and activate developer settings
- Then update the apps list.
- Then go to apps list and search and install g2p_csv_import module.

## **Important  validations to use this Feature** 
  - Name is mandatory for using this Feature.
  - File should be csv/excel file only
  - It is better to check file size should be less than 25mb.

## **Flow of importing csv/excel file**
![Flow](https://github.com/RamakrishnaVellala/openg2p-csv-import/blob/develop/g2p_csv_import/csv%20import%20flow.jpg)


## **Steps:**
1.  First make sure the  module is installed. If it isnt then you can click on the g2p_csv_import module in the applications view.

2. Go to Settings -> Configuration -> General Settings and check the "Allow users to import data from CSV files" checkbox.

3. Go to Registry -> Individuals then Click on the "Import" link next to the Create button and make sure that file should be csv/excel file.

4. Click the "Upload File" button and find your csv/excel file to import.

5. Match the fields from the csv file to the fields in the drop down menus.

6. Click the "Test" button to see if any errors occurred. Correct any errors on the csv file, save it, then reload the file by clicking the Load File button next to the "Test" button.

7. Click "Test" again. If there are still errors, then repeat step 6, otherwise click the "Import" button. Then youre done.








