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
