## Table of Contents
- [flutter notes](#flutter-notes)
  - [what is flutter](#what-is-flutter)
  - [key terms and deinitions](#key-terms-and-definitions)
-[defintions with structures](#flutter-defintions)
 [Code Definitions](#code_definitions)
-[notebook style guide](#markdown-style-guide-coding-notebooks).
 
## Flutter Notes 

###  What is Flutter?
- Definition:a framwork made by google for buildings apps that work on web,andriod,and ios-with one codebase
- Why is it useful?
---

###  Key Terms and Definitions

| Term             | Definition                                      | Example / Notes                          |
|------------------|--------------------------------------------------|-------------------------------------------|
| Widget           |    basic building block a flutter app evrything is a widget    text,inmage.container,colum                                              |                                           |
| MaterialApp      |    the root of the app sets up rutes and themes.        found in main dart                                              |                                           |
| Scaffold         |    provides basic visuyal layout- like a header,body floating button   each screen uses it                                            |                                           |
| StatelessWidget  |   predefinded paths to navigate between screens   |                                           |
| StatefulWidget   |   a UI component in frameworks like Flutter that can change its internal data                                               |                                           |
| Navigator        |    a person, instrument, or software that directs the course or finds a path                                              |                                           |
| AppBar           |   a persistent UI element found at the top or bottom of an application                                               |                                           |
| Column           |    a coulum seprating diffrent things                                               |                                           |
| Row              |   horizontal layout                                               |                                           |
| Container        |    storing data                                               |                                           |
| Text             |    displays text                                              |                                           |
| Image.network    |                                                  |                                           |
| Padding|||
| center|||
---

### 🎨 Layout and Design Widgets
- How do you center a widget?
- How do you align something to the left or right?
- What widget adds space around content?

           
        







##code defintion 

| Term | Definition | Base Structure / Syntax | Real Life Example | App Example |
|------|------------|--------------------------|-------------------|-------------|
| variable    | A named container used to store a value that may change. | `var x = 5;` |  |  |
| constant    | A fixed value that cannot change once set. | `const PI = 3.14;` |  |  |
| data type   | The kind of value a variable holds, like numbers or text. | `int`, `String`, `bool` |a sentence vs and age  |  |
| string      | A sequence of characters used to represent words or text. | `"Hello World"` |the objective of video game    |  |
| integer     | Whole number values. | `int age = 16;` |counting |  |
| double      | Number values with decimals. | `double age = 16.2;` |coutning and adding numbers   |  |
| boolean     | A value that can be true or false. | `bool isLoggedIn = false;` |reading  real news an nreading fake news  |  |
| list        | A collection of values in a specific order. | `List<String> names = [];` |listing different things to do  |  |
| null        | A special value that means “nothing.” | `String? name = null;` |when you need to know a value but there isnt a value yet |  |
| function    | A reusable block of code that performs an action. | `void sayHi() { print("Hi"); }` |gettting game over after ur character keeps dying  |  |
| parameter   | The information passed into a function to change how it works. | `greet(String name)` |someone giving an opnion and inputting a opinion  |  |
| return      | The result a function gives back. | `return total;` |giving money and getting in return a item  |  |
| scope       | Where a variable or function can be used. | (No set syntax — concept-based) |u can only have that checkspot in that area  |  |
| class       | Blueprint for creating objects with specific structure and behavior. | `class Dog {}` | something that has a spefic matter   |  |
| object      | A specific version of a class. | `Dog myDog = Dog();` | a tangible thing that can be seen or touched, something a thought or action is directed toward  |  |
| property    | A variable that belongs to a class/object. | `String name;`  anything that can be owned|  |  |
| method      | A function that belongs to a class. | `void bark() {}` | a manner in which a thing is done or in which it happens |  |
| constructor | A special function used to set up a class when it’s created. | `Dog(this.name);` |a person or entity responsible for building or creating  |  |
| abstraction | Hiding the inner workings of code so users only interact with what they need. | (Concept — not specific code) |keyboard hiding the codes under the letters  |  |
| override    | Changing how a built-in or inherited function behaves. | `@override` |  to use superior authority or power to disregard |  |
| void        | A function that does not return a value. | `void printMessage() {}` |an empty or vacant space  |  |




## Flutter Definitions with structures

| Term | Definition and Description | Base Structure | Real Life Example | App Example |
|------|----------------------------|----------------|-------------------|-------------|
| main  | A function that runs when your app starts. It tells Flutter what app to show. | `void main() => runApp(MyApp());` | agry brids  |  |
| MaterialApp| The widget that sets up your whole app’s look and navigation. | `MaterialApp(...)` |my space  |  |
| scaffold     | A widget that gives you the basic layout: background, navigation bar, floating button, etc. | `Scaffold(...)` |a template  |  |
| colum     | A widget that holds and displays your content in a straight line from top to bottom. | `Column(...)` |tables  |  |
|  row    | A widget that shows things side-by-side. | `Row(...)` |the tables  |side by side  |
| container     | A box that holds other widgets. You can add color, padding, borders, or size. | `Container(...)` |storage  |  |
|  text    | A widget to display text on the screen. | `Text('Hello')` |texting bubbles  |  |
| image network     | A widget to show an image using a link from the internet. | `Image.network('https://...')` |images  |  |
| onpressd     | A clickable button that floats above content. You choose what happens when it's clicked. | `ElevatedButton(onPressed: ..., child: ...)` |trigger  |  |
| stateless widget  | The code that gets run when a button is tapped or something happens. | `onPressed: () => doSomething()` |the homepage  |  |
|  statefull wigdet    | A class that creates widgets that never change. Good for static screens. | `class HomeScreen extends StatelessWidget` |summited work conffiti falling down  |  |
| navigator     | A class for widgets that can change while the app is running. | `class MyWidget extends StatefulWidget` |lets go to diffrent pages  |  |
| padding     | Lets you move from one screen to another using route names. | `Navigator.pushNamed(context, '/about')` |make space around where ur sitting  |  |
| center     | Makes space around a widget inside its container. | `Padding(padding: EdgeInsets.all(8.0), child: ...)` |the center   |  |
|  wrap    | Aligns content in the center of the screen or container. | `Center(child: ...)` |when typing in docs and it wraps the text  |  |
|   override   | Automatically puts widgets onto a new line when there's no space. | `Wrap(children: [...])` |  |  |
| widget     | This marks a method as one that’s replacing a method in a parent class. | `@override` |  |  |
|  build    | The special function in every widget that describes what gets drawn on the screen. | `Widget build(BuildContext context) {...}` |  |  |
| buildcontext context     | Required in every widget class to describe what to show. | `build` |  |  |
|   super.key   | A variable that helps the widget know where it is and lets it communicate with the app. | `BuildContext context` |emailing teacher  |  |
|  const    | A keyword used to pass a value to the parent widget. | `super.key` |title  |  |
|      | A keyword that means the value won't change and is set once. | `const` |  |  |






















[Notebook Style Guide](#markdown-style-guide-for-coding-notebooks)
## Markdown Style Guide for Coding Notebooks

Follow this guide to keep your coding notebook **clear, consistent, and professional**.  
This ensures your notes are easy for you (and others) to read later.

---

## 🔹 Headings
**When to use:** Organize your notebook into sections (like days, topics, or projects).  
- `#` for the notebook title (use once at the top).  
- `##` for each day or major topic.  
- `###` for subsections (like "Notes", "Practice", "Reflections").  

✅ Example:


# My Coding Notebook
## Day 1
### Notes
### Practice

🔡 Text Formatting
When to use: Highlight important ideas or add emphasis.

Use bold for key terms or definitions.

Use italic for emphasis or side comments.

Use inline code for keywords, functions, or commands.

 

✅ Example:

**Class** = a blueprint for objects  
*Remember:* always test your code  
Use `System.out.println()` to print

 

💻 Code Blocks
When to use: Anytime you write multiple lines of code.

Inline code for short snippets.

Fenced code blocks with language for full examples.

✅ Example:

```java
public class Hello {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```

🧾 Lists
When to use: Organize steps, notes, or key points.

Numbered lists for sequences or steps.

Bulleted lists for unordered ideas.

✅ Example:

1. Define the class
2. Write the main method
3. Test your program

Variables
- Loops
- Conditionals
 

✅ Checklists
When to use: Track progress on assignments or tasks.

✅ Example:

[x] Complete coding warm-up
- [ ] Finish project draft
- [ ] Reflect on learning

 

➡️ Blockquotes
When to use: Call out notes, reminders, or teacher comments.

✅ Example:

> 💡 Remember: Loops repeat code until a condition is false.

 

📊 Tables
When to use: Compare values, track progress, or organize data neatly.

✅ Example:

| Task        | Status   | Notes          |
|-------------|----------|----------------|
| Homework 1  | Done ✅  | Submitted      |
| Homework 2  | Pending  | Needs review   |

 

🔗 Links & Images
When to use: Add references, resources, or visuals.

✅ Example:

[Java Docs](https://docs.oracle.com/javase/8/docs/api/)  
![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

 

📂 Collapsible Sections
When to use: Hide solutions, extended notes, or extra details.

✅ Example:

<details>
  <summary>Click to reveal solution</summary>
  
System.out.println("Answer: 42");

</details>

 

📝 Footnotes
When to use: Add references or side notes without cluttering the page.

✅ Example:

This concept is related to object-oriented programming.[^1]

[^1]: See "Objects and Classes" in your textbook.

 

🎯 Style Rules
Consistency matters more than creativity

Always use headings to structure your notes.

Always use code blocks for multi-line code.

Clarity first

Bold key terms.

Use lists instead of long sentences when outlining steps.

Professional tone

Don’t mix casual notes with formal work in the same section.

Use blockquotes for reflections or teacher feedback.

Track your learning

Use checklists to mark what’s done.

Use collapsible sections if you want to hide answers until review time.

 

✅ Bottom Line:

Headings = Structure

Bold/Italic = Emphasis

Code blocks = Code

Lists = Steps/Ideas

Tables = Organization

Checklists = Progress

Blockquotes = Notes/Tips

Collapsible = Hide/Show detail

Keep it simple, consistent, and clear.
