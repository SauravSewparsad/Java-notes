# Java-notes

# Week 1 of Java
--------------------------------
# Introduction to Java

What is Java?
- Java is a widely used programming language used by software engineers to create web, mobile, and desktop apps, requiring the Java Development Kit (JDK) for compilation and operation.

Algorithms in Programming
- Computers are data processors that require precise instructions, called programs.
- In the past, these instructions were in zeros and ones, but programmers made it easier with languages like Java.
- Algorithms are now crucial for problem-solving, serving as step-by-step guides for computers to follow.
- Numerous programming languages exist to simplify these tasks.
- As an example on this in real life, To calculate an employee's earnings before deductions, use a step-by-step approach, including calculating hours worked, hourly wage rate, and multiplying by rate, and use programming language like Java.

# Getting Your Java Environment Ready

Getting Your Java Environment Ready
- Installing JDK
   + The Java development kit (JDK) is essential for building and running Java apps on a computer.
   + The standard edition, Java 17.0.2, is suitable for our needs. However, newer versions are acceptable, and it's crucial to choose the appropriate JDK for your operating system.

Installing itenlliJ IDEA
- This course uses IntelliJ, a free and open-source code editor, to create code.
- To download, visit jetbrains.com/idea and download the Community Edition.
- Open the app on a Mac or follow the installation prompts on Windows.
- The IDE, or integrated development environment, is where all code will be written, making it easy to use and use for future coding.

Executing Java Programs
- Java programs can be written and run using text editors and the command line, but this approach can become unwieldy as the program grows.
- An IDE (Integrated Development Environment) is a solution that is focused on coding and offers built-in tools to streamline the software development process.
- Its graphical user interface (GUI) allows users to skip typing out command lines and run code with just a click. Additionally, an IDE comes with a debugger, making coding quicker and simpler.
- IntelliJ, a custom-made IDE for Java development, is used in this course. It comes in two flavors: a paid ultimate version and a free community version. The community version is suitable for this course.
- IntelliJ is a popular choice for Java development, as it offers a graphical user interface and a debugger for spotting and fixing errors.

Explore Intellij IDEA
- IntelliJ IDE is a powerful tool for creating and modifying Java programs.
- To begin, click on "New Project" and configure settings, including the Java version.
- For beginners, choose Java 20 and download the JDK for Java 20. Name the project "Learning Java" and create a new folder on your desktop. Start the project by clicking "Create" and use the navigation pane to switch between different project files.
- The SRC folder is the source code hub, where most of the coding takes place.
- The external library section links up the Java Development Kit (JDK) for your Java projects.
- In the top-right corner, you can run and debug your program. To compile and run the program, hit the play button. However, the "Debugging" button is grayed out as you have not written any Java code yet.
- Start crafting your Java code and enjoy the excitement!

Writing Your First Java Program
- To begin writing your first Java program, create a Java file in the SRC folder and choose "New" or "Java class" to create a new Java class.
- Java is known for its verbosity, which can be beneficial for beginners as it helps them understand concepts better.
- Every Java program needs a class, which is the foundation of all Java code.
- The code editor in the main pane is used to write the code, which can be easily accessed in the SRC folder by double-clicking it.
- To tweak the code, add extra Java code inside curly brackets, which are the main functions that start the program.
- Any action scribbled within these curly braces gets green light when the run button is pressed. The program gets its own flavor from what is spelled inside those curly braces, such as the "system.out.println" trick.
- In this beginners' journey, we will learn about "void" and "static" in the future, as well as the basics of Java 101.

Running Your First Java Program
- The text outlines the basics of a Java program, including the main function, which serves as the VIP entrance.
- The HelloWorld class is the lead role, and the main function is a supporting function.
- To run the program, simply click the "Run HelloWorld.main" button in the IDE.
- The program will then display a console at the bottom of the screen, where it will greet the user with a "Hello World!" message.
- To run the program one-click, set up a special configuration in the top right corner.
- Edit the HelloWorld class, which is grooving with Java 20 and knows the main act is in the HelloWorld class.
- Click "Cancel" to avoid messing with the configuration.
- The Play button on the right will change from gray to green, and the console will display the "HelloWorld" message.
- This is the first Java program show using the IDE.

# Java essentials

- Packages
   + A package in Java is a special folder that holds one or more Java files.
   + To create a package in IntelliJ, create a project and choose Java. Name the project "Fundamental" and finish.
   + To add a new package, right-click on "new" and select "add a new package." Packages can be multiple in a project depending on code organization.
   + To create a package, follow conventions and name it "gross_calculator." Expand the source folder and see the new package with a circular icon.
- Classes
   + To create a new Java class, right-click on the package, choose "New," and select "Java Class." Name the class "GrossPayCalculator" and follow Java conventions, starting with an uppercase letter.
   + All Java files, or classes, have a ".java" extension. Double-click on the Java file to make the tab larger.
   + The first line of the Java file is a package declaration, followed by the package name followed by a semicolon (;).
   + The class declaration is a public class called "GrossPayCalculator" enclosed in two curly braces. This creates the first Java class, allowing you to group code together in Java.
   + The package name should be followed by the package name followed by a semicolon (;).
- Main Method
   + In Java, curly braces are used to create a method, which is a small code house within a Java class.
   + To create a method, write "public static void main" and include curly braces.
   + This method is where a program starts running, and Java searches for it when the class is run.
   + To display something in Java, use'system.out.println' followed by the desired text within parentheses.
   + For example, to print 'Hello World', write 'Hello World' inside quotes and end the line with a semicolon.
   + This line represents an instruction to display text on the console, and the semicolon signifies the end of an instruction.
   + To execute a Java program, right-click anywhere in the program and select the 'run' option.
   + The console window opens, and the program prints 'Hello World' as instructed.

Reversed words
- The code consists of reserved words, such as "package," "public," "class," "static," and "void," which are specific terms within a programming language.
- These words have specific meanings and cannot be used to name variables or elements in a program.
- Java has reserved these words for specific purposes, so labeling them as "class," "public," or "package" is not allowed.
- It's important to monitor the colors in your code and note when you encounter another reserved word.

# Java Variables

creating variables
- The algorithm for determining an employee's pay involves creating a variable called "hours" to store the number of hours worked.
- The variable is declared as an integer, which takes up different amounts of memory. In JavaScript, the data type of a variable is determined as the program runs, but in statically typed languages like Java, variables must be declared before use.
- For example, "hours" is declared as an integer, with the value 40. The hourly pay rate is set to $25.50, which requires a data type that can handle decimal numbers.
- A variable named "pay rate" is declared as a "double" and set to 25.50.
- To calculate the gross pay, the hours are multiplied by the pay rate and stored in another variable.
- The data type for this result is a "double," which equals "hours" times "pay rate." The result is then printed out using "system.out.println," and a string is created with the "gross pay" variable added.
- The program is then run by right-clicking and choosing "run" or hitting the play button, and the gross pay calculator is ready to calculate the employee's pay.

