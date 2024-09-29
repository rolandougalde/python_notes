# Intro

As an IT professional with coding experience, diving into Python can feel like a natural next step but may come with
its own challenges, especially if programming logic hasn’t always been your strongest suit. The good news is that 
Python was designed to be simple and readable, making it an ideal language for both beginners and those looking to 
strengthen their coding skills. Its clean syntax mimics everyday language, reducing the intimidation factor that 
comes with more complex languages. 

For someone like you, with a basic understanding of coding, Python offers an excellent environment to grow. It 
encourages you to focus on the logic behind your code rather than getting bogged down in confusing syntax. From 
automating repetitive IT tasks to analyzing logs or even building small apps, Python has the versatility to help you 
accomplish practical goals.

As you get more comfortable, exploring Python's libraries—like `pandas` for data manipulation or `Flask` for web 
development—will open even more doors. Don’t just stop at learning the basics; use your curiosity to investigate how 
Python can fit into your daily IT work or side projects. There are always new tools and tricks to discover, and 
Python’s supportive community makes it easier to learn. Keep asking questions, keep coding, and enjoy the 
process—you’ll be surprised at what you can create.

## Getting started

Hello, fellow tech enthusiast!

If you're ready to start your Python journey, you're in the right place. Python is a fantastic programming language, 
and getting it up and running is super simple—whether you're on Windows, Mac, or Linux.

