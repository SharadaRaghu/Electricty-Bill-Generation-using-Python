# Electricty-Bill-Generation-using-Python
A Simple program to calculate electricity bill 

Given an integer U denoting the amount of KWh units of electricity consumed, the task is to calculate the electricity bill with the help of the below charges:

1 to 100 units – Rs. 10/unit
100 to 200 units – Rs. 15/unit
200 to 300 units – Rs. 20/unit
above 300 units – Rs. 25/unit

Examples:
Input: U = 250
Output: 3500
Explanation:
Charge for the first 100 units – 10*100 = 1000
Charge for the 100 to 200 units – 15*100 = 1500
Charge for the 200 to 250 units – 20*50 = 1000
Total Electricity Bill = 1000 + 1500 + 1000 = 3500

Input: U = 95
Output: 950
Explanation:
Charge for the first 100 units – 10*95 = 950
Total Electricity Bill = 950

Check units consumed is less than equal to the 100, If yes then the total electricity bill will be:
{Total Electricity Bill} = (\text{units} * 10)

Else if, check that units consumed is less than equal to the 200, if yes then total electricity bill will be:
{Total Electricity Bill} = (100*10) + (\text{units}-100) * 15

Else if, check that units consumed is less than equal to the 300, if yes then total electricity bill will be:
{Total Electricity Bill} = (100*10) + (100*15) + (\text{units}-200) * 20

Else if, check that units consumed greater than 300, if yes then total electricity bill will be:
{Total Electricity Bill} = (100*10) + (100*15) + (100*20) + (\text{units}-300) * 25