Primative datatypes
- Java has eight primitive data types: integral, byte, short, int, and long. Each type has a specific memory size, with byte being 8-bit and long being 64-bit.
- Decimals are float and double, with float providing seven decimal digits and double handling 16 digits.
- The boolean data type is simple, with true or false as the default. Finally, char is a single character holder, but values should be placed in single quotes, not doubles.

Local Variable Type Inference
- Java, being statically typed, allows type inference with local variables.
- By declaring a variable as VAR, Java determines its data type based on the assignment.
- However, this method requires a kickstart when declaring the variable, as it cannot be used for global variables outside of class methods.
- This guessing game is only applicable to local variables within a method.

Naming variables
- The GrossPayCalculator program uses descriptive names for variables, such as 'hours' and 'payRate', to make them clear and understandable.
- Shortcuts like 'h' or 'r' are not recommended as they can confuse others and future self.
- Descriptive names are essential for code, especially when collaborating with peers.
- Numbers are acceptable within the name, but not as the first character.
- Special characters like $ or _ are acceptable, but avoid dashes.

Modifying Variables
- The GrossPayCalculator program initializes hours and pay rate values to zero, making them flexible.
- Users can input their values, which are then stored in the hours and payRate variables.
- A scanner is used to read user input, which is then stored in the variables.
- The program can handle various hours and pay rates, such as 30 hours and 8.25 US dollars per hour.
- The scanner object is closed to prevent memory leaks.

Arithmetic Operators
- Java has five operators for basic math calculations. They work with numeric values, such as bytes, shorts, ints, longs, floats, and doubles.
-  The five are
   + "+"
   + "-"
   + "*"
   + "/"
   + "%"
- The plus sign adds two numeric values, while the minus sign subtracts one.
- The asterisk sign multiplies two values, and the slash sign divides one value by another.
- The percent sign, also known as the modulo operator, returns the remainder of dividing one value by another.

# Decision Structures in java
- If statement
   + Programs use decision structures, such as the "if statement," to make choices and provide different paths.
   + For instance, if a salesperson makes more than 10 sales a week, they receive an extra bonus of \$250.
   + The main path of the program is to pay the salesperson \$1,000, but the code checks if the salesperson made more than the quota.
   + If so, the bonus is added to their payment. If the salesperson makes more than 10 sales, the bonus is added.
   + To test the code, run it in debug mode, allowing you to step through the code line by line.
   + For example, if the code has 10 sales, the If statement won't run, and the employee's salary will be $1,250.

if - else statement
- The if-else statement is a decision structure that allows a program to take one of two paths based on whether a certain condition is met.
- For example, a salesperson might be congratulated if they meet their quota, or reminded to try harder. In this code, the quota is initialized to 10, and the user is informed if they meet their quota.
- If they do, they are informed, and if not, they are informed and told how many sales they were short.
- The if statement checks the condition, and the else statement handles the alternative path.
- The salesShort variable stores the number of sales the user was short.

If-Else-If Statements
- The if-else-if statement is a useful tool for controlling program flow and executing code blocks based on multiple conditions.
- It is useful for grading tests, determining discounts, and making other decisions. In a program with five possible grades (A, B, C, D, and F), the if-else-if decision structure is used to determine the grade. The code starts with an if statement, stating that if the score is less than 60, the grade variable will be updated to equal F.
- If the score is not less than 60, the next condition is to determine the grade. If the score is less than 70, the grade is D, if it is less than 80, the grade is C, if it is less than 90, the grade is B, and if it is not less than 90, the grade is A.

Switch Statements
- The switch statement is a decision structure similar to the if-else-if method, which checks for equality rather than conditions.
- In a scenario where a user inputs their letter grade, a switch statement is used to display a message matching the student's letter grade.
- The switch statement is written with parentheses and curly braces, and inside it, there are "cases" that represent possible paths.
- For example, if the "grade" equals 'A,' the "message" would be "Excellent job." The "default" case is used as a catch-all for unexpected inputs.
- The "default" case is written with a colon, and the first "case" is executed. If the "break" is not placed, a domino effect occurs, going through all "cases until a "break" is found.
- The switch statement is typically used for a variety of conditions, but it can sometimes be the right tool for the job. It is up to the user to choose the right tool for the task.

Switch Expressions
- Switch expressions are a more convenient alternative to switch statements, as they simplify the process of assigning a message.
- They can be simplified by placing an equal sign after the message and shifting the switch structure to the right side.
- They can also be made cleaner by using an arrow instead of ":message=". Switch expressions do not require break statements, making them a more streamlined option.
- They can be used for multiple cases, separated by commas, and can include more than just assignments in cases.
- To choose between a switch statement and a switch expression, consider your needs and choose the one that best suits your needs.

Relational Operators
- Relational operators are these symbols that you use when you are dealing with conditions. Think of them like decision-making tools in Java. Picture this: Java has these six special operators, and they help us figure out if something's true or false.
- Greater Than Operator >:  This one checks if the number on the left is bigger than the one on the right. Take the example: we are asking, "Is 2 greater than 3?" Nope, that is false.
- Less Than Operator <:  Now, it is the opposite. We are asking, "Is 2 less than 3?" Yes, it is! So, true.
- Greater Than or Equal Operator >=:  Here, we want to know if the number on the left is either bigger or equal to the number on the right. Well, 4 is indeed greater than or equal to 4, so that is true.
- Less Than or Equal Operator <=:  But, 4 is definitely not less than or equal to 3, so that is false.
- Equal To Operator ==:  In Java, using a single equal sign (=) is reserved for assignments, not for comparing stuff. So, to see if two things are equal, we use the double equal sign (==). When we ask, "Is 3 equal to 2?" Nope, false again.
- Not Equal To Operator !=:  When you want to check if something is *not* equal, you use an exclamation mark and an equal sign (!=) together. Like when we ask, "Is 3 not equal to 2?" Yes, indeed it is not equal, so true.

Logical Operators
- Logical operators in Java allow for the combination of conditions to give a clear yes or no answer, similar to a Boolean value.
- They are useful when dealing with complex requirements for decision-making. For example, if someone qualifies for a loan, they need to earn at least 30,000 US dollars and have worked for at least two years.
- Three logical operators in Java are AND, OR, and NOT. AND combines two conditions, ensuring both must be true for the result to be true.
- OR combines two conditions, ensuring at least one condition must be true for the result to be true. AND flips the truth of a single condition, if the condition is false, converting it into true.
- For the AND operator, two conditions are combined, resulting in true results.
- The OR operator requires only one condition to be true, while the NOT operator flips the condition, ensuring true results.
- In an if-else scenario, the AND operator is used to check if the salary is high enough and if the person has worked long enough for the required number of years.
- These operators help maintain code cleanliness without getting tangled up in nested if statements.

