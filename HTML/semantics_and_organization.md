# Semantics and organization:

Any paragraph or an essay has a particular style of writing. Dividing an essay into sections and subsections will make the reader interested in reading it. Therefore, we use semantics to organize the content in a webpage.

1) Structural elements:
'header' , 'footer' , 'article' and 'aside' are the semantic elements in a html code.
'header' is the text that is placed at the top of a page whereas 'footer ' is the text placed on the bottom. Any paragraph placed in between header and footer can be referred to as an article. Also, each article can have a header and footer of it's own.
'aside' is used when the content is related to the paragraph surrounding it but has to be viewed separately.

Example code:

      <!DOCTYPE html>
      <html>
          <head>
              <meta charset='utf-8'>
              <title>
                  Structural elements
              </title>
              <body>
                  <header>
                      This section contains header of the page
                  </header>
                  <article>
                      <p>This paragraph is contained in the article tag.</p>
                      <p>
                          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."
                      </p>
                  </article>
                  <aside>
                      <p>This line is in the aside tag.</p>
                  </aside>
                  <footer>

                      This section contains the footer of the page
                  </footer>
              </body>
          </head>
      </html>

2)Navigation:
Navigation is used to move from one webpage to another by clicking on links. It can therefore be defined as an unordered list of all links. It can be implemented by using the keyword 'nav'.
Syntax:

        <nav>
              <ul>
                <li><a href="nameofthepage1.html">description1</a></li>
                <li><a href="nameofthepage2.html">description2</a></li>
                <li><a href="nameofthepage3.html">description3</a></li>
              </ul>
        </nav>

3)Non-Semantic elements:
Non-semantic elements like 'div' are used to represent a part of the code which doesn't have a special element dedicated to represent it. It can also be used when there is a necessity of an additional element for layout or styling purposes.
'div' is a non-semantic version of 'header', 'footer' and 'article'. It is a block level element.
            
 Syntax:
 
            <div>
            <p>
              Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem.
            </p>
            </div>

'span' is the non-semantic version of 'strong' and 'em'. When we don't have to indicate the importance or emphasize the text but need to specialize it by adding color or changing the font later on with the help of CSS ,'span' is used. It is an inline element.

syntax:

            <span class="brand color">blue</span>


4)HTML comments:
Comments may be used to improve the understandability of any code. The are usually used at the end of div class. In html, we can add comments as represented below:
      '!--this is a comment--' (enclose it within greater than and less than symbols)


5)Sections:
Section tags give a semantic meaning to a webpage. Any chapter can be broken into sections and subsections for better understandability. Also, borders can be added and styling can be done using CSS efficiently if the code is divided into sections. Sections within sections form a subsection.
When sections are created, size of the heading levels too change. Ex: The usual h3 would be similar to h1 written in a subsection.

Code:


            <!DOCTYPE html>
            <html>
                <head>
                    <meta charset='utf-8'>
                    <title>
                      Structural elements
                    </title>
                    <body>
                    <!-- This is a comment-->
                        <h1>h1 is used for this heading</h1>
                        <header>
                            <strong><em>This section contains header of the page</em></strong>
                        </header>
                        <article>
                            <p>This paragraph is contained in the article tag.</p>
                            <p>
                                <section>
                                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."
                            </section></p>
                        </article>
                        <section><h1>h1 is used in this section.</h1>
                            Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem.
                            <section>
                                <h1>H1 is used in this subsection.</h1>
                            </section>
                        </section>
                        <aside>
                            <p>This line is in the aside tag.</p>
                        </aside>
                        <footer>

                            <strong><em>This section contains the footer of the page</em></strong>
                        </footer>
                    </body>
                </head>
            </html>
