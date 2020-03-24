Drawing
=========

In Scratch, every sprite has a hidden pen and the ability to live marks on the stage when it moves.

If we want to draw, we need to use the blocks from the category **Pen**. First, we need to add this category of blocks to the Scratch interface. We can do this by clicking on the button |Ekstenzija|, which is located in the bottom left corner of the screen, and selecting the extension **Pen**.
  .. |Ekstenzija| image:: ../_images/Ekstenzija.png

.. image:: ../_images/crtanje/ekstOlovka.png 
   :align: center

A new category of blocks **Pen** will appear in the **Code** tab. In this category, we have 9 blocks, which we can use for drawing on the stage. With these blocks we can erase everything we have drawn on the stage (*erase all*), put the pen down and up (*pen down*, *pen up*), control the color and the size of the pen easily (*set pen color*, *change pen color*, *set pen size*, *change pen size*). 

.. image:: ../_images/crtanje/BlokoviOlovka.png 
   :align: center

Initially, the sprite has the pen in the up position. **To make the drawing possible, we have to put the pen down.**

"Freehand" Drawing
-------------------------

.. |LikOlovka| image:: ../_images/crtanje/LikOlovka.png
  		    :width: 70px
.. |OK1| image:: ../_images/kretanje/OK1.png

.. |Uradi| image:: ../_images/Uradi.png

When we think about the freehand drawing, we usually picture us drawing with a pen. This is why we will use the sprite |LikOlovka| to create a program, which will simulate the freehand style of drawing. You can find this sprite in the Sprite library. 

In Scratch, the sprites draw with their center. If we want to draw with the pencil's "graphite tip", we will have to change the center of the sprite. We can do this in the **Costumes** tab. 

VIDEO - SPRITE'S CENTER

When we examined sprite's movement on the stage, we presented the block |OK1|. If we run this blocks an infinite number of times (*Forever*), the sprite will continuously move around on the stage following the mouse cursor. Therefore, we can use this block to simulate drawing - by moving the mouse cursor around on the stage, we will "draw" on the stage. 
    
Analyze the following scripts:

.. image:: ../_images/crtanje/KodSR.png  
   :align: center

|Uradi| Create a program, which allows freehand drawing and ensure that the program stops running when you press the **s** key. Look for the appropriate blocks in the categories **Events** and **Control**.

Controlling the movement of the sprite by using the keyboard and drawing
-------------------------------------------------------------------------

This is a great opportunity to use the blocks that allow the sprite to move with the help of arrows and upgrade them further by making the sprite draw lines of certain color and size (thickness). 

Arrange so that the sprite draws in the following manner:

•	while it moves to the right, it should draw a blue line, and the size should be 5 pixels;
•	while it moves to the left, it should draw a green line, and the size should be 10 pixels;
•	while it moves upward, it should draw a red line, and the size should be 15 pixels;
•	while it moves downward, it should draw a yellow line, and the size should be 20 pixels.

Create the following blocks:

.. image:: ../_images/crtanje/strelicebojadebljina.png
   :width: 840px   
   :align: center

We drew the image you see below:

.. image:: ../_images/crtanje/slobodnaruka.png
   :width: 650px   
   :align: center

Try to create a program, which will draw a similar image. 

Absolute movement and drawing
-------------------------------

.. image:: ../_images/crtanje/brodic.png
   :width: 650px   
   :align: center

Analyzing the image above, we can see that it will not be hard to determine the points we need to connect to draw the boat.  

|Uradi| Create a program, which will draw the boat by using light blue lines 5 pixels thick (pen size). Don't forget to erase everything on the stage before the drawing starts. Also, don't forget to put the cat sprite to be a sailor on the deck of the boat.


.. reveal:: sakrivanjeCrtanje1
   :showtitle: Compare your solution with ours
   :hidetitle: Hide the solution
 
   **Possible solution**
     
    .. image:: ../_images/crtanje/BrodicKod.png
	:width: 350px   
	:align: center

Stamp
------

.. |BO2| image:: ../_images/crtanje/BO2.png

.. |Paint| image:: ../_images/crtanje/Paint.png

Sometimes we need to draw and rotate images that are more complex on the stage. Instead of drawing the desired shape over and over again, it can be easier to create a costume with a specific shape, and then multiply and rotate it by using the block Stamp |BO2|.

  


We just need to use |Paint| to draw a new sprite, and then draw the shape we want in the paint editor located in the **Costumes** tab.

HERE VIDEO DRAGONS

We can also use the Stamp with the costumes of the sprites found in the Scratch sprite library.


