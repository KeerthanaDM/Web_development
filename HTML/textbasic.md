Texts include headings, Lists, Attributes like Bold and Italic text.

# 1)Headings:
 There are 6 levels of headings ranging from 1 to 6 with 1 being the largest and 6 being the smallest.
 All these headings appear in bold.


    <!DOCTYPE html>
    <html>
        <head>
            <meta charset="utf-8">
            <title>Headings:-</title>
        </head>
        <body>
            <h1>Heading level 1</h1>
            <h2>Heading level 2</h2>
            <h3>Heading level 3</h3>
            <h4>Heading level 4</h4>
            <h5>Heading level 5</h5>
            <h6>Heading level 6</h6>
        </body>
    </html>
    
    
    
  #  2) Lists:
   There are three types of lists that can be created in html namely
   i) Unordered list: tag is 'ul'
   ii) Ordered list: tag is 'ol'
   iii) Description list : tag is 'dl'
Each list item is specified with the help of the tag  'li' in ordered and unordered lists 
Components of the descriptive list are 'dt' i.e. description term and 'dd' i.e. description of the description term.
Within a descriptive list, a description term and a description are paired with each other.
Program given below shows the types of list that can be created using html.
  
  
   <!DOCTYPE html>
        <html>
            <head>
                <meta charset= "utf-8">
                <title>Types of list.</title>
            </head>
            <body>
               <p> There are 3 types of lists namely ordered list, unordered list and descriptive list. </p>
               <h4>Unordered list:</h4>
               <ul>
                   <li>Apples</li>
                   <li>Bananas</li>
                   <li>Oranges</li>
               </ul>
               <h4>Ordered list:</h4>
               <ol>
                   <li>Monday</li>
                   <li>Tuesday</li>
                   <li>Wednesday</li>
                   <li>Thursday</li>
                   <li>Friday</li>
               </ol>
               <h4>Description list: </h4>
               <dl>
                   <dt>Name of the book:</dt>
                   <dd>Harry Potter and the Philosopher's stone</dd>
                   <dt>Name of the author:</dt>
                   <dd>JK Rowling</dd>
                   <dt>Number of pages:</dt>
                   <dd>500</dd>
               </dl>
               </body>
        </html>

  
 
# 3)Bold and Italic:
  
i) Bold words: 'b' or 'strong' tags can be used. 'Strong' is preferred as it will be helpful for further developments of the webpage using CSS.
 'b' is only used for presentational purposes whereas 'strong' highlights the additional importance given to the strengthened text in the webpage.

ii) Italic words:'i', <def> or 'em' tags can be used. 'i' tag is not very preferred as it only gives presidential preference of the word rather than signifying importance. Therefore 'em' tag is used for italic words.
'def' stands for definition which is also represented in italic style.
Also, a class can be created in the 'i' tag and an attribute can be assigned to it. This method is feasible as well and behaves similar to 'em'.
      

        <!DOCTYPE html>>
        <html>
            <head>
                <meta charset="utf-8">
                <title>Bold and Italic font representation.</title>
            </head>
            <body>
                <p>Work <strong>Hard ,Dream </strong>big!</p>
                <p><b>Bold</b> using another tag.</p>
                <p>This paragraph contains a word in <em>Italic!</em></p>
                <p><i>Italic</i> using a different html tag.</p>
                <p><i class="term">Italic</i> font again!</p>
                <p><dfn>Italic</dfn> using an other tag.</p>
                <p>Paragraph in<strong><em> Bold and Italic :)</em></strong></p>
            </body>
        </html>
