# Template-Generator for Moodle Database Activity

Excel file that generates html and css templates for a [Bootstrap](https://getbootstrap.com/) database activity in [Moodle](https://moodle.org/).

## Description

The "generator" is an Excel (.xlsx) file which combines input variables with html and css code.
Simply add your database fields to the excel file and copy pre-formatted templates for your database.
The list view is a bootstrap table with one field in each column and might be the base for custom formatting.

## Getting Started

* Create a database in Moodle or use an existing one
* Create input fields or use existing ones
* Copy all field names in the excel sheet "Fields"
* **Optional:** change setting in excel sheet "Settings"
* Copy templates from excel sheet "Template"

## Dependencies

* A bootstrap based Moodle Theme (like the [standard themes](https://docs.moodle.org/401/en/Standard_themes) Boost and Classic)
* Microsoft Excel (Libre Office might work as well, not tested)
* **Optional:** Source-code editor to make adjustments

## Features

* English and German
* Uses Bootstrap Grid
    * Modern Design
    * Responsive
* Easily adjustable colors
* Optional: [DataTables](https://datatables.net/) for a mobile friendly list view
    * Assign priorities to fields/columns. Priority 1 will always be shown on narrow screens while higher priorities will collapse.

## Help

* Set language by choosing "EN" or "DE" on sheet "Settings"
* Moodle fields must have a unique name (no duplicates)
* Activate DataTables by selecting "Yes / Ja" on sheet "Settings"
* DataTable priorities: n columns can have priority 1,...,n
    * Not all columns need priorities. No priority = column will collapse first on narrow screens

## Version History

* 1.1
    * Added support for tags like ##user##, ##timeadded## etc.
    * new layout for sheet "fields"
* 1.0
    * Initial Release

## Acknowledgments

Inspiration, code snippets, etc.
* Florian Dagner: [Dropdown-Menü für Datenbanken](https://fdagner.notion.site/Dropdown-Menu-f-r-Datenbank-Aktionen-ad16054184c740de816a092c7a487260)
* Florian Dagner: [Tabellen-Generator für die Moodle-Datenbank](https://fdagner.de/wpress/tabellen-generator-fuer-die-moodle-datenbank-beta/)
* [DataTables](https://datatables.net/)

## Screenshots

### View List
![image](https://github.com/margomius/moodle-database-generator/blob/main/Screenshots/05_List_View.PNG?raw=true)

### View Single
![image](https://github.com/margomius/moodle-database-generator/blob/main/Screenshots/06_Single_View.PNG?raw=true)

### DataTables on mobile (collapsed and expanded)
![image](https://github.com/margomius/moodle-database-generator/blob/main/Screenshots/07_DataTables_List_View_Collapsed.PNG?raw=true)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![image](https://github.com/margomius/moodle-database-generator/blob/main/Screenshots/08_DataTables_List_View_Expanded.PNG?raw=true)
