# Management-Dashboard-Excel-Project
In this project Excel Dashboard is made from a source data of a Company where Project progress and Manager's Task are Analyzed. 

## Steps

Step 1	Format source data in an Excel Table - CTRL+T				
					
Step 2	Dashboard PivotTable				
					
Step 3	Insert Table for Tasks Bar Chart 				
					
	formulas	task not stared= countif progress column =0			
		task inprogress=countifs progress column <>0,<1			
		task completed=countif progress column <1			
					
Step 4	Insert doughnut chart PivotTable for Overall Completed - Completed Days vs Duration				
					
		Days Completed =		sum of days completed/sum of duration	
					
		Days Remaining= 1- 		Days Completed 	
					
Step 5	Insert budget vs actual doughnut & bar chart PivotTable 				
					
Step 6	Insert Slicers for Project and Manager fields & connect to all PivotTables				
					
Step 7	Add data bars to Progress column of PivotTable				
					
Step 8	Add text for date range to header cell F1:				
					
	TEXT(MIN('start date' range),"d-mmm-yy")&" to "&TEXT(MAX('END date 'range),"d-mmm-yy")				
					
Step 9	Insert Avrege Progress column bar chart				
