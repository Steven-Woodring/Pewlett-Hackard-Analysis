# Pewlett Hackard Analysis with PostgreSQL
### An analysis of a hypothetical corporation’s employee data to determine future hiring needs

## Overview
Pewlett Hackard, a large corporation with thousands of employees, is experiencing a mass exodus of these employees as baby boomers age out of the workforce. The hypothetical company will be offering a retirement package for certain employees. Additionally, the large number of retirements will create many job openings, and Pewlett Hackard will need to be prepared to fill these vacant positions. This analysis will build an employee database with SQL and generate a list of all employees eligible for the retirement package.

## Results
### Retiring Employees
- There are nearly 72,500 employees who are expected to retire soon (born 1952-1955).
<img width="113" alt="Screen Shot 2022-02-06 at 10 52 29 PM" src="https://user-images.githubusercontent.com/95303422/152726026-cd960809-ae51-40e6-af74-552a453bcb36.png">

- Most of these expected retirees are in senior positions, meaning Pewlett Hackard will have to replace some of its most experienced and qualified employees.
<img width="208" alt="Screen Shot 2022-02-06 at 8 08 35 PM" src="https://user-images.githubusercontent.com/95303422/152726047-861e0d5d-6b27-4b0c-8890-cf50f39554d8.png">

### Mentorship-Eligible Employees
- There are only 1,549 employees who are eligible for the mentorship program (born in 1965). This program will have to be expanded if the company is to fill the open positions left by the retiring employees.
<img width="115" alt="Screen Shot 2022-02-06 at 10 51 16 PM" src="https://user-images.githubusercontent.com/95303422/152726124-f9cebac1-37a3-429b-bcf6-bed6bf032ef7.png">

- Less than 1,000 of the eligible employees are currently in a senior position. It is likely that many of these lower-level employees will be expected to take on more responsibility in the coming years.
<img width="114" alt="Screen Shot 2022-02-06 at 11 26 50 PM" src="https://user-images.githubusercontent.com/95303422/152726145-69da6df9-7f97-4640-a622-89e1361d1859.png">

## Summary
- A massive number of employees will be vacating their positions in the coming years, leaving an expected 72,458 roles needing to be filled. This number represents almost a quarter of the corporation’s workforce. The following query returned the number of employees who are expected to retire soon:
<img width="479" alt="Screen Shot 2022-02-06 at 11 37 45 PM" src="https://user-images.githubusercontent.com/95303422/152726204-b3de2dd3-33c8-4ac1-9f8c-642c555d7211.png">

- Over 50,000 of the 72,458 retirement-ready employees are senior-level. Considering there are only 1,549 employees who are eligible for the mentorship program, there should be no shortage of qualified mentors for the next generation of Pewlett Hackard leaders. The following query informed this conclusion:
<img width="249" alt="Screen Shot 2022-02-06 at 11 44 27 PM" src="https://user-images.githubusercontent.com/95303422/152726229-397e0f84-0554-4c20-8ab1-b420fd8be032.png">