To get started, head over to the official Python download page: [Download Python](https://www.python.org/downloads/).

After installation, you're all set to start coding!

### Download & Install

Here’s a quick guide for each operating system:

**For Windows:**
1. Download the installer from the link above.
2. When running the installer, make sure to check the box that says "Add Python to PATH" before you hit install.
3. Once installed, open up the Command Prompt (just type `cmd` in your search bar), and type `python` to ensure it's installed properly.

**For Mac:**
1. Mac users, you're in luck—Python often comes pre-installed! To check, open your Terminal and type `python3`.
2. If it’s not installed or you need the latest version, download the installer from the link above, run it, and you’re good to go.

**For Linux:**
1. Python is usually included with most Linux distributions. Just open the terminal and type `python3`.
2. If it’s not there or needs updating, run this command:  
   `sudo apt-get install python3` (for Ubuntu/Debian-based systems).

### Choosing an IDE

**Python IDLE** (Integrated Development and Learning Environment) is the default editor that comes bundled with Python, 
designed to make writing and running Python code simple and beginner-friendly. It offers a graphical interface where 
you can write your code, run it, and even experiment with snippets in real-time.

When you open Python IDLE, you’ll see two main components:

1. *Interactive Shell*: This is the area where you can type Python commands and see immediate results. It’s perfect 
for testing small pieces of code or learning how Python behaves one step at a time. For example, if you type 
`print("Hello, World!")`, the shell will instantly show the output.

2. *Script Editor*: When you’re ready to write longer programs, you can open a new file from the menu 
(File > New File). This brings up the Script Editor, where you can write and save Python programs. You can then run 
your code using the **Run** menu or by pressing `F5`. Any output from your program will appear in the Shell.

IDLE is lightweight, intuitive, and perfect for beginners or anyone looking to quickly test and run Python scripts 
without the need for a full-fledged development environment. It’s a fantastic starting point for writing your first 
Python programs!

**Visual Studio Code** (VS Code) is a popular, free code editor that works great for Python programming. Here are three things that make it stand out:

1. *Extensions*: With the Python extension, VS Code provides powerful features like IntelliSense (code completion), debugging, and linting (code quality checks).
   
2. *Integrated Terminal*: You can run Python scripts directly within VS Code’s terminal without needing to switch between windows, making it efficient for testing and running code.

3. *Customizable*: VS Code is highly customizable with themes, keybindings, and additional extensions for various languages and tools, making it a flexible option for coders of all levels.

It’s an excellent tool if you're looking for a feature-rich environment as you advance in Python!

**PyCharm Community** Edition is a powerful, free IDE tailored specifically for Python development. Here are three great features:

1. *Smart Code Assistance*: PyCharm offers intelligent code completion, error checking, and quick fixes, helping you write clean, error-free Python code faster.

2. *Built-in Debugger*: It comes with an integrated debugger and testing tools, allowing you to troubleshoot and test your Python applications without additional setup.

3. *Project Management*: PyCharm makes it easy to organize and manage larger projects, with support for virtual environments and version control systems like Git.

It's an excellent choice if you're working on more complex Python projects and need a robust, dedicated environment.

### Running programs

At last, we finally will write a program, the classic message `Hello World!`, in Python looks like that:

Code:
```python
print("Hello World!")
```

Output:
```
Hello world!

=== Code Execution Successful ===
```

### Examples

1. Displaying a Welcome Message

```python
# Example 1: Basic welcome message
def welcome_user(name):
    print(f"Welcome, {name}!")

# Call the function
welcome_user("Alice")
```

**Explanation:**

> This example demonstrates a simple function that prints a personalized welcome message using string formatting.

2. Displaying a Multiplication Table

```python
# Example 2: Print a multiplication table for a number
def multiplication_table(number):
    print(f"Multiplication Table for {number}")
    for i in range(1, 11):
        print(f"{number} x {i} = {number * i}")

# Call the function
multiplication_table(5)
```

**Explanation:**

> This function prints the multiplication table of a given number from 1 to 10 using a for loop.

3. Displaying a List of Items

```python
# Example 3: Print items in a list with their index
def display_items(items):
    print("Items in your list:")
    for index, item in enumerate(items, start=1):
        print(f"{index}. {item}")

# Call the function
display_items(["Apple", "Banana", "Orange"])
```

**Explanation:**

> This function takes a list of items and prints them with an index, showing how enumerate() can be used in conjunction with print() to display numbered lists.
> Each of these examples highlights a practical use of print() combined with functions, loops, and string formatting.

Here’s a chart that explains the flow of Example 1:

<svg aria-roledescription="flowchart-v2" role="graphics-document document" viewBox="0 0 178.421875 326" style="max-width: 25%;" class="flowchart" xmlns="http://www.w3.org/2000/svg" width="100%" id="graph-div" height="100%" xmlns:xlink="http://www.w3.org/1999/xlink"><style>#graph-div{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;fill:#ccc;}#graph-div .error-icon{fill:#a44141;}#graph-div .error-text{fill:#ddd;stroke:#ddd;}#graph-div .edge-thickness-normal{stroke-width:1px;}#graph-div .edge-thickness-thick{stroke-width:3.5px;}#graph-div .edge-pattern-solid{stroke-dasharray:0;}#graph-div .edge-thickness-invisible{stroke-width:0;fill:none;}#graph-div .edge-pattern-dashed{stroke-dasharray:3;}#graph-div .edge-pattern-dotted{stroke-dasharray:2;}#graph-div .marker{fill:lightgrey;stroke:lightgrey;}#graph-div .marker.cross{stroke:lightgrey;}#graph-div svg{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;}#graph-div p{margin:0;}#graph-div .label{font-family:"trebuchet ms",verdana,arial,sans-serif;color:#ccc;}#graph-div .cluster-label text{fill:#F9FFFE;}#graph-div .cluster-label span{color:#F9FFFE;}#graph-div .cluster-label span p{background-color:transparent;}#graph-div .label text,#graph-div span{fill:#ccc;color:#ccc;}#graph-div .node rect,#graph-div .node circle,#graph-div .node ellipse,#graph-div .node polygon,#graph-div .node path{fill:#1f2020;stroke:#ccc;stroke-width:1px;}#graph-div .rough-node .label text,#graph-div .node .label text{text-anchor:middle;}#graph-div .node .katex path{fill:#000;stroke:#000;stroke-width:1px;}#graph-div .node .label{text-align:center;}#graph-div .node.clickable{cursor:pointer;}#graph-div .arrowheadPath{fill:lightgrey;}#graph-div .edgePath .path{stroke:lightgrey;stroke-width:2.0px;}#graph-div .flowchart-link{stroke:lightgrey;fill:none;}#graph-div .edgeLabel{background-color:hsl(0, 0%, 34.4117647059%);text-align:center;}#graph-div .edgeLabel p{background-color:hsl(0, 0%, 34.4117647059%);}#graph-div .edgeLabel rect{opacity:0.5;background-color:hsl(0, 0%, 34.4117647059%);fill:hsl(0, 0%, 34.4117647059%);}#graph-div .labelBkg{background-color:rgba(87.75, 87.75, 87.75, 0.5);}#graph-div .cluster rect{fill:hsl(180, 1.5873015873%, 28.3529411765%);stroke:rgba(255, 255, 255, 0.25);stroke-width:1px;}#graph-div .cluster text{fill:#F9FFFE;}#graph-div .cluster span{color:#F9FFFE;}#graph-div div.mermaidTooltip{position:absolute;text-align:center;max-width:200px;padding:2px;font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:12px;background:hsl(20, 1.5873015873%, 12.3529411765%);border:1px solid rgba(255, 255, 255, 0.25);border-radius:2px;pointer-events:none;z-index:100;}#graph-div .flowchartTitleText{text-anchor:middle;font-size:18px;fill:#ccc;}#graph-div :root{--mermaid-font-family:"trebuchet ms",verdana,arial,sans-serif;}</style><g><marker orient="auto" markerHeight="8" markerWidth="8" markerUnits="userSpaceOnUse" refY="5" refX="5" viewBox="0 0 10 10" class="marker flowchart-v2" id="graph-div_flowchart-v2-pointEnd"><path style="stroke-width: 1; stroke-dasharray: 1, 0;" class="arrowMarkerPath" d="M 0 0 L 10 5 L 0 10 z"></path></marker><marker orient="auto" markerHeight="8" markerWidth="8" markerUnits="userSpaceOnUse" refY="5" refX="4.5" viewBox="0 0 10 10" class="marker flowchart-v2" id="graph-div_flowchart-v2-pointStart"><path style="stroke-width: 1; stroke-dasharray: 1, 0;" class="arrowMarkerPath" d="M 0 5 L 10 10 L 10 0 z"></path></marker><marker orient="auto" markerHeight="11" markerWidth="11" markerUnits="userSpaceOnUse" refY="5" refX="11" viewBox="0 0 10 10" class="marker flowchart-v2" id="graph-div_flowchart-v2-circleEnd"><circle style="stroke-width: 1; stroke-dasharray: 1, 0;" class="arrowMarkerPath" r="5" cy="5" cx="5"></circle></marker><marker orient="auto" markerHeight="11" markerWidth="11" markerUnits="userSpaceOnUse" refY="5" refX="-1" viewBox="0 0 10 10" class="marker flowchart-v2" id="graph-div_flowchart-v2-circleStart"><circle style="stroke-width: 1; stroke-dasharray: 1, 0;" class="arrowMarkerPath" r="5" cy="5" cx="5"></circle></marker><marker orient="auto" markerHeight="11" markerWidth="11" markerUnits="userSpaceOnUse" refY="5.2" refX="12" viewBox="0 0 11 11" class="marker cross flowchart-v2" id="graph-div_flowchart-v2-crossEnd"><path style="stroke-width: 2; stroke-dasharray: 1, 0;" class="arrowMarkerPath" d="M 1,1 l 9,9 M 10,1 l -9,9"></path></marker><marker orient="auto" markerHeight="11" markerWidth="11" markerUnits="userSpaceOnUse" refY="5.2" refX="-1" viewBox="0 0 11 11" class="marker cross flowchart-v2" id="graph-div_flowchart-v2-crossStart"><path style="stroke-width: 2; stroke-dasharray: 1, 0;" class="arrowMarkerPath" d="M 1,1 l 9,9 M 10,1 l -9,9"></path></marker><g class="root"><g class="clusters"></g><g class="edgePaths"><path marker-end="url(#graph-div_flowchart-v2-pointEnd)" style="" class="edge-thickness-normal edge-pattern-solid edge-thickness-normal edge-pattern-solid flowchart-link" id="L_A_B_0" d="M89.211,62L89.211,68.167C89.211,74.333,89.211,86.667,89.211,95.917C89.211,105.167,89.211,111.333,89.211,116.833C89.211,122.333,89.211,127.167,89.211,129.583L89.211,132"></path><path marker-end="url(#graph-div_flowchart-v2-pointEnd)" style="" class="edge-thickness-normal edge-pattern-solid edge-thickness-normal edge-pattern-solid flowchart-link" id="L_B_C_1" d="M77.833,190L75.235,196.167C72.636,202.333,67.439,214.667,66.14,223.917C64.841,233.167,67.439,239.333,69.779,244.886C72.119,250.438,74.199,255.376,75.24,257.845L76.28,260.314"></path><path marker-end="url(#graph-div_flowchart-v2-pointEnd)" style="" class="edge-thickness-normal edge-pattern-solid edge-thickness-normal edge-pattern-solid flowchart-link" id="L_B_C_2" d="M100.588,190L103.187,196.167C105.785,202.333,110.983,214.667,112.282,223.917C113.581,233.167,110.983,239.333,108.643,244.886C106.303,250.438,104.222,255.376,103.182,257.845L102.142,260.314"></path></g><g class="edgeLabels"><g transform="translate(89.2109375, 99)" class="edgeLabel"><g transform="translate(-28.8984375, -12)" class="label"><foreignObject height="24" width="57.796875"><div style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;" class="labelBkg" xmlns="http://www.w3.org/1999/xhtml"><span class="edgeLabel"><p>variable</p></span></div></foreignObject></g></g><g transform="translate(62.2421875, 227)" class="edgeLabel"><g transform="translate(-19.21875, -12)" class="label"><foreignObject height="24" width="38.4375"><div style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;" class="labelBkg" xmlns="http://www.w3.org/1999/xhtml"><span class="edgeLabel"><p>value</p></span></div></foreignObject></g></g><g transform="translate(116.1796875, 227)" class="edgeLabel"><g transform="translate(-14.71875, -12)" class="label"><foreignObject height="24" width="29.4375"><div style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;" class="labelBkg" xmlns="http://www.w3.org/1999/xhtml"><span class="edgeLabel"><p>text</p></span></div></foreignObject></g></g></g><g class="nodes"><g transform="translate(89.2109375, 35)" id="flowchart-A-12" class="node default"><rect height="54" width="162.421875" y="-27" x="-81.2109375" data-et="node" data-id="abc" style="" class="basic label-container"></rect><g transform="translate(-51.2109375, -12)" style="" class="label"><rect></rect><foreignObject height="24" width="102.421875"><div style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel"><p>welcome_user</p></span></div></foreignObject></g></g><g transform="translate(89.2109375, 163)" id="flowchart-B-13" class="node default"><rect height="54" width="69.15625" y="-27" x="-34.578125" ry="5" data-et="node" data-id="abc" rx="5" style="" class="basic label-container"></rect><g transform="translate(-19.578125, -12)" style="" class="label"><rect></rect><foreignObject height="24" width="39.15625"><div style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel"><p>name</p></span></div></foreignObject></g></g><g transform="translate(89.2109375, 291)" id="flowchart-C-15" class="node default"><rect height="54" width="109.875" y="-27" x="-54.9375" data-et="node" data-id="abc" style="" class="basic label-container"></rect><g transform="translate(-24.9375, -12)" style="" class="label"><rect></rect><foreignObject height="24" width="49.875"><div style="display: table-cell; white-space: nowrap; line-height: 1.5; max-width: 200px; text-align: center;" xmlns="http://www.w3.org/1999/xhtml"><span class="nodeLabel"><p>Output</p></span></div></foreignObject></g></g></g></g></g></svg>

This chart shows the following steps:

1. *Start*: The function welcome_user("Alice") is called.
2. *Is function called?*: The function takes name = "Alice" as input.
3. *Print step*: The print statement is executed to display "Welcome, Alice!".
4. *End*: The function completes.

You can use this code in a Mermaid rendering tool to visualize the flow.

---

| Go back | Next.. |
|---------|--------|
| [Table of Contents](../index.md) | [Chapter 2](chapters/chapter2.md) |