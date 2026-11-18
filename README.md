# Timbolkyle

while True:

    user = input("Enter Your Name: ").upper()

    print("\n==================================================")
    print(f" WELCOME TO MY PYTHON TUTORIAL PROGRAM {user} ^_^")
    print("==================================================")

    print("\n1. Introduction to Python ")
    print("2. Problem Solving, Process and Algorithm")
    print("3. Pseudocode and Pseudocode Elements")
    print("4. Arithmetic Operators and PEMDAS")
    print("5. Flowchart and Flowchart Symbols")
    print("6. Conditional Statements in Python")
    print("7. Logical Operators")
    print("8. Introduction to Iteration and Loops")

    print("\n0. Exit")
    print("==================================================")

    choice = input("\nChoose a lesson: ")

    # LESSON 1: INTRODUCTION TO PYTHON

    if choice == "1":

        print("\n===== INTRODUCTION TO PYTHON =====")

        print("\nWHAT IS PYTHON?")
        print("Python is a widely used programming language.")
        print("Created by Guido van Rossum in 1991.")
        print("It is a high-level, interpreted,")
        print("and general-purpose programming language.")

        print("\n===== WHY LEARN PYTHON? =====")
        print("1. Simple and easy to learn")
        print("2. Readable syntax")
        print("3. Versatile - used in many fields")
        print("4. Huge community")

        print("\n===== PYTHON BASIC SYNTAX =====")
        print("Syntax refers to the rules for writing Python programs.")

        print("\n1. CASE-SENSITIVE")
        print("Python treats uppercase and lowercase letters differently.")

        name = "John"
        print(f"\nExample: name = '{name}'")
        print("Incorrect: print(Name)")
        print("Correct: print(name)")
        print(f"Output: {name}")
        
        print("============================================")
        
        print("\n2. INDENTATION")
        print("Python uses spaces to define blocks of code.")

        print("\nExample:")
        print("if 5 > 2:")
        print('    print("Five is greater than two")')
        print("Output: Five is greater than two")
        
        print("============================================")

        print("\n3. PRINT STATEMENT")
        print("The print() function displays information.")
        print("Syntax: print(value)")

        print('\nExample: print("Hello, World!")')
        print("Output: Hello, World!")
        
        print("============================================")

        print("\n4. PRINTING TEXT AND NUMBERS")
        print("Text uses quotation marks.")
        print("Numbers can be printed without quotation marks.")

        print('\nExample: print("Hello")')
        print("Example: print(100)")
        print("Output: Hello")
        print(f"Output: {100}")
        
        print("============================================")

        print("\n5. PYTHON COMMENTS")
        print("Comments are ignored by Python.")
        print("They explain the code.")
        print("# is the symbol for comments.")

        print('\nExample: # This is a comment')
        print('print("Hello")')
        print("Output: Hello")
        
        print("============================================")

        print("\n6. VARIABLES AND CONSTANTS")

        name = "John"
        print("A variable stores data in a program.")
        print(f"\nExample: name = '{name}'")
        print("Variable: name")
        print(f"Stored value: {name}")

        print("\nA constant is a value intended to remain unchanged.")
        print("Python commonly uses uppercase names for constants.")

        SCHOOL_NAME = "CCST"
        print(f"\nExample: SCHOOL_NAME = '{SCHOOL_NAME}'")
        print(f"Output: {SCHOOL_NAME}")
        
        print("============================================")
        
        print("\n7. VARIABLE NAMING RULES")
        print("1. Names can be short or descriptive.")
        print("2. Must start with a letter or underscore.")
        print("3. Cannot start with a number.")
        print("4. Special characters are not allowed except underscore.")
        print("5. Variable names are case-sensitive.")

        print("\nCorrect:")
        print('name = "John"')
        print("student_age = 18")

        print("\nIncorrect:")
        print("2name = 'John'")
        print("@age = 18")

        print("\n8. ASSIGNING VALUE TO VARIABLES")
        print("The = symbol assigns a value to a variable.")

        school = "Clark College"
        print(f"\nExample: school = '{school}'")
        print(f"Output: {school}")
        
        print("============================================")
        
        print("\n9. OUTPUTTING MULTIPLE VARIABLES")
        print("You can use commas or + to display strings.")

        a = "I"
        b = "Love"
        c = "CCST"

        print("\nUsing comma:")
        print(a, b, c)

        print("\nUsing plus:")
        print(a + " " + b + " " + c)

        print("\n10. BASIC DATA TYPES")
        print("INT - Whole numbers without decimals.")
        print("FLOAT - Numbers with decimal points.")
        print("STR - Text or characters inside quotation marks.")
        print("BOOL - Represents True or False.")

        age = 20
        grade = 89.5
        student = "Maria"
        enrolled = True

        print("\nExamples:")
        print(f"Age: {age} - INT")
        print(f"Grade: {grade} - FLOAT")
        print(f"Student: {student} - STRING")
        print(f"Enrolled: {enrolled} - BOOLEAN")
        
        print("============================================")

    # LESSON 2: PROBLEM SOLVING, PROCESS AND ALGORITHM

    elif choice == "2":

        print("\n===== INTRODUCTION TO PROBLEM SOLVING =====")
        print("Problem solving is the process of analyzing")
        print("a problem and finding the best solution")
        print("before writing a computer program.")

        print("\nExample:")
        print("Problem: Find the sum of two numbers.")
        print("Solution: Get two numbers, add them,")
        print("and display the result.")

        print("\n===== PROBLEM-SOLVING PROCESS =====")
        print("1. PROBLEM - Understand the problem.")
        print("2. ANALYZE - Identify inputs, outputs, and requirements.")
        print("3. CREATE ALGORITHM - Plan the solution step by step.")
        print("4. WRITE PSEUDOCODE - Write steps using simple English.")
        print("5. DRAW FLOWCHART - Visualize steps using a diagram.")
        print("6. WRITE PROGRAM - Convert the algorithm into code.")
        print("7. TEST PROGRAM - Test and fix errors.")

        print("\n===== ALGORITHM =====")
        print("An algorithm is a step-by-step procedure")
        print("used to solve a problem or complete a task.")

        print("\nExample: Add two numbers")
        print("1. Start")
        print("2. Input first number")
        print("3. Input second number")
        print("4. Add the two numbers")
        print("5. Display the sum")
        print("6. End")

        number1 = 10
        number2 = 5
        total = number1 + number2

        print("\nSample:")
        print(f"First number: {number1}")
        print(f"Second number: {number2}")
        print(f"Sum: {total}")

    # LESSON 3: PSEUDOCODE AND PSEUDOCODE ELEMENTS

    elif choice == "3":

        print("\n===== PSEUDOCODE =====")
        print("Pseudocode is an informal way of writing")
        print("program logic using simple English statements.")

        print("\nRemember:")
        print("- It is not a programming language.")
        print("- It is a plan before coding.")

        print("\n===== PSEUDOCODE ELEMENTS =====")
        print("START/END - Begins and ends an algorithm.")
        print("DECLARE - Declares variables and data types.")
        print("= - Assigns a value or result.")
        print("INPUT - Accepts information from the user.")
        print("OUTPUT - Displays information.")
        print("IF/ELSE - Conditional structure.")
        print("WHILE/FOR - Looping structure.")

        print("\nEXAMPLE 1: Display your name")
        print("START")
        print('OUTPUT "Juan Dela Cruz"')
        print("END")

        print("\nEXAMPLE 2: Input and display age")
        print("START")
        print("DECLARE Age : INTEGER")
        print("INPUT Age")
        print("OUTPUT Age")
        print("END")

        print("\nEXAMPLE 3: Sum of two numbers")
        print("START")
        print("DECLARE number1, number2, sum : INTEGER")
        print("INPUT number1")
        print("INPUT number2")
        print("sum = number1 + number2")
        print("OUTPUT sum")
        print("END")

    # LESSON 4: ARITHMETIC OPERATORS AND PEMDAS

    elif choice == "4":

        print("\n===== ARITHMETIC OPERATORS =====")

        print("+ Addition")
        print("- Subtraction")
        print("* Multiplication")
        print("/ Division")
        print("// Floor Division")
        print("% Modulus")
        print("** Exponentiation")

        a = 10
        b = 3

        print("\na = 10")
        print("b = 3")

        print("\nEXAMPLES:")
        print(f"Addition: 10 + 3 = {a + b}")
        print(f"Subtraction: 10 - 3 = {a - b}")
        print(f"Multiplication: 10 * 3 = {a * b}")
        print(f"Division: 10 / 3 = {a / b}")
        print(f"Floor Division: 10 // 3 = {a // b}")
        print(f"Modulus: 10 % 3 = {a % b}")
        print(f"Exponentiation: 10 ** 3 = {a ** b}")

        print("\n===== PEMDAS =====")
        print("Python follows the order of PEMDAS")
        print("when performing mathematical calculations.")

        print("P - Parentheses")
        print("E - Exponent")
        print("M - Multiplication")
        print("D - Division")
        print("A - Addition")
        print("S - Subtraction")

        print(f"\n2 + 3 * 4 = {2 + 3 * 4}")
        print(f"(2 + 3) * 4 = {(2 + 3) * 4}")

    # LESSON 5: FLOWCHART AND FLOWCHART SYMBOLS

    elif choice == "5":

        print("\n===== FLOWCHART =====")
        print("A flowchart is a diagram representing")
        print("the logical sequence of steps or operations.")
        print("It shows how a process or program works.")

        print("\nPURPOSE OF FLOWCHART:")
        print("1. Shows the steps of a program.")
        print("2. Makes program logic easier to understand.")
        print("3. Helps plan before coding.")

        print("\n===== FLOWCHART SYMBOLS =====")
        print("OVAL - Start or End")
        print("PARALLELOGRAM - Input or Output")
        print("RECTANGLE - Processing")
        print("ARROW - Direction of flow")
        print("CIRCLE - Connection")
        print("DIAMOND - Decision")
        print("HEXAGON - Preparation or Initialization")

        print("\nThese symbols help represent")
        print("the steps of a program visually.")
    

    # LESSON 6: CONDITIONAL STATTEMENTS

    elif choice == "6":

        print("\n===== CONDITIONAL STATEMENTS IN PYTHON =====")

        print("\n1. INTRODUCTION TO CONDITIONAL STATEMENTS")
        print("Conditional statements allow a program to make")
        print("decisions based on whether a condition is")
        print("True or False.")

        print("\nBasic Structure:")
        print("if condition:")
        print("    statement")

        print("\nExample:")
        print("age = 18")
        print("if age >= 18:")
        print('    print("You are an adult.")')

        age = 18

        if age >= 18:
            print("Output: You are an adult.")

        print("\n2. RELATIONAL OPERATORS")
        print("Relational operators are also called")
        print("comparison operators.")
        print("They are used to compare two values.")
        print("The result is always True or False.")

        print("\nOPERATORS:")
        print("==  Equal to")
        print("!=  Not equal to")
        print(">   Greater than")
        print("<   Less than")
        print(">=  Greater than or equal to")
        print("<=  Less than or equal to")

        print("\nEXAMPLES:")
        print(f"10 == 10 : {10 == 10}")
        print(f"10 != 5  : {10 != 5}")
        print(f"10 > 5   : {10 > 5}")
        print(f"5 < 10   : {5 < 10}")
        print(f"10 >= 10 : {10 >= 10}")
        print(f"5 <= 10  : {5 <= 10}")

        print("\n3. THE IF STATEMENT")
        print("The if statement executes a block of code")
        print("only when a condition is True.")

        print("\nSyntax:")
        print("if condition:")
        print("    statement")

        print("\nExample:")
        print("age = 20")
        print("if age >= 18:")
        print('    print("You are an adult.")')

        age = 20

        if age >= 18:
            print("Output: You are an adult.")

        print("\nIf the condition is False,")
        print("the block of code will be skipped.")

        print("\n4. THE IF-ELSE STATEMENT")
        print("The else statement provides an alternative")
        print("when the if condition is False.")

        print("\nSyntax:")
        print("if condition:")
        print("    statement")
        print("else:")
        print("    statement")

        print("\nExample:")
        print("score = 65")
        print("if score >= 75:")
        print('    print("Passed")')
        print("else:")
        print('    print("Failed")')

        score = 65

        if score >= 75:
            print("Output: Passed")
        else:
            print("Output: Failed")

        print("\n5. THE IF-ELIF-ELSE STATEMENT")
        print("The elif statement is used when there are")
        print("multiple conditions to evaluate.")
        print("Python checks each condition from top to bottom.")
        print("The first True condition is executed.")

        print("\nSyntax:")
        print("if condition1:")
        print("    statement")
        print("elif condition2:")
        print("    statement")
        print("else:")
        print("    statement")

        print("\nExample:")
        print("score = 85")
        print("if score >= 90:")
        print('    print("Excellent")')
        print("elif score >= 80:")
        print('    print("Very Good")')
        print("elif score >= 75:")
        print('    print("Passed")')
        print("else:")
        print('    print("Failed")')

        score = 85

        if score >= 90:
            print("Output: Excellent")
        elif score >= 80:
            print("Output: Very Good")
        elif score >= 75:
            print("Output: Passed")
        else:
            print("Output: Failed")

        print("\n6. NESTED CONDITION")
        print("-----------------------------------")

        print("A nested condition is a condition")
        print("inside another condition.")
        print("The second condition is checked only")
        print("if the first condition is True.")

        print("\nSyntax:")
        print("if condition1:")
        print("    if condition2:")
        print("        statement")
        print("    else:")
        print("        statement")
        print("else:")
        print("    statement")

        print("\nExample: Debutant Age Rules")

        print('gender = "M"')
        print("age = 21")
        print('if gender == "M":')
        print("    if age >= 21:")
        print('        print("Male Debutant")')
        print("    else:")
        print('        print("Not a debutant yet.")')
        print('elif gender == "F":')
        print("    if age >= 18:")
        print('        print("Female Debutant")')
        print("    else:")
        print('        print("Not a debutant yet.")')

        gender = "M"
        age = 21

        if gender == "M":
            if age >= 21:
                print("\nOutput: You are a MALE DEBUTANT.")
            else:
                print("\nOutput: You are a male, but not a debutant yet.")

        elif gender == "F":
            if age >= 18:
                print("\nOutput: You are a FEMALE DEBUTANT.")
            else:
                print("\nOutput: You are a female, but not a debutant yet.")

        else:
            print("Invalid gender.")

    # LESSON 7: LOGICAL OPERATORS

    elif choice == "7":

        print("\n===== LOGICAL OPERATORS =====")

        print("AND - True when both conditions are True.")
        print("OR - True when at least one condition is True.")
        print("NOT - Reverses True and False.")

        print("\n===== AND EXAMPLE =====")
        print(f"True and True = {True and True}")
        print(f"True and False = {True and False}")

        print("\n===== OR EXAMPLE =====")
        print(f"True or False = {True or False}")
        print(f"False or False = {False or False}")

        print("\n===== NOT EXAMPLE =====")
        print(f"not True = {not True}")
        print(f"not False = {not False}")

        print("\nPRACTICAL EXAMPLE:")

        age = 18
        has_id = True

        print(f"Age: {age}")
        print(f"Has ID: {has_id}")
        print(f"Can enter: {age >= 18 and has_id}")

    # LESSON 8: INTRODUCTION TO ITERATION AND LOOPS

    elif choice == "8":

        print("\n===== INTRODUCTION TO ITERATION AND LOOPS =====")

        print("\n1. INTRODUCTION TO ITERATION")
        print("Iteration means repeating a process.")
        print("In programming, it means repeatedly executing")
        print("a set of instructions.")
        print("Each repetition is called an iteration.")

        print("\nExample:")
        print("for number in range(3):")
        print('    print("Welcome to Python!")')

        print("\nOutput:")

        for number in range(3):
            print("Welcome to Python!")

        print("\nThe print() instruction executes")
        print("once during each iteration.")

        print("\n2. TYPES OF LOOPS IN PYTHON")
        print("Python has two main types of loops:")

        print("\nA. FOR LOOP")
        print("Repeats instructions for each item in a sequence.")
        print("Useful when the number of repetitions is known.")

        print("\nB. WHILE LOOP")
        print("Repeats instructions while a condition is True.")
        print("Useful when repetition depends on a condition.")

        print("\n3. PYTHON FOR LOOP")
        print("A for loop is used to repeat a block of code")
        print("for each item in a sequence.")

        print("\nSyntax:")
        print("for variable in sequence:")
        print("    statement(s)")

        print("\nExample 1: Print Hello three times")

        print("\nCode:")
        print("for number in range(3):")
        print('    print("Hello!")')

        print("\nOutput:")

        for number in range(3):
            print("Hello!")

        print("\nExample 2: Counting 1 to 5")

        print("\nCode:")
        print("for number in range(1, 6):")
        print("    print(number)")

        print("\nOutput:")

        for number in range(1, 6):
            print(number)

        print("\nRemember:")
        print("range(1, 6) starts at 1 and stops before 6.")

        print("\nExample 3: Display a name five times")

        name = "Python"

        print("\nCode:")
        print("for number in range(5):")
        print('    print("Python")')

        print("\nOutput:")

        for number in range(5):
            print(name)

        print("\n4. PYTHON WHILE LOOP")
        print("A while loop repeats instructions")
        print("as long as the condition is True.")

        print("\nSyntax:")
        print("while condition:")
        print("    statement(s)")

        print("\nExample 1: Counting 1 to 5")

        print("\nCode:")
        print("count = 1")
        print("while count <= 5:")
        print("    print(count)")
        print("    count += 1")

        print("\nOutput:")

        count = 1

        while count <= 5:
            print(count)
            count += 1

        print("\nExplanation:")
        print("count = 1 starts the counting.")
        print("count <= 5 checks the condition.")
        print("count += 1 increases count by 1.")
        print("When count becomes 6, the loop stops.")

        print("\nExample 2: Print Hello three times")

        print("\nCode:")
        print("count = 1")
        print("while count <= 3:")
        print('    print("Hello!")')
        print("    count += 1")

        print("\nOutput:")

        count = 1

        while count <= 3:
            print("Hello!")
            count += 1

        print("\n5. REPEATING A PROGRAM WITH WHILE TRUE")
        print("while True keeps a program repeating.")
        print("The break statement stops the loop.")

        print("\nExample Code:")
        print("while True:")
        print('    name = input("Enter your name (X to exit): ")')
        print('    if name.upper() == "X":')
        print('        print("Program stopped.")')
        print("        break")
        print('    print("Hello,", name)')

        print("\nHow it works:")
        print("1. while True keeps the program repeating.")
        print("2. Enter a name to display a greeting.")
        print("3. Type X or x to exit the program.")
        print("4. break stops the loop.")

        print("\nSample Run:")
        print("Enter your name (X to exit): Ana")
        print("Hello, Ana")
        print("Enter your name (X to exit): Mark")
        print("Hello, Mark")
        print("Enter your name (X to exit): X")
        print("Program stopped.")

    # EXIT

    elif choice == "0":

        print(f"\nThank you for using my Python Tutorial, {user}!")
        print("Keep practicing and learning Python until you become a pro!")
        print("-_^")

        print("\n====================================================================")
        print(f"Also, {user}, if you want to practice coding, just search:")

        print("\n(Online GDB) - For mobile and computer users")
        print("\n(PyCharm) - For computer or laptop users")
        print("\n(W3Schools) - If you want to learn more about coding")
        print("\n( Python CodePad ) - For offline practice, available in app store")

        break

    else:

        print(f"\nInvalid choice: {choice}")
        print("Please choose a number from 0 to 8.")

    if choice != "0":
        input("\nPress ENTER to return to the main menu...")
