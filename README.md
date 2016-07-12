# Company-Shifting-Software-employee-
Zulu, a software company is planning to expand from its headquarters to a new office space. It asks its employees to opt-in if they would wish to shift to the new office location. You are a software engineer working at Zulu and you have been tasked to make this split. So far, you already have the data split into two parts – the records of the employees at Zulu headquarters, and the employee IDs of workers who have opted to shift. Your job is to return the updated employee records for the headquarters and the new office. There is one important constraint: You can only move at the most k employees from the headquarters to the new office space (where 0 <= k <= n/2, and n is the total employees before the split at Zulu’s headquarters). If there are more than k employees who have opted to shift to the new office space, you will prioritize by tenure, and then by their salary (more tenure and higher salary gets preference).

##Sample Input

3

123002, Xia Ming, 4, 100000 

134234, Tim Lee, 5, 99000 

145345, Ashish Kumar, 3, 120000 

2 1

123002

134234

##Sample Output

HQ

123002

145345

NEW

134234


## Explanation: 
m=2, and k=1. Two employees have applied to shift to the new office. However, only one employee can be shifted to the new office. Xia Ming and Tim Lee applied for shifting to the new office. Since Tim has more experience (5 years) as compared to Xia (4 years), Tim is preferred.

