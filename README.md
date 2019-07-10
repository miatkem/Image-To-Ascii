# Image-To-Ascii
Convert an image (JPG, PNG, ect.) to a TXT file made from ASCII characters.

# Method
<ol><li> Load image specified by user
  <li> Convert image to RGB mapping
  <li> Loop through RGB mapping and translate to ASCII based on their average RGB value (darkness)
    <li> Place ASCII characters in a string that is then written to a textfile
     <\ol>
    
# Resources
The Python Imaging Library was used to import and manipulate the image
