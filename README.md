# Ex03 To-Do List using JavaScript

## AIM
To create a To-do Application with all features using JavaScript.

## ALGORITHM
### STEP 1
Build the HTML structure (index.html).

### STEP 2
Style the App (style.css).

### STEP 3
Plan the features the To-Do App should have.

### STEP 4
Create a To-do application using Javascript.

### STEP 5
Add functionalities.

### STEP 6
Test the App.

### STEP 7
Open the HTML file in a browser to check layout and functionality.

### STEP 8
Fix styling issues and refine content placement.

### STEP 9
Deploy the website.

### STEP 10
Upload to GitHub Pages for free hosting.

## PROGRAM
```

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>To Do List</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:linear-gradient(135deg,#4facfe,#e5dddd);
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
}

.container{
    background:white;
    width:400px;
    padding:25px;
    border-radius:15px;
    box-shadow:0 10px 25px rgba(0,0,0,0.2);
}

h1{
    text-align:center;
    color:#333;
    margin-bottom:20px;
}

input{
    width:100%;
    padding:12px;
    border:2px solid #ddd;
    border-radius:8px;
    margin-bottom:15px;
    outline:none;
}

button{
    width:100%;
    padding:12px;
    background:#12e0ef;
    color:white;
    border:none;
    border-radius:8px;
    cursor:pointer;
    font-size:16px;
}

button:hover{
    background:#06b2e1;
}

ul{
    list-style:none;
    margin-top:20px;
}

li{
    background:#f3f3f3;
    padding:10px;
    margin-bottom:10px;
    border-radius:8px;
}

footer{
    margin-top:20px;
    text-align:center;
    color:#666;
    font-size:14px;
}
</style>
</head>

<body>

<div class="container">
    <h1>To Do List</h1>

    <input type="text" placeholder="Enter your task">
    <button>Add Task</button>

    <ul>
        <li>Complete Assignment</li>
        <li>Study HTML & CSS</li>
        <li>Practice Coding</li>
    </ul>

    <footer>
        MIRTYUNJAY S
        212224040190
    </footer>
</div>

</body>
</html>
```
## OUTPUT

<img width="1920" height="1200" alt="Screenshot 2026-09-17 083116" src="https://github.com/user-attachments/assets/8cbec2cf-5557-49ef-9ed2-181cd721ffe5" />

## RESULT
The program for creating To-do list using JavaScript is executed successfully.
