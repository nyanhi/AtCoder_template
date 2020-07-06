# AtCoder_template
Small script to generate template files for AtCoder ABC contests.


## How to use
Run the template.py in a directory where you would like to create working files for AtCoder ABC contest.
Then input 3 digit number for the contest (e.g. if you will be working on ABC174, input 174).

>
    $python -m template.py
    input number of ABC contest(e.g. 174)
    *174*


## Directory Structure
The script will generate directories like below:

![Directory Structure](https://github.com/nyanhi/AtCoder_template/blob/ABC/images/directory_tree.png)


## Description for generate files

### main.py
write your answer under resolve()
This enables you to do unittest with test_*.py file with a Chrome Extension [AtCoder Unit Test](https://github.com/YujiSoftware/ac-unit-test)

### test_*.py
Copy-and-paste test cases as AtCoder Unit Test instructs.