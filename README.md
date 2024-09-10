<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Open Recruitment</title>
    <link rel="stylesheet" href="style.css">
    
</head>
<body>
   
</body>

<body>
    <form action="results.html" method="get">
        <fieldset>
            <legend> BIODATA </legend>
    <table>
        <tr><div>
            <td><label for="Name"> Name </label></td>
            <td><input type="text" name="name" id="Name" placeholder="Username" required></td>
        </div></tr>
        <tr><div>
            <td><label for="Password"> Password </label></td>
            <td><input type="password" name="Password" id="Password" required></td>
        </div></tr>
        <tr><div>
            <td><label for="Email"> Email </label></td>
            <td><input type="Email" name="Email" id="Email" required></td>
        </tr></div>
        <tr><div>
            <td><label for="Age"> Age </label></td>
            <td><input type="number" name="age" id="Age" required min="15" max="18" step="1"></td>
        </div></tr>
        <tr><div>
            <td><label for="date"> Birthdate </label></td>
            <td><input type="date" name="date" id="date" required></td>
        </div></tr>
        <tr><div>
            <td><label for="Gender"> Gender </label></td>
            <td><input type="radio" name="jk" value="Men" > Man </td>

            <td><input type="radio" name="jk" value="Woman" > Woman </td>
         </div></tr>
        
        <tr><div>
            <td><label for="VoiceType"> Voice Type </label></td>
            <td><select name="VoiceType" id="VoiceType">
                <option value="Sopran"> Sopran </option>
                <option value="Alto"> Alto </option>
                <option value="Tenor"> Tenor </option>
                <option value="Bass"> Bass </option>
            </select></td>  
        </div></tr>

        <tr><div>
            <td>Favorite Music</td>
            <div><td><label for="Folksong"> Folksong </label></td>
            <td><input type="checkbox" name="Folksong" value="Folksong"></div></td>

            <div><td><label for="Baroque"> Baroque </label></td>
            <td><input type="checkbox" name="Baroque" value="Baroque"></div></td>
                
            <div><td><label for="Others"> Others </label></td>
            <td><input type="checkbox" name="Others" value="Others"></td></div>
         </div></tr>

        <tr><div>
            <td><label for="Address"> Address </label></td>
            <td><textarea id="Address" name="Address" placeholder="your address"></textarea>
         </div></tr>

        <tr>    
            <td><button type="reset"> Reset </button></td>
            <td><button type="submit"> Submit </button></td>
        </tr>
    </table>
    </fieldset>
    </form>
</body>
</html>
