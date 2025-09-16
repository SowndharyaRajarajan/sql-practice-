create database task15;
use task15;

-- Task1
-- table marks_det
-- For each subject related to finance, cost,corporate the marks should be greaterthan 50, after that,
-- The average check should be  
/*90-A,
80-B, 
70-C, 
Otherwise D grade
alot grades like that and also print,

If any one of the subject mark is below 50,  don't check average print
"no grade"  */ 

select * from marks_info;

select *,
case when finance > 50 and cost> 50 and corporate > 50 then "pass"
else "no grade"
end as grades,
case
when (finance+cost+corporate)/3 >= 90 then "A"
when (finance+cost+corporate)/3 >= 80 then "B"
when (finance+cost+corporate)/3 >= 70 then "C"
else "D"
end as avg  
from marks_info;


-- Task 2
-- table matrix (sheet 1)
/*income >6000 then "A grade"
income >5000 then "B grade"
income >4000 then "c grade"
income >1500 then "d grade"
other wise "no grade"*/ 

SELECT m.*,
CASE
WHEN income > 6000 THEN 'A Grade'
WHEN income > 5000 THEN 'B Grade'
WHEN income > 4000 THEN 'C Grade'
WHEN income > 1500 THEN 'D Grade'
ELSE 'No Grade'
END AS Income_Grade
FROM matrix m; 



use task15;

-- Task 3
/*1. Create a result field using function (Check Average only)
Average >35 then "pass"
other wise "fail"*/ 
select *,
case 
when average > 35 then "pass" 
else 'fail' 
end as result
from logicfunctions;


/*2. create a Ind_result_field using function (check each subjects)
  Each subjects >35 then "pass"
 other wise "fail" */

SELECT *,
CASE
WHEN tamil > 35 
AND english > 35 
AND accounts > 35 
AND commerce > 35 
AND economics > 35
THEN 'Pass'
ELSE 'Fail'
END AS Ind_Result
FROM logicfunctions l;

