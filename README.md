# School_District_Analysis

## Overview of the PyCity Schools District Analysis

The purpose of this analyis is to address the concerns of the PyCity School Board. They have recently been made aware of potential academic dishonesty at Thomas High School. The math and reading scores of the entire ninth grade are in question. The School Board would like to uphold testing standards. So, a plan is formed to remove the Thomas High School ninth grade math and reading scores and replace them with "NaN" values, which will exclude these scores from the data set. When that is complete, the entire School District Analysis will be run again, excluding the Thomas High School ninth grade math and reading scores.

## Results

The District Summary does not appear to be extremely affected by the removal of the Thomas High School Ninth Grade reading and math scores. The pictures below show a slight drop in all scores and percentages:

Old District Summary
<img width="906" alt="Original District Summary" src="https://user-images.githubusercontent.com/106849689/178114384-2cac4a5f-f962-4831-82ac-0e83b3b46a10.png">

New District Summary
<img width="906" alt="New District Summary" src="https://user-images.githubusercontent.com/106849689/178114405-5d38e567-68af-4163-b171-b2fcd65112c0.png">

The School Summary for Thomas High School is affected in different ways. The average math score drops by only about .01%. The average reading score increase by approximately .05%. In contrast, the "% Passing Math" value for Thomas High School drops by about 26%. The "% Passing Reading" score decreased by approximately 28%. The %Overall Passing also decreased by about 26% as shown below:

Old Per School Summary
<img width="1081" alt="Original Per School Summary" src="https://user-images.githubusercontent.com/106849689/178114594-35b755fc-7eaf-4a0f-8fb7-a81bde53ed8b.png">

New Per School Summary
<img width="1081" alt="New Per School Summary" src="https://user-images.githubusercontent.com/106849689/178114613-3e3baa59-f284-457f-9831-5994f567c4c4.png">

Replacing the ninth graders' math and reading scores actually does not affect the rank of Thomas High School amongst the other schools, as seen below:

New Top 5 Schools
<img width="1125" alt="New Top 5" src="https://user-images.githubusercontent.com/106849689/178159358-b244cfd3-b28c-4f35-860b-c90833f95162.png">

Replacing the Thomas High School ninth grade math and reading scores with "NaN" values, of coures, affects the ninth grade math and reading scores by there not being an actual calculation. The other grades values were not affected. Please see graphics below:

Old Math Scores by Grade

<img width="406" alt="Old Math Scores by Grade" src="https://user-images.githubusercontent.com/106849689/178160659-92cf68f0-f368-4455-95b2-a508cf206f01.png">

Old Reading Scores by Grade

<img width="406" alt="Old Reading Scores by Grade" src="https://user-images.githubusercontent.com/106849689/178160742-8f87473f-9c72-46d4-a2a6-671d346bbd39.png">

New Math Scores by Grade

<img width="406" alt="New Math Scores by Grade" src="https://user-images.githubusercontent.com/106849689/178160732-d01a45fa-f42c-4da9-9025-14ebe2eae0d3.png">

New Reading Scores by Grade

<img width="406" alt="New Reading Scores by Grade" src="https://user-images.githubusercontent.com/106849689/178160751-27f52cf7-da98-4a45-9977-3142a4a7dcd2.png">

Replacing the Thomas High School ninth grade math and reading scores does not seem to affect "Scores by School Spending", as seen below:

Old Scores by School Spending
<img width="915" alt="Old Scores by School Spending" src="https://user-images.githubusercontent.com/106849689/178160834-df6e80fb-855f-4cd7-9e44-a26e0c27cea4.png">

New Scores by School Spending
<img width="915" alt="New Scores by School Spending" src="https://user-images.githubusercontent.com/106849689/178160844-dfc03868-0c84-4018-966e-16ed52e4a516.png">

Replacing the Thomas High School ninth grade math and reading scores also does not seem to affect the  "Scores by School Size":

Old Scores by School Size
<img width="868" alt="Old Scores by School Size" src="https://user-images.githubusercontent.com/106849689/178160860-38140819-9d51-4264-bf70-8436ed8bae39.png">

New Scores by School Size
<img width="868" alt="New Scores by School Size" src="https://user-images.githubusercontent.com/106849689/178160868-d1154824-cca3-4a02-9360-002b9e91800c.png">

Replacing the Thomas High School ninth grade math and reading scores does not have an affect on "Scores by School Type":

Old Scores by School Type
<img width="826" alt="Old Scores by School Type" src="https://user-images.githubusercontent.com/106849689/178160886-7bfe5642-e800-4475-be4c-6711007868a4.png">

New Scores by School Type
<img width="826" alt="New Scores by School Type" src="https://user-images.githubusercontent.com/106849689/178160899-30543742-b30e-4cd6-a723-1649cdc1b027.png">

## Summary: 

Four notable changes in the Py City Schools District Analysis, after removing the Thomas High School ninth grade
math and reading scores are:

1. A drop in both math and reading scores listed in the District Summary.
2. A drop in both % passing reading and math as listed in the District Summary.
2. The "% Passing Math" at Thomas High School drops about 26%.
3. The "% Passing Reading" at Thomas High School drops about 28%.
