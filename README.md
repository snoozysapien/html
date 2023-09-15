# html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form 2</title>
</head>
<body>
    <h2>Job Application</h2>
    
    <form>
        <label for="name">Name : </label>
        <input type="text" id="name" name="name">
        <br/>
        <br/>

        <label for="emailID">Email ID : </label>
        <input type="email" id="emailID" name="emailID">
        <br/>
        <br/>

        <label for="phonenumber">Phone No.</label>
        <input type="tel" id="phonenumber" name="phonenumber">
        <br/>
        <br/>

        <label for="fileupload">Resume : </label>
        <input type="file" name="fileupload" id="fileupload">
        <br/>
        <br/>

        <label for="counter">Experience (In years) : </label>
        <input type="number" name="counter" id="counter" min="0" max="50" >
        <br/>
        <br/>

        <fieldset>
            <legend>Topics of Interest</legend>

            <input type="checkbox" name="checkbox" id="checkbox1">
            <label for="checkbox1">HTML</label>

            <input type="checkbox" name="checkbox" id="checkbox2">
            <label for="checkbox2">CSS</label>

            <input type="checkbox" name="checkbox" id="checkbox3">
            <label for="checkbox3">JavaScript</label>

        </fieldset>
        <br>

        <label for="educationType">Highets Education : </label>
        <select name="educationType" id="educationType">
            <option value="a">A</option>
            <option value="b">B</option>
            <option value="c">C</option>
            <option value="d">D</option>
            <option value="e">E</option>
        </select>
        <br>
        <br>

        <fieldset>
            <legend>Availability</legend>

            <label for="radio1">Full-time</label>
            <input type="radio" name="radio" id="radio1">
            <br/>

            <label for="radio2">Part-time</label>
            <input type="radio" name="radio" id="radio1">
        </fieldset>
        <br>

        <label for="textarea1">Additional Comments : </label>
        <br/>
        <textarea name="textarea1" id="textarea1" cols="30" rows="10"></textarea>
        <br/>

        <input type="submit" value="Submit Application">
 

    </form>

    
</body>
</html>
