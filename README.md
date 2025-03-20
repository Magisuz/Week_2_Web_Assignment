# Week_2_Web_Assignment
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta name="description" content="My First Web Assignment">
        <meta name="author" content="Margaret">
        <title>Sign Up Form</title>
    </head>
    <body>
        <header>
        <h3>Sign UP</h3>
        </header>
        <main>
            <img src="join.jpg" alt="Join Us" width="300" height="200">
        <form>
        <fieldset width="100" height="100">
            <legend>Registration Form</legend>
            <label for="fname">First Name:&ensp;&ensp;</label>
            <input type="text" id="fname" name="fname" placeholder="Enter Firstname" required>
            <label for="lname">&ensp;&ensp;Last Name:&ensp;&ensp;</label>
            <input type="text" id="lname" name="lname" placeholder="Enter Lastname" required><br><br>
            <label for="gender">Gender:&ensp;&ensp;&ensp;&ensp;</label>
            <input type="radio" id="gender" name="gender" value="male"> Male
            <input type="radio" id="gender" name="gender" value="female"> Female<br><br>
            <label for="email">Email:&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;</label>
            <input type="text" name="useremail" placeholder="Enter Email"required><br><br>
            <label for="country">Country:&ensp;&ensp;&ensp;&ensp;</label>
            <select name="country" id="country">
                    <option>--Select Country--</option>
                    <option value="Kenya">Kenya</option>
                    <option value="Nigeria">Nigeria</option>
                    <option value="Tanzania">Tanzania</option>
                    <option value="South Africa">South Africa</option>
            </select><br><br>
            <label for="date">Date of Birth:</label>
            <input type="date" id="birthday" name="birthday" required><br><br>
            <label for="hobbies">Hobbies:</label>
                <input type="checkbox" name="hobbies" value="sports"> Sports
                <input type="checkbox" name="hobbies" value="music"> Music
                <input type="checkbox" name="hobbies" value="art"> Art
                <input type="checkbox" name="hobbies" value="travel"> Travel<br><br>
            <label for="Password">Password:&ensp;&ensp;&ensp;</label>
            <input type="text" id="password" name="password" placeholder="Enter Password"required>
            <label for="Password">&ensp;&ensp;Re-Enter Password:&ensp;&ensp;</label>
            <input type="text" id="password" name="password" placeholder="Re-Enter Password"required><br><br>
            <input type="submit" value="Submit">
            <br>
        </fieldset>
        </form>
            <br><br>
        <table border="1">
                <caption>Contact Details</caption>
                <thead>
                    <tr>
                        <th>Name</th>
                        <th>Address</th>
                        <th>Mobile</th>
                        <th>Email</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Esperanza</td> 
                        <td>Donholm</td>
                        <td>12345</td>
                        <td>aranza@outmail.com</td>
                    </tr>
                    <tr>
                        <td>Leslie</td> 
                        <td>Kigali</td>
                        <td>123456</td>
                        <td>leslie@outmail.com</td>
                    </tr>
                    <tr>
                        <td>Thando</td> 
                        <td>SA</td>
                        <td>123456</td>
                        <td>thando@outmail.com</td>
                    </tr>
                    <tr>
                        <td>OgaObina</td> 
                        <td>Kalaba</td>
                        <td>1234567</td>
                        <td>ogaobina@outmail.com</td>
                    </tr>
                    <tr>
                        <td>Lakshmi</td> 
                        <td>India</td>
                        <td>12345678</td>
                        <td>lakshmi@outmail.com</td>
                    </tr>
                </tbody>
        </table>
        <br><br>
        <h3>Our Signed Up Users</h3>
            <ol type="i">
                <li>Esperanza</li>
                <li>Leslie</li>
                <li>Thando</li>
                <li>OgaObina</li>
                <li>Lakshmi</li>
            </ol>
            <br><br>
            <audio controls>
                <source src="fragrance.mp3" type="audio/ogg">
                <source src = "fragrance.mp3" type="audio/mpeg">
            Your browser doesn't support the audio element.
        </audio>
        <br><br>
            <video controls width ="300" height = "300">
                <source src="FRAGRANCE - Michelle Chinonso.mp4" type="video/mp4">
                <source src="FRAGRANCE - Michelle Chinonso.ogg" type="video/ogg">
            Your browser does not support the video tag.
            </video>
       |<br><br>

        For more Information you can search more of Our Users on:
        <a href="https:google.com">Google</a> <br>
        </main>
        <br><br><br>
        <footer>
            Contacts<br>
            Email:oursers@outbox.com<br>
            Phone Number: 123456789<br>
            Social Media site: <a href="https:facebook.com">Visit Our Facebook Page</a>
            <p> &copy;2025 Users. MyWebsite. All rights reserved.</p>
        </footer>
    </body>
</html>
