This is a popcat autoclicker.
How to use it?
First Copy the following code --> Then go to popcat.click --> On the site do: CTRL + SHIFT + i --> Go to console --> Scroll down is you see errors 
--> Copy the code in the text box, and press enter and your done! You don't have to do anything, and you can do something else.
 IMPORTANT: Do not close the tab. Just leave it.


    var event = new KeyboardEvent('keydown', {

    key: 'g', // The key that is getting pressed

    ctrlKey: true

    });




    setInterval(function(){

    for (i = 0; i < 100; i++) { // You can change the 100, just not to high or it will not work, just like 1000 or 1200. It will lag a bit

        document.dispatchEvent(event);

    }

    }, 0);
