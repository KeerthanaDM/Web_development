# Forms:

Forms are the interactive parts of a webpage.
Form to enter text:

    <!DOCTYPE html>
    <html>
        <head>
            <meta charset="utf-8">
            <title>
                sample form
            </title>
        </head>
        <body>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="fullname"><br><br>
                <label for="usn">USN:</label>
                <input type="text" id="usn" name="rollnumber"><br><br>
                <input type="Submit" value="Save!">
            </form>
        </body>
    </html>


'br' tag is used to skip a line while displaying. It could be guessed intuitively that the tag used to create a form is 'form'. Since the desired input is of the text type, input type is mentioned as 'text'. To create a submit button, input is given an attribute of type 'submit'. Boxes where data can be entered are thus obtained. A label is now required to specify what the box is meant for. Hence, a label tag is used for the same. In order to map the label to it's respective box, an id is created with an attribute and is given to the label as well. Instead, the input can be nested within the label tag but this is not a feasible solution.

Syntax to enter multiple lines of text:

          <label for="address">Address:</label>
          <textarea id="address" name="yourmsg"></textarea><br>
          <input type="submit" value="save!">


--> Note: To enter an email, the attribute given to input type is "email".
          To enter a phone number, the attribute is 'tel'.


-->Types of options:
1)Dropdown: These are used when there are multiple options and one of them has to be selected.
2)Radio inputs: Used when only 1 of the options has to be selected(when less number of options are available)
3)Checkboxes: Used when multiple options have to be selected.

    <!DOCTYPE html>
    <html>
        <head>
            <meta charset="utf-8">
            <title>
                sample form
            </title>
        </head>
        <body>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="fullname"><br><br>
                <label for="usn">USN:</label>
                <input type="text" id="usn" name="rollnumber"><br><br>
                <label for="Address">Address:</label>
                <textarea id="Address" name="yourmsg"></textarea><br>
                <label for="favcolor">Choose a color:</label>
                <select name="color" id="favcolor">
                    <option value="colorRed">Red</option>
                    <option value="colorblue">Blue</option>
                    <option value="colororange">Orange</option>
                    <option value="coloryellow">Yellow</option>
                    <option value="white">white</option>
                </select><br><br>

                <fieldset><legend>Fav meal:</legend>
                    <input type="radio" name="favmeal" id ="breakfast"  value="meal1">
                    <label for="breakfast">Breakfast</label>
                    <input type="radio" name="favmeal" id="brunch" value="meal2" >
                    <label for ="brunch">Brunch</label>
                    <input type="radio" name="favmeal" value="meal3" id="lunch" >
                    <label for="lunch">Lunch</label>
                </fieldset>

                <fieldset><legend>Fav meals:</legend>
                    <input type="checkbox" name="favmeal" id ="breakfast"  value="meal1">
                    <label for="breakfast">Breakfast</label>
                    <input type="checkbox" name="favmeal" id="brunch" value="meal2" >
                    <label for ="brunch">Brunch</label>
                    <input type="checkbox" name="favmeal" value="meal3" id="lunch" >
                    <label for="lunch">Lunch</label>
                    <input type="checkbox" name="favmeal" value="meal4" id="dinner">
                    <label for="dinner">Dinner</label>
                </fieldset>

                <br><input type="submit" value="save!">
            </form>
        </body>
    </html>
