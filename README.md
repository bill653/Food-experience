<!DOCTYPE html>
<html>
<head>
    <title>Food Experience Survey</title>
</head>

<body bgcolor="lightyellow">

    <center>
        <h2><b>🍽️ FOOD EXPERIENCE SURVEY 🍽️</b></h2>
        <p><i>Please fill in the form below</i></p>
    </center>

    <form method="POST" action="location and file name">

        <!-- Hidden Field -->
        <input type="hidden" name="formid" value="F001">

        <hr>

        <!-- TEXT FIELD -->
        <p>
            <b>1. Enter Your Name:</b><br>
            <input type="text" name="name" size="30" maxlength="25">
        </p>

        <!-- PASSWORD FIELD -->
        <p>
            <b>2. Enter Your Password:</b><br>
            <input type="password" name="password" size="30">
        </p>

        <hr>

        <!-- RADIO BUTTON -->
        <p>
            <b>3. Are you a vegetarian or non-vegetarian?</b><br>
            <input type="radio" name="food" value="Vegetarian"> Vegetarian<br>
            <input type="radio" name="food" value="Non-Vegetarian"> Non-Vegetarian
        </p>

        <hr>

        <!-- CHECKBOX -->
        <p>
            <b>4. What do you think about our food?</b><br>
            <input type="checkbox" name="taste" value="Good"> Food is Good<br>
            <input type="checkbox" name="service" value="Nice" checked> Service is Nice<br>
            <input type="checkbox" name="environment" value="Clean"> Environment is Clean<br>
        </p>

        <hr>

        <!-- MENU FIELD -->
        <p>
            <b>5. What is your profession?</b><br>
            <select name="profession" size="4">
                <option>Teaching</option>
                <option>Research</option>
                <option>Medicine</option>
                <option>Engineering</option>
                <option>Clerical</option>
                <option>Business</option>
                <option>Other</option>
            </select>
        </p>

        <hr>

        <!-- MULTIPLE MENU (Extra creativity but still Lesson 11 compliant) -->
        <p>
            <b>6. Select your favourite foods:</b><br>
            <select name="foods" multiple size="4">
                <option>Biriani</option>
                <option selected>Pilau</option>
                <option>Seafood</option>
                <option>Vegetables</option>
            </select>
        </p>

        <hr>

        <!-- TEXTAREA -->
        <p>
            <b>7. Type your comments on our food items:</b><br>
            <textarea name="comments" rows="5" cols="40">
Please enter your message here!
            </textarea>
        </p>

        <hr>

        <!-- SUBMIT & RESET -->
        <p>
            <input type="submit" value="Send Information" name="submit">
            <input type="reset" value="Clear Form" name="reset">
        </p>

    </form>

    <center>
        <p><b><i>Thank you for your feedback!</i></b></p>
    </center>

</body>
</html>
