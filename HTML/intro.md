## Introduction to HTML and CSS

HTML stands for Hyper Text Markup Language. It is ubiquitously used to create and design interactive webpages(Pages that can be viewed on the internet). Text, audio, video, Checkboxes, Dropdowns etc. can be created using a html program.

CSS stands for Cascading Style Sheets. It is used to animate webpages i.e. add color, transitions ,background images etc. can be included in the webpage.

A html program is coded on a text editor and is saved with the extension .html .It consists of 2 main components namely head and body. Head is the part of the program which gives information about the page(like title, font, character set that is being used to display the text in body ) whereas the body contains data that gets displayed in the page(headings, paragraphs, images, audio, video).

It can be said that the code for a html program is like a sandwich. Every opening tag must have a closing tag. The closing tag differs from and opening tag by a mere '/'. We can have the data/information to be displayed in between the opening and closing tags. Sometimes, values may be assigned to the code. These values are called as attributes. For example,

<a href="name_of_the_page.html">click here</a>

Here, name_of_the_page(user defined) is an attribute that is assigned to the anchor(a).

Headings of different sizes ranging from size 1 to size 6 can be added onto the webpage whose code is given as follows:

    <h1> This heading is displayed in level 1.</h1>
    <h2> This heading is displayed in level 2.</h2>
    <h3> This heading is displayed in level 3.</h3>
    <h4> This heading is displayed in level 4.</h4>
    <h5> This heading is displayed in level 5.</h5>
    <h6> This heading is displayed in level 6.</h6>
    

To add a paragraph, the code is as follows:
    <p>This is a paragraph. It contains two sentences.</p>



A list can also be created in a website:
There are 2 types of lists that can be created,

1)Ordered list - Created if a list containing elements in an order has to be created.(May be used to write a priority list)

    <h1>Priority list of 3 fruits</h1>
    <ol>
    <li>Apples</li>
    <li>Oranges</li>
    <li>Mangoes</li>
      </ol>

2)Unordered list - Created if the elements in the list do not follow any specific order(May be used to write a grocery list)

    <h1>Grocery list</h1>
    <ul>
    <li>Eggs</li>
    <li>Milk</li>
    <li>Bread</li>
      </ul>

Furthermore, a list within another list can be created.
The above example of the grocery list can be extended as :

    <h1>Grocery list</h1>
    <ul>
      <li>Eggs</li>
      <li>Milk</li>
      <li>fruits
        <ol>
          <li>Apples</li>
          <li>Oranges</li>
          <li>Mangoes</li>
        </ol>
      </li>
    </ul>
