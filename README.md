# Online-Voting-Sytem

**Project Report:-**

**Abstract**
The project is a voting program that allows users to create polls, vote on polls, and view the results of polls. The users can also download the poll results in the form of a pie chart.

**Methodology:**
Create a database to store poll information.
Create a graphical user interface (GUI) to allow users to interact with the program.
Implement functionality for creating new polls, voting on polls, and viewing poll results.
Test the program to ensure that it is working correctly.

**Libraries and Modules:**

1.)tkinter: This is a standard Python library for creating graphical user interfaces (GUIs) with Tkinter.
2.)sqlite3: This is a Python module that provides an interface to the SQLite database engine.
3.)matplotlib.pyplot: This is a Python module for creating 2D plots and charts.

**Technologies:**

1.)Object-Oriented Programming (OOP): The code employs OOP principles to organize the code into classes and objects, making it more modular and maintainable.
2.)Database Management: The code interacts with a SQLite database to store and retrieve poll data.
3.)Data Visualization: The code uses matplotlib.pyplot to generate pie charts for visualizing poll results.
 

1. Functions:
create(): Handles the creation of a new poll. It takes user input for the poll name and candidate names, creates the necessary database tables, and inserts the poll data into the database.
polls(): Displays a list of existing polls and allows users to select one to vote in.
pollpage(): Presents the voting page for the selected poll. It displays a list of candidates and allows the user to vote for one.
proceed(): Processes the user's vote by updating the corresponding candidate's vote count in the database.
selpl(): Displays a list of existing polls and allows users to select one to view the results.
results(): Generates a pie chart representing the poll results and displays it in a new window.
about(): Displays a simple about message with project credits.

2. Classes:
Tk(): The main Tkinter class that creates the root window for the GUI application.
Toplevel(): Used to create child windows for specific tasks, such as creating a poll, viewing poll results, or displaying the about message.
Label(): Creates a label widget to display text on the GUI.
Entry(): Creates an entry widget to allow users to input text.
Button(): Creates a button widget that triggers an action when clicked.
StringVar(): A Tkinter variable type used to store and manage text data.
Combobox(): A Tkinter widget that provides a drop-down list for selecting options.
messagebox (from tkinter module): Provides functions for displaying dialog boxes with messages.
sqltor (from sqlite3 module): Used for connecting to and interacting with SQLite databases.
plt (from matplotlib.pyplot module): Provides functions for creating and displaying plots, including pie charts.

These functions and classes work together to create a functional voting program that allows users to create polls, vote, and view results.

**Key features**
1.)Easy to use: The program has a simple and intuitive GUI that makes it easy to create polls, vote in polls, and view poll results.
2.)Flexible: The program allows users to create polls with any number of candidates.
3.)Data-driven: The program stores all poll data in a database, which makes it easy to track the results of polls over time.

**Areas of Improvement**

Challenge 1: Handling duplicate votes
The original code did not have any mechanism for preventing users from voting multiple times. This meant that it was possible for users to vote multiple times for the same candidate, which would have skewed the results of the poll.

Challenge 2: Handling invalid poll names
The original code did not have any validation for poll names. This meant that it was possible for users to create polls with invalid names, which could lead to errors.

Challenge 3: Create a separate Admin and User GUI.

**References**
The tkinter library for Python (https://docs.python.org/3/library/tkinter.html) is used to create the graphical user interface (GUI) for the program.
The sqlite3 library for Python (https://docs.python.org/3/library/sqlite3.html) is used to create and manage the database that stores the poll data.
The matplotlib library for Python (https://matplotlib.org/) is used to create the pie chart that displays the poll results
