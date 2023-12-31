# task3
#nexel


<!DOCTYPE html>
<html lang="en">
<head>
	<link rel="stylesheet" href="deep.css">
	<script src="app.js" defer></script>
    <title>
        Form validation using HTML and JavaScript
    </title>
	
</head>
 
<body>
    <h1 style="text-align: center;" 
        REGISTRATION FORM
    </h1>
    <form name="RegForm" onsubmit="return GEEKFORGEEKS()"
          method="post">
        <p>
            Name:
            <input type="text" size="65" name="Name" />
        </p>
        <br />
        <p>
            Password:
            <input type="text" size="65" name="Password" />
        </p>
r
        <br />
<p> phone number:
	<input type="text" size="65" name="phone number"/>
</p>
<br/>
            <p>
            Select your course 
            <select type="text" value="" name="Subject">
                <option>BTECH</option>
                <option>BBA</option>
                <option>BCA</option>
                <option>B.COM</option>
                <option>MTECH</option>
		<option>MBA</option>
                <option>MED</option>
                <option>MCA</option>
                <option>M.COM</option>
                <option>OTHER</option>
            </select>
        </p>
        <br />
        <br />
        <p>
            Comments:
            <textarea cols="55" name="Comment"> </textarea>
        </p>
        <p>
            <input type="submit" value="send" name="Submit" />
            <input type="reset" value="Reset" name="Reset" />
        </p>
    </form>
</body>
</html>

            body{
    background: rgb(34,193,195);
    background: linear-gradient(0deg, rgba(34,193,195,1) 0%, rgba(121,32,153,1) 86%);
    background-attachment: fixed;
    margin:0;
    font-family: 'Poppins', sans-serif; 
}


}
