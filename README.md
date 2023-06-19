# Ex.06 JavaScript - Student Result
## AIM
  To write a program in JavaScript for displaying the result of a student.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to generate the result grade.

### STEP-3
  Using branching statements analyze the grade achieved.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```
<html>
<head>
<title>JavaScript program to display the result of a student</title>
<script type="text/javascript">
function student()
{
    var mark1, mark2, mark3, mark4, mark5, total, percentage;
    mark1 = parseInt(prompt("Enter Subject-1 Marks"));
    mark2 = parseInt(prompt("Enter Subject 2 Marks"));
    mark3 = parseInt(prompt("Enter Subject 3 Marks"));
    mark4 = parseInt(prompt("Enter Subject 4 Marks"));
    mark5 = parseInt(prompt("Enter Subject 5 Marks"));
    total = mark1 + mark2 + mark3 + mark4 + mark5;
    percentage = total / 5;

    if (percentage >= 91 && percentage <= 100)
    {
        alert("O Grade");
    }
    else if (percentage >= 81 && percentage <= 90)
    {
        alert("A+ Grade");
    }
    else if (percentage >= 71 && percentage <= 80)
    {
        alert("A Grade");
    }
    else if (percentage >= 61 && percentage <= 70)
    {
        alert("B+ Grade");
    }
    else if (percentage >= 51 && percentage <= 60)
    {
        alert("B Grade"); 
    }
    else
    {
        alert("RA Grade");
    }
}
</script>
</head>
<body>
<h1 onclick="student()">
Click me to Find Grade Result of a Student
</h1>
</body>
</html>
```


## OUTPUT
![image](https://github.com/sharaneeya/Ex06_Web-Design/assets/119670918/5720a0b9-abbc-4276-bf95-5a47c81377d5)
![image](https://github.com/sharaneeya/Ex06_Web-Design/assets/119670918/287ac4cf-a816-4a51-9078-1ad9a6e3c36b)
![image](https://github.com/sharaneeya/Ex06_Web-Design/assets/119670918/53fabe77-5578-4a2b-8cdc-a2d30978c0eb)
![image](https://github.com/sharaneeya/Ex06_Web-Design/assets/119670918/93670765-fe4f-45e6-b0a7-95e0e38b6c62)
![image](https://github.com/sharaneeya/Ex06_Web-Design/assets/119670918/1a29e389-415b-42a9-9ff4-e18835bd485f)
![image](https://github.com/sharaneeya/Ex06_Web-Design/assets/119670918/8b7da32a-4d97-4393-9d66-55248fdee216)





## RESULT
  Student result using JavaScript is created successfully.
