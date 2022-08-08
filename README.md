# EXCEL-Determining-Potential-Outcomes-Using-Scenarios
Create a scenario that preserves the original projection values for revenue and expenses.
    Select the Projections worksheet.
    Select the range B4:B8. Press and hold Ctrl and select the range B12:B17.
    Select Data→What-If Analysis→Scenario Manager.
    In the Scenario Manager dialog box, select Add.
    In the Add Scenario dialog box, in the Scenario name text box, type Original
    Observe that the Changing cells field shows the range B4:B8,B12:B17.
    In the Comment field, at the end of the default comment text, press Enter and type Original Values
    Note: Best practice is to add to the default scenario comment text, giving you the ability to note who created the scenario and when it was created.
    Select OK.
    In the Scenario Values dialog box, verify that the original values are listed.
    Note: Cell names have been created for each scenario value to help both with creating scenarios and later for using with a scenario summary.
Create another scenario for an advertising campaign.
    In the Scenario Values dialog box, select Add.
    In the Add Scenario dialog box, in the Scenario name text box, type Advertising Campaign
    In the Comment field, at the end of the default comment text, press Enter, type Advertising budget increase to $40,000 and each country's revenue increased by 10% and then select OK.
    In the Scenario Values dialog box, change the values for this scenario as follows:
    Note: You may either enter formulas or values in the changing cells. Make sure to scroll down past Salaries and Rent_Utilities to change the Advertising value.
Australia: =200000*1.1 (or, enter 220000)
Canada: =130000*1.1 (or, enter 143000)
Germany: =150000*1.1 (or, enter 165000)
Great_Britain: =100000*1.1 (or, enter 110000)
United_States: =300000*1.1 (or, enter 330000)
Scroll as needed so you can see Advertising.
Change Advertising to 40000
    Select OK.
    If you entered formulas instead of values, a dialog box will inform you that names and results of formulas were converted into values.
    If the Microsoft Excel dialog box is shown, select OK to dismiss the message and return to the Scenario Manager dialog box.
Show the scenarios.
    In the Scenario Manager dialog box, select Advertising Campaign if necessary and select Show.
    Observe the changes made to Total Revenue, Total Expenses, and Profit.
    In the Scenario Manager dialog box, in the Scenarios list box, select Original and select Show.
    The original values are restored.
Create a scenario summary.
    In the Scenario Manager dialog box, select Summary.
    In the Scenario Summary dialog box, verify the Report type option selected is Scenario summary.
    In the Result cells field, select B9, press and hold Ctrl, and drag to select the range B18:B19.
    Select OK.
    Verify the new worksheet Scenario Summary is created.
Add the Scenario command to the Quick Access Toolbar.
    Select the Ribbon Display Options button, then select Show Quick Access Toolbar
    Select File→Options.
    Select the Quick Access Toolbar tab.
    From the Choose commands from drop-down list, select All Commands.
    In the commands list, select Scenario and select the Add button.
    Select OK.
Use the Scenario command from the Quick Access Toolbar.
    Select the Projections worksheet.
    In the Quick Access Toolbar, select Scenario.
    Select Advertising Campaign.
    In the dialog box, select No to avoid editing the scenario values.
