# prog3
Reads from an input file the month (string), year (integer), and total amount (real) of sales collected.

Assume the state sales tax is 4% and the city sales tax is 2% (total of 6%), 
if the total amount collected is known and the total sales tax is 6$ (city and state) the amount of the product sales is calculated as follows: S = T / 1.06 where S is the product sales and T is the total income (product sales plus sales tax)
if product sales for the month are less than $100,000 the business is only responsible for 90% of the taxes it would pay if product sales had met or exceeded $100,000

*Note: use named constants for all literal 

This C++ program is processed as follows:
1. read from an input file the month, year and total collected at the cash register
2. calculate the actual product sales
3. calculate city taxes on product sales
4. calculate state taxes on product sales 
5. calculate total taxes (city and tax)
6. write program to output file 
  a) authors information
  b) tax report
7. write program output to the screen
  a) authors information
  b) message indicating the month the tax report was generated and the name of the file in which the report has been saved 

*Note: based on the product sales, a business will either qualify for a state tax break or it won't 

The output file is outlined as follows:
1. print the authors information on the first four lines 
2. skip two blank lines before printing the sales tax report 

*Note: do not use functions other than main, arrays, structures or classes 
*Note: use the string library and declare the month as a string 
