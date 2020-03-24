Variables
===========

We believe that you know multiple people can use one program and that you know this from your own experience. We create programs with the intention of making solving and performing tasks easier. We create them to have fun, relax, and connect with other people. 

The fact that one program can be used by multiple people, who enter their data and receive corresponding results, tells us that programming has an excellent concept of managing and using computer memory. 

Think of the memory of a digital device as being a huge, we mean enormous, almost endless room with rows and rows of shelves. Now, imagine that you can put data into every compartment on every shelf. Finally, imagine that you can name each of these compartments whatever you wish and, as soon as you call its name, the information in it becomes immediately available. 

We call these "compartments" of computer memory **variables**. A variable can potentially contain only one piece of information (a number, string, values true or false, etc.).   

Ask and Wait
-------------

In the category **Sensing** there is a block **Ask and wait** |BlokAskWait|. This blocks allows us to ask the user for something (usually in the form of a request or a question), and then wait for the user to click the button |Stikliranje| or press *Enter*.
  .. |BlokAskWait| image:: ../_images/promenljive/BlokAskWait.png
  .. |Stikliranje| image:: ../_images/promenljive/Stikliranje.png

User's response is entered into the variable |VAnswer|, and the program continues to run.
    .. |VAnswer| image:: ../_images/promenljive/VAnswer.png

|Uradi| It's best we use this block immediately. We will create a program in which the cat asks the user for his/her name, and then repeats the name and says that it is a very lovely name.
  .. |Uradi| image:: ../_images/Uradi.png

.. image:: ../_images/promenljive/KodPromenljivaAnswer.png   
   :align: center

Therefore, we will start the program by clicking on the green flag. After the command |BlokAsk|, the program stops running, expecting the user to type in his/her answer into the input field and click on the button |Stikliranje| or press *Enter*. At that moment, the content of the variable |VAnswer| does not exist |Answer|.
    .. |BlokAsk| image:: ../_images/promenljive/BlokAsk.png
    .. |Answer| image:: ../_images/promenljive/Answer.png

When the user enters the answer (e.g. Mima) and clicks the button |Stikliranje| or presses *Enter*, the content of the variable |VAnswer| will be |AnswerMima|.
    .. |AnswerMima| image:: ../_images/promenljive/AnswerMima.png

Now, the cat can say the string |BlokSay|, which we made by using the block for connecting strings |Join| (in the field *apple* we put the variable |VAnswer|, and in the field *banana* we put the string "is a lovely name!". 
    .. |Join| image:: ../_images/promenljive/Join.png
    .. |BlokSay| image:: ../_images/promenljive/BlokSay.png

In the figure below, you can see our program when it runs.

.. image:: ../_images/promenljive/TokPromenljivaAnswer.png   
     :align: center

Creating Variables
----------------------

Let's look at the situation where the user enters 4 numbers, then the program adds the numbers and displays the sum. It is true that the block **Ask and wait** |BlokAskWait| allows the user to enter a certain value, which will then be placed in the variable |VAnswer|. Nevertheless, what happens when we need 4 answers?

.. mchoice:: Promenljive1
   :answer_a: 50
   :answer_b: 30
   :answer_c: 20
   :answer_d: 80
   :correct: d
   :feedback_a: The variable contains only one piece of information (a number, string, value true or false, etc.). Think again and choose the correct answer. 
   :feedback_b: The variable contains only one piece of information (a number, string, value true or false, etc.). Think again and choose the correct answer.
   :feedback_c: The variable contains only one piece of information (a number, string, value true or false, etc.). Think again and choose the correct answer.
   :feedback_d: You are right, well done! The variable |VAnswer| contains only the user's final answer, and that is number 20. The sprite will say 80 (20+20+20+20).

   The user enters the following numbers one after the other: 5, 10, 15 and 20. When the program shown in the figure runs, the sprite will say:

   .. image:: ../_images/promenljive/4pitanja.png   
     :align: center

It is obvious that we need more than one variable for the program to be able to display the correct sum.

We create the variables in the category **Variables**, by clicking on the button **Make a variable**. A window will open where we can type in the name of the variable, and then we decide if we want to make it available to all sprites or only to the sprite that is active while we are creating the variable. We can also check the option that saves the variable on the server, in the data cloud. Finally, clicking the button **OK** creates the variable.

In the figure below, we can see the block, which will become available to us once we have created the variable. With the first block, we will set the value of the variable, the second one we can use if we want to increase or decrease that value, while the third and the fourth are used to make the variable visible or to hide it. 

.. image:: ../_images/promenljive/MakeVariable.png   
   :align: center

.. mchoice:: Promenljive2
   :answer_a: Running of scripts A and B has the same result 
   :answer_b: Running of scripts A and B has different results 
   :correct: a
   :feedback_a: Well done! Even though they are different, the running of both programs has the same result. 
   :feedback_b: Think about your answer. If you still think the same, create these programs in Scratch and run them. Don't forget to arrange so that the values of the variables can be seen on the stage.

   Analyze the scripts and mark the correct statement: 

   .. image:: ../_images/promenljive/4brojaProm.png   
     :align: center


