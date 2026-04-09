# SiteBook
1) Project Screen:-
Add New Project Screen:- Add Another field, Deal End Date which is the time given to pay remaining balance.
On Project Screen for each venture just show below financial values
a) Total Land, Total Deal Value, Paid So far, Remaining balance - 1 row
b) Plots, Sold, Total Cents, remaining Cents - 2nd row
Remove overall profitablity and Project expenditure section here. We will just maintain high level info here
All PLOT INFO small screen should move to another screen (Project Expenditure) which we will discuss now.

2) Add another New screen - Project Expenditure.
Show Project name - on clicking should display all the Plots INFO small screens that we created in Project Screen of each venture
Now on clicking any plot ## Info - Plot Info section - Remove Construction Phase details and show following details
Under Plot Info Screen:-
Have 2 fields under Plot No and Plot Sixe, Default Description box saying Advance paid for land, Amount paid -(Total Advance Paid for Land/No of cents * Current Plot size)
Add Construction expenses
Default One Edit box - Advance for Construction - Amount - Date 
under that +Add Expense which should give one description box, amount, Date
Now another Section called Miscellaneous expenses 
Default with DDL with Registration, BoreWell,BoreMotor, Brokerage, Electric Meter, AMount date
under that +Add Other Expense which should give one description box, amount, Date.
Now display 2 Labels, Total Construction cost = Construction+Miscellaneous expenses
Total Investment :- Total construction Cost + Advance paid for land.
Rest of fields like status, sold Price, Advance price, save and cancel button should be same, Buyer Name, Partial AMounts Recieved with dates are same only.
Also when i change status of house/Plot TO SOLD, then and there i should get above sold info, currently its not coming. 
Need Extra FINAL field at bottom with field Total PLOT Profit - (Sold Price - Total plot Cents*Deal Cent price+Construction Cost+Miscellaneous Cost)

Here you can show Overall Profitability section under each venture
Should have - Total Invested Amount(Land Price actutal given+Construction amounts of all plots+ Miscellaneous expenditure of all plots),
Total Plots, Sold, Advances received, Expected amounts to recieve,Intrests paid(Get intrests amounts that paid until date from FInance Screen,
Total Profits = This has to be very intelligent- It should consider only Plots that are sold Status - 
Logic to calculate amount--> (Sold Price)-(Total Actual Land Price for plot size (cent rate * no of cents)+Total Construction Cost+Miscellaneous)


Finance Screen:-
In Active Loan Info, Add Emi/Month (Approximately) based on details given.
Auto Create Monthly Entrie(s) with 1st Date of every month after loan start date and have Paid? Yes/No.Check Box functionality. Have Edit Icon to edit date/Amounts if needed.
Let it Add Payment button as it is.
