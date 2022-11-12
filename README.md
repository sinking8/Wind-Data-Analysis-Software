# Wind Data Analysis Software

## I. Introduction

Windographer software is designed for importing, analyzing and visualizing wind resource data measured by met tower, sodar or lidar.<br/>
This software will be able to quickly import data from a variety of different formats allowing for rapid quality control and statistical analyses, including measure-correlate-predict (MCP), and the functionality to export data to almost any wind flow model that is commonly used within the wind power industry.

<b>Current Version 1.0.0 consists of 3 major tests </b>

<hr/>
## II. Implementation

The software was implemented using Tkinter which is a standard Python GUI Library.

### libraries used:

- numpy==1.19.3
- pandas==1.1.3
- matplotlib==3.3.3
- Pillow==8.2.0
- openpyxl==3.0.7
- scipy==1.5.4

<hr/>
## III. WorkFlow of the Application

- Step 1: Import the file
  Select Configure
  File => Import
- Step 2: Click on the row and edit the values as per requirement and click ok
- Step 3: Then click Processing.
  Ongoing to processing the graph selector dialog box is visible.
  Select the required ones to see the graph

- Step 4: The selections can be changed once inside the processing tab too.

- Step 5: The tab has options below to undo all changes, undo and redo, move button, zoom, adjustments button and save button.

- Step 6: The test settings Button in Processing has all three tests which can be done on the button click. If required new values can be given and can be saved using the Update button and then the tests can be run. Info has the default values.
- Step 7: On doing the tests we can see flags where the data is removed.(More than one workspaces can be created to perform comparitive study.)

- Step 8: The Correlation tab has a graph which can be used to correlate two values using the dropdown box values.
- Step 9: On completion of all the tasks the result file can be downloaded as an Excel sheet.
  File =>Download and name the file and mention the location.

<hr/>
## Note

Since its a licensed software for NIWE Kindly reach out for source code or for contribution

[contactUs] ashwinblaze111@gmail.com
