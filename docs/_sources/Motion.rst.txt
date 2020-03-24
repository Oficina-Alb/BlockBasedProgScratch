Motion
========

You already got to know the Scratch user interface, you learned how to create sprites and determine their position on the stage. Now is a perfect time to learn how to move them by using commands (blocks) from the category **Motion**. These blocks will enable you to make simple games and animations.

There are 3 types of blocks you can use to move your sprite:

•	Blocks for absolute motion
•	Blocks for relative motion
•	Other motion blocks

Blocks for absolute motion
-----------------------------

In the category **Motion**, there are 4 blocks, which enable absolute motion. 

.. image:: ../_images/kretanje/AKBlokovi.png  
   :align: center

You will use these blocks when you need to program your sprite to move to a **specific location (point) on the stage**. 

.. infonote::

    **The cat is chasing the mouse...**
        
    The cat is located in the center of the stage, and the mouse is in the point **(x:150 y:100)**. 

    .. image:: ../_images/kretanje/MM1.png 
       :width: 400px
       :align: center

    
    We remind you that the stage is a rectangular surface 480 pixels wide and 360 pixels high. The center has the coordinates **(x:0 y:0)**.

.. |AK1| image:: ../_images/kretanje/AK1.png
.. |AK2| image:: ../_images/kretanje/AK2.png
.. |AK3| image:: ../_images/kretanje/AK3.png
.. |AK4| image:: ../_images/kretanje/AK4.png

If you want the cat to catch the mouse you can just use the block |AK1|.

.. image:: ../_images/kretanje/MM1a.png 
   :width: 400px   
   :align: center

If you want the chase to last longer, you can use the block |AK2|. With this block the cat will glide for 1 second from the point **(x:0 y:0)** to the point **(x:150 y:100)**.

By using the blocks |AK3| and |AK4| you can make it seem like the cat is slowly sneaking up to the mouse:

.. image:: ../_images/kretanje/MM34a.png  
   :width: 800
   :align: center

You can always see the current position of the sprite (the current values of **x:** and **y:**) below the stage, in the sprite list.

.. image:: ../_images/kretanje/XY.png  
   :align: center

.. mchoice:: AKZadatak1
   :answer_a: Program A
   :answer_b: Program B
   :feedback_a: Well done! The cat "caught" all the mice!    
   :feedback_b: Hm.. We recommend that you carefully read the lesson Position of the sprite on the stage.
   :correct: a

   Analyze the position of the mice presented in the figure below and select the program, which will allow the cat to "catch" all the mice.

   .. image:: ../_images/kretanje/AKZ1.png
      :width: 700
      :align: center

.. |Vazno| image:: ../_images/Vazno.png

.. infonote::

    |Vazno|   **So, by using the blocks for absolute motion, you tell your sprite exactly where it should go on the stage.**

Blocks for relative motion
-----------------------------

.. |RKS2| image:: ../_images/kretanje/RKS2.png

Relative motion is not determined by the location the sprite should go to, but by the current position of the sprite.

In the category **Motion**, you have at your disposal several blocks, which enable relative motion. 

.. image:: ../_images/kretanje/RKBlokovi.png  
   :align: center

In the example where the cat was chasing the mouse, we knew the exact location of the mouse (the point in which it is located). The situations where we do not know the sprite's location are more common. In these cases, we will use blocks for relative motion to move our sprites.

When it comes to relative motion, it is very important to point (turn) the sprite in the desired direction. We achieve this by dragging the arrow around the circle of the block |RKS2|. 

It is good for you to know that direction toward 0 represents up, toward 90 is to the right, toward 180 is down, and toward -90 is to the left.

.. image:: ../_images/kretanje/RKS1.png  
   :width: 800
   :align: center

You can always see the current direction of the sprite below the stage, in the sprite list in the field **Direction**.

.. image:: ../_images/kretanje/XY.png 
   :align: center

.. mchoice:: RKZadatak1
   :answer_a: Direction: 90 (right) Position: (x:50 y:-100)
   :answer_b: Direction: 180 (down) Position: (x:50 y:100)
   :feedback_a: Analyze the program again. Does turning the sprite 90 degrees change its direction?    
   :feedback_b: Well done! You understand the movement of the sprite well!
   :correct: b

   Analyze the program presented in the figure, and select what you think is the direction of the sprite, as well as what will be its position after the program finished running.

   .. image:: ../_images/kretanje/RKZ1.png
      :align: center

.. infonote::

    |Vazno|   **So, by using blocks for relative movement, you tell the sprite where to point and move relative to its current position.**


Other motion blocks
--------------------------

In the category **Motion**, you have 4 more blocks at your disposal, which enable sprites to move. 

.. image:: ../_images/kretanje/OKBlokovi.png   
   :align: center

.. |OK3| image:: ../_images/kretanje/OK3.png
.. |OK4a| image:: ../_images/kretanje/OK4a.png
.. |OK4b| image:: ../_images/kretanje/OK4b.png

The stage is a limited space. When the sprite reaches the edge of the stage, it would be natural for it to turn around and continue moving in another direction. You will enable this behavior of the sprite by using the block |OK3|. You will also decide how the sprite continues to move. If within the block |OK4a| you set the rotation style of the sprite to **all around**, it will continue to move upside-down. This will not happen if, from the drop-down list of the block, you choose the option left-right |OK4b|.

.. image:: ../_images/kretanje/OKRub12.png
   :width: 800
   :align: center

You can always see the current style of your sprite's movement below the stage in the sprite list, in the field **Direction**.

.. image:: ../_images/kretanje/XY.png
   :width: 400px   
   :align: center

Let's go back to our sprites: |macka| and |mis|. 

.. |OK1| image:: ../_images/kretanje/OK1.png
.. |OK1a| image:: ../_images/kretanje/OK1a.png
.. |macka| image:: ../_images/kretanje/macka.png
.. |mis| image:: ../_images/kretanje/mis.png

If we do not know the exact position of the mouse, and we want the cat to point toward it (turn toward it), we can use the block |OK1|. We just need to select the Mouse sprite |OK1a| from the drop-down list, and the problem is solved.

We will show you how the last two blocks work in the following example.

.. infonote::

    **The cat is chasing the mouse...**
        
    The cat is chasing the mouse, gliding toward it. The mouse constantly turns and goes toward the cursor, which we are moving around the stage.

    .. image:: ../_images/kretanje/OKPR1.png   
       :align: center

    
    Above each of the sprites are scripts that enable the described behavior. 

.. |Izazov| image:: ../_images/Izazov.png

|Izazov| Upgrade the program presented above by adding one more sprite - an apple. Have the mouse chase the apple and the cat chase the mouse. Make the apple move toward the cursor (which we control), the mouse should move toward the apple, and the cat should move toward the mouse.

.. image:: ../_images/kretanje/MMJ.png  
   :width: 400
   :align: center

.. reveal:: sakrivanjeKretanje
   :showtitle: Compare your solution with ours
   :hidetitle: Hide the solution
 
   **Possible solution:**
     
   .. youtube:: QgCCzBw6DKU
      :width: 735
      :height: 415
      :align: center
   
   
