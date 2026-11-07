<html>
    <head>
        <title>regester student</title>
        <body>
            <h1><b>Studen regester form</b></h1>
            
            <form action="" method="post">
                <fieldset>
                    <legend> Personal Information

                    </legend>
                    <label for="name">Full name

                    </label>
                    <input type="name" id="name"
                    name="name"
                    placeholder="Enter you full name" 
                    required>
                    <br><br>
                    <label for="email"> Your email</label>
                    <input type="email" id="email"
                    placeholder="please enter your email" required> 
                    <br><br>
                    <label for="password">your passwrd</label>
                    <input type="password" id="password"
                    placeholder="Please enter your password" required>
                    <br><br>
                    <label for="dob">Date of birth</label>
                    <input type="date" id="dob" name="dob">
                    <br><br>
                    <label for="Gender">Gender</label>
                    <input type="radio" name="gender">male
                    <input type="radio" name="gender">female
                    <br><br>
                    <label for="phone">phone</label>
                    <input type="tel" id="phone" name="phone">
                    
                </fieldset>
                    
                
                        <br><br>
                    <legend>Academicc Information</legend>
                    <label for="Studentid">Student id</label>
                    <input type="text" id="studentid" name="studentid">
                    <br><br>
                    <label for="major">Major</label>
                   <select name="major" id="major">
                    <option value="">Select Major</option>
                    <option value="IT">Information Teachnology</option>
                    <option value="CS">Computer Science</option>
                    <option value="SE">Software Engineering</option>
                    <option value="DS">Data Science</option>

                   </select>
                   <br><br>
                   <label>Skills:</label>
                   <input type="checkbox" name="skills" value="HTML">html
                
                   <input type="checkbox" name="skills" value="css"> css
                   <input type="checkbox" name="skills" value="javascript">Java
                   <br><br>
                   <label for="photo">Upload Photo</label>
                   <input type="file" id="phone" name="phone">
                    <br>
                </fieldset>
                <fieldset>
                    <legend> Additional Information</legend>
                   <label for="Address">Address:</label>
                   <br>
                   <textarea name="address" id="address" rows="4" cols="40"></textarea>
                   <br><br>
                   <label for="color">Favorite color</label>
                   <input type="color" id="color" name="color">
                </fieldset>
                    <br>
                    <input type="checkbox" name="agree" required>
                    I agree to the registration terms.
                    <br><br>
                    <input type="submit" value="Register">
                    <input type="reset" value="clear form">

                    
                
            </form>
        </body>
    </head>
</html>
