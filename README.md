<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Information Form
        </title>
        <style>
            body{
                font-family: Arial, sans-serif;
                background-color: #f4f4f4;
                margin: 0;
                padding: 0;
                display: flex;
                justify-content: center;
                align-items: center;
                height: 100vh;
            }
            .form-container{
                background-color: #fff;
                padding: 20px;
                border-radius: 8px;
                box-shadow: 0 0 10px rgba(0,0,0,0.1);
                width: 300px;
            }
            .form-container h2 {
                margin-bottom: 20px;
                font-size: 24px;
                color:#333;
            }
            .form-group{
                margin-bottom: 15px;
            }
            .form-group label{
                display: block;
                margin-bottom: 5px;
                color:#555;
            }
            .form-group input{
                width: 100%;
                padding: 8px;
                border: 1px solid #ccc;
                border-radius: 4px;
                font-size: 14px;
            }
            .form-group input:focus{
                border-color: #007bff;
                outline: none;
            }
            .form-group button{
                width: 100%;
                padding: 10px;
                background-color: #007bff;
                border: none;
                border-radius: 4px;
                color: #fff;
                font-size: 16px;
                cursor: pointer;
            }
            .form-group button:hover{
                background-color: #0056b3;
            }
        </style>
    </head>
    <body>
        <div class="form-container">
            <h2>Personal Information</h2>
            <form action="#" method="post">
                <div class="form-group">
                    <label for="firstName">First Name:</label>
                    <input type="text" id="firstName" name="firstName" required>
                </div>
                <div class="form-group">
                    <label for="lastName">Last Name:</label>
                    <input type="text" id="lastName" name="lastName" required>
                </div>
                <div class="form-group">
                    <label for="fieldStudy">Field of Study:</label>
                    <input type="text" id="fieldStudy" name="fieldStudy" required>
                </div>
                <div class="form-group">
                    <label for="DOB">Date of Birth:</label>
                    <input type="date" id="DOB" name="DOB" required>
                </div>
                <div class="form-group">
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <dive class="form-group">
                    <label for="phone">Phone Number:</label>
                    <input type="tel" id="phone" name="phone" required>
                </dive>
                <dive class="form-group">
                    <label for="matricule">Matricule:</label>
                    <input type="number" id="matricule" name="matricule" required>
                </dive>
                <div class="form-group">
                    <label for="comment">Other Comments:</label>
                    <input type="text" id="comment" name="comment">
                </div>
                <div class="form-group">
                    <button type="submit">Submit</button>
                </div>
            </form>
        </div>
    </body>
</html>