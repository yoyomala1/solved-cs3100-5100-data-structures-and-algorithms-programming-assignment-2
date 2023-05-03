Download Link: https://assignmentchef.com/product/solved-cs3100-5100-data-structures-and-algorithms-programming-assignment-2
<br>
<ol>

 <li>Overview</li>

</ol>




The objective of this programming assignment is to practice your C++ programming skills. In this programming assignment, you will implement an abstract data type stack, and test its functionality by writing some sample test programs in main.cpp.




A stack is a container of objects that are inserted and removed according to the last-in-first-out principle. <strong>The header file SStack.h, and Employee.h will be provided to you.</strong> SStack.h is the header file that specifies the interface of the abstract data type stack that you need to implement. You must implement all the functions in SStack.h.<strong> The following basic operations and some other supportive operations must be supported by the ADT Stack.</strong>




<strong>Push  — Add an element onto the stack (to the top of the stack)</strong>

<strong>Pop  — Remove an element from the stack (from the top of the stack)</strong>

<strong>Top —  Look at the element that is on top of the stack (DO NOT remove it)</strong>

<strong>isEmpty — Check whether the stack is empty or not</strong>

<strong>size: returns the number of elements stored in the stack</strong>




It is important to note that all the push and pop operations are done on the top of the stack. A stack can be implemented in many ways. In this project, we implement a stack using a dynamic array of a given size, i.e., there is a limit on the number of objects the stack can hold. The size of the stack should be specified by the programmer or using a default size while creating the stack.




To test the stack of the string type, a file “Employee-Database.txt” with many employee objects is provided to you. In your main.cpp, you will write code to test all the member functions of the stack ADT.  In your main.cpp, you should first create a stack of type string whose capacity is specified by you (should be in the order of 100). Then read the employee objects from Employee-Database.txt and push the employee objects to the stack. The number of employee objects pushed onto the stack should be less than the capacity of the stack. After you pushed the employee objects onto the stack, you should test ALL the other functions in SStack.h. You should print out a message describing the operation you tested.




In the beginning of your main() function,  you should open the input file,  create a  Stack: prompt the user for the capacity of the stack (should be in the order of 100 or larger), and a specified number (should be in the order of 100 or larger) that is less than the capacity of the stack. Then read the specified number of the employee objects from the input file, Employee-Database.txt, and push these employee objects into the stack.




Then create a stack using the copy constructor with the specified capacity.




Then you can create a third stack to test the union( ) function later.




Then in your main() function, you will provide a <strong>user interface</strong> <strong>(MENU) </strong>to test the member functions of the stack ADT and to support the following operations:




<ol>

 <li>Push: prompt user for an employee object, and push it onto the top of the stack, then print the number of the elements in the stack to the screen, and only print the top 5 elements in the stack to the screen if the number of elements in the stack is larger than 5.</li>

</ol>




<ol start="2">

 <li>Pop: prompt user for a number, and if the number of the elements in the stack is larger than the number entered by the user, pop the specified number of the elements from the stack, and print the employee objects popped from the stack, and the remaining number of the elements in the stack to the screen. Otherwise, pop all the elements from the stack.</li>

</ol>




3.Top: print the employee object on the top of the stack and the remaining number of the elements in the stack to the screen.




<ol start="4">

 <li>Union: Union two stacks together.</li>

</ol>




<ol start="5">

 <li>Print: Print all the elements in the stack onto the screen.</li>

</ol>




6.Save: save all the elements in a stack to a file on the disk.




<ol start="7">

 <li>Quit: clear all the elements in the stack, so there is no memory leak in your program, and quit.</li>

</ol>







<ol start="2">

 <li>Requirements</li>

</ol>




The main.cpp file includes code that will test the implementation of your member functions of your Stack ADT.




<ol>

 <li>You need to use Employee.h, and Employee.cpp from the first project.</li>

</ol>




<ol start="2">

 <li>In SStack.cpp, you must implement all the functions in SStack.h.</li>

</ol>




<ol start="3">

 <li>Your code should follow the Code Standards posted on Pilot. Your code will be graded according to its correctness, efficiency, organization, and readability.</li>

</ol>




<ol start="4">

 <li>Make sure that each file includes your name and email address in the header comments.</li>

</ol>




<ul>

 <li>Code Submission and Testing</li>

</ul>




<ol>

 <li>The grader will test your source code using visual studio 2019. It is suggested that you test your source code on the computers located in the computer labs in the first floor of Russ Engineering building before you submit your code on Pilot.</li>

</ol>




<ol start="2">

 <li>You must submit an ELECTRONIC COPY of your source program through Pilot before the due date. If for some reason Pilot is unavailable, submit your source code to the instructor Meilin Liu.</li>

</ol>




<ol start="4">

 <li>Submit the source code files including employee.cpp, employee.h, SStack.h, SStack.cpp, main.cpp, a README file. You are recommended to submit a README file to tell the instructor and the grader what they need to know when testing your program.</li>

</ol>




<ol start="5">

 <li>All the submitted project files should have: Course Number / Course Title , Your Name, Prof.’s Name, Date, and the Project Name. If you did not include these required contents in your submitted files, then 5 points will be deducted. It is recommended that your filename include your last name.</li>

</ol>




<ol start="5">

 <li>The instructor or the grader will test your programs under visual studio 2019. It is YOUR responsibility to make your programs workable and runnable under visual studio 2019.</li>

</ol>




<ol start="6">

 <li>The programming assignment is individual. You must do the project by yourself. If you allow others to copy your programs or answers, you will get the same punishment as those who copy yours.</li>

</ol>




<ol start="7">

 <li>Be honest. If your program does not work, SAY SO in your README. The instructor will run your programs with ANY DIFFERENT input files. If your program does not work, but you “claim” yours work, you will have severe penalty!</li>

</ol>