Short Circuit Logic
- The 'and' and 'or' logical operators are used to combine two conditions into one.
- The 'and' operator requires both conditions to be true, reducing the need to evaluate unnecessary ones.
- The 'or' operator, on the other hand, evaluates both conditions simultaneously, avoiding unnecessary evaluations.
- This short-circuiting technique is similar to a shortcut in logic, where the final outcome is known.
- In this example, the program starts with false and true, resulting in false.
- The program then checks true or false, ensuring that only one true condition is needed to make the entire condition true.
- The 'and' operator evaluates both conditions, ensuring both are true, making the entire condition true.
- This short-circuiting technique can help organize conditions more efficiently.

# Repetition Structures in Java

While Loop
- Loops are a useful tool in programming to perform repetitive tasks without the need for repeated copying and pasting.
- In a scenario where an employee earns $15 an hour, a program is needed to input the weekly hours worked by each employee and calculate their gross pay.
- However, the program must ensure the input is valid, as overtime is not allowed.
- To create a loop, use the word "while" and set a condition in parentheses.
- If the condition is true, enter the loop. If the input is more than the maximum hours allowed, the loop will loop back, indicating that the input is invalid.
- Inside the loop, the program informs the user that their input is invalid and updates the "hoursWorked" variable with the new input.
- The loop continues until the input is correct, and if the condition turns false, break free from the loop.
- This ensures that the program continues running until the correct data is provided.
- While loops are useful when you need to keep running code, it's important to ensure that the condition remains valid.
- In this case, a while loop is recommended for situations where you might need to keep running the code, but it's crucial to ensure that the condition remains valid.

do while loop
- A do while loop is a type of loop that checks if a condition is met after it has been executed, ensuring that the loop continues to run at least once.
- It is often used in programming to perform number crunching, where the user inputs numbers, adds them up, and presents the sum until the user is done.
- The loop starts with a "do" and curly braces, and then adds a "while" and a condition inside parentheses.
- For this particular problem, the condition is whether the user wants to hit the replay button.
- A variable called "runAgain" is created, and if it equals one, the loop continues playing the same track.
- The loop then asks the user for their numbers, adding them together and presenting the result.
- The loop is updated based on the user's input, and the loop continues until the user hits the "play" button.
- The do while loop is similar to the while loop, but it checks the condition after it has completed its task, ensuring that the loop continues to run at least once.
- This makes it an ideal choice for situations where the loop needs to perform its task at least once and then potentially repeat it depending on a condition.

For Loop
- The for loop is a type of loop that is driven by counting, rather than a condition.
- It helps track the count of items to be scanned and adds up the total cost.
- To start the loop, write "for" and put parentheses inside. Inside these parentheses, there are three statements:
   + 1. Create a counter called "I" to track how many times the loop has run.
   + 2. Set the condition that will stop the loop as long as "I" is less than the quantity.
   + 3. Update the counter by adding one to "I" using the shorthand "I++."
- Inside the loop, ask for the price of each item and add it to the total price. The total price equals whatever it was before plus the new price.
- After running the loop the right number of times, print the total outside the loop. Close the scanner outside of the loop and print the total.
- To run the loop in debug mode, put a breakpoint in the first line inside the loop. Right-click anywhere and select "debug".
- The loop will ask for the number of items to scan, update the total, and check the values.
- For loops are responsible for counting and checking the condition before diving into the loop.
- They are ideal for situations where you know exactly how many times you want something to happen.

Nested Loops
- Nested loops are repetitive tasks that can be solved using loops within loops.
- In a real-life scenario, a class of 24 students with four tests is divided into four groups.
- A for loop is used to go through each group, starting with a variable called "i" and increasing by one.
- The loop then moves on to the next student, processing their test scores.
- A new variable, "j", is introduced to handle the inner loop, running for the four tests.
- The "j" variable is set to zero and incremented by one after each round.
- A total variable is set up to calculate each student's individual grades.
- The total variable is then added to the total variable, prompting the user for the score.
- The score is read into a variable called "score" using "scanner.nextDouble," and updated.
- The average for each student is calculated as "total divided by the number of tests" and printed out.
- The process continues for all 24 students, computing the average of their four test scores.
- Nested loops can be used in various situations, such as two while loops or a while loop inside a for loop.

Break Statement
- In a program to search for the letter A in a string, a For Loop is used to search through the text.
- The loop initializes 'I' at zero and runs until 'I' reaches the end of the text.
- The loop increments 'I' by one after each iteration.
- Inside the loop, the current letter is stored in a variable called 'currentLetter'.
- If 'currentLetter' is an uppercase or lowercase 'A', 'letterFound' is set to true.
- Once 'A' is found, the loop stops, and the 'break' statement is used to break out of the loop.

# Methods in Java

Creating methods
- In Java, methods are tools within a class that help tackle big problems by breaking them into smaller, more manageable parts.
- They perform specific jobs and can save time by avoiding repetition in the code. A method is made up of a header, which is the opening line of the method, and a return type, which specifies the type of answer it will return.
- Parentheses are used to store information the method needs, and a signature is used to distinguish them.
- The body, enclosed in curly braces, is the actual code executed when the method is called.
- If the method is not a "void" type, it must have a "return" statement at the end, sending the answer back out. "Return" is a special word in Java, and this is how a method works.

Calling methods
- A method's action is not determined by its order, but rather by the order it is called in.
- For instance, a greetUser method can be placed after the main method or upfront.
- The greetUser method, which asks the user's name, stores it in the name variable, and then provides a friendly greeting.
- However, if the program is launched without calling the main method, it would simply sit idle.
- To activate the greetUser method, call its name from the main method or any other method within or outside the class. This will trigger the greetUser method when the class is launched.

Variable Scope
- A method is a function that runs within a class, and its order doesn't matter.
- Variables are limited edition stickers that only work where they are born.
- They can be declared in curly braces or outside of methods, with the scope being narrower. For example, a variable called "myVariable" can only be used within an "if" block.
- Local variables are defined within methods, like those inside loops or decision structures, while global variables are defined outside of methods and have a wider reach, extending to the entire class.
- Accessing global variables from anywhere in the class, including within its methods, is possible. When using a global variable and a local variable with the same name, the one with the narrower scope takes precedence when referenced.
- In local scope, the compiler assumes the local variable is the default variable, but if you need to access the global variable, you can use the "this" keyword. This tells the compiler that you want the version associated with this class.
- When deciding whether to declare a variable globally or locally, consider where in your program you will need it.
- If it's only necessary within a limited scope, go with a local variable. If you need to reference the variable across multiple methods, a global scope is the way to go.

