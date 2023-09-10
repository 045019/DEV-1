
1. Solve System of Linear Equations
1.1. Solve for x, y & z where: 
Eq1 : x + y + z = 2 | Eq2 : 6x - 4y + 5z = 31 | Eq3: 5x + 2y + 2z = 13 

2. Create & Update Dictionary
2.1. Create a Employee Dictionary 'emp_dict' with following Information: 
Name	Education	Gender
ABC	Graduate	Male
DEF	Postgraduate	Female
GHI	Postgraduate	Male
JKL	Graduate	Other
MNO	Graduate	Female
PQR	Postgraduate	Female
STU	Graduate	Male

2.2. Update the Employee Dictionary 'emp_dict' with following Information: 
Age
22
27
26
23
24
30
21

3. Create & Update Dataframe
3.1. Create a Dataframe 'emp_df' from the Dictionary 'emp_dict' 
3.2. Update the Dataframe 'emp_df' with the following Information: 
Salary_Lakhs	Bonus%
6	12.50
15	8.75
20	6.25
5	10.20
10	13.60
18	11.40
12	9.80

3.3. Update the Dataframe ‘emp_df’ with the following information: 
Name	Education	Gender	Age	Salary_Lakhs	Bonus%
VWX	Postgraduate	Male	35	14	5.50
YZA	Graduate	Female	28	7	7.75
BCD	Postgraduate	Other	32	8	14.80

3.4. Create a Column ‘Gross_Salary_Lakhs’ with the following information: 
Gross_Salary_Lakhs = Salary_Lakhs * (1 + Bonus%)

4. Subset Dataframes
4.1. Create a Subset ‘emp_df_ss’ from ‘emp_df’ with the following Variables: {Name, Age, Gross_Salary_Lakhs} 

5. Sort Dataframes
5.1. Create a Copy of 'emp_df' Named as 'emp_df_age_sorted' and Sort {Highest to Lowest} by 'Age' 
5.2. Create a Copy of 'emp_df' Named as 'emp_df_age_salary_sorted' and Sort: First by 'Age' {Lowest to Highest}, Second by 'Gross_Salary_Lakhs' {Highest to Lowest} [05 marks]

6. Filter Dataframe
6.1. Create a Dataframe ‘emp_df_filtered’ to Filter ‘emp_df’ using the following Information: 'Age' >= 25 & 'Gender' = 'Female' [05 marks]
6.2. Create 2 Subsets: ‘emp_df_grad’ & ‘emp_df_postgrad’ from ‘emp_df’ containing Information of Employees having ‘Education’ as ‘Graduate’ & ‘Postgraduate’, respectively [05 marks]

7. Merge Dataframe
7.1. Create a Dataframe ‘emp_df_merged’ to Inner Merge ‘emp_df_grad’ having only following Variables {Name, Gender, Age} with ‘emp_df_postgrad’ having only following Variables {Name, Gender, Gross_Salary_Lakhs} on ‘Gender’ [05 marks]

8. Group Dataframe
8.1. Group ‘emp_df’ to Create a Table ‘emp_df_gen_edu’ using ‘Gender’ & ‘Education’ having Count of Employees 
8.2. Group ‘emp_df’ to Create a Table ‘emp_df_gen_age_sal’ using ‘Gender’ with Average of Variables {Age & Gross_Salary_Lakhs} [05 marks]

9. Create Panel Dataframe from Cross-Sectional Dataframe
9.1. From the following Cross-Sectional Dataframe 'df_cross_section': 
Company	2023	2024
ZYX	123	321
WVU	456	654
TSR	789	987
Create the following Panel Dataframe 'df_panel':
Company	Year	Profit
TSR	2023	789
TSR	2024	987
WVU	2023	456
WVU	2024	654
ZYX	2023	123
ZYX	2024	321

