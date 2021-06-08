# SalaryBreakdown
Salary Breakdown is a  C# windows Console Application.
The Application allows user to enter the gross salary and pay frequency, to display the breakdown of the salay and pay packet.
Class Salary contains function SalaryBreakdownData which gets the input from user, validates it and creates SalaryInputData.
SalaryInputData is then passed on to SalaryBreakdownCalculation class.
SalaryBreakdownCalculation class calculates Superannuation contribution, Taxable income, Deduction such as Medicare Levy, Budget Repair Levy and Income Tax. It then calculates the netIncome and pay packet the user will get based on the pay frequency entered.
SalaryBreakdownOutput is then passed onto DisplayData Function that displays all the calculated data.

