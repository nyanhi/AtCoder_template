# AtCoder_template
Small script to generate template files for AtCoder ABC contests

## How to use
Run the template.py in a directory where you would like to create working files for AtCoder ABC contest.
Then input 3 digit number for the contest (e.g. if you will be working on ABC174, input 174).
The script will generate directories like below:

ABC174
├── A
│   ├── main.py
│   └── test_A.py
├── B
│   ├── main.py
│   └── test_B.py
├── C
│   ├── main.py
│   └── test_C.py
├── D
│   ├── main.py
│   └── test_D.py
├── E
│   ├── main.py
│   └── test_E.py
└── F
    ├── main.py
    └── test_F.py

## generate file descriptions
### main.py
write your answer under resolve(). 
This enables you to do unittest with test_*.py file with a Chrome Extension AtCoder Unit Test 
https://github.com/YujiSoftware/ac-unit-test

### test_*.py
Copy-and-paste test cases as AtCoder Unit Test instructs 