Passing Data to Methods
- To determine if a user qualifies for a loan based on their salary and credit score, a new method called "isUserQualified" is created outside the main method.
- The "isUserQualified" method requires the user's salary and credit score variables, which are stored in the main method.
- To make them accessible, they are listed as parameters in the parameter list. Inside "isUserQualified", two additional variables are introduced: one for the required salary and another for the required credit score.
- An "if" statement is added to check if the user meets these conditions and print an approval message if approved, and a friendly "Sorry, you have been declined" if not.
- To call the method, the variable names for salary and credit score are the same in both the main method and "isUserQualified".
- However, changing the variable names to "actualSalary" and "actualCreditScore" in the main method does not cause errors, as the order of arguments must match the parameter list's order.

Returning Data from Methods
- Methods in programming are used to perform tasks and sometimes return results.
- For example, the isUserQualified method is a one-way street that returns true if it checks if something is true, and false otherwise.
- When a method returns a yes or no, it is stored in a variable called "qualified".
- The "notifyUser" method is picky and requires a boolean response.
- It determines the message to send based on the response.
- The "qualified" box is created from the main method, which returns the answer from isUserQualified.
- If the response is false, the "notifyUser" message is declined.

Overloading Methods
- Overloading is the practice of having multiple methods with the same name but different characteristics in a class.
- In a "month" class, there are two "getMonth" methods, one accepting an integer representing the month and the other taking a string as the month's name.
- Overloading allows the compiler to determine which method to use when calling it by passing an argument matching the method's parameter list.
- However, creating overloaded methods with the same parameter list can result in a compilation error.
- Overloading methods offer similar methods with slight variations, allowing for a more efficient handling of different scenarios without a messy, conditional logic.

# Objects in Java

Defining Classes for Objects
- In programming, objects are containers that hold data and actions, similar to building a blueprint for a rectangle.
- Rectangles have characteristics like length and width, which are called "fields".
- These fields are declared as "double length" and "double width".
- The class is not meant to perform tasks itself, but to create rectangle objects.
- To set these values, "getter" and "setter" methods are used.
- Encapsulation is a golden rule in object-oriented programming (OOP)Agile, which states that a class's data should be kept private while its methods can be shared with other classes.
- Encapsulation is achieved by adding a "private" label on the length and width fields and a "public" label on the methods that define the behavior.
- A "protected" access modifier is also used, allowing only classes in the same package to access it.
- In summary, objects are like the blueprint for a rectangle, with fields and methods being shared between classes.

Java Constructors
- Constructors are essential for setting initial values or configuring an object's state.
- The default constructor is the first type encountered, as it does not take any parameters.
- In Java, default constructors are always present, acting as methods without a return type.
- They start with a keyword like 'public' and do not have a return type.
- The constructor's name matches the class name, like'rectangle'.
- The constructor does not have any parameters, and curly braces for the body.
- The goal of this default constructor is to give default values to the class's fields, like setting the length and width to zero.
- Multiple constructors can be created, each with the same name but accepting different parameters.
- For example, 'public Rectangle' can be used with 'double length' and 'double width' as parameters.
- The setter methods can then be used to set the fields, providing options for setting up a rectangle's state.

Object Instantiation
- In this Rectangle class scenario, we create two objects to calculate the area of a few rooms in a house.
- To create a new object, we create an instance of the class based on the Rectangle class and specify its data type.
- We name the object "room1" and create an instance using the keyword "new" followed by the class's constructor.
- The dot operator allows us to tap into an object's superpowers.
- We set the width of "room1" using "setWidth" and "setLength" and calculate the area using "room1.calculateArea".
- Next, we create another room object using the constructor that takes the length and width as arguments.
- We call "Rectangle room2 = new Rectangle" and pass in 30 and 75 values, which IntelliJ assigns to "length" and "width".
- This class is used to model physical rooms, serving as the blueprint for all kinds of rectangles.
- In this case, we use it to represent rooms in a house, which is a type of rectangle. In essence, a class is a blueprint that can be used to create specific objects tailored to your needs.

Method Parameters as Objects
- Objects can be used as method arguments in programming, similar to primitive data types.
- For example, two Rectangle objects representing rooms like kitchen and bathroom can be used as method arguments.
- A method named calculateTotalArea is created, taking two Rectangle objects as input.
- The dot operator is used to call calculateArea methods, and the sum is returned.
- The main method then calls calculateTotalArea with the kitchen and bathroom as arguments, and prints the total area with the area value.

Method Return Types
- To create a method that provides the length and width of a rectangle, we can use a getRoom method instead of creating a new Rectangle directly.
- This method asks for the dimensions and returns an object with them. The return type should be the type of object we want to create, which is a rectangle.
- Once we have the length and width, we can create a rectangle object using the information and send it back using the return_new Rectangle method.

Wrapper Classes
- Wrapper classes transform primitive data types into objects, such as number1 (int) and number2 (integer).
- They offer numerous methods compared to primitive data types, including MIN_VALUE and MAX_VALUE, compare and compareTo methods, conversion tricks like doubleValue and floatValue, and the parseInt method.
- The Integer wrapper class is a treasure chest for handling integers, with methods like MIN_VALUE and MAX_VALUE, compare and compareTo, doubleValue and floatValue, and the parseInt method.
- The valueOf method can be used to convert a plain integer variable into an Integer object. Similar tricks are found in other wrapper classes.

Records
- A record is a Java class designed for simple objects with fields and methods that handle those fields.
- It is similar to a class but is tailored for objects with fields and methods.
- Record creation is easy, just like classes. For example, creating an "account" model with fields in parentheses and curly braces is a record.
- Records are set in stone and untouchable once confirmed.
- Accessor methods are the same name as the field, not "get".
- Records are useful for wrangling simple objects, which can be accessed later in the code.
- They are often called POJOs, or Plain Old Java Objects, and simplify the code for basic objects.
-----------------------------

# Week 2 Java Fundamentals
------------------------

# inheritance
Inheritance involves a new class taking on the content of another class, forming an extension. The parent class, also known as the superclass, shares its data with the child class, allowing them to recycle and build upon it.

- Constructors in Inheritance
   + When dealing with constructors and inheritance, it's important to be explicit when calling constructors from the superclass.
   + For instance, if you want a different constructor from the superclass to run first, you must create a new constructor in 'person' that takes a name as a parameter.
   + In 'employee,' you can call any of 'person's' constructors using'super'.
   + If you want another constructor, you can pass the necessary arguments.
   + If the superclass does not have a default constructor, the subclass must explicitly call one of its other constructors.
   + If you remove the'super' call from 'employee' and the default constructor from 'person,' you will see an error.
   + To fix it, you must call one of the other constructors that still exist.
   + In summary, a superclass constructor runs first, explicit calls to superclass constructors use'super', and if there is no default in the superclass, you must call one of the others.

