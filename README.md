# Ex.08 Customer Registration Form
## AIM
  To write a program in JavaScript for creating a customer registration form for an agro-based company.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define different functions to register the customers based on their qualifications.

### STEP-3
  Using form elements to create the registration details of a customer.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```
<!DOCTYPE html>
<html>
<head>
  <title>Agro-based Industry Registration Form</title>
  <script>
    function clearForm() {
      document.getElementById("registrationForm").reset();
    }
  </script>
</head>
<body>
  <h2>Agro-based Industry Registration Form</h2>
  <form id="registrationForm">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required><br><br>
    
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required><br><br>
    
    <label for="phone">Phone:</label>
    <input type="tel" id="phone" name="phone" pattern="[0-9]{10}" required><br><br>
    
    <label for="address">Address:</label><br>
    <textarea id="address" name="address" rows="4" cols="50" required></textarea><br><br>
    
    <label for="industry">Type of Industry:</label>
    <select id="Crop" name="crop" required>
      <option value="">Select Crop Type</option>
      <option value="Rice">Rice</option>
      <option value="Wheat">Wheat</option>
      <option value="Raagi">Raagi</option>
      <option value="Other">Other</option>
    </select><br><br>
    
    
    <input type="submit" value="Register">
    <input type="button" value="Clear All" onclick="clearForm()">
  </form>
</body>
</html>
```

## OUTPUT
![Exp 8 01](https://github.com/SaiganeshVelu/EX08_Web-Design/assets/127816325/6668a509-355f-4e39-9182-fe76898ebab7)
![Exp 8 02](https://github.com/SaiganeshVelu/EX08_Web-Design/assets/127816325/b531f181-0bdc-4e4a-a923-87f2118c3b7e)



## RESULT
  Customer registration form using JavaScript is created successfully.
