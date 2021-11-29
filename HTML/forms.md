# Forms:
Forms are the interactive parts of a webpage.

Form to enter text and read the entered value:

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


--> Note: To enter an email, the attribute given to input type is "tel". 
          To enter a phone number, the attribute is 'tel'.