- Overriding and Overloading Inherited Methods
   + A subclass inherits methods from its superclass, but sometimes it wants to change how a method works.
   + This is known as "overriding a method." In this case, the "square" class inherits methods from the "rectangle" class, but the way the square calculates the perimeter is different from the regular rectangle.
   + To fix this, the "square" class creates a new method in "square" that looks exactly like the one in "rectangle" and tweaks the inside to fit the square's formula for calculating perimeter, which is sides times length.
   + Overloading methods is another technique where multiple methods with the same name are in one place but take different types of inputs.
   + When working with a subclass, you can tweak a method that you got from a superclass, even if that method is in a different class.
   + For example, in the rectangle class, we add a new method called "print" that simply says, "I am a rectangle."
   + In the square class, we give "print" the same name but take a string as a parameter, and we have two choices when calling "print" on the square class: the one we inherited and the new tweaked version.

- Chain of Inheritance
   + In Java, a class can inherit from one superclass and another class, creating a chain of inheritance where a subclass inherits from its ancestor classes.
   + For example, a Vehicle class inherits from a Vehicle, adds a doors field, and sets the doors to 2.
   + To test this chain of inheritance, create an instance of Coupe, "myCar," and set its color to red.
   + Despite the lack of a "setColor" method in Coupe and Car, myCar can be given a color.
   + To print the car's color and doors, use "myCar.getColor()" and "myCar.getDoors()".
   + This hierarchy of inheritance allows classes to inherit from a chain of other classes, despite Java not supporting multiple inheritance.

Limiting Access in Inheritance
- When a subclass inherits from a superclass, it inherits only public and protected methods and fields, while private methods and fields remain exclusive to the superclass.
- For example, the Square class can use the fields'side' and 'length' from the Rectangle class, as they are marked as 'protected' in terms of access.
- However, if'sides' is marked as 'private', it would not be inherited and cannot be used outside of the Rectangle class.
- Overriding methods, such as the 'calculatePerimeter' method from the Rectangle class, can be made less strict by changing the method to 'protected' in the superclass.
- Access modifiers act as bouncers in the class world, deciding who gets in and out of the code.
- Superclasses use these modifiers to control what can be shared with their subclasses.

Sealed Classes
- Java classes can be considered "sealed classes" if they only allow certain inheritance rules.
- For example, if we have shapes like circle, rectangle, and square, we can only allow rectangle and circle to inherit from the main shape class.
- To do this, we add a "sealed" label to the class and add a "permits" section to list the classes allowed to inherit from this sealed class.
- Sealed classes follow the same rules as their parent, while non-sealed classes are open for extension.
- Final classes are off-limits for inheritance.
- In the context of shapes, rectangles can be sealed to only allow square to be its buddy, while circles can be non-sealed.


# Polymorphism 
- Polymorphism With Objects
   + Polymorphism is a concept in Object-Oriented Programming that allows for shape-shifting between classes.
   + It involves a superclass being the big boss, and a subclass being the cool kid who can perform tasks similar to the superclass.
   + For example, a dog inherits from an animal, allowing it to bark, fetch, and perform other doggy behaviors.
   + Polymorphism allows for unique sounds in animals, dogs, and cats.
   + For example, Rocky, a regular dog, can make a loud "woof" when he is a dog, while Sasha, an animal but also a dog, can make a doggy "woof" when she is a cat.
   + This morphing allows Sasha to sound like a dog or a cat depending on her mood, showcasing the power of polymorphism in Java.
   + Overriding a superclass type allows for the application of subclass elements, allowing for the morphing of Sasha to sound like a dog or a cat depending on her mood.

Object Type Casting
- Type casting is a method used to transform an object's type, either explicitly or implicitly.
- It involves creating an object that is technically of the superclass but wears the hat of a subclass, known as an implicit upcast.
- This upcast only knows about the methods of the class it was casted up to, meaning it cannot perform dog-specific tricks.
- To unleash these special tricks, it must be explicitly downcast back to a Dog.
- For example, a cat named Sasha can be transformed into a Cat by adding the 'Cat' class in parentheses and wrapping the whole thing in parentheses.
- This allows Sasha to scratch using the dot operator, triggering the scratch method from the Cat class.
- However, it is important not to get too trigger-happy with casting, as the compiler may allow casting to any object without issue.
- Type casting should only be used when absolutely necessary and double-checked to avoid mishaps.

Instanceof Operator
- Java's "instanceof" operator is used to check if an object belongs to a specific class.
- For example, if we have an "animal" superclass with "dog" and "cat" subclasses, we can check if Sasha is an "animal" by checking if she is a dog.
- If it is true, it means Sasha is an animal, and if it is false, it means she is a cat.
- The "feed" method in Java allows us to feed any animal or subclass of animal using "polymorphism".
- This method can be used to determine the actual subclass of an object, such as dogs or cats.
- For example, if Sasha is a dog, we can feed it dog food, and if it is a cat, we can feed it cat food.
- Instanceof is a useful tool for checking and transforming an object, similar to pattern matching in Java.

# Abstraction
- Abstract Classes and Methods
  + Abstraction in object-oriented programming refers to having an idea that is not yet ready for conceptualization.
  + In Java, an abstract class is added to classes and methods, serving as a blueprint for specific shapes.
  + These abstract classes are vague and cannot be directly used, but guide more specific shapes.
  + Abstract methods are even more abstract, with no instructions inside, leaving it up to subclasses to fill in the details.
  + When defining an abstract method, the word "abstract" is used, followed by the return type and method name.
  + Abstraction in Java sets rules and expectations for related concepts in code.

Inheriting From Abstract Classes
- An abstract class is a blueprint for other classes, like a rectangle class that extends the abstract class Shape.
- When it extends Shape, the rectangle class inherits the "calculate area" abstract method, which is similar to passing the baton of responsibility.
- The class must decide whether to implement this method or declare it as abstract, as it carries unimplemented abstract methods from Shape.
- If the rectangle only wants to tackle 5 of the 20 abstract methods, it can declare the class as abstract and push the remaining 15 to any class that extends the rectangle.
- To implement the inherited abstract method, right-click, select "generate", and choose "implement methods".

Creating Objects With Abstract Types
- Abstract classes are templates that cannot be directly used, like "shape".
- They cannot be converted into objects, but can be used as types if an instance of their non-abstract subclasses is created.
- For example, "rectangle" can be converted into a shape by multiplying its length and width.
- Abstract classes are for inheritance purposes only, and revisiting them is part of the learning process.
- It's important to stick with abstract concepts and avoid creating instances.

# Interfaces
- Creating an Interface
   + An interface is a blueprint for an abstract idea, similar to an abstract class.
   + It lacks state, constructors, and cannot change the values of its fields.
   + Classes implement interfaces rather than extending them. To create an interface for products, create a Java class with 'interface' as the type and name.
   + Fields in an interface must be constant and public, and cannot be accessed by implementing classes.
   + This allows for the creation of methods without bodies, similar to abstract classes.
   + For example, to create getter and setter methods for 'name', declare the return type and method name, and include any necessary parameters.
   + Interfaces are useful in Java for abstraction, polymorphism, and multiple inheritance.
 
