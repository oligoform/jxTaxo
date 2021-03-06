#jxTaxo#

OXID eShop Admin Extension for Setting up the Taxonomy/Classification of each Category for Shopping Portals like Google Shopping or Amazon Product Ads.


## Usage ##

1. Unzip the complete file with all the folder structures and upload the content of the folder copy_this to the root folder of your shop.
2. After this navigate in the admin backend of the shop to _Extensions_ - _Modules_. Select the module _jxTaxo_ and click on `Activate`.
3. Switch to the menu _Service_ - _Tools_, load the file install.sql and press `Start Update`.
4. Remain in the menu _Tools_ and press `Update views`

If you open the new menu _Product Export_, you will see the the new menu item _Google Product Taxonomy_ and _Amazon Product Ads_.

Download the actual Google product taxonomy catalog (see [more details here](https://support.google.com/merchants/answer/160081)), choose for each of your shop categories the suitable google category and copy the complete text into the field right to the shop category.
  
Example:  
![screenshot](https://github.com/job963/jxTaxo/raw/master/docs/img/edit-amazonclassification-rs.png)

![screenshot](https://github.com/job963/jxTaxo/raw/master/docs/img/edit-googletaxonomy-rs.png)

**IMPORTANT**  
This module requires an additional module for exporting/creating a Google productfeed file.
  
Tested in OXID 4.7, 4.8 and 4.9

## Release history ##

- **0.1 - Initial release**
	- Creating new column in oxcategories
	- Form for editing the taxonomy settings  

- **0.1.1 - Adaption for OXID 4.9**
	- deprecated functions exchanges
	- compatible with 4.7, 4.8 and 4.9  

- **0.2 - New module for multiple shopping portals**
	- Amazon product ads added
	- New installation module
