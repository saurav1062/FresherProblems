# Coding Problems

# Instructions:
1. Code in any language.
2. Try to reduce time complexity using better algorithm or an efficient data structure.
3. Attempt at least one question (Candidates with more solutions will be given preference).

# Questions
1. The “King Number” is a prime number that is the factor of the most numbers in a given list. Can you find the “King Number”  in each list? For example, for the list {2, 3, 5, 6, 9, 14, 20}, the answer is 2, since it's a factor of 2, 6, 14 and 20, while 3 is only a factor of 3, 6 and 9. 

2. For a newly opened hospital, opened on 1st, you have data of entry and exit date of patients between date 1st to 10th.
You have to find the date on which there are most number of patients in the hospital.  
For example, you have array of entry and exit date of patients(entry, exit) like [(1,3),(2,5),(4,8),(9,10),(5,6),(4,7),(7,10)]
then your output will be date 5 as this date has 4 number of patients.

3. On election day, a voting machine writes data in the form (voter_id, candidate_id). Write a program that takes data as array of (voter_id, candidate_id) and returns the top 3 candidates at any given time. If you find a voter voting more than once, report this as fraud and dont count this voter's any vote and print these voters id as fraud candidates.   
Example: For data: [(1,2), (2,3),(3,2), (1,3), (4,3), (5,3),(6,2), (7,3), (8,2), (9,3),(10,1), (11,4), (12,4)] , output should be,   
Top Three candidates: 3, 2, 4    
Fraud candiates: 1