Implementing Interfaces
- In Java, dealing with interfaces is like signing a contract.
- A "Book" class must implement the "Product" interface, which does not use "extends" to connect with others.
- To comply, the Book class must either have all the required methods or label it as abstract.
- If not, Java may demand the implementation or declare the class as abstract.
- To comply, right-click on the class and tell Java to generate and implement the methods, adding data like a "private String name."
- The Book class can also be customized with unique features like author names, page numbers, and ISBNs.
- However, if the class implements multiple interfaces, it must follow all their rules.
- If methods have the same name but different return types, Java will reject the class, as it cannot ignore such clashes.

Instantiating Objects With Interface Types
- The text describes a problem with creating a "book" interface in the book class, which is not possible due to the error message.
- A workaround is to use any class that implements the product interface, such as "book".
- To name the book, use the "setName" method from the book class and name it "In the Kitchen with H+ Sport."

Default and Static Methods
- Interfaces in programming can house default and static methods, which are different from abstract methods.
- For example, a "Product" interface can have methods to set and get the product name, but these methods need to be public and abstract by default.
- To avoid breaking non-abstract classes that use the Product interface, default methods can be made "default" by marking them with the word "default" and giving them a body.
- However, these methods become available to all classes that use the interface.
- Static methods are similar to default methods but cannot be overridden by implementing classes.
- They can only be accessed through the interface itself. Any class that uses an interface must implement its methods or declare itself abstract.
- By default, interface methods are public and abstract.

# Data Structures
- Collections Framework
   + A collection is a container for organizing data, with elements holding references to other things.
   + Java offers a collections framework, a toolbox for handling these groups or collections.
   + The "Collection" interface is the main interface, followed by Set, List, Queue, and Map.
   + Java also provides a "collections" class with useful items like binarySearch, copy, frequency, reverse, shuffle, and sort.
   + These tools help handle data in Java, providing a comprehensive approach to data management.

Sets
- A set in programming is a group of unique items that do not care about order, like a club without duplicates.
- It can be created directly or like a blueprint, with different types including hash sets, linked hash sets, and tree sets. Sets are not just for strings, but can be used for any object type.
- To check if a set has a specific requirement, use the "contains" method. To remove something from a set, use the "remove" option.
- The "of" method is an easier way to fill up a set, but it can become stubborn and cause an unsupported operation exception if used.
- The Java documentation provides more details about sets.

Lists
- Lists are common in programming and can be categorized into array lists, link lists, stack, and vector. To create an array list, use the "add" method to add an apple, lemon, banana, and orange.
- The order remains intact, and items can be accessed by their position using the "get" method.
- To swap items, use the "set" method, and lists are happy with duplicates.
- To find specific items, use "index of" to find the first occurrence and "last index of" for the last.
- To remove items, use the "remove" option, but be cautious with doubles.
- An unchangeable list can be created using "list.of". For example, adding a cherry, cranberry, and plum all at once.

Queues
- A queue is a system where items are added and removed in a line, following the "first in, first out" rule.
- It can be used in various types, such as linked lists or priority queues.
- Queues can be modified to place the same item multiple times.
- The "first in, first out" rule ensures that the first item to be removed is the first to be removed.
- Queues can be saved in a variable and printed out. The peek method allows for checking the front of the line without causing it to move.

Maps
- Java's Map interface is a dictionary that pairs keys with values, such as fruit names and calorie counts.
- There are different types of maps, such as HashMap, TreeMap, and LinkedHashMap.
- The map presents as a jumbled-up list, but it is easy to find if you know the key.
- To update a value, use 'putIfAbsent' instead of 'put'.
- There is also a'replace' method for replacing items.
- To get something from the map, use the key.
- To clean up the map, remove the key you want to remove.
- If you want to know if a map contains something, use 'containsKey' and 'containsValue'. 'Map.of' allows you to create a map in one go.
- Maps can also provide sets, such as 'entrySet' for keys and values, 'keySet' for keys, and 'values' for values.

Iterators
- In Java, iterators are a common way to loop through collection elements.
- These are provided by the collection interface and can be used to access items by index.
- To loop through all elements, call the method on the collection and use a condition to check if there are more items to process.
- Inside the loop, print out an element using, which gives you the next element in the collection.
- You can customize this loop to perform any processing you need.
- The method is available for all collections inheriting from the collection interface, but Maps do not inherit from the collection interface.
- Instead, Maps provide the method to loop through Map elements as a set.

Enhanced For Loops
- An enhanced for loop is a useful tool in programming for looping through collections of items.
- In this example, we have a list of strings called "fruits" and want to show each one.
- The for loop starts with "for" followed by parentheses, and we name the current item inside parentheses.
- Then, we add a colon and the name of our collection, "fruits". The for loop will read "for each 'fruit' in the 'fruits' collection".
- However, an error occurs when the types do not match.
- To fix this, we can specify the type of elements the collection can contain using angle brackets.
- The loop then prints out each fruit from the collection. This loop works with all types of collections.

forEach() and Lambdas
- The forEach method on Map collections simplifies the process of going through collections compared to using an iterator.
- It requires no loop setup and can be used with lambda expressions, such as "f" for example. For example, "system.out.println(f)" would be a simple way to print "f".
- For one method, a method reference can be used to name the input and output.
- For each element, actions can be wrapped in curly braces.
- For Map collections with key and value, lambda expressions need two inputs, "k" for key and "v" for value.
- The action is then performed, like "print k + ':' + v". ForEach is the modern way to go through Java collections, and practicing it with collections can make it useful.

# Functional Interfaces
- Functional Interfaces
   +  Functional programming is a software development style that uses mathematical functions to process inputs and produce outputs.
   +  Java, an object-oriented language, has a toolkit called java.util.function, which houses functional interfaces with a single job, which are executed using lambda expressions and method references.
   +  For example, to print a list of countries, we can use forEach with a lambda expression that secretly corresponds to the Consumer functional interface.
   +  This interface has a special method that takes something and returns nothing, which is executed by our lambda expression.
   +  In addition to lambda expressions, method references are also available in java.util.function, which includes other functional interfaces like Supplier, Predicate, Function, and specialized operators like UnaryOperator and BiFunction.
   +  These interfaces have one main method, default, and static methods.
   +  For example, the function interface has a default method called andThen, which allows for additional operations on its result.
   +  To create your own functional interfaces, it is recommended to annotate your interface with @FunctionalInterface to ensure only one main method.
   +  You can also include extra static or default methods for added utility. With this knowledge, you can use Java for both object-oriented and functional programming.

Streams
- Java provides both the java.util.function and java.util.stream packages for functional programming.
- A stream is a conveyor belt of items from a collection or array, allowing for manipulation without affecting the original source.
- The java.util.stream package offers tools for performing these tricks, such as morphing an array of even numbers into a stream, resulting in a series of odd numbers.

