Blloqet
=======

Programet kompjuterike janë grupe komandash, të cilat ne i përdorim për t'i shpjeguar kompjuterit se si të përfundojmë një detyrë të caktuar ose të zgjidhim një problem. Duke pasur parasysh që shumica e gjuhëve programuese janë tekstuale, zhvilluesit shpesh shtypin komanda.

Në gjuhën e programimit vizual Scratch, ne nuk shkruajmë komanda, por përkundrazi përdorim blloqe, të cilat i përfaqësojnë ato. Ne krijojmë programe duke rregulluar (grumbulluar) blloqe në rendin e duhur.

Llojet e bllokimeve në Scratch
----------------------------

Janë 4 lloje në Scratch: 

.. image:: ../_images/blokovi/4Bloka.png   
   :align: center

1. Blloqet komanduese;
2. Blloqe që lidhin ngjarjet me drejtimin e programit;
3. Blloqe që kontrollojnë drejtimin e programit;
4. Blloqe që raportojnë një vlerë të caktuar (blloqe funksioni).


Blloqet komanduese
~~~~~~~~~~~~~~~

Blloqet komanduese kanë nivele në krye dhe gunga në fund. Ato janë dizajnuar në një mënyrë që lejon që ata të lidhen (grumbulluar) me blloqe të tjera. Ne thjesht mund të tërheqim një bllok nga kategoria e përshtatshme në zonën e skripteteve (hapësirë për programim) dhe ta lidhim atë me blloqe të tjera, të cilat tashmë janë aty. Blloqet lidhëse duken si tërheqje magnetike - posa të vendosim një nivel të një blloku afër gungës së një tjetri, do të "ngjitet" në të, duke vazhduar kështu sekuencën. Gungat lejojnë që blloqet e reja të shtohen.

Blloqe që lidhin ngjarjet me ekzekutimin e programit
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

Këto blloqe kanë "kapele". Kjo do të thotë që ato mund të vendosen vetëm në fillim të një pirg blloqe. Zakonisht fillojmë një skenar me një nga këto blloqe. Në pjesën e poshtme, ata kanë gunga, të cilat lejojnë që blloqeve të reja t'u shtohen atyre.

Është e rëndësishme për ju të dini se këto blloqe paraqesin shkaktues, të cilët fillojnë ekzekutimin e skriptave bashkangjitur tyre. Për shembull, blloku |ZZ| siguron që blloqet e komandës bashkëngjitur tij të funksionojnë vetëm kur të klikohet flamuri i gjelbër, i vendosur sipër skenës.

Blloqe që kontrollojnë drejtimin e programit
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Ngjashëm me blloqet e komandës, blloqet që kontrollojnë drejtimin e programit kanë pika në krye dhe gunga në pjesën e poshtme. Ne mund t'i vendosim ato mbi blloqe të tjera, si dhe të vendosim blloqe të tjera poshtë tyre.

Këto blloqe karakterizohen gjithashtu nga aftësia për të akomoduar blloqe të tjera (blloqe të tjera mund të vendosen brenda tyre). Për shembull, skenari |R10M10| lejon sprite tona të lëvizin 10 hapa 10 herë.

Blloqe që raportojnë një vlerë të caktuar (blloqe funksioni)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Përveç formës së tyre, këto blloqe janë të ndryshme nga blloqet e tjera sepse nuk mund të jenë pjesë e skenarit më vete. Me fjalë të tjera, ato **nuk janë shtuar** në blloqe të tjera, por ato formojnë një pjesë integrale të bllokut në të cilin futen.

Blloqet e funksioneve përmbajnë një vlerë të caktuar. Pamja e tyre varet nga lloji i informacionit që ato përmbajnë:

• blloqet me skaj të rrumbullakosur përmbajnë numra |XP| ose vargjet |Costum|
• blloqet këndore përmbajnë vlera *True* ose *False* |Touch|

Blloqet komanduese dhe blloqet që kontrollojnë ekzekutimin e programit kanë fushat hyrëse në të cilat mund të futen blloqet e funksionit. Këto fusha hyrëse mund të kenë një formë të rrumbullakosur ose gjashtëkëndore.

.. |Vazno| image:: ../_images/Vazno.png

.. infonote::

    |Vazno|  Në blloqet të cilat kanë fushat hyrëse të rrumbullakosura |SayE|, mund të vendosim blloqe funksionesh të rrumbullakosura dhe gjashtëkëndore |Say|, ndërsa blloqet me një fushë gjashtëkëndore të hyrjes |WUE|, mund të marrin vetëm blloqe të funksionit gjashtëkëndor |WU|.


Pranë blloqeve të funksionimit, në kategoritë ku ato janë vendosur, ka kuti që mund t'i kontrolloni. Kur të kontrolloni këto kuti, vlera e ruajtur në këto blloqe do të bëhet e dukshme në skenë.

.. image:: ../_images/blokovi/Touch.png   
   :align: center

Vlera e ruajtur në një bllok funksioni gjithashtu mund të shihet duke klikuar në vetë bllokun. Për shembull, blloku |Touch| ruan vlerën *false* sepse sprite tona nuk po prekin ngjyrën e shfaqur, ndërsa blloku |Sabiranje| ruan vlerën *22*, sepse kjo është shuma e numrave që shohim në bllok).

.. mchoice :: BlokoviZadatak1
    :answer_a: Kur klikojmë në flamurin e gjelbër, sprite do të thotë "True".
    :answer_b: Kur klikojmë në flamurin e gjelbër, sprite do të thotë "False".
    :feedback_a: Ju keni absolutisht të drejtë!
    :feedback_b: Blloku i funksionit këndor kthen vlerat e vërteta ose false. Meqenëse deklarata është 60> 50 e vërtetë, sprite do të thotë "True".
    :correct: a

    Analizoni skenarin e paraqitur në figurë. Zgjidhni rezultatin e ekzekutimit të programit.
     .. image:: ../_images/blokovi/6050.png  
	:align: center
