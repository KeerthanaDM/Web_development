## Adding media to a html file

# 1)Adding an image :

An image can be added to a html file by using the following syntax:

    <img src="name_of_the_image.jpg" alt="description_about_the_image">

The above code is followed only if the image is stored in the same folder as that of the html program. Else, we need to replace the attribute name_of_the_image with address_of_the_image.
Address of the file can be obtained by right clicking on the file and selecting the option "copy as path".

    <img src="address_of_the_image.jpg" alt="description_about_the_image">

In the above syntax, "img src" tells that an image is being added from the particular source i.e. address_of_the_image and is of the type jpg. In case the browser doesn't support an image file(browsers meant only for reading), we give a description about the image for user convenience. This is done by assigning the description to "alt" as an attribute.


# 2)Adding an audio clip :

An audio file is usually saved with the extension .mp3 but all browsers do not support this format. Hence it can be saved with the extension .ogg (a format used to store compressed audio files). Audio can be added to a html file as follows:

    <audio controls>
      <source src="name_of_the_audio_file.mp3" type="audio/mpeg">
      <source src="name_of_the_audio_file.ogg" type="audio/ogg">
      <a href="address_of_the_aud_file">description_about_the_audio</a>
    </audio>

Controls like play, pause, playback speed, volume are enabled using the keyword "controls" in the "audio " tag. Source of the audio file is then provided (simiar to adding image). It is done in 2 ways in the above block of code. Also, a link is created in case both the formats are not supported by the web browsers through which the audio can be accessed. Even though the same audio file is provided in 3 ways, it will not be displayed thrice. Once the format that is supported by the web browser is encountered in the code, the others(formats) will not be executed.

# 3)Adding a video clip:

It is hard to add a video clip onto a webpage as permission from 3rd party services is required to add a video downloaded from a random website. Therefore, html is not a great option to add a video clip. Instead, javascript can be used. It can be done with a html program as follows:

    <video controls >
    <source src="address_of_the_video.mp4" type="video/mp4">
    <source src="address_of_the_video.webm" type="video/webm">
    <source src="address_of_the_video.ogv" type="video/ogg">
    </video>

Some browsers like mozilla firefox do not support mp4 files. Therefore video files can be saved in the format .webm and uploaded. It can also be accessed by saving the file with the format .ogv (similar to .ogg for audio).
Older html versions do not support videos. Back then, adobe flash players were used to access video files or a link can be created which displays a message to update the web browser (http://browsehappy.com).

Complications in adding a video clip:
1)older browser supported
2)video resolution may be decreased
3)Branding concerns/custom UI

Resolving these issues is out of scope of simple html. Hence, it is ignored for now.

# 4)Adding vector graphics

Vector graphics is an image that is not created out of pixels but out of random shapes overlapping each other. Therefore, there is no loss of quality when we zoom into the picture. But still there are a few disadvantages of svg over a normal image.
We can use adobe illustrator to create vector graphics. It can also be created for free on a software called " figma ".
We can add it into a webpage similar to that as an image. We can also drag it onto the text editor where it will be converted into a piece of code which can be included at the appropriate location in the program.