Exception Handling
- An exception is a runtime hiccup caused by an error, disrupting the smooth flow of a program.
- It can be a "array index out of bounds exception" where a loop attempts to access something from an array's index that does not exist.
- To handle these exceptions, Java's File class has a method called "createNewFile" that creates a file with a path that does not exist.
- If the directory where the file is supposed to be created does not exist, an "IO exception" is thrown.
- To catch an exception, a try block is wrapped in curly braces, followed by a catch block with parentheses and parentheses specifying the type of exception to catch.
- Java will try to create the file, but if it fails, the catch block is used to print a message, preventing the program from crashing.

Stack Trace and Exception Message
- Exceptions are messages that help understand what went wrong in code.
- They can be obtained through methods that provide information about the exception and can be added to user displays.
- A "stack trace" is a map showing the path the program took before hitting the exception, helping to identify the cause.
- Printing the stack trace when catching an exception is common.
- It shows a list of classes, methods, and line numbers that led to the exception, which can be accessed for more details.
- The last line in the stack trace indicates the trouble started, while the next entry reveals the line causing the problem.
- Sometimes, an entry without a line number may be missing due to a native method written in a different language.

Handling Multiple Exceptions
- Code errors can be handled using three techniques: polymorphism, using a series of catch blocks, and having one block that can catch multiple errors.
- Polymorphism is useful when errors are related like a family, with the parent "Exception" being the parent.
- A series of catch blocks can be used to handle multiple errors, such as "FileNotFound" and "InputMismatch".
- However, if both errors cause the same code crash, having one catch block can simplify the process.
- These three techniques help prevent code from going wrong by handling errors in a way that treats them differently and ensuring that the code is executed correctly.
-----------------------------------------------------

# Week 3 Intermediate Java
------------------------
# Streams and Lambda Expressions

Functional Programming
- Functional Programming is a popular programming paradigm that focuses on assessing mathematical functions and avoiding altering data states.
- It allows functions to be assigned to variables, passed as arguments, and returned from other functions.
- Functional programming offers advantages such as fostering code comprehension, simplifying debugging, enhancing modularity by composing smaller functions into more complex ones, and improving concurrency by eliminating multiple states.
- In Java 8, features like Lambda Expressions, method references, and the stream API enable functional programming.
- This paradigm can be implemented in Java projects to enhance code comprehension, modularity, and concurrency.

Lambda Expressions
- Functional programming is a fundamental paradigm that includes lambda expressions, which are concise, nameless functions used to implement functional interfaces.
- These interfaces have only one abstract method and consist of a parameter list, arrow token (->), and body.
- Lambda expressions require a functional interface with a corresponding signature for effective use.
- Examples include Predicate in IntelliJ, which evaluates string length, and Consumer, a built-in functional interface.
- Lambda expressions can be dynamic and assigned to variables, making code more flexible.
- A shorthand syntax called Method Reference is used for invoking existing methods more concisely.
- This feature is particularly powerful when combined with the Stream API to handle and process data sets effectively within the functional programming paradigm.

Streams API and Handling Data Sets
- The Stream API is a functional programming tool that simplifies working with datasets.
- Streams are sequences of elements that can be processed sequentially or in parallel, sourced from collections, arrays, or I/O channels.
- Common methods for creating a Stream include ".stream()" or collections, ".stream()" with arrays, and the "Stream.of" method.
- Intermediate operations, such as filtering, transformation, and flattening, are chainable and lazy.
- Terminal operations, like "f or each" or "col<= ct", conclude the processing.
- This approach aligns with the functional programming style, enhancing code readability and maintainability.

 # Generics and Collections
 
Collection Framework
- The Java collection framework offers various tools for managing groups of items, including interfaces and classes for collections like list, set, queue, and map.
- These interfaces handle tasks like adding, removing, and looping through items. The list, set, and queue are closely related as they extend the collection interface.
- The map is a loner, focusing on key-value pairs rather than single items.
- Implementation classes provide specific functions and performance boosts for these data structures.
- Lists include ArrayList and LinkedList, sets include HashSet and TreeSet, and maps include HashMap and TreeMap.
- Examples include creating an ArrayList, adding and removing elements, and printing the list.
- The type of the list is specified as strings on line eight, which helps the compiler catch any wrong additions and saves time.

Generics Role
- Generics in Java have revolutionized the way collections handle objects, allowing for easier type safety and reusability.
- They allow collections to determine the object type a collection can hold at compile time, preventing runtime errors.
- Generics catch type-related issues during compilation, preventing runtime hangovers.
- They also allow generic classes and interfaces to work with various types, making code cleaner and less repetitive.
- For example, a list of integers with numbers cannot accommodate non-numeric guests like "hello" or long strings of characters.
- The compiler ensures that everything lines up when adding numbers, making the code safer and more efficient.
- Generics are like the unsung heroes of Java, making code safer and more efficient.

Parameterized Types
- This section explains how to create and leverage generic classes in Java, which are useful for code and make built-in Java code easier to understand.
- To create a generic class, type parameters are defined within angle brackets in the class declaration, acting as stand-ins for actual types when creating class instances.
- In IntelliJ, a generic "Pair" class can hold two objects of the same type, with "T" being the parameterized type.
- Type safety is ensured by defining actual type arguments when using the class.
- The generic class can handle String and Integer types without casting, making it smart enough to handle both types without fuss.

# Annotations and Reflection
Introduction to Annotations
- Annotations are small tags that can be added to Java classes, methods, or fields to add extra information or modify code behavior.
- They are versatile and can be used for generating code, adhering to coding standards, or providing hints to tools and frameworks.
- Java has built-in annotations, such as "@Override" to signal a method's intended override, "@Deprecated" to indicate a method's discontinuation, and "@SuppressWarnings" to suppress warnings.
- Annotations can be added to classes, fields, parameters, and more.
- They are essential for adding metadata and directing code's behavior at compile or runtime.

Creating Custom Annotations
- Custom annotations are a useful tool in Java frameworks like Spring, allowing developers to define attributes like priority and tags.
- These annotations can be used on classes, methods, and fields, and can be used for data validation, logging, and auditing purposes.
- For example, a custom annotation with "priority" and "tags" can be set on a class and a method, with the class setting values for priority and tags, and the method specifying tags.
- By combining custom annotations with the Java Reflection API, developers can create powerful tools for data validation, logging, and auditing.

