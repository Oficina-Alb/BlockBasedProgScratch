Blocks
=======

Computer programs are sets of commands, which we use to explain to the computer how to complete a certain task or solve a problem. Given that most programming languages ​​are textual, developers often type commands.

In the visual programming language Scratch, we don't write commands, but instead we use blocks, which represent them. We create programs by arranging (stacking) blocks in the appropriate order. 

Types of Blocks in Scratch
----------------------------

There are 4 types of blocks in Scratch: 

.. image:: ../_images/blokovi/4Bloka.png   
   :align: center

1. Command blocks;
2. Blocks which link events with the running of the program;
3. Blocks which control the running of the program;
4. Blocks which report a certain value (function blocks).


Command Blocks
~~~~~~~~~~~~~~~

Command blocks have notches at the top and bumps on the bottom. They are designed in a way that allows them to be connected (stacked) to other blocks. We can just drag a block from the appropriate category into the scripts area (space for programming) and connect it to other blocks, which are already there. Connecting blocks looks like magnetic attraction - as soon as we place a notch of one block close to the bump of another, it will "stick" to it, thus continuing the sequence. The bumps allow new blocks to be added.    

Blocks which link events with the running of the program
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. |ZZ| image:: ../_images/blokovi/ZZ.png
.. |R10M10| image:: ../_images/blokovi/R10M10.png
.. |Costume| image:: ../_images/blokovi/Costume.png
.. |XP| image:: ../_images/blokovi/XP.png
.. |Touch| image:: ../_images/blokovi/Touch.png
.. |Touching| image:: ../_images/blokovi/Touching.png
.. |Sabiranje| image:: ../_images/blokovi/Sabiranje.png
.. |WU| image:: ../_images/blokovi/WU.png
.. |Say| image:: ../_images/blokovi/Say.png
.. |SayE| image:: ../_images/blokovi/SayE.png
.. |WUE| image:: ../_images/blokovi/WUE.png

These blocks have "hats". This means that they can only be placed at the beginning of a stack of blocks. We usually start a script with one of these blocks. On the bottom, they have bumps, which allow new blocks to be added to them. 

It is important for you to know that these blocks represent triggers, which start the running of scripts attached to them. For example, the block |ZZ| ensures that the command blocks attached to it run only when the green flag, located above the stage, is clicked. 

Blocks which control the running of the program
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Similar to command blocks, the blocks controlling the running of the program have notches at the top and bumps on the bottom. We can put them above other blocks, as well as put other blocks below them. 

These blocks are also characterized by the ability to accommodate other blocks (other blocks can be put inside them). For example, the script |R10M10| allows our sprite to move 10 steps 10 times. 

Blocks which report a certain value (function blocks)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Apart from their shape, these blocks are different from other blocks because they cannot be part of the script on their own. In other words, they are **not added** to other blocks, but they form an integral part of the block they are inserted to.

Function blocks contain a certain value. Their appearance depends on the type of information they contain:

•	the blocks with rounded edges contain numbers |XP| or strings |Costume|;
•	angular blocks contain values *True* or *False* |Touch|.

Command blocks and blocks that control the running of the program have input fields into which function blocks can be inserted. These input fields can have a rounded or hexagonal shape.  

.. |Vazno| image:: ../_images/Vazno.png

.. infonote::

    |Vazno|  In blocks which have rounded input fields |SayE|, we can insert both rounded and hexagonal function blocks |Say|, while blocks with a hexagonal input field |WUE|, can only receive hexagonal function blocks |WU|.


Next to function blocks, in categories where they are located, there are boxes that you can check. When you check these boxes, the value stored in these blocks will become visible on the stage.

.. image:: ../_images/blokovi/Touch.png   
   :align: center

The value stored in a function block can also be seen by clicking on the block itself. For example, the block |Touching| stores the value *false* because our sprite is not touching the displayed color, while the block |Sabiranje| stores the value *22*, because that is the sum of the numbers we see in the block).

.. mchoice:: BlokoviZadatak1
   :answer_a: When we click on the green flag, the sprite will say "true".
   :answer_b: When we click on the green flag, the sprite will say "false".
   :feedback_a: You are absolutely right!    
   :feedback_b: The angular function block returns the values True or False. Since the statement is 60>50 true, the sprite will say "true".
   :correct: a

   Analyze the script presented in the figure. Choose the result of the running of the program.
     .. image:: ../_images/blokovi/6050.png  
	:align: center