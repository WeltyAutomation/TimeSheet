# TimeSheet
Billable Time Tracking 

Used for logging billable time and expenses. Replacing existing spreadsheet solution.

## Use Cases

Given no started work
* Start work - Defaults to Now with minimum hours. (0.25)
* End work - not available
---
Given Started work
* Start work -
  * Ends Started with now and calculates hours.
  * Starts work with Now with minimum hours. (0.25)
* End work -
  * Defaults to now and calculates hours
  
## Features

Allow for default rate and minimum hours. 
* These can change over time. 
* Changes won't affect logged time. 

Recent work descriptions easy to pick from.
Descriptions can be templates allowing for:
* Service - {Customer}
* Stored description is formated result. 
* Recent entries captures the template. 

Shows recent entries. 
Shows yearly, weekly, daily total hours.
Shows analysis against goals (yearly/hourly).

Load company holidays for the year. 
* Load by date or date range
* List loaded holidays
* Manage holidays (edit/delete)

Edit/Delete time entries.


