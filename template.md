### Name of the language

Lisp

### History of the language: who/when invented it, which languages influenced it, etc.

 &nbsp;&nbsp; Developed by John McCarthy, creator of artificial intelligence applications, in 1958 to find effective solutions to many problems to be used in artificial intelligence applications. McCarthy published his design in an article titled "Recursive Functions of the Symbolic Expressions and Calculation with the Machine, Part I" at ACM's Communications in 1960. It has shown that it can create a Turing-complete language for algorithms, with an indicator for some simple operators and anonymous functions borrowed from the Church.
Steve Russell performed Lisp for the first time. This application was done on an IBM 704 computer using punch cards. Russell read the McCarthy's document and realized that the Lisp eval function could be implemented in the machine code, and consequently a lisp interpreter was formed. <br/>
 &nbsp;&nbsp; Two compilation language macros for IBM 704 have become primitive processes for parsing lists: the car (the content of the Address number of the Registration number) and cdr (the content of the Decrease of the Registration number).
In 1962, Tim Hart and Mike Levin implemented the first full Lisp compiler written in Lisp. This application of Hart and Levin was closer to the modern Lisp style. <br/>
&nbsp;&nbsp; MIT graduate student Daniel Edwards developed his first garbage collection routines. <br/>
 &nbsp;&nbsp; A number of new lisp dialects emerged. During the 1880s and 1990s, efforts were made to combine new lisp dialects in one language. Emerging as a remedy for this extravagant variety, Common Lisp was a version of Lisp in which its derivatives were combined and their disadvantages were eliminated. In 1994, ANSI Common Lisp standard published "ANSI X3.226-1994 Information Technology Programming Language Common Lisp. <br/>
&nbsp;&nbsp; Lisp's development slowed somewhat in the 1990s, but it resumed after 2000. Most of the new events focused on Common Lisp, Scheme, Emacs Lisp, Clojure and Racket applications. The content of the new studies also included the development of portable libraries and applications. <br/>

### Why was it invented

 In fact, Lisp was created as an practical mathematical representation for computer programs affected by the lamda notation of the Alonzo Church. Then it started to be preferred for artificial intelligence research.
 
### When/why shall we use it

We can use it in functional programming, or object oriented programming. It includes structures that are not exist in most languages. Why shall we use it? Because it is indispensable for Artificial Intelligence. It supports Lambda Calculus. 

### How to setup an environment to use it in different platforms

###### Windows:
- Go to: http://mirror.rackdc.com/gnu/emacs/windows/ <br/>
- Choose the version you want.  <br/>
- Unzip the downloaded file. <br/>
- Move the unzipped file to a permanent place. <br/>
- Open the exe file inside the unzipped file (find bin\addpm.exe). <br/>
- Now, you can see the GNU Emacs on the start menu. <br/>

###### MacOS:
- Go to: https://emacsformacosx.com/ <br/>
- Open the .dmg file <br/>
- Move Emacs to the Application folder <br/>

###### Linux:
> sudo apt-get install emacs

### Example codes

###### Hello World!:
> (print "Hello world")

###### Factorial:
> (defun factorial (n) <br/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (loop for i from 1 to n <br/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; for fac = 1 then (* fac i) <br/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; finally (return fac))) <br/>
  
###### Sum List
> (define (sum xs) <br/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (if (null? xs) <br/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 0 <br/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (+ (car xs) (sum (cdr xs))))) <br/>
         
### Things that are specific to this language?
- **Conditionals** <br/>
> if-then-else construct <br/>
- **Function data type** <br/>
Functions can be used as arguments.
- **Lisp supports recursion** <br/>
- **Binding a value to a variable means copying the pointer.** <br/>
- **Lisp has garbage-collector**
- **Programs are compositions of expressions.**
