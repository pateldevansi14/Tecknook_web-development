# Tecknook_web-development
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Assignment 1</title>
</head>
<body>
    <div align="center">
    <div class="container">
        <div class="box">
            <h3>Register Now</h3>
            <div>
                <form action="">

                    <label class="lebels">Name:</label><br>
                    <input class="feilds" type="text" name="Name" required><br>

                    <label class="lebels">Email:</label><br>
                    <input class="feilds" type="email" name="Email" required><br>

                    <label class="lebels">Password:</label><br>
                    <input class="feilds" type="password" name="Password" required><br>

                    <label class="lebels">Phone:</label><br>
                    <input class="feilds" type="number" name="Phone" required><br>

                    <label class="lebels">Date of birth:</label><br>
                    <input class="feilds" type="date" name="DateOfBirth"><br>

                    <select class="feilds">
                        <option style="font-weight:bold ;">select your city</option>

                        <option>Delhi</option>

                        <option>Kolkata</option>

                        <option>Bangalore</option>

                        <option>Bhubaneswar</option>
                    </select>

                    <fieldset>
                        <legend id="gender">choose your gender</legend>

                        <input type="radio" name="gender">male<br />

                        <input type="radio" name="gender">female<br />

                        <input type="radio" name="gender">other<br />
                    </fieldset>


                    <input id="submitbtn" type="submit" class="feilds" submit><br>
                    <input id="resetbtn" type="reset" class="feilds" reset>
                </form>
            </div>
        </div>
    </div>
</div>
</body>
</html>
