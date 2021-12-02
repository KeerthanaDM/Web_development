# Tables in html:

A table is created to store a set of related information for easy utilization.
Tags used for the creation of a table are

'table'- to create a table.

'thead'- to write the contents of a table header

'tbody'- to create individual rows and columns of a table

'th'-tag used to define the table header

'tr'- to define the individual table rows

'td'-used to define the table data

'tfoot'- to represent the footer of the table or the last row of the table

Preferably table footer has to be inserted before the table body

Sample code for creating a table:


    <!DOCTYPE html>
    <html>
        <head>
            <meta charset="utf-8">
            <title>Sample table</title>
        </head>
        <body>
            <h2>
                Table for alphabets and numbers
            </h2>
            <table><thead>
                <tr>
                    <th>Alphabet</th>
                    <th>Number</th>
                    <th>Number in words</th>
                </tr></thead>
                <tbody>
                <tr>
                    <td>a</td>
                    <td>1</td>
                    <td>one</td>
                </tr>
                <tr>
                    <td>b</td>
                    <td>2</td>
                    <td>two</td>
                </tr>
                <tr>
                    <td>c</td>
                    <td>3</td>
                    <td>three</td>
                </tr>
                <tr>
                    <td>d</td>
                    <td>4</td>
                    <td>four</td>
                </tr>
                <tr>
                    <td>e</td>
                    <td>5</td>
                    <td>five</td>
                </tr></tbody>
                <tfoot>
                    <tr>
                        <td>-</td>
                        <td>sum=15</td>
                        <td>-</td>
                    </tr>
                </tfoot>

            </table>
        </body>
    </html>
