**How it Works**

The program follows these steps to calculate the net salary:

Define Hypothetical Tax Rates:
Hypothetical tax rates are used for tax, NHIF deductions, and NSSF deductions. These rates should be replaced with actual rates obtained from reliable sources.

Calculate Gross Salary:
The gross salary is calculated by adding the basic salary and benefits.

Calculate Tax:
Tax is calculated based on the tax rate and the gross salary.

Calculate NHIF Deductions:
NHIF deductions are calculated based on the NHIF rate and the gross salary.

Calculate NSSF Deductions:
NSSF deductions are calculated based on the NSSF rate and the gross salary.

Calculate Net Salary:
The net salary is calculated by subtracting the total deductions (tax, NHIF, and NSSF) from the gross salary.

Usage
To calculate the net salary for an individual:

Open the JavaScript file where the calculateNetSalary function is defined.

Call the calculateNetSalary function, passing the basic salary and benefits as arguments. For example:

javascript

const basicSalary = 59000; // Basic salary in KES
const benefits = 4500; // Benefits in KES
const result = calculateNetSalary(basicSalary, benefits); // Calculate net salary
Run the program and observe the output. It will display the gross salary, tax, NHIF deductions, NSSF deductions, and net salary for the provided inputs.

