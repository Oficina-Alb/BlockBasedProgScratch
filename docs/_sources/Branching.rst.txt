Branching
===========

.. |If| image:: ../_images/grananje/If.png
.. |IfElse| image:: ../_images/grananje/IfElse.png
.. |And| image:: ../_images/grananje/And.png
.. |Or| image:: ../_images/grananje/Or.png
.. |Not| image:: ../_images/grananje/Not.png

We mentioned that repeating one or more commands (blocks) is a powerful concept in programming.

Equally useful and important is the **program branching concept**. Branching allows certain sets of blocks to be executed by the program, while others are not. Which commands will run depends on the fulfillment of the **conditions**. You should understand the condition as a statement that can be **true** or **false**. 

Even though, up until now, we have created programs that run commands one after the other, from the beginning until the end of the program, most of the programs contain branches.

There are two blocks for branching, and they are located in the category **Control**:

•	The block |If| checks the condition and if the condition is **true** it runs the blocks held inside it , and
•	The block |IfElse| checks the condition an if the condition is **true** it runs one set of commands, and if the result is **false** it runs another set.

.. |VeceOd| image:: ../_images/grananje/VeceOd.png
.. |Jednako| image:: ../_images/grananje/Jednako.png
.. |ManjeOd| image:: ../_images/grananje/ManjeOd.png

One way to determine if a condition is fulfilled is to select, from the category **Operators**, one of the **comparison operators**:

•	greater than |VeceOd|; 
•	less than |ManjeOd|;
•	equal to |Jednako|.

.. mchoice:: GrananjeZ1
   :answer_a: As a result of running script A, the program will write a sentence "I'll buy ice cream!".
   :answer_b: Running script A and B will have the same result - the programs will write a sentence "I'll buy ice cream!".
   :answer_c: As a result of running script B, the program will write a sentence "I'll buy ice cream!".  
   :feedback_a: Look carefully at the comparison operator in the script A. We believe that you can see that the program will write the sentence "I'll buy ice cream!" only if the price of the ice cream is less than 100 coins.    
   :feedback_b: Analyze how the comparison operator in script A is defined, and how it is in script B. We believe that you can see that in script A the sentence "I'll buy ice cream!" will be written only if the price of the ice cream is less than 100 coins. By running script B, the sentence "I'll buy ice cream!" will be written if the price is less than or equal to 100 coins.
   :feedback_c: Well done! The program will write the sentence "I'll buy ice cream!" if the price is less than or equal to 100 coins. 
   :correct: c

   The price of the ice cream is 100 coins. Analyze the scripts presented in the figure and select the correct statement.

   .. image:: ../_images/grananje/Sladoled.png
      :align: center

The easiest way to understand branching is to create a program that simulates a quiz. When we ask the user a question and wait for his/her answer, it is expected that we would provide feedback on whether the answer was correct or not. We can only provide information about the correctness of an answer when we determine whether the user's response is identical to the correct answer.

.. image:: ../_images/grananje/Kviz1.png
   :align: center

Even though it seems that we wrote the code correctly, and the correct answer to the question "How many legs does a dog have?" is 4, the user could answer the question by typing a string instead of a number. In other words, the correct answer to the question is not only 4, but also:

•	četiri; 
•	cetiri;
•	four.

It is obvious that we need to define the condition more carefully, i.e. to accept every possible correct answer.

We can overcome this situation by using the **logical operators**, which we can find in the category **Operators**:

•	and |And|; 
•	or |Or|;
•	not |Not|.

In our case, the correct answer can be **4 or četiri or cetiri or four**. This is why we will use the operator |Or| multiple times to define the condition. 

.. image:: ../_images/grananje/Uslov.png
   :align: center

The code, which accepts all possible forms of the correct answer looks like this:

.. image:: ../_images/grananje/Kviz2.png
   :align: center

.. |Uradi| image:: ../_images/Uradi.png

|Uradi| Children are used to touchscreen devices. They are not particularly skilled when it comes to using a mouse. We will help them develop this skill by creating a program with a Truck sprite and a Road as the backdrop. The truck should follow the user's mouse pointer and go from the left side to the right side of the stage. On its way, the truck must not touch the edge of the road. If the truck touches the edge at any point, it will return to its original position (starting position at the beginning of the journey on the left side of the stage - **x: -226**, **y: -41**). For creating this program, we recommend you use the project *Journey*, which you can find on |https://scratch.mit.edu/projects/326419371/|.

.. |https://scratch.mit.edu/projects/326419371/| raw:: html

 <a href="https://scratch.mit.edu/projects/326419371/" target="_blank">https://scratch.mit.edu/projects/326419371/</a>

.. image:: ../_images/grananje/Putovanje.png
   :align: center

As you can see, the Truck sprite is too big for the narrow road drawn on the backdrop of the stage we are using in this program. You can also see that the road is white and that a black line is separating the road from the grass. You should keep these things in mind if you want to create this program on your own. 

.. reveal:: sakrivanjeGrananje1
   :showtitle: Look at one of the possible solutions
   :hidetitle: Hide the solution
 
   **Possible solution**
     
   .. image:: ../_images/grananje/Putovanje1.png 
	:align: center

.. |Izazov| image:: ../_images/Izazov.png

|Izazov| It would be good if our program could measure how long it takes the user to "bring" the truck to the end of the road. Upgrade the program by adding the script, which will measure the time it takes the user to "complete the journey". 

.. reveal:: sakrivanjeGrananje2
   :showtitle: Look at one of the possible solutions
   :hidetitle: Hide the solution
 
   **Possible solution**
     
   .. image:: ../_images/grananje/Putovanje2.png 
	:align: center

|Izazov| Using the concepts and techniques shown in this and previous lessons create a program that simulates password entry when working on a computer. Let the program allow the user to enter the password three times. If the user fails to enter the correct password, the program will stop working. If the user succeeds, the sprite will change its costume. We recommend using the project, which you can find on the following link |https://scratch.mit.edu/projects/326403173/|, where we put the Laptop sprite that has two costumes. Good luck!  

.. |https://scratch.mit.edu/projects/326403173/| raw:: html

 <a href="https://scratch.mit.edu/projects/326403173/" target="_blank">https://scratch.mit.edu/projects/326403173/</a>

.. reveal:: sakrivanjePonavljanje1
   :showtitle: Look at one of the possible solutions
   :hidetitle: Hide the solution
 
   **Possible solution**
     
   You will find our solution in the project **Password solution**, at |https://scratch.mit.edu/projects/326417414/|. We recommend you remix the project and explain our solution by using comments. We know you can do it!

.. |https://scratch.mit.edu/projects/326417414/| raw:: html

 <a href="https://scratch.mit.edu/projects/326417414/" target="_blank">https://scratch.mit.edu/projects/326417414/</a>