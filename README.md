# lightEvaluation
A light evaluation tool for evaluating static visualization images in a drag-and-drop manner

# usage
Please put two data into the config filefolder:

1) Name your visualization image to visualize "vis.png"
2) Write your tasks as the following format (The descriptive text and each task occupy one line):

Descriptive Text
1. Task1 Content
2. Task2 Content
.

n. TaskN content

# optional setting
You can put an config file of 'imgsize.csv' in the config folder, setting the image with desired width and height.

width,height
800,400

It is optional. By default, you don't need this config file.

# set up

The "index.html" should be opened in a web browser of a server, e.g.
1) python -m http.server
2) Other web servers 