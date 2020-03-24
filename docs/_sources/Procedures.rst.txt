Procedures
===========

We don't have to create the program as a whole.

It is far more clear if we divide pieces of code into smaller, separate parts - **procedures**. Defining procedures makes writing programs and finding mistakes easier. That is why it is good to keep the procedures in your "backpack". That way, you will be able to use them in other programs you create, and not waste time on making them again. 

Broadcasting
-------------

Programs made in Scratch usually have multiple sprites that interact with each other. We can define the interaction ourselves, and we can also use the built-in procedure That allows the sprites to broadcast messages and affect the running of the program. Using the broadcasting procedure will significantly decrease the number of blocks in the program, and it will make it easier for us to read the code. 

.. image:: ../_images/procedure/ProcZ1a.png
   :width: 800px   
   :align: center

.. image:: ../_images/procedure/ProcZ1b.png
   :width: 800px   
   :align: center

.. mchoice:: ProcedureZ1
   :answer_a: Program A
   :answer_b: Program B
   :feedback_a: When we run the program, we can see that all three girls are saying hello in their own language at the same time. This would not be the case in real life, during a normal conversation. We usually listen to the person we are talking to, and then we speak.     
   :feedback_b: You are right! When we broadcast the messages, we allow everyone participating in the conversation to be polite - and not interrupt one another.
   :correct: b

   There are two programs - A and B, presented in the figures above. Both programs contain 3 sprites, girls speaking English, German and French. Below each girl are blocks that belong to them (the blocks allow them to say hello to the other two in their own language). Create programs you see in the figures above. Analyze what happens when they run. Which program represents a simulation of a normal (regular) conversation between three strangers? 

.. reveal:: sakrivanjeDevojke
   :showtitle: Watch the video instruction for creating the conversation between three girls
   :hidetitle: Hide the video instruction
 
   **Watch the process of creating the program, which allows the girls to speak without interrupting one another:**
     
   .. youtube:: QgCCzBw6DKU
      :width: 735
      :height: 415
      :align: center

Defining a new procedure
--------------------------

.. |Vazno| image:: ../_images/Vazno.png

.. |Uradi| image:: ../_images/Uradi.png

In Scratch, we can create a new procedure that would correspond to our needs. 

Imagine that we want to create a program, which draws a flower on the stage. A flower is made of petals. Therefore, we need two procedures:

•	**Petal**, within which we will define the drawing of one petal, and
•	**Flower**, within which we will define the drawing of five petals.

In other words, the procedure **Flower** will call the procedure **Petal**, and the main program will call the procedure **Flower**.

We create a procedure by clicking on the category **My Blocks**, where we should click on the button **Make a Block**. A window will open, which will allow us to name our procedure.

.. image:: ../_images/procedure/ProcLatica.png
   :width: 600px   
   :align: center

If you want your flower to have the same petals like the one in the figure below, create the procedure **Petal** we presented:

.. image:: ../_images/procedure/KodProcLatica.png
   :width: 780px   
   :align: center

|Uradi| We will let you make a procedure, which draws 5 petals. **Little help**: After drawing one petal, you need to turn the sprite 72 degrees to the right.

.. reveal:: sakrivanjeCvet1
   :showtitle: Compare your solution with ours
   :hidetitle: Hide the solution
 
   **Possible solution**
     
    .. image:: ../_images/procedure/Cvet.png
	:width: 770px   
	:align: center

.. infonote::

  |Vazno|   **So, by using procedures, we make writing programs and finding mistakes easier.**




   
   
