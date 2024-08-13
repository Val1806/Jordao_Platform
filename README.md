# Jordao Platform
Web Platform for a Portuguese company, related to a MySQL Database.
Here's the user manual.

# I) Home page and navigation

When you arrive on the site, you come across the platform’s home page. You will find the drop-down menu on the left of the screen, which will allow you to access the different tables and functionalities of the site. You can close the menu by clicking on the icon **☰** at the top left of the screen. At any time, you can return to this home page by clicking on the **🏠︎** icon at the top left of the screen.



# II) Tabs: Data Tables & Features

As indicated previously, the menu tabs allow you to access the different tables in the database.
We have as submenus:

- <ins>***Equipment Attributes***</ins> : This submenu brings together the attribute tables which allow you to create a ***Equipment***.

- <ins>***All Equipments***</ins> : This submenu includes the table ***Equipment***, which brings together all the equipment entries in the database.

- <ins>***Components Tables***</ins> : This submenu groups together the component tables, namely ***Compressor***, ***Evaporation Fan***, ***Condenser Fan*** and ***Blade Condenser***. These components, associated with a ***Equipment***, will make it possible to form a final ***Product***.

- <ins>***All Products***</ins> : This submenu includes the table ***Product***, which brings together all the product entries in the database.

- <ins>***Reference Tables***</ins> : This submenu groups together the tables containing the reference values ​​linked to temperature, climatic conditions and energy measurements. These tables are all read-only.

- <ins>***Other Features***</ins> : This submenu brings together all the additional functionalities of the site: ***Expansion Valve Orifice Calculation*** to find the right valve and/or the right orifice according to our needs / simulations.

## Inserting into a table

To insert an entry into any table, here is the procedure:

- Click on one of the menu tabs to navigate to a table.

- Click on the button "***Add***" above the table to be redirected to the insert form.

- Enter information for the form fields.

- Once the fields are completed, click on the button “***Insert***” in order to validate your insertion. 
If everything is correct, you will see a popup with the message “***New \[table name] inserted successfully***”. Otherwise, a popup with a message telling you the nature of the error will be displayed.
If you ever want to cancel an insertion in progress, all you have to do is navigate to another page: the insertion will be automatically canceled.


## Editing a row in a table

To modify the data of an entry in a table, here is the procedure to follow:

- Select the line whose information you want to edit.

- Click on the button "***Edit***" above the table to be redirected to the edit form.

- The fields will be pre-populated with the row's current information. Change the information you want simply by editing the form fields.

- Once the changes are made, click on the button “***Save Changes***” to save your changes, then “Yes”. If you want to stay on the edit form, click “***No***”.
If everything is correct, you will see a popup with the message “***Changes saved successfully***”. Otherwise, a popup with a message telling you the nature of the error will be displayed.
If you ever want to cancel a modification in progress, click on the button “***Cancel***”, then “***Yes***”. If you want to stay on the edit form, click “***No***”.

>[!NOTE]
> \[02/08/2024] For certain tables, the editing functionalities are deliberately disabled, the logic behind not yet being developed because the editing of certain information has too significant an impact on other tables - ***Product*** notably.




## Deleting one or more rows in a table

To delete one or more rows in a table, here is the procedure to follow:

Select the row(s) you want to delete.

Click on the button "Remove", Then "Yes” in order to validate the deletion.
If everything is correct, you will see a popup with the message “Element(s) [deleted elements] saved successfully”. Otherwise, a popup with a message telling you the nature of the error will be displayed.
If you ever want to undo the deletion, click “No”.


If you ever want to speed up the removal process, you can use the “Select / Deselect All” to select or deselect all rows in the table. It is nevertheless a button to use with caution in order to avoid incorrect manipulations.


## Generating a documentation PDF

[This feature only concerns the table Product]

To generate a documentation PDF for a particular product line, here is the procedure to follow:

Open the drop-down menu on the left (button ☰), then navigate to the section All Products > Product.

Click on the button "PDF" on the top of the table Product. You will then be redirected to the PDF generation form.

Once on the page, choose the type of equipment you want to generate the PDF. When selecting equipment, the sections Depth And Length are dynamically updated to display the values ​​available for the chosen equipment.

You can then choose the value of Depth that you want to appear on the PDF, as well as the different values ​​of Length among those available.

Once all the values ​​are selected, click on the button “Generate PDF”, then “Yes” in order to start generating the PDF. If you ever want to stay on the PDF generation form, click on “No”.
The download will start automatically when it is ready. If successful, a popup will appear with the following message: “PDF file downloaded successfully”. Otherwise, a popup with a message telling you the nature of the error will be displayed.

## Expansion Valve Orifice Calculation

If you want to use the orifice and valve calculation functionality, here are the steps to follow:

Open the drop-down menu on the left (button ☰), then navigate to the section Other Features > Expansion Valve Orifice Calculation. 

Please choose the Product for which you want to find the valve and orifice.

The Cooling Power of Product selected is then automatically retrieved and displayed. 
However, if you wish to carry out a simulation, you can check the button “Manual” above the reserved field. This will disable the Product selection, and you can then manually change the Cooling Type and the Cooling Power.

Then select the Gas and the Valve Type that you want to test.

When all the information is entered, click “Find Orifices” to start the search. You'll also see tube diameter values and available adapters.
If results exist, they will be displayed in a table at the bottom of the page, after the form. Otherwise, you will see a popup if there is no result or an error.
