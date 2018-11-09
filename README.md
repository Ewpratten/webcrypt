# webcrypt
simple web origin verification using some javascript

## Idea
sites come in paired files.
The first file is an html file with a bit of javascript. It should load very quickly then display a js loading screen. It will then grab a corisponding pgp file from the server by finding the file path from the address bar. Finally, it will load the page and display the signer's info.
