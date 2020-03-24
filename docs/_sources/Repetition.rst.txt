Repetition
===========

We have already mentioned that repeating one or more commands (blocks) is a powerful concept in programming. When some of the commands run multiple times in a program, we say that the program contains **loops**. We have used this concept several times before.

.. |Repeat10| image:: ../_images/ponavljanje/Repeat10.png
.. |RepeatF| image:: ../_images/ponavljanje/RepeatF.png
.. |RepeatU| image:: ../_images/ponavljanje/RepeatU.png

In Scratch, we have 3 types of blocks that repeat commands:

•	The block that repeats commands a specific number of times; 
•	The block that repeats commands an infinite number of times;
•	The block that repeats commands until a specific condition is fulfilled.

We will insert the blocks we need to repeat into one of these blocks.

The block that repeats commands a specific number of times
-----------------------------------------------------------

.. |Uradi| image:: ../_images/Uradi.png
.. |Repeat10a| image:: ../_images/ponavljanje/Repeat10a.png
.. |Repeat5| image:: ../_images/ponavljanje/Repeat5.png

.. image:: ../_images/ponavljanje/Repeat10.png
   :align: center

We used the block that repeats commands a specific number of times in the project *Farm* (you can find more information in the lesson *Looks*).  

The chick sprite in the program was simulating the pecking motion by changing costumes a, b and c 10 times. After this simulation, the chick increased in size by 10. Our goal was to increase the size of the chick sprite by 50, so we repeated the part of the code that increased the size of the sprite 5 times. To achieve the desired behavior, we used the blocks |Repeat10a| and |Repeat5|.

In the figure below, we shrank the part of the script related to the repetition of commands, and we made the same program, but this time without using the repetition blocks. The script we got was really long, so for clarity, we had to divide it into five columns. 

.. image:: ../_images/ponavljanje/PileBezRepeat.png
   :width: 1200px   
   :align: center

|Uradi| Create the program *Farm* without using the blocks for repetition. Compare your code with ours. We believe that you can see that stacking identical groups of blocks makes the program longer, harder to understand and upgrade.

The block that repeats commands an infinite number of times
------------------------------------------------------------

.. |StopAll| image:: ../_images/ponavljanje/StopAll.png
.. |StopTS| image:: ../_images/ponavljanje/StopTS.png
.. |StopOS| image:: ../_images/ponavljanje/StopOS.png

.. image:: ../_images/ponavljanje/RepeatF.png
   :align: center

This block for repeating commands runs an infinite number of times. The running of this block never stops on its own. We have to stop it by clicking the button, which stops the program (the red button next to the green flag) or by using one of the following blocks |StopAll| / |StopTS| / |StopOS|, from the category **Control**.

We used the block that repeats commands an infinite number of times in the project *The cat is chasing the mouse* (you can find more information in the lesson *Motion*).

.. mchoice:: PonavljanjeZ1
   :answer_a: New blocks can be inserted into the block itself, so there is no need to continue the script.
   :answer_b: It is a bug in Scratch. The block for infinite repetition must have an option for continuing the script. 
   :answer_c: Adding the blocks is pointless because they would never run.  
   :feedback_a: The option to insert new blocks into the block |RepeatF| does not provide the possibility to stack scripts that will never be repeated, it just adds commands that will be repeated an infinite number of times.    
   :feedback_b: How likely is it that one of the most frequently used blocks in Scratch is not constructed properly? We suggest you think again about the question and give a new answer. 
   :feedback_c: Great conclusion, well done!  
   :correct: c

   Analyze the appearance of blocks for repeating commands. You can see that the block, which repeats commands an infinite number of times, does not have the option to connect with other blocks, i.e. you cannot add another block onto it. Why?
   

The block that repeats commands until a specific condition is fulfilled
-------------------------------------------------------------------------

.. |VSec| image:: ../_images/ponavljanje/Vsec.png

.. image:: ../_images/ponavljanje/RepeatU.png
   :align: center

This block for repeating commands runs until a certain condition is fulfilled. The scripts within this block are executed based on a test, which determines whether the condition placed in the block is true or not. We use this block when we do not know how many times we need to repeat commands within the block for repetition, and therefore, we want them to run until a certain condition is fulfilled.

.. mchoice:: PonavljanjeZ2
   :answer_a: The block that repeats commands a specific number of times.
   :answer_b: The block that repeats commands an infinite number of times. 
   :answer_c: The block that repeats commands until a specific condition is fulfilled.  
   :feedback_a: If you choose this block, firing rockets has nothing to do with your sprite's energy level, does it?  
   :feedback_b: If you choose this block, firing rockets has nothing to do with your sprite's energy level, does it?
   :feedback_c: You are right! The number of repetitions depends on the fulfillment of the conditions. The moment your sprite's energy level drops below a certain value, firing rockets will stop.  
   :correct: c

   You want to create a program where your sprite (hail cannon) is firing rockets on hail-bearing clouds until its energy level falls below a certain value. Which block for repeating commands will you use?

We will demonstrate how a *block that repeats commands until a specific condition is fulfilled* works - we will create a program that functions as a timer, i.e. it counts down seconds from the entered value to zero.

For this program, we will create the variable |VSec|, which will store the value of the remaining seconds while the timer is counting down. We will ask the user to enter a certain number of seconds. Then, we will start the countdown. After the entered time has elapsed, we will hear a sound signal.

The figure below contains our suggestion of the program's code with comments, which serve as an explanation. Programmers find it helpful to comment on scripts and explain what certain blocks do. Commenting makes it easier for other programmers to understand and upgrade the programs we create. You can add a comment by right-clicking on the script, and selecting the option **Add comment**.

.. image:: ../_images/ponavljanje/Tajmer.png
      :align: center

|Uradi| The program *Timer* can be found on the link |https://scratch.mit.edu/projects/326420353|. Upgrade it by adding a clock ticking sound, which will be heard as the timer counts down.

.. |https://scratch.mit.edu/projects/326420353| raw:: html

 <a href="https://scratch.mit.edu/projects/326420353" target="_blank">https://scratch.mit.edu/projects/326420353</a>