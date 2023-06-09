# iis_webapp

# Preface
This code was taken from a GitHub Enterprise repository hosted by Texas A&M University to avoid its loss before it shuts down. This code was in no way shape or form stolen, copied, or fabricated. Credit goes to Nassef Ameen, Mitchell Taylor, Ross Petersen, and Julio Gonzalez for contributing to this repository. 

In order to run this program, you will need to first run the server program on one terminal before starting the client program on another.

# Server Side

To run the server program, make sure the proper packages are installed in the server folder:
```
pg
cors
express
```
you will also need to install nodemon globally, which you can do with this command:
`npm install -g nodemon`

to run the server, navigate to the server folder and run:
`nodemon index`

once you see that the server has started on port 5000, you can open a new terminal for the client side.

# Client Side

To run the client program, you will need to navigate to the client folder, and then run `npm start`.
After awhile you'll see the React application open up in your browser.
