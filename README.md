Forms and the DOM Event Model

JavaScript Calculator

Using DOM, DOM Events, Functions, and more to create a calculator.

- There is a text box that will display the value of each button click and 16 different buttons each of which represents a major key on a basic calculator. Begin adding an event listener to the window object that “listens” for the load event and when heard, calls a user-defined function called init().
- A user-defined function called init() will be created.
- Within the init() function, an event listener is attached to each of the 16 buttons in the web page. The click event will be listened for and when heard, a function called enter() will be called for each of the buttons except for the equal sign.
- A function called calculate() will be called when the equal button is pressed.
- A user-defined function called enter() will accept val as an argument. 
- Within the enter() function, the result text box will be retrieved by its ID and its value set plus equal to the val parameter being passed in.
- A user-defined function called calculate() is created to get the result text box by its ID and set its value equal to the calculation currently stored in the result text box.

JavaScript Image Rollovers

An application that features a navigation bar with rollover images, using the DOM, DOM Events, and Functions.

- A helper function called getImage() will accept one parameter. Within the function, the result of getting an element by its ID will be returned, passing in the function’s argument as a parameter into the getElementById() method.
- A new constructor function called Rollover is created that accepts two arguments including imageId and newImageURL.
- A new object variable called target is created and store this within it.
- 3 properties associated with target are created: newImageURL, image, and oldImageURL.
- The value of the newImageURL parameter is stored within the newImageURL property.
- The return value of the getImage() function is stored, passing in the imageID argument as a parameter within the image property.
- The URL source (this.image.src) is stored within the oldImageURL property.
- An event handler is created for onmouseover and one for onmouseout for each target image.
- In the mouseover, the src property of the target.image is set to the newImageURL property.
- In the mouseout, the src property of the target.image is set to the oldImageURL property.
- An event handler is created to handle the loading of the web page (window). 
- Within the event handler function, 5 new instances of the Rollover object are created, passing in the image’s ID and the rollover image path for each image as parameters within the constructor.
