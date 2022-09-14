
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Register</title>
</head>
<body>
    <link rel="stylesheet" href="register.css">
    <script src="form.js" defer></script>
    <h1 align="center">Register</h1>
    <div class="box">
        <form class="form" id="form">
            <table>
                <tr>
                    <td><label for="name">Name:</label></td>
                <td>
                <input required type="text" class="input" name="name" id="name" 
                placeholder="Enter your Name">
                </td>
                </tr>

                <tr>
                    <td><label for="email">Email:</label></td>
                <td>
                <input required type="email" class="input" name="email" id="email" 
                placeholder="Enter your Email address">
                </td>
                </tr>

                <tr>
                    <td><label for="name">Password:</label></td>
                <td>
                <input required type="password" class="input" name="password" id="password" 
                placeholder="Enter the Password">
                </td>
                </tr>
                <tr>
                    <td><label for="dob">Date of Birth:</label></td>
                <td>
                <input required type="date" class="input" name="dob" id="dob" >
                </td>
                </tr>
                <tr>
                    <td>
                        <br>
                        <input type="checkbox" name="agree" id="agree">
                        <label for="checkbox">Accept Terms & Conditions</label>
                    </td>
                </tr>

                <tr>
                    <td>
                        <button class="button" type="submit">Submit</button>
                    </td>
                </tr>
            </table>
        </form>
    </div>

    <div class="entry">
        <h2 class="subheading">Entries</h2>
        <div id="tableDiv"></div>
    </div>
</body>
</html>

