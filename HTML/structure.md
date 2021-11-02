## STRUCTURE OF A html PROGRAM

A html program follows a particular structure. Unless this structure is not followed, resulting output will vary.
A tag namely

    <!DOCTYPE html>
    
is used to represent that the most recent version of the web browser must be used to run the code present underneath the tag.
The whole code must be enclosed with opening and closing html tags indicating that the program is being coded in  Hypertext markup language .

    <html>
        </html>

The program can further be divided into head and body sections wherein head represents details about the code whereas body represents the content to be displayed on the webpage.

      <head> </head>
      <body> </body>

A tag "title" can be added within the head to represent the title of the webpage(Description on the tab of a website). Also, the character set to be used to display content can be defined within the head. For example,

      <meta charset="utf-8">
      
is the code commonly used for English character set.

To sum up, any html program keeps up with the following structure:

    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <title>My first webpage</title>
      </head>

      <body>
        <h1> My heading </h1>
        <p> Paragraph 1</p>
        <p> Paragraph 2</p>
      </body>
    </html>


# Linking webpages together

Collection of multiple webpages together results in the formation of a website. To do so, we must link webpages together. Addition of a simple line of code can enable this process to increase the functionality of a website.The code for the purpose mentioned above is given as follows:

    <a href="name_of_the_page_linked.html"> description_of_the_page_it_leads_to </a>

Here, a stands for anchor and href stands for hypertext reference. A sample program to demonstrate the same is given below:

    <!DOCTYPE html>
    <html>
    <head>
        <meta charset="utf-8">
        <title>to buy</title>
    </head>
    <body>
        <h1>Click <a href="unordered list.html">here </a> to display my grocery list!</h1>
    </body>
    </html>

To run the above code, save it with the name "linkingpages .html" as the extension. Also, save the code given below with the name "unordered list.html" within the same folder.

    <!DOCTYPE html>
    <body>
    <h1>My Grocery List</h1>
    <ul>
    <li>Milk    </li>
    <li>Eggs</li>
    <li>Bread
        <ul>
            <li>a bread</li>
            <li>b bread</li>
            <li>c bread</li>
            </ul>
            </li>
    </ul>
    <a href="linkingpages.html">back to homepage</a>
    </body>
