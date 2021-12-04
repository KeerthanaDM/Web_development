# CSS basic

CSS stands for Cascading style sheets. It is used to add color and design to a webpage.  It has to be saved with an extension of .css .

To link a html page to an empty css page, we use the following syntax:

    <link rel="stylesheet" href="address_of_the_file">

To add a color to the heading 'h1' in the html file,

    h1{
      color: orange;
    }

To align text in a paragraph,

     p{
       text-align: center;
     }

To add background color to a paragraph,

    p{
      background-color: yellow;
    }

These commands are called selectors. There are 3 types of selectors namely

i) Type selectors:
    It targets every element of the given name in the page.
ii) Descendent selectors:
    Hierarchy of what has to be selected in the page is given.[Type selector + family tree]
iii) Class selectors:
    A class is created in the html program for the section to be selected and the name of the class with a . preceding the name of the class is given.

A combination of class and type selectors is given most preference in the css code.

-->Cascade: The process of overwriting the defaults in a browser is called cascading.
For example:

    h1{
      font-size: 165%;
      font-weight: normal;
    }

-->Inheritance: When properties are passed on from the parent to child elements.

For example:

    body{
      color: green;
    }
    
    footer{
      color: grey;
    }

All properties cannot be inherited.

-->Specificity: If 2 or more styles compete with one another, one of them must be chosen. Overwriting a value that is explicitly set on a value might be tricky.

For example:

    p{
      color: orange;
    }
    
    footer{
      color: green;
    }

The above code does not display a green footer. Therefore, we must use the following code by specifying the hierarchy of footer giving it more priority.


    p{
      color: orange;
    }

    p footer{
      color: green;
    }

Priority order may be defined as follows:

    type selector < descendant selector < Class selector < descendant selector in a class(combination)

In case 2 styles are given to the same value, the one in the last takes precedence.

    p{
      color: blue;
    }
    p{
      color: green;
    }

Thus, the paragraph is printed in green.

## Code to demonstrate the above concepts:

#### HTML:

    <!DOCTYPE html>
    <html>
    <head>
        <meta charset="utf-8">
        <title>Final site</title>
    </head>
    <header>
        <h1>THIS IS A SAMPLE PAGE.</h1>
    </header>
    <link rel="stylesheet" href="first.css">
    <body>
             <p class="hi">"Lorem ipsum dolor sit amet, consectetur adipiscing elit,
             sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
             Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
             Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. 
             Excepteur sint occaecat cupidatat non proident,
             sunt in culpa qui officia deserunt mollit anim id est laborum."</p>

             <p class="ht">"Lorem ipsum dolor sit amet,consectetur adipiscing elit,
                sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
                Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
                Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. 
                Excepteur sint occaecat cupidatat non proident,
                sunt in culpa qui officia deserunt mollit anim id est laborum."</p>
    </body>
    <footer>
        <p>&copy; 2021 - Learning CSS</p>
    </footer>
    </html>


#### CSS:

    h1{
        color:rgb(30, 45, 255);
        text-align:center;
        font-size: 150%;
        font-style: inherit;
        font-weight: normal;
    }


    body .ht{
        color:green;
        size:110px;
    }

    body .hi{
        background-color: rgb(220, 241, 144);
     }

    footer p{
        color:grey;
        text-align:right;
    }

    footer p{
        color: lightblue;
        text-align: right;
    }



    
