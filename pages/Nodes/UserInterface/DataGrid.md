# Data grid
Displays data in a table by creating a list of grids.
### Node properties
##### Label
Text displayed. As of writing this this text is not visible anywhere.
##### Selectable
Shows a select box for the user to select a complete row. If this is unchecked, clicking a new row deselects the old row.
##### DefaultSelected
Denotes which row(s) has been selected by default
##### Height
Denotes the height of the grid
##### font Size
Denotes the font size of the text
##### Data source
The source of the data. The data has to be in an array. All the text can be replaced with a reference to another node with `Nodes.NodeName` as long as the node contains an array.
##### Height 
Denotes how tall the rows of the grid are. Height/RowHeight will then denote the amount of rows per page.
##### GridDefiniton
Select what data is shown in which cell of the grid. It is possible to make multiple ‘rows’ in a single row in the list. Cells are combined by dragging across them.
###### Sub-properties:
Sub settings to define the gird.
|name|system name|property|
|-|-|-|
|Property name |grid-definition.field-name| the name of the property show in the cell|
|Property type |grid-definition.field-type| the type of the property shown in the cell|
|Cell color |grid-definition.cell-color| The color of the cell background|
|Text color |grid-definition.text-color| The color of the text|
|Font size |grid-definition.font-size| the size of the text|
|Text align |grid–definition.text-align| the alignment of the text|
|Bold |grid-definition.font-weight| when checked, the text is embolden|
##### Validate
When checked this control checks if the user has filled in all fields that have the ‘Mandatory’ property

# Examples:
[Report a problem (status update)](https://github.com/conneqtDocumentation/connectDocumentation/blob/main/Nodes/Examples/ReportAProblem.md)