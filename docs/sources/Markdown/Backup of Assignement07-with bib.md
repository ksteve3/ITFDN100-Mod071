Kate Stevens

November 20, 2019

IT FDN 100 A

Assignment07

Exception Handling & Pickling

*Assignment07: Research and document your knowledge about the use and benefits of the Pickle module and exception handling in Python. The full assignment and further notes following this week’s discussions can be viewed or downloaded here: *[Assigment07.pdf](https://canvas.uw.edu/courses/1342958/modules/items/9973247)*[64]** (external link), *[_Mod7PythonProgrammingNotes.pdf](https://canvas.uw.edu/courses/1342958/modules/items/9973246)* **[65]** **(external link).*

Intro

The primary focus of week seven of Introduction to Python Programing, consisted of demonstrations on how to work with and configure error handling in Python which included the topics of try/except blocks, exception errors, built-in and custom error exceptions and exception classes, and Python’s Pickling Module. The secondary focus of this week was on learning how to use [basic writing and formatting syntax](https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax) [86] (external link ) using Jekyll. used to build and present personal and professional scripting projects with GitHub Webpages. 

This weeks assignment consists of researching and documenting knowledge on the following bullet point topics and programming methods and presenting our research on GitHub Webpages using Jekyll’s writing and formatting syntax discussed in  Mod07 YouTube tutorial found at [Module07 Course Video ](https://youtu.be/4IkIdXJBC6o)[65] (external link), starting at 1:30:00.

The following topics will be briefly discussed in this document containing the sources and conclusions of my research pertaining to Assignment07’s research exercise detailed in [Assigment07.pdf](https://canvas.uw.edu/courses/1342958/modules/items/9973247) [64] (external link).

# ![image alt text](image_0.png)[Exception Handling in Python ](#heading=h.tyjcwt)

# ![image alt text](image_1.png)[Pickling in Python ](#heading=h.qsh70q)

*Exception Handling in Python *

*(Assignment Overview)** **[71]*

#### Search the web for examples of how to use Python’s exception handing features. Make note of the URL for any pages you feel are good at explaining the subject, and why you feel that way. 

# Topic overview

Exception handling protocols are written/implemented by a script’s author(s) to make troubleshooting easier for users or other developers. This type of script editing helps to replace long, incomprehensible traceback error messages (for those who are not developers) with more specific and/or conducive instruction to follow if an error occurs while running a script/program.  

These traceback errors can appear with basic user interaction, reading /writing data files, and edits or manipulation to the code that prevents the program from running correctly. If traceback messages are not addressed and met with some form of error anticipation/moderation by the script author(s), it will cut back on intended efficiency and productivity for other developers as well as deter others from using, utilizing or running the program altogether. To help guide or provide a user or fellow developer with a good experience using your program/script, many programmers will start by refining their code using "if/Elif" Error Handling processes.

Error handling is also useful for developers because it provides useful insight to anticipate sections of our code that might throw an error or an exception for other future users down the road. 

With this information, developers can try to configure error blocks and handle them in the way that we want instead of allowing Python (and/or other programming languages) to auto-generate and present a string of obscure and/or vague error messages to the end-user.

I located external sources by searching ‘Exception Handling’ key phrases mentioned in [_Mod7PythonProgrammingNotes.pdf](https://canvas.uw.edu/courses/1342958/modules/items/9973246) [68] (external link, Listing 11-15). The Top two resources I found most useful (other than the [Module07 Course Video[65] ](https://youtu.be/4IkIdXJBC6o)(external link)) was in the format of a YouTube Tutorial, [Python Tutorial: Using Try/Except Blocks for Error Handling](https://www.youtube.com/watch?v=NIWwJbo-9_8) [86] (external link) and it’s linked [GitHub Repository page](https://www.youtube.com/redirect?q=https%3A%2F%2Fgithub.com%2FCoreyMSchafer%2Fcode_snippets%2Ftree%2Fmaster%2FExceptions&event=video_description&v=NIWwJbo-9_8&redir_token=xVJvI7xsA5txpuMJMcr_Z2-gkJB8MTU3NDQ4MTIxM0AxNTc0Mzk0ODEz) [87] (external link) posted in the authors information. I appreciated how closely related the examples were to the material discussed in the Mod07 tutorial, as many of the outside resources I come across tend to be either more advanced/specialized modifications or workarounds with limited description.

The Exception Handling examples below describe three ways to implement Python’s Exception handling functionalities modeled in the YouTube Tutorial, [Python Tutorial: Using Try/Except Blocks for Error Handling](https://www.youtube.com/watch?v=NIWwJbo-9_8) [86](external link).

The tutorial I choose to model the following examples from, stood out to me because it allowed the viewer to experience the narrators fluid and uncut thought process while evolving the code through several stages of performance and efficiency allowing the viewer to "Thought Shadow" every step of his development process and logic. 

##### *Exception Handling in Python*

##### *Examples 7.1, 7.2, 7.3*

Prerequisites

##### ![image alt text](image_2.png) Video Tutorial Reference: [26]

#####  (Examples 7.1, 7.1, 7.3): 

*[Python Tutorial: Using Try/Except Blocks for Error Handlin*g](https://www.youtube.com/watch?v=NIWwJbo-9_8) [86] (external link), Timestamp: 00:50

##### GitHub Starter Code Download (Examples 7.1, 7.1, 7.3):

# [CoreyMSchafer](https://github.com/CoreyMSchafer)/[code_snippets](https://github.com/CoreyMSchafer/code_snippets)[2]

Branch: master 

Top of Form

[code_snippets](https://github.com/CoreyMSchafer/code_snippets)/**Exceptions**

<table>
  <tr>
    <td>Name</td>
    <td>Latest commit message</td>
    <td>Commit time</td>
  </tr>
  <tr>
    <td>..</td>
    <td> </td>
    <td> </td>
  </tr>
  <tr>
    <td>currupt_file.txt</td>
    <td>Added Python code snippets</td>
    <td>3 years ago</td>
  </tr>
  <tr>
    <td>exceptions.py</td>
    <td>Added Python code snippets</td>
    <td>3 years ago</td>
  </tr>
  <tr>
    <td>test_file.txt</td>
    <td>Added Python code snippets</td>
    <td>3 years ago</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>


*Examples 7.1 – Basic Exception Handler*

*To follow along download the Tutorial’s starter code.*

Description:

 Anticipate areas in your code that may throw an error that will cause a user to see a default traceback error message when ran. Use the reference tutorial to learn how we can handle exceptions in specific ways to look at the control flow of a try/except/else/finally statement to replace default traceback error messages with custom or built-in error messages to help increase the speed and productivity of troubleshooting.

7.1 Output Requirements:  

Create a Try/Except code handling block with limited capabilities to notify the developer/user of a FileNotFound error.  

##### *7.1 Example overview:*

Example 7.1, starts out with Starter-code (Figure 1) from the YouTube tutorial, referenced above, that has that has two problems to be addressed in order to achieve the desired output requirements (above).  

*Error 1:*

In this case the code instructs to open a file, however the name of the file specified as ‘testfile.txt’ (Figure 1, Figures 3 red) which does not exist in the project’s directory, because the name of the file or path is wrong which result in a default traceback error message when the code is run. 

*Error 2:*

Figures 1 & 3 also shows that a Try/except exception block has been accepted in the code but skipped over because the exception is read as a "pass" otherwise known as a placeholder. In order to implement an Exception handler to override Python’s default traceback error message shown in (Figures 1 & 3), the developer must replace “pass” (shown in Figures 1 & 3) with a valid exception handler. 

7.1 Input "Starter-code" (without exception handler)

Figure 1: User Input with incorrect file name (red) without an active exception handler in place of the "pass" placeholder. 

*7.1 Output "Starter-code" (without exception handler)*

![image alt text](image_3.png)

Figure 2: Default error message "output" displayed in CMD running code from Figure 1.

*7.1 Input / Output "Starter-code" viewed in PyCharm (without exception handler)*

![image alt text](image_4.png)

Figure 3: Displays for the flawed Input errors resulting in an Output with default traceback error message.

*7.1 Input code: Basic Exception Handling*

![image alt text](image_5.png)

*Figure 4: Shows how to manipulate the code from Figure 1 to successfully call an Exception handler to output a basic FileNotFound message back to the user whenever the defined exception occurs in the future. *

*7.1 Input/output results: Basic Exception Handling*

![image alt text](image_6.png)

*Figure 5: Highlights the changes made in figure four resulting in the custom error message we input in Figure 4. *

*7.1 Output results: Basic Exception Handling*

![image alt text](image_7.png)

Figure 6: 7.1 Solution output od code found in Figure 4

##### *Example:7.2- *Custom Exception Handlers

7.2 Output Requirements:

*Create a Try/Except code handling block with multiple exception capabilities to notify the developer/user of a FileNotFound error using custom error messages.  (Use Figure 5 input code as "starter-code")*

# *7.2 Example Overview*

Figures 6, 7 & 8 show the successful implementation of a Try/Except exception handler using customized error handling messages for defined error occurrences. 

Using the successful Try/except block code from Example 7.1, Figure 4 as "starter code", manipulate the Try/except block to implement multiple exception handlers with custom error message descriptions. 

*7.2 Input (use Figure 5 Input as starter code)*

![image alt text](image_8.png)

Figure 7:  Shows new version of Try/except block after it has been manipulated using the "starter-code" from used in example 7.1, Figure 4.  This new Try/except block uses the developer’s custom exception handler descriptions to display error messages for multiple errors that could occur. 

*7.2 Figure 7 Output (first exception output)*

![image alt text](image_9.png)

*Figure 8: Output of first Exception handler, which displays a NameNotFound exception with a custom error message, "1. Sorry, this file does not exist" indicating the file name or the file path is wrong or does not exist in the project directory. Edit “open(‘<example>.py’)”.*

*7.2 Figure 7 Output (second exception output)*

![image alt text](image_10.png)

Figure 9: Output of second Exception handler, which displays the custom error message, "2. Sorry, something else went wrong" when a name is not defined in the code. 

### *Example:7.3 – Built-in Exception Handling *

Please also refer to python.org "Built-in Exceptions — Python 2.5.17 documentation" [80]

7.3 Output Requirements:  

Create a Try/Except code handling block with multiple exception capabilities to notify the developer/user when an error occurs using Python’s built-in exception handlers.

Example 7.3 Overview

Figures 10, 11 & 12 show the successful implementation of a Try/Except block using Python’s built-in error handling messages. 

Using the successful Try/except block from Example 7.2, Figure 7 as "starter code, manipulate the Try/except block code to implement multiple exception handlers with built-in error message descriptions.  

* 7.3 Input*

![image alt text](image_11.png)

*Figure 10:  Shows new version of Try/except block after it has been manipulated using the "starter-code" used in example 7.2, Figure 7  This new Try/except block uses Python’s “Built-in” exception handlers to display multiple error message descriptions to display a variety of different errors that could occur*. 

*7.3 Output*

![image alt text](image_12.png)

*Figure 11: Output of first Exception handler, which displays a name error exception with a built-in error handling message, "name ‘bad_var is not defined" indicating the file name or variable has not been defined in the code.*

*7.3 Input / Output PyCharm Overview*

![image alt text](image_13.png)

Figure 12: Shows both the corrected code input and its output results after the addressing the errored line of code that triggered a built-in error description to be displayed in Figure 11. After the errored line of code was commented out <var = bad_var> and the wrong file name <’testfile.txt’> (responsible for error codes in displayed in Figures 4 & 5) was changed to <’test_file.txt’>, the "try: file = open(‘<example>’)" statement finally was able to run successfully without error disruptions (Figure 13). 

*7.3 Output (Successful debugging)*

![image alt text](image_14.png)

Figure 13: Exception handling success!

*Pickling in Python*

* (Assignment Overview)** **[71]*

*Search the web for examples of how to use Python’s Pickling features. Make note of the URL for any pages you feel are good at explaining the subject, and why you feel that way.*

*:mod:`pickle` --- Python object serialization* [29]

The [pickle](https://docs.python.org/2/library/pickle.html#module-pickle) [49] module implements a fundamental, but powerful algorithm for serializing and de-serializing a Python object structure. "Pickling" is the process whereby a Python object hierarchy is converted into a byte stream, and “unpickling” is the inverse operation, whereby a byte stream is converted back into an object hierarchy. Pickling (and unpickling) is alternatively known as “serialization”, “marshalling,” [49] or “flattening”, however, to avoid confusion, the terms used here are “pickling” and “unpickling”.

![image alt text](image_15.png)

Figure 14: Security warning - [python.org](https://docs.python.org/3/library/pickle.html) [58](external link)

# Defined Functions of Pickle Module: 

*Apart from the **Pickler** and **Unpickler** classes, the module defines the following functions, and an exception:*

**dump** (*object, file*[*, bin*])

Write a pickled representation of *object* to the open file object *file*. This is equivalent to "Pickler(*file*, *bin*).dump(*object*)". If the optional *bin* argument is present and nonzero, the binary pickle format is used; if it is zero or absent, the (less efficient) text pickle format is used.

**load** (*file*)

Read a pickled object from the open file object *file*. This is equivalent to "Unpickler(*file*).load()".

**dumps** (*object*[*, bin*])

Return the pickled representation of the object as a string, instead of writing it to a file. If the optional *bin* argument is present and nonzero, the binary pickle format is used; if it is zero or absent, the (less efficient) text pickle format is used.

**loads** (*string*)

Read a pickled object from a string instead of a file. Characters in the string past the pickled object's representation are ignored.

PicklingError

This exception is raised when an unpicklable object is passed to Pickler.dump().

Pickle Exceptions

Below are some of the common exceptions raised while dealing with pickle module −

Pickle.PicklingError: If the pickle object doesn’t support pickling, this exception is raised.

Pickle.UnpicklingError: In case the file contains bad or corrupted data.

EOFError: In case the end of file is detected, this exception is raised.

*See Also:*

Module [copyreg](https://docs.python.org/2.0/lib/module-copyreg.html) [32] (external link):

pickle interface constructor registration.

<table>
  <tr>
    <td>Module shelve [61] (external link) </td>
  </tr>
</table>


indexed databases of objects; uses pickle.

Module [copy](https://docs.python.org/2.0/lib/module-copy.html)[91] (external link):

shallow and deep object copying.

Module [marsha](https://docs.python.org/2.0/lib/module-marshal.html)[l](https://docs.python.org/2.0/lib/module-marshal.html) [63](external link):

high-performance serialization of built-in types.

Advantages of using Pickle Module:

* Comes handy to save complicated data.

* Easy to use, lighter and doesn’t require several lines of code.

* The pickled file generated is not easily readable and thus provide some security.

* Recursive objects (objects containing references to themselves): Pickle keeps track of the objects it has already serialized, so later references to the same object won’t be serialized again. (The marshal module breaks for this.)

* Object sharing (references to the same object in different places): This is similar to self- referencing objects; pickle stores the object once and ensures that all other references point to the master copy. Shared objects remain shared, which can be very important for mutable objects.

* User-defined classes and their instances: Marshal does not support these at all, but pickle can save and restore class instances transparently. The class definition must be importable and live in the same module as when the object was stored.

*Disadvantages of Using Pickle Module*

* Languages other than python may not able to reconstruct pickled python objects.

* Risk of unpickling data from malicious sources (see Figure 16 ) 

Security Alert 

(At your own risk.  Use with caution)

![image alt text](image_16.png)

*Figure 15: Security warning - **[python.or*g](https://docs.python.org/3/library/pickle.html)* **[58]** (external link)*

*2.1 Register Pickle Python.org *[50], *[92], [70]*

*Example Code*

# [copyreg](https://docs.python.org/2/library/copy_reg.html#module-copy_reg) — Register [pickle](https://docs.python.org/2/library/pickle.html#module-pickle) support functions

The [copyreg](https://docs.python.org/2/library/copy_reg.html#module-copy_reg) module offers a way to define functions used while pickling specific objects.

The [pickle](https://docs.python.org/2/library/pickle.html#module-pickle), [cPickle](https://docs.python.org/2/library/pickle.html#module-cPickle), and [copy](https://docs.python.org/2/library/copy.html#module-copy) modules use those functions when pickling/copying those objects. The module provides configuration information about object constructors which are not classes. Such constructors may be factory functions or class instances.

#### *copyreg.constructor(object)*

* Declares *object* to be a valid constructor. If *object* is not callable (and hence not valid as a constructor), raises [TypeError](https://docs.python.org/2/library/exceptions.html#exceptions.TypeError) [88] (external link).

*copyreg.pickle(type, function[, constructor])*

* Declares that *function* should be used as a "reduction" function for objects of type *type*; *type* must not be a “classic” class object. (Classic classes are handled differently; see the documentation for the [pickle](https://docs.python.org/2/library/pickle.html#module-pickle) module for details.) *function* should return either a string or a tuple containing two or three elements.

* The optional *constructor* parameter, if provided, is a callable object which can be used to reconstruct the object when called with the tuple of arguments returned by *function* at pickling time. [TypeError](https://docs.python.org/2/library/exceptions.html#exceptions.TypeError) [88] (external link). will be raised if *object* is a class or *constructor* is not callable.

* See the [pickle](https://docs.python.org/2/library/pickle.html#module-pickle)[49] (external link) module for more details on the interface expected of *function* and *constructor*.

# *2.1 copyreg – Pickle Registration Example *[47] [70]

![image alt text](image_17.png)

*Figure 16*

*#TODO<img>![^](:// "^")   </caption>*

*#TODO<href/> [2.1-Listing 16 Image](https://ksteve3.github.io/ITFnd100-Mod07/Snips/Pickle/2.1/Figure 16.png " "2.1-Listing 16 Image") ,(GitHub Page)*

#TODO<href/> [2.1-Listing 26](https://ksteve3.github.io/ITFnd100-Mod07/Snips/Pickle/2.1/2.1 - Listing 16 .py "2.1-Listing 16"), (GitHub Page)

#TODO<href/> [2.1-Listing 26](https://ksteve3.github.io/ITFnd100-Mod07/Snips/Pickle/2.1/2.1 - Listing 16 .txt "2.1-Listing 16") ,(GitHub Page)

# *2.2 Pickle / Unpickle*

*Example Code*

# 2.2 Python Pickling & Unpickling [69] [94]

Python pickle module is used for serializing and de-serializing python object structures. The process to converts any kind of python objects (list, dict, etc.) into byte streams (0s and 1s) is called pickling or serialization or flattening or marshalling. We can converts the byte stream (generated through pickling) back into python objects by a process called as unpickling. 

*Why Pickle?: *

In real world scenario, the use pickling and unpickling are widespread as they allow us to easily transfer data from one server/system to another and then store it in a file or database.

*Figure 18: Security warning - **[python.or*g](https://docs.python.org/3/library/pickle.html)* [60] (external link)*

Note Before you Unpickle:

* *Only after importing pickle module we can do pickling and unpickling. *

* *On running above script(unpickle) (below) we get our dictionary back as we initialized earlier. *

* *Also, please note because we are reading bytes here, we have used "rb" instead of “r”*

# *2.2. Input*

#TODO<replace>"C:\Users\kstev\Desktop\Snips 2\Pickle\2.2\Listing 19 .txt"

*Listing 19*

# *2.2 Output*

{1: 'Zack', 2: '53050', 3: 'IT', 4: '38', 5: 'Flipkart'}

*Figure 20*

*#TODO<img>![^](:// "^")   </caption>*

#TODO<href/> [^](://"^") ,(GitHub Page )

#TODO<href/> [^](://"^") ,(GitHub Page )

#TODO<href/> [^](://"^") ,(GitHub Page )

# *2.3 (a) Python Pickle Module for saving Objects by serialization** *[95]

![image alt text](image_18.png) Video Tutorial Reference: [95] 

Sentdex, "Python Programming Tutorials," *Pythonprogramming.net*, 2019. [Online]. Available: https://pythonprogramming.net/python-pickle-module-save-objects-serialization/

Pickling is used to store python objects. This means things like lists, dictionaries, class objects, and more.

Generally, you will find pickling to be most useful with data analysis, where you are performing routine tasks on the data, such as pre-processing. Also, it makes a lot of sense when you're working with Python-specific data types, such as dictionaries.

For example, we use [pickling in the NLTK tutorial series to save our trained machine learning algorithm](https://pythonprogramming.net/pickle-classifier-save-nltk-tutorial/). This is so that, every time we want to use it, we do not need to constantly re-train it, which takes a while.

Instead, we just train the algorithm once, store it to a variable (an object), and then we pickle it. In the case of the NLTK module, generating the classifiers every time was taking 5-15+ minutes. With pickle, it was taking about 5 seconds.

If you have a large dataset, for example, and you're loading that massive data set into memory every time you run the program, it may make a lot of sense to just pickle it, and then load that instead, because it will be far faster, again by 50 - 100x, sometimes far more depending on the size.

Through saving the serialized object, its nature is included, so we don't have to worry about loading things "as" strings, dictionaries, lists, etc.

# *2.3a Input (Part 1)*

#TODO<replace>"C:\Users\kstev\Desktop\Snips 2\Pickle\2.3\2.3a - Listing 21 .txt"

*Listing 21*

#TODO<href/> [^](://"^") ,(GitHub Page )

#TODO<href/> [^](://"^") ,(GitHub Page )

## *2.3(b) Saving Classifiers with NLTK*

![image alt text](image_19.png) Video Tutorial Reference: [26]

Sentdex," Pythonprogramming.net, 2019. [Online]. Available: https://pythonprogramming.net/pickle-classifier-save-nltk-tutorial/

Training classifiers and machine learning algorithms can take a very long time, especially if you're training against a larger data set. Ours is actually pretty small. Can you imagine having to train the classifier every time you wanted to fire it up and use it? What horror! Instead, what we can do is use the Pickle module to go ahead and serialize our classifier object, so that all we need to do is load that file in real quick.

So, how do we do this? The first step is to save the object. To do this, first you need to import pickle at the top of your script, then, after you have trained with .train() the classifier, you can then call the following lines:

# 2.3 b Input (Part 2)

#TODO<replace>"C:\Users\kstev\Desktop\Snips 2\Pickle\2.3\2.3b - Listing 22.txt"

*Listing 22*

#TODO<href/> [^](://"^") ,(GitHub Page )

#TODO<href/> [^](://"^") ,(GitHub Page )

# 2.4 Understanding Python Pickling [9]

*Prerequisite: **[Pickle Modul*e](https://www.geeksforgeeks.org/pickle-python-object-serialization/)* **[23]**  **🡪** See 2.5 *

Python pickle module is used for serializing and de-serializing a Python object structure. Any object in Python can be pickled so that it can be saved on disk. What pickle does is that it "serializes" the object first before writing it to file. Pickling is a way to convert a python object (list, dict, etc.) into a character stream. The idea is that this character stream contains all the information necessary to reconstruct the object in another python script.

# 2.4 Input:

 #TODO<replace>"C:\Users\kstev\Desktop\Snips 2\Pickle\2.4\2.4a_Input_Listing 23 .txt"

*Listing 23*

*2.4 Output:*

![image alt text](image_20.png)

*Figure 24*

*#TODO<img/> [^](://"^") ,(GitHub Page )*

#TODO<txt/> [^](://"^") ,(GitHub Page )

#TODO<py/> [^](://"^") ,(GitHub Page )

##### *2.4(b) *Input: (Pickle without a file)

#TODO<replace>"C:\Users\kstev\Desktop\Exception Snips\Pickling\2.4\2.4.2 Pickling without a file.txt"

*Listing 25*

#TODO<href/> [^](://"^") ,(GitHub Page )

*2.5 pickle—Python object serialization** [23]*

*The code samples in Section 2.5 (below) are the Prerequisites for installing the packages located on the **[Pickle Modul*e](https://www.geeksforgeeks.org/understanding-python-pickling-example/)* **[9](external link) page.*

*The pickle module is used for implementing binary protocols for serializing and de-serializing a Python object structure.*

* *Pickling: **It is a process where a Python object hierarchy is converted into a byte stream.*

* *Unpickling: **It is the inverse of Pickling process where a byte stream is converted into an object hierarchy.*

*Module Interface :*

* *dumps()* – This function is called to serialize an object hierarchy.

* *loads()* – This function is called to de-serialize a data stream.

![image alt text](image_21.png)*For more control over serialization and de-serialization, Pickler or an Unpickler objects are created respectively**.*

# *Constants provided by the pickle module :*

* pickle.HIGHEST_PROTOCOLThis is an integer value representing the highest protocol version available. This is considered as the protocol value which is passed to the functions dump(), dumps().

* pickle.DEFAULT_PROTOCOLThis is an integer value representing the default protocol used for pickling whose value may be less than the value of highest protocol.

*Functions provided by the pickle module :*

* *pickle.dump(obj, file, protocol = None, *, fix_imports = True)*

* **This function is equivalent to Pickler (file, protocol).dump(obj). This is used to write a pickled representation of obj to the open file object file.

* The optional protocol argument is an integer that tells the pickler to use the given protocol.

* The supported protocols are 0 to HIGHEST_PROTOCOL. If not specified, the default is DEFAULT_PROTOCOL. If a negative number is specified, HIGHEST_PROTOCOL is selected.

* If fix imports is true and protocol is less than 3, pickle will try to map the new Python 3 names to the old module names used in Python 2, so that the pickle data stream is readable with Python 2.

*2.5(a) Input (pickle.dump:)*

*#TODO<replace>"C:\Users\kstev\Desktop\Exception Snips\Pickling\2.7\2.5.1 pickle.dump - input.txt"*

*Listing 26*

*2.5(a) Output (pickle.dump:)*

***

*Figure 27*

*2.5(b) Input (pickle.load:)*

*#TODO<replace>"C:\Users\kstev\Desktop\Exception Snips\Pickling\2.7\2.5.2pickle.load - input.txt"*

*Listing 28*

*2.5(b) Output (pickle.load:)*

![image alt text](image_22.png)

*Figure 29*

*2.5(c) Input (pickle.load:)*

*#TODO<replace>"C:\Users\kstev\Desktop\Exception Snips\Pickling\2.7\2.5.3 pickle.load - input.txt"*

*Listing 30*

*2.5(c) Output (pickle.load:)*

***

*Figure 31*

*2.5(d) Input (pickle.load:)*

*#TODO<replace>"C:\Users\kstev\Desktop\Exception Snips\Pickling\2.7\2.5.4 pickle.loads.txt"*

*Listing 32*

*2.5(d) Output (pickle.load:)*

***

*Figure 33*

*Exceptions provided by the pickle module :*

* 1.exception pickle.PickleErrorThis exception inherits Exception. It is the base class for all other exceptions raised in pickling.

* 2.exception pickle.PicklingErrorThis exception inherits PickleError. This exception is raised when an unpicklable object is encountered by Pickler.

* 3.exception pickle.UnpicklingErrorThis exception inherits PickleError. This exception is raised when there is a problem like data corruption or a security violation while unpickling an object.

# Classes exported by the pickle module:

1. class pickle.Pickler(file, protocol = None, *, fix_imports = True)This class takes a binary file for writing a pickle data stream.

* 1.dump(obj) – This function is used to write a pickled representation of obj to the open file object given in the constructor.

* *2.persistent_id(obj) –* If persistent_id() returns None, obj is pickled as usual. This does nothing by deafult and exists so that any subclass can override it.

* 3.Dispatch_table – A pickler object’s dispatch table is a mapping whose keys are classes and whose values are reduction functions.By default, a pickler object will not have a dispatch_table attribute, and it will instead use the global dispatch table managed by the copyreg module.

Example : The below code creates an instance of pickle.Pickler with a private dispatch table handles the SomeClass class specially..

*2.5(d) Output (pickle.load:)*

![image alt text](image_23.png)

*Figure 34*

* *4.Fast –*** **The fast mode disables the usage of memo and speeds up the pickling process by not generating superfluous PUT opcodes.

*2. class pickle.Unpickler(file, *, fix_imports = True, encoding = "ASCII", errors = “strict”)* This class takes a binary file for reading a pickle data stream.

* *1.load() –*** **This function is used to read a pickled object representation from the open file object file and return the reconstituted object hierarchy specified.

* *2.persistent_load(pid) –*** **This raises an UnpicklingError by default.

* *3.find_class(module, name) –*** **This function imports module if required and returns the object called name from it, where the module and name arguments are str objects.

What can be pickled and unpickled?The following types can be pickled :

* None, True, and False

* integers, floating point numbers, complex numbers

* strings, bytes, bytearrays

* tuples, lists, sets, and dictionaries containing only picklable objects

* functions defined at the top level of a module (using def, not lambda)

* built-in functions defined at the top level of a module

* classes that are defined at the top level of a module

* instances of such classes whose __dict__ or the result of calling __getstate__() is picklable

Pickling Class Instances :This section explains the general mechanisms available to define, customize, and control how class instances are pickled and unpickled.No additional code is needed to make instances picklable. By default, pickle will retrieve the class and the attributes of an instance via introspection.

Classes can alter the default behavior by providing one or several special methods :

* object.__getnewargs_ex__()This method dictates the values passed to the __new__() method upon unpickling. The method must return a pair (args, kwargs) where args is a tuple of positional arguments and kwargs a dictionary of named arguments for constructing the object.

* object.__getnewargs__()This method supports only positive arguments. It must return a tuple of arguments args which will be passed to the __new__() method upon unpickling.

* object.__getstate__()If this method is defined by classes, it is called and the returned object is pickled as the contents for the instance, instead of the contents of the instance’s dictionary.

* object.__setstate__(state)If this method is defined by classes, it is called with the unpickled state. The pickled state must be a dictionary and its items are assigned to the new instance’s dictionary.

* object.__reduce__()The __reduce__() method takes no argument and shall return either a string or preferably a tuple.

* object.__reduce_ex__(protocol)This method is similar to __reduce__ method. 

* It takes a single integer argument. The main use for this method is to provide backwards-compatible reduce values for older Python releases.

Example : Handling Stateful ObjectsThis example shows how to modify pickling behavior for a class. The TextReader class opens a text file, and returns the line number and line *contents each time its readline() method is called.*

* *1.If a TextReader instance is pickled, all attributes except the file object member are saved.*

* *2.When the instance is unpickled, the file is reopened, and reading resumes from the last location.*

*2.5(e) Input (Handling Stateful Objects:)*

#TODO<replace>"C:\Users\kstev\Desktop\Exception Snips\Pickling\2.7\2.5.5 Handling Stateful Objects.txt"

*Figure 35*

*2.5(e) Output (Handling Stateful Objects:)*

![image alt text](image_24.png)

*Figure 36*

Bibliography

[1]	C. Schafer, "Python Tutorial: Using Try/Except Blocks for Error Handling," Corey Schafer. 2019.

[2]	CoreyMSchafer, "CoreyMSchafer/code_snippets," GitHub, 17-Oct-2019. [Online]. Available: https://github.com/CoreyMSchafer/code_snippets. [Accessed: 24-Nov-2019].

[3]	Sentdex, "Python 3 Programming Tutorial - Try and Except error Handling," YouTube. 12-Jul-2014.

[4]	Kstevens, "Compiled List of Resources and Tutorials Related to Exception Handling in Python 3," Google.com, 20-Nov-2019. [Online]. Available: https://docs.google.com/spreadsheets/d/e/2PACX-1vRnad3aZB7_j9aKOajRgzOf3bGkSlcJ_NSVobVJnApOc_f7yzTMFPAHcjIhD6IxhiaIhZpEK6UEiXn1WBTG3sg/pubhtml.

[5]	Kstevens, "Compiled List of Resources and Tutorials Related to Pickle Module Resources- Python Programming," Google.com, 20-Nov-2019. [Online]. Available: https://docs.google.com/spreadsheets/d/e/2PACX-1vTFel2-8hzvknNPtJF_e_WGJuCEDRUhxEj-0LKL5En0fUX8QQTvouHaENlUEVZDDAnRQ427D_W6cxDJUEIVZFU/pubhtml.

[6]	PythonProgramming.org, "Python Repository :: cpython/Lib/," python/cpython | GitHub, 23-Nov-2019. [Online]. Available: https://github.com/python/cpython/tree/master/Lib. [Accessed: 24-Nov-2019].

[7]	"CommonMark Spec," Commonmark.org, 2019. [Online]. Available: https://spec.commonmark.org/0.29/. [Accessed: 24-Nov-2019].

[8]	"commonmark.js demo," Commonmark.org, 2019. [Online]. Available: https://spec.commonmark.org/dingus/?text=%09foo%09baz%09%09bim%0A. [Accessed: 24-Nov-2019].

[9]	GeeksforGeeks.org, "Understanding Python Pickling with example - GeeksforGeeks," GeeksforGeeks, 08-Jun-2017. [Online]. Available: https://www.geeksforgeeks.org/understanding-python-pickling-example/. [Accessed: 24-Nov-2019].

[10]	PythonProgramming.org, "Python Repository :: cpython/Doc/library/pickle.rst," cpython/Doc/library/pickle.rst | GitHub, 03-Nov-2019. [Online]. Available: https://github.com/python/cpython/blob/master/Doc/library/pickle.rst. [Accessed: 24-Nov-2019].

[11]	"Python," GitHub, 24-Nov-2019. [Online]. Available: https://github.com/python. [Accessed: 24-Nov-2019].

[12]	Super User, "Try, Except, Else, Finally," Uci.edu, 2019. [Online]. Available: http://tutors.ics.uci.edu/index.php/79-python-resources/104-try-except. [Accessed: 24-Nov-2019].

[13]	"control flow of a try/except/else/finally statement - Google Search," Google.com, 2015. [Online]. Available: https://www.google.com/search?q=control+flow+of+a+try%2Fexcept%2Felse%2Ffinally+statement&oq=control+flow+of+a+try%2Fexcept%2Felse%2Ffinally+statement&aqs=chrome..69i57j33.253j0j4&sourceid=chrome&ie=UTF-8. [Accessed: 24-Nov-2019].

[14]	"Python Pickle Module for saving Objects by serialization - Google Search," Google.com, 2016. [Online]. Available: https://www.google.com/search?q=Python+Pickle+Module+for+saving+Objects+by+serialization&newwindow=1&sxsrf=ACYBGNQ09VGG3sOEeJVAaKC9tl_Mr36xFg:1574474257447&source=lnms&tbm=vid&sa=X&ved=2ahUKEwiUuMrWnf_lAhWDvJ4KHba0BvoQ_AUoAnoECGgQBA&biw=1920&bih=893&google_abuse=GOOGLE_ABUSE_EXEMPTION%3DID%3D92b1be5e5b19d7a0:TM%3D1574537361:C%3Dr:IP%3D2601:602:9d02:a130:2527:41bc:a3bd:1516-:S%3DAPGng0uGzsujrIUb0rhzIjIStAJ2lX4gkg%3B+path%3D/%3B+domain%3Dgoogle.com%3B+expires%3DSat,+23-Nov-2019+22:29:21+GMT. [Accessed: 24-Nov-2019].

[15]	"11.1. pickle — Python object serialization — Python 2.7.17 documentation," Python.org, 2019. [Online]. Available: https://docs.python.org/2/library/pickle.html#relationship-to-other-python-modules. [Accessed: 24-Nov-2019].

[16]	N. Bowers, "Test::Cmd - Perl module for portable testing of commands and scripts - metacpan.org," Metacpan.org, 25-Oct-2015. [Online]. Available: https://metacpan.org/pod/Test::Cmd. [Accessed: 24-Nov-2019].

[17]	"Python Global, Local and Nonlocal variables (With Examples)," Programiz.com, 2019. [Online]. Available: https://www.programiz.com/python-programming/global-local-nonlocal-variables. [Accessed: 24-Nov-2019].

[18]	datacamp, "datacamp/pythonwhat," GitHub, 16-Sep-2019. [Online]. Available: https://github.com/datacamp/pythonwhat. [Accessed: 24-Nov-2019].

[19]	"pythonwhat — pythonwhat 2.21.0 documentation," Readthedocs.io, 2019. [Online]. Available: https://pythonwhat.readthedocs.io/en/latest/. [Accessed: 24-Nov-2019].

[20]	"SCTs python - Google Search," Google.com, 2019. [Online]. Available: https://www.google.com/search?newwindow=1&sxsrf=ACYBGNTaog76UITs3dol-M8EyHeyXbGz6w%3A1574596186347&ei=Wm7aXcXkFMTn-wSn5oXoBQ&q=SCTs+python&oq=SCTs+python&gs_l=psy-ab.3...3244.5795..7643...0.2..0.79.471.7......0....1..gws-wiz.......0i71j0i67j0i20i263j0i10j0j0i22i30j0i22i10i30j33i160j0i13j0i13i30.6-ksYmYFEGA&ved=0ahUKEwjF-efy44LmAhXE854KHSdzAV0Q4dUDCAs&uact=5. [Accessed: 24-Nov-2019].

[21]	google, "Python: API for verifying SCTs. · google/certificate-transparency@e9a274f," GitHub, 13-Feb-2015. [Online]. Available: https://github.com/google/certificate-transparency/commit/e9a274f358702f634da2a67cc07113e33bdfff87. [Accessed: 24-Nov-2019].

[22]	"ControLling mUltiple streams for tElepresence Wiki," Ietf.org, 2015. [Online]. Available: https://trac.ietf.org/trac/clue. [Accessed: 24-Nov-2019].

[23]	"pickle — Python object serialization - GeeksforGeeks," GeeksforGeeks, 08-Jun-2017. [Online]. Available: https://www.geeksforgeeks.org/pickle-python-object-serialization/. [Accessed: 24-Nov-2019].

[24]	"Python Programming Tutorials," Pythonprogramming.net, 2019. [Online]. Available: https://pythonprogramming.net/pickling-scaling-machine-learning-tutorial/. [Accessed: 24-Nov-2019].

[25]	"Python Programming Tutorials," Pythonprogramming.net, 2019. [Online]. Available: https://pythonprogramming.net/machine-learning-tutorial-python-introduction/. [Accessed: 24-Nov-2019].

[26]	"Python Programming Tutorials," Pythonprogramming.net, 2019. [Online]. Available: https://pythonprogramming.net/pickle-classifier-save-nltk-tutorial/. [Accessed: 24-Nov-2019].

[27]	python.org, :"mod:`pickle` --- Python object serialization," https://docs.python.org/, 2019. [Online]. Available: https://docs.python.org/2/_sources/library/pickle.rst.txt. [Accessed: 24-Nov-2019].

[28]	python, "python/cpython," GitHub, 23-Nov-2019. [Online]. Available: https://github.com/python/cpython/tree/master/Doc/library. [Accessed: 24-Nov-2019].

[29]	"Python Module Index — Python 3.8.0 documentation," Python.org, 2019. [Online]. Available: https://docs.python.org/3/py-modindex.html. [Accessed: 24-Nov-2019].

[30]	"Index — Python 3.8.0 documentation," Python.org, 2019. [Online]. Available: https://docs.python.org/3/genindex-all.html. [Accessed: 24-Nov-2019].

[31]	"Index of Menu Items - Help | PyCharm," Jetbrains.com, 2019. [Online]. Available: https://www.jetbrains.com/help/pycharm/index-of-menu-items.html. [Accessed: 24-Nov-2019].

[32]	"Query results - Help | PyCharm," Jetbrains.com, 2019. [Online]. Available: https://www.jetbrains.com/help/pycharm/viewing-query-results.html#export-data. [Accessed: 24-Nov-2019].

[33]	"Full-stack Web Development - Features | PyCharm," JetBrains, 2019. [Online]. Available: https://www.jetbrains.com/pycharm/features/web_development.html. [Accessed: 24-Nov-2019].

[34]	"Regular Expression Syntax Reference - Help | PyCharm," Jetbrains.com, 2019. [Online]. Available: https://www.jetbrains.com/help/pycharm/regular-expression-syntax-reference.html. [Accessed: 24-Nov-2019].

[35]	"Managing data sources - Help | PyCharm," Jetbrains.com, 2019. [Online]. Available: https://www.jetbrains.com/help/pycharm/managing-data-sources.html. [Accessed: 24-Nov-2019].

[36]	"Scope Language Syntax Reference - Help | PyCharm," Jetbrains.com, 2019. [Online]. Available: https://www.jetbrains.com/help/pycharm/scope-language-syntax-reference.html. [Accessed: 24-Nov-2019].

[37]	"Install EduTools Plugin - Help | Educational Products," Jetbrains.com, 2019. [Online]. Available: https://www.jetbrains.com/help/education/install-edutools-plugin.html?section=IntelliJ%20IDEA. [Accessed: 24-Nov-2019].

[38]	"Regular Expression Syntax Reference - Help | PyCharm," Jetbrains.com, 2019. [Online]. Available: https://www.jetbrains.com/help/pycharm/regular-expression-syntax-reference.html. [Accessed: 24-Nov-2019].

[39]	"Import/Export options from CSV to database - Features | DataGrip," JetBrains, 2019. [Online]. Available: https://www.jetbrains.com/datagrip/features/importexport.html. [Accessed: 24-Nov-2019].

[40]	"Built-in Developer Tools - Features | PyCharm," JetBrains, 2019. [Online]. Available: https://www.jetbrains.com/pycharm/features/tools.html. [Accessed: 24-Nov-2019].

[41]	"Download DataGrip: Cross-Platform IDE for Databases & SQL," JetBrains, 2019. [Online]. Available: https://www.jetbrains.com/datagrip/download/#section=windows. [Accessed: 24-Nov-2019].

[42]	"Free downloads of Ablebits.com Excel add-ins and Outlook plug-ins," Ablebits.com, 2019. [Online]. Available: https://www.ablebits.com/downloads/index.php. [Accessed: 24-Nov-2019].

[43]	"Python Programming Tutorials," Pythonprogramming.net, 2019. [Online]. Available: https://pythonprogramming.net/python-pickle-module-save-objects-serialization/. [Accessed: 24-Nov-2019].

[44]	"25.4. 2to3 - Automated Python 2 to 3 code translation — Python 2.7.17 documentation," Python.org, 2019. [Online]. Available: https://docs.python.org/2/library/2to3.html#module-lib2to3. [Accessed: 24-Nov-2019].

[45]	"Python Pickling," Tutorialspoint.com, 2019. [Online]. Available: https://www.tutorialspoint.com/python-pickling. [Accessed: 24-Nov-2019].

[46]	"11.1. pickle — Python object serialization — Python 2.7.17 documentation," Python.org, 2019. [Online]. Available: https://docs.python.org/2/library/pickle.html#module-pickle. [Accessed: 25-Nov-2019].

[47]	"copyreg — Register pickle support functions — Python 3.8.0 documentation," Python.org, 2019. [Online]. Available: https://docs.python.org/3/library/copyreg.html. [Accessed: 25-Nov-2019].

[48]	"pickle — Python object serialization — Python 3.8.0 documentation," Python.org, 2019. [Online]. Available: https://docs.python.org/3/library/pickle.html. [Accessed: 25-Nov-2019].

[49]	"3.11.1 Example," Python.org, 2019. [Online]. Available: https://docs.python.org/2.0/lib/pickle-example.html. [Accessed: 25-Nov-2019].

[50]	"Module Index," Python.org, 2019. [Online]. Available: https://docs.python.org/2.0/lib/modindex.html. [Accessed: 25-Nov-2019].

[51]	"Python Library Reference," Python.org, 2019. [Online]. Available: https://docs.python.org/2.0/lib/lib.html. [Accessed: 25-Nov-2019].

[52]	"Extending and Embedding the Python Interpreter," Python.org, 2019. [Online]. Available: https://docs.python.org/2.0/ext/ext.html. [Accessed: 25-Nov-2019].

[53]	"11. Data Persistence — Python 2.7.17 documentation," Python.org, 2019. [Online]. Available: https://docs.python.org/2/library/persistence.html. [Accessed: 25-Nov-2019].

[54]	"pickle — Python object serialization — Python 3.8.0 documentation," Python.org, 2019. [Online]. Available: https://docs.python.org/3/library/pickle.html. [Accessed: 25-Nov-2019].

[55]	"Stateful - APIDesign," Apidesign.org, 2010. [Online]. Available: http://wiki.apidesign.org/wiki/Stateful. [Accessed: 25-Nov-2019].

[56]	"3.14 shelve -- Python object persistence," Python.org, 2019. [Online]. Available: https://docs.python.org/2.0/lib/module-shelve.html. [Accessed: 25-Nov-2019].

[57]	"3.15 copy -- Shallow and deep copy operations," Python.org, 2019. [Online]. Available: https://docs.python.org/2.0/lib/module-copy.html. [Accessed: 25-Nov-2019].

[58]	"3.16 marshal -- Alternate Python object serialization," Python.org, 2019. [Online]. Available: https://docs.python.org/2.0/lib/module-marshal.html. [Accessed: 25-Nov-2019].

[59]	"hmac — Keyed-Hashing for Message Authentication — Python 3.8.0 documentation," Python.org, 2019. [Online]. Available: https://docs.python.org/3/library/hmac.html#module-hmac. [Accessed: 25-Nov-2019].

[60]	"json — JSON encoder and decoder — Python 3.8.0 documentation," Python.org, 2019. [Online]. Available: https://docs.python.org/3/library/json.html#module-json. [Accessed: 25-Nov-2019].

[61]	"Research Guides: Microsoft Word for Dissertations: Cross-References," Umich.edu, 2019. [Online]. Available: https://guides.lib.umich.edu/c.php?g=283073&p=1888264. [Accessed: 25-Nov-2019].

[62]	I. Periodicals, "IEEE EDITORIAL STYLE MANUAL FOR AUTHORS."

[63]	University of Washington, "ITFDN100 A, ‘Foundations of Python Programming,’" https://canvas.uw.edu/, 2019. [Online]. Available: https://canvas.uw.edu/courses/1342958/modules/items/9973247. [Accessed: 25-Nov-2019].

[64]	PythonMod7Project, "PythonMod7Project," ITFDN100 |  YouTube, 13-Nov-2019. [Online]. Available: https://www.youtube.com/watch?v=4IkIdXJBC6o&feature=youtu.be. [Accessed: 25-Nov-2019].

[65]	"Assignment07.pdf: IT FDN 100 A Au 19: Foundations Of Programming: Python," Uw.edu, 2019. [Online]. Available: https://canvas.uw.edu/courses/1342958/files/59791641?module_item_id=9973247. [Accessed: 25-Nov-2019].

[66]	"Lab7-1_Starter.py: IT FDN 100 A Au 19: Foundations Of Programming: Python," Uw.edu, 2019. [Online]. Available: https://canvas.uw.edu/courses/1342958/files/59729143?module_item_id=9973388. [Accessed: 25-Nov-2019].

[67]	"_Mod7PythonProgrammingNotes.pdf: IT FDN 100 A Au 19: Foundations Of Programming: Python," Uw.edu, 2019. [Online]. Available: https://canvas.uw.edu/courses/1342958/files/59801217?module_item_id=9973246. [Accessed: 25-Nov-2019].

[68]	"Assignment07.pdf: IT FDN 100 A Au 19: Foundations Of Programming: Python," Uw.edu, 2019. [Online]. Available: https://canvas.uw.edu/courses/1342958/files/59791641?module_item_id=9973247. [Accessed: 25-Nov-2019].

[69]	"_Mod7PythonProgrammingNotes.pdf: IT FDN 100 A Au 19: Foundations Of Programming: Python," Uw.edu, 2019. [Online]. Available: https://canvas.uw.edu/courses/1342958/files/59801217?module_item_id=9973246. [Accessed: 25-Nov-2019].

[70]	python, "python/cpython," GitHub, 31-Oct-2018. [Online]. Available: https://github.com/python/cpython/blob/3.8/Lib/copyreg.py. [Accessed: 25-Nov-2019].

[71]	"Build software better, together," GitHub, 2019. [Online]. Available: https://github.com/collections/government. [Accessed: 25-Nov-2019].

[72]	"Build software better, together," GitHub, 2019. [Online]. Available: https://github.com/collections/government. [Accessed: 25-Nov-2019].

[73]	mangini, "mangini/gdocs2md," GitHub, 09-Oct-2013. [Online]. Available: https://github.com/mangini/gdocs2md/blob/master/converttomarkdown.gapps. [Accessed: 25-Nov-2019].

[74]	mangini, "mangini/gdocs2md," GitHub, 09-Oct-2013. [Online]. Available: https://github.com/mangini/gdocs2md/blob/master/converttomarkdown.gapps. [Accessed: 25-Nov-2019].

[75]	"18 Software Documentation Tools that Do The Hard Work For You | Process Street | Checklist, Workflow and SOP Software," Process Street, 24-Aug-2016. [Online]. Available: https://www.process.st/software-documentation/. [Accessed: 25-Nov-2019].

[76]	"18 Software Documentation Tools that Do The Hard Work For You | Process Street | Checklist, Workflow and SOP Software," Process Street, 24-Aug-2016. [Online]. Available: https://www.process.st/software-documentation/. [Accessed: 25-Nov-2019].

[77]	"18 Software Documentation Tools that Do The Hard Work For You | Process Street | Checklist, Workflow and SOP Software," Process Street, 24-Aug-2016. [Online]. Available: https://www.process.st/software-documentation/. [Accessed: 25-Nov-2019].

[78]	electron, "electron/electronjs.org," GitHub, 25-Nov-2019. [Online]. Available: https://github.com/electron/electronjs.org. [Accessed: 25-Nov-2019].

[79]	"Webhooks — Read the Docs 3.10.0 documentation," Readthedocs.io, 2019. [Online]. Available: https://docs.readthedocs.io/en/latest/webhooks.html. [Accessed: 25-Nov-2019].

[80]	"Webhooks — Read the Docs 3.10.0 documentation," Readthedocs.io, 2019. [Online]. Available: https://docs.readthedocs.io/en/latest/webhooks.html. [Accessed: 25-Nov-2019].

[81]	"6. Built-in Exceptions — Python 2.7.17 documentation," Python.org, 2019. [Online]. Available: https://docs.python.org/2/library/exceptions.html#exceptions.TypeError. [Accessed: 26-Nov-2019].

[82]	"3.13 copy_reg -- Register pickle support functions," Python.org, 2019. [Online]. Available: https://docs.python.org/2.0/lib/module-copyreg.html. [Accessed: 26-Nov-2019].

[83]	"3.15 copy -- Shallow and deep copy operations," Python.org, 2019. [Online]. Available: https://docs.python.org/2.0/lib/module-copy.html. [Accessed: 26-Nov-2019].

[84]	"Basic writing and formatting syntax - GitHub Help," Github.com, 2019. [Online]. Available: https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax. [Accessed: 26-Nov-2019].

[85]	C. Scafer, "Python Tutorial: Using Try/Except Blocks for Error Handling," Corey Scafer. 13-Nov-2015.

[86]	CoreyMSchafer, "CoreyMSchafer/code_snippets," GitHub, 25-Mar-2017. [Online]. Available: https://github.com/CoreyMSchafer/code_snippets/tree/master/Exceptions. [Accessed: 26-Nov-2019].

[87]	CoreyMSchafer, "CoreyMSchafer/code_snippets," GitHub, 25-Mar-2017. [Online]. Available: https://github.com/CoreyMSchafer/code_snippets/tree/master/Exceptions. [Accessed: 26-Nov-2019].

[88]	"CoreyMS - Development, Design, DIY, and more," CoreyMS, 19-Nov-2019. [Online]. Available: https://coreyms.com/. [Accessed: 26-Nov-2019].

[89]	"Built-in Exceptions — Python 3.8.0 documentation," Python.org, 2019. [Online]. Available: https://docs.python.org/3/library/exceptions.html#TypeError. [Accessed: 26-Nov-2019].

[90]	"3.13 copy_reg -- Register pickle support functions," Python.org, 2019. [Online]. Available: https://docs.python.org/2.0/lib/module-copyreg.html. [Accessed: 26-Nov-2019].

[91]	"CoreyMS - Development, Design, DIY, and more," CoreyMS, 19-Nov-2019. [Online]. Available: https://coreyms.com/. [Accessed: 26-Nov-2019].

[92]	"Python Pickling," Tutorialspoint.com, 2019. [Online]. Available: https://www.tutorialspoint.com/python-pickling. [Accessed: 26-Nov-2019].

[93]	Sentdex, "Python Programming Tutorials," Pythonprogramming.net, 2019. [Online]. Available: https://pythonprogramming.net/python-pickle-module-save-objects-serialization/. [Accessed: 26-Nov-2019].

[94]	"KTH Royal Institute of Technology | Stockholm, Sweden | KTH," ResearchGate, 2017. [Online]. Available: https://www.researchgate.net/institution/KTH_Royal_Institute_of_Technology. [Accessed: 26-Nov-2019].

[95]	DataFlair Team, "Python Pickle | What is Serialization in Python with Example - DataFlair," DataFlair, 27-Mar-2018. [Online]. Available: https://data-flair.training/blogs/python-pickle/. [Accessed: 26-Nov-2019].

[96]	DataFlair Team, "Python Collections Module - Python Counter, DefaultDict, OrderedDict, NamedTuple - DataFlair," DataFlair, 10-Feb-2018. [Online]. Available: https://data-flair.training/blogs/python-collections-module/. [Accessed: 26-Nov-2019].

[97]	quarkslab, "quarkslab/cpython," GitHub, 27-Sep-2014. [Online]. Available: https://github.com/quarkslab/cpython/blob/master/Doc/library/pickle.rst. [Accessed: 26-Nov-2019].

[98]	"(PDF) Instant Pickles: Generating Object-Oriented Pickler Combinators for Fast and Extensible Serialization," ResearchGate, 2013.

[99]	o365devx, "Document object (Word)," Microsoft.com, 23-May-2019. [Online]. Available: https://docs.microsoft.com/en-us/office/vba/api/word.document. [Accessed: 26-Nov-2019].

[100]	DataFlair Team, "Python Pickle | What is Serialization in Python with Example - DataFlair," DataFlair, 27-Mar-2018. [Online]. Available: https://data-flair.training/blogs/python-pickle/. [Accessed: 26-Nov-2019].

[101]	"Full text of ‘Python In A Nutshell By Alex Martelli,’" Archive.org, 2019. [Online]. Available: https://archive.org/stream/PythonInANutshellByAlexMartelli/python%20in%20a%20nutshell%20by%20alex%20martelli_djvu.txt. [Accessed: 26-Nov-2019].