Reflection API for Dynamic Code Manipulation
- Java's reflection API provides a backstage pass to your code's metadata, including classes, methods, and fields, while it is running.
- It allows you to explore a class's structure, methods, fields, and annotations.
- By pairing it with annotations, you can create new instances of a class, call methods, access fields, and even change how a class, method, or field behaves while the program is running.
- For example, to check if a class has a custom annotation called "my custom annotation," we can get data from the "info" class and save it in a special class object.
- If it does, we print the "priority" and "tags" value. If not, we loop through all the methods in "info," checking if each method has our custom annotation.
- The reflection API makes dynamic code manipulation a breeze, enabling applications like code generation, dependency injection, and runtime configuration.
- It's like next-level Java, enabling cool applications like code generation, dependency injection, and runtime configuration.

# Multithreading and Concurrency

Introduction to Concurrency and Multithreading
- Concurrency and multithreading are crucial in programming, enhancing the efficiency and responsiveness of applications.
- Concurrency involves juggling multiple tasks simultaneously, while multithreading allows different threads to run simultaneously within a single process.
- This allows for more efficient use of system resources, leading to faster and more responsive applications.
- Java supports multithreading through the "Thread" class and "java.util.concurrent" package, allowing for the creation and management of threads in Java apps.
- For instance, a "MyRunnable" class can start threads by implementing "Runnable" and printing a message with the thread ID.
- By understanding these concepts and using Java's built-in support, developers can significantly improve their app's performance.

Concurrency Concepts
- Java provides a range of tools and APIs to manage concurrency and multithreading.
- The "Thread" class and the "Runnable" interface are essential for managing threads, offering methods for kickstarting, halting, and keeping them in check.
- Java also provides synchronization and locks to ensure shared resources are accessed safely by multiple threads.
- The "java.util.concurrent" package with the "Executor" framework simplifies the creation and management of threads, especially for handling multiple tasks concurrently.
- In IntelliJ, you can create a fixed thread pool with a specified number of threads and execute tasks concurrently.
- Java also offers concurrent collections, such as the "ConcurrentHashMap," designed for safe manipulation by multiple threads.
- The "Future" and "Callable" interfaces are useful for dealing with delayed responses, such as retrieving results with an "ExecutorService" and "Future."
- This overview should help you create apps that can handle multiple tasks simultaneously.

# Design Patterns
Singleton Design Pattern
- The singleton design pattern is a widely used pattern that ensures a class has only one instance, creating a universal point of access.
- It is favored by Spring Boot and is used for managing a single database connection, global logger, or centralizing application settings.
- The benefits of the singleton pattern include controlled access, lazy instantiation, and efficient management of shared resources or states.
- It is ideal for classes that need to maintain a single instance across an application.

Singleton Pattern Implementation
- The singleton design pattern is implemented using two common approaches: eager initialization and lazy initialization.
- Eager initialization creates a singleton instance immediately upon class loading, making it suitable for resource-heavy or long-term applications.
- This is done by creating a static instance and ensuring only one instance exists.
- On the other hand, lazy initialization waits until the instance is needed before creating it, making it more efficient for resource-intensive or non-recurrent applications.
- This is achieved through synchronization, ensuring only one thread can create the instance at a time, and a double null check to prevent simultaneous instances.
- However, non-synchronized getInstance methods can create multiple instances in multi-threaded environments, while synchronized methods can prevent this.
- Understanding the pros and cons of each approach helps choose the right one for each scenario.

# Input and Output
Introduction to I/O in Java
- Streams are used for data read or written, with applications in file operations and console input.
- They represent a one-way flow of data, with OutputStreams sending data out and InputStreams taking data in.
- In the Java Streams API, there are two core abstract classes: InputStream and OutputStream, which have concrete implementations for handling different data types.
- Reader and Writer are abstract classes that handle characters, Unicode, and character encoding, while InputStream and OutputStream deal with bytes.
- Concrete implementations are used based on the data type being worked with.

Reading from System
- In this example, an app is created using the Scanner class to read user input from the console.
- The class is created and linked to "System.in" to fetch keyboard inputs.
- The user-friendly interface is made by using "system.out.print" to keep the input on the same line and using "scanner.nextLine()" to get the user's input.
- The "name" variable is then printed out to display the user's name.
- The same approach is used for the age, using "scanner.nextInt()" to get the number.
- The code is then run to check if the user's name, age, and occupation are correct.
- However, there is a problem with "nextLine" and "nextInt" in the code.
- To fix this, the code can switch "nextLine" to "nextLine" for age and convert the string to an integer, or add another "nextLine" to jump past the line separator.
- The Scanner is then used to read the user's input.

Reading files
- To read input from a file named "example.txt" in a folder named "06_03", create a BufferedReader using the following code: "BufferedReaderread ==/wBufferedReader(=/wFi<=Reader(src/main/java/06_03/example.txt));"

Using try-with-resources
- The code for reading a file with a buffered reader can be improved by adding a "finally" block after the "try-catch" sections to ensure proper resource closure.
- However, in complex applications with multiple resource openings, this step is often overlooked.
- A simpler solution is "try-with-resources," which declares the resource inside brackets after the "try" keyword.
- This minor change can prevent memory leaks and make the application safer.
- Therefore, consider using "try-with-resources" whenever creating resources inside a "try" block.

# Files and Directories
Working with Files
- Java has file-handling capabilities, with two main packages: java.io and java.nio.
- The "File" class, which creates files and lists directory contents, has limitations.
- The java.nio package offers new classes like "Path," "Paths," and "Files," providing a modern API with improved error handling.
- It is generally better to use java.nio classes for file work, as they offer better error handling.
- The main players from java.nio are "Path" and "Paths," which represent file system paths and offer static methods for tasks like copying, moving, and deleting files.

Creating a New File
- In Java, creating an empty file is a common task in software development.
- To do this, declare a "Path" variable and set it using the "Paths" class's "get" method.
- Import the "Path" and "Paths" classes from the "java.nio.file" package.
- Then, use the "Files" class to create an empty file named "example.txt" in the specified folder.
- To avoid an "file already exists" exception, check if the file exists before attempting to create it.
- Use the "Files.notExists" method to determine if the file exists and only create it if it is not, ensuring the file remains empty.

Working with Directories
- In Java, working with directories is easy using the "directories example" class.
- To list the contents of a directory, use the "Files" class's static method "list".
- This method returns a stream of path objects, with the current directory represented by "Paths.get".
- To print each entry, use the "forEach" method.
- However, the "list" method throws an IO exception, so a try-catch block is used to display all project contents.
- To filter out directories, use the "filter" method before "forEach".
- To create a new directory, use the "Files.createDirectory" method, which checks if the directory already exists using "Files.notExists".
- This creates an empty directory without any exceptions, making listing and creating directories a breeze.

Copying Files
- This code demonstrates how to copy files in Java using a directory structure with subdirectories.
- The "FileCopier" class is used to copy the file "example.txt" with the content "hello world".
- The "Paths.get" method is used to set the path to the source file, and the "Files.copy" method is used to copy the file.
- To handle potential exceptions, a try-catch block is used.
- The code ensures correct paths are provided and checks if the file exists in the destination directory using "Files.notExists".
------------------------------------------
