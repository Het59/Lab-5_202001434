# IT-314 SOFTWARE ENGINEERING
### Student_ID: 202001434 
### Name: Het Patel
---
#### **Static Analysis Tools:** pylint
#### **Github Repository link:** https://github.com/saadmk11/banking-system
---
* Cloning Repository and installing pylint:

![image](https://user-images.githubusercontent.com/124347145/227490213-8ba8ff44-70b1-46b1-a196-dae4fd2e6d16.png)

---
### Static Analysis of files:

* *File link:* https://github.com/saadmk11/banking-system/blob/master/accounts/models.py

![image](https://user-images.githubusercontent.com/124347145/227491665-28e9fbdb-ef34-4b14-9620-89b08080e6c6.png)

* *File link:* https://github.com/saadmk11/banking-system/blob/master/accounts/managers.py

![image](https://user-images.githubusercontent.com/124347145/227492015-fab9b0f9-faee-4c41-84c9-9ba2fc8eedea.png)

* *File link:* https://github.com/saadmk11/banking-system/blob/master/transactions/forms.py

![image](https://user-images.githubusercontent.com/124347145/227492190-46f35bc3-478c-4a67-a79c-22cc243d1329.png)

* *File link:* https://github.com/saadmk11/banking-system/blob/master/transactions/models.py

![image](https://user-images.githubusercontent.com/124347145/227492281-c1348c74-c1c5-4482-aae9-8589327e5971.png)

* *File link:* https://github.com/saadmk11/banking-system/blob/master/transactions/views.py

![image](https://user-images.githubusercontent.com/124347145/227492563-c10f9650-0df1-4c0f-a86d-5d3a1e047b2b.png)

---

### Understanding of errors:

* *C0114:* Missing module docstring: When a module lacks a docstring, this error is displayed. A module, class, function, or method definition's opening statement is referred to as a docstring. It offers a summary of the operation of the module, class, function, or method.*
* *E0401:* Unable to import module: This error is displayed when Python is unable to import a module that is being used in the code. If the module is not installed, not available, or not in the Python path, an error may result.
* *C0115:* Missing class docstring: When a class lacks a docstring, the error is triggered. The functions, characteristics, and other information of a class are described in its documentation string.
* *C0116:* No method or function documentation: When a function or method lacks a docstring, this error is thrown. A function or method's docstring gives an explanation of the function or method's purpose, its input arguments, and its output.
* *C0103:* Constant name not in UPPER CASE: This error is thrown when a constant's name deviates from the accepted practise of utilising only uppercase letters and hyphens to separate words.
* *R1721:* Extraneous "else" following "return" This mistake occurs when a function's "return" statement is followed by a "else" statement. The "else" argument is not required because the "return" statement finishes the function's execution immediately.
* *R0903:* Too few public methods: A class that has too few public methods receives this error. The context and goal of the class will determine the precise number of methods needed to prevent this issue.
* *C0209:* No whitespace permitted before bracket: This error is displayed when there is whitespace before an open bracket. For instance, use my list [0] rather than my list[0].
* *W0212:* Access to a Protected Member: When code accesses a protected member of a class, this warning is sent. A member whose name begins with a single underscore is considered to be protected. Though not strictly prohibited, accessing a protected member is discouraged since it disrupts encapsulation.
* *W0707:* Several Statements on One Line (Semicolon): When there are many statements on one line that are separated by semicolons, this warning is displayed. It is often advised to limit statements to one per line.
* *W0613:* Unused argument: When a function or method contains an unnecessary parameter, this warning is sent. It signifies that the argument can be safely eliminated because it is not utilised elsewhere in the function or method.
