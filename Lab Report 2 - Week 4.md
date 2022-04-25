# Lab Report 2 - Week 4

* ## First code changes:

1.  a screenshot of the code change differn from Github

![image1](report201.png)

2. Link to the test file for a failure-inducing input that prompted you to make that change
 
   [test file 1](https://github.com/Eunggseo/markdown-parser/blob/main/test-file.md)

3.  the symptom

   ![image2](labreport202.png)

4. The __symptom__ is there is an infinite loop when there is an empty line(__failure-inducing input__) in test-file.md

   The __bug__ is that it prints out the “link” even when the link is not a valid link.

   If there is no link provided, the code should return null. 


