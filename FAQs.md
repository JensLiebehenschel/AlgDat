Interested in a some more information? - Sure, here we go, see my answers to questions you might have.

What is the main idea behind this approach?
- My goal was to have a tool to enable a better understanding of algorithms and data structures.
- There was one main criterion: It should be a static view that discloses the steps of algorithms "at a glance".
- Obviously, this is much easier for algorithms working with linear data structures than with graphs, for example.
  - For linear data structures we can use an additional dimension (e.g. the x axis) for visualization of the behavior over time.
- All notebooks are stand-alone, i.e. can be used without the others.

What is the history of this approach?
- Since I lectured algorithms and data structures for the first time in 2016 I was looking for a good visualization of algorithms.
- There was a prototype for visualizing sorting algorithms.
  - Different algorithms were implemented.
  - A generic approach for the helping functions e.g. for visualization was implemented.
- From time to time I looked at it but most of the time neglected working on it.
- During preparation of the lecture for summer 2021 the topic came back to my focus.
  - The main point was to simplify working on a single algorithm and/or data structure.
  - This resulted in removing the generic approach to simplify the code at the price of increasing redundancy.

Why was this public repository created?
- It is easier to access it from outside the university network.
- I also want to make this work available to people outside Frankfurt University of Applied Sciences.

What are the references?
- Only for the standard algorithms and data structures sources were used.
- The material and the python code we provide to our students, initially created by my colleague Jörg Schäfer.
  - This is based among other literature on the book Introduction to Algorithms by Cormen et. al.

Why Python?
- Well, why not? - Ok, I made the answer too easy for me.
- There are so many reasons, it is easy to learn, you can write compact code, and used in many domains.
- Python is appropriate for quickly writing powerful code.
- Further it is the language for data science and artificial intelligence, so it is worth learning it.

Sometimes the code is not pythonic, why?
- This is done due to didactical reasons (again an easy answer) ...
- ... but: The goal is to learn about basic algorithms and data structures, so we need to see all calculation steps.
- Python offers most of the functionality with a single method call, but one cannot see what is going on.
  - Examples: methods index() and sort() for lists instead of algorithms searching and sorting functions.

I found several code duplicates. Is this a good style of programming?
- No, definitively not!
- I decided to do this for didactical reasons - again.
  - Every notebook shall be usable stand-alone without loading additional functionality from other files.
  - In the notebooks duplicates could be prevented by using dedicated methods, but this would increase the amount of code to look at.
- Try to prevent code duplicates in any productive software.

Why Jupyter notebooks?
- It is a good way to work with Python code.
- Simply use it on your computer without any software installation by launching the binder.

What can I do with the provided Jupyter notebooks?
- There are many possibilities, just play around with the algorithms and data structures.
- You can have a look at the notebooks, at the code, the statistics and the visualization.
- You can run them with the same or other data, our or even better with code changes.
  - Example: Modifications for getting other statistics or different visualizations.
- You can play around with the code and adapt it to your individual needs.

Do I need to use the launch binder icon to work with the notebooks?
- No, you certainly can download the code or fork the repository and work locally on your computer.
- Anyway, you need the have a working installation of Jupyter notebooks. (I used version 6.1.4 with python 3.8.5 for initial development.)
- In this case you can also save your changes in your environment.

Why are there different notebooks for all algorithms and data structures?
- Quite simple, they have different objectives.
- You always find one with the basic functionality, here you can start using the algorithms.
- Then you might find other notebooks with more functionalily but less clarity of the basic algorithms due to necessary code instrumentation.
  - Examples: Output of runtime statistics or graphical visualization of the behavior.

Why are there different statistics for different algorithms?
- I tried to show different aspects that gain insight into the behavior of the algorithms.
- If you would like to see other statistics, please implement them on your own.

Is there any documentation for the notebooks?
- Yes and no!
- Yes, inside the notebooks, some hopefully useful information in headings and code comments, and also speaking names in the code.
- No, there is no separate description outside the code. Anyway, the code is quite small and should be understandable in acceptable time.

How to start?
- Several possibilities, you first need to know what you want to look at.
- Here are only some ideas, there are many more possibilities.
- First, select an algorithm or a data structure you want to understand.
- Then have a look at the available notebooks and understand what is implemented, the notebook name describes the content.
- Finally adapt the code to see what happens. Does it behave as expected?
  - Modify the code, e.g. invert the sorting order of sorting algorithms.
  - Add additional outputs to observe the behavior.
  - Add additional statistics to better understand what happens at runtime.
  - The visualization notebooks contain boolean variables to control the output. Modify them and observe the behavior.
- You also can work with several notebokks in parallel, e.g. compare the number of key comparisions and key exchanges by two sorting algorithms.

Will there be more algorithms and data structures in the future?
- Maybe, we will see.

What to do if I find an error or want to make a suggestion for improvement?
- What, an error? No, unbelievable - Ok, it is software and there are errors ...
- ... and great, just contact me via email, perhaps you already have a fix for it.
- If you want to contribute, also send me an email.

Anything else?
- Yes, I hope it is useful for understandig the basic algorithms and data structures.
- Playing around with the code supports you in understanding the algorithms and data structures.
- The more you play around with the code, the deeper your understanding might get.
- Have fun using the notebooks and learning!

Jens Liebehenschel, liebehenschel@fb2.fra-uas.de, Frankfurt University of Applied Sciences, FB2, Computer Science, March 2021
