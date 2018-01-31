**Questions to discuss during the lecture:**

<panel header=":lock: Review code for quality">
<question has-input="true">

Suggest ways to improve the quality of the code below. 

```java
...
private static final String MESSAGE_COMMAND_HELP_PARAMETERS = "Parameters: %1$s";
private static final String MESSAGE_COMMAND_HELP_EXAMPLE = "Example: %1$s";
private static final String MESSAGE_DISPLAY_PERSON_DATA = "%1$s  Phone Number: %2$s  Email: %3$s";
private static final String GOODBYE_MESSAGE = "Exiting Address Book... Good bye!";
private static final String MESSAGE_INVALID_COMMAND_FORMAT = "Invalid command format: %1$s";
...
/** List of all persons in the address book. */
private static final ArrayList<String> person = new ArrayList<>();
...
public static void main(String[] args) {
    showWelcomeMessage();
    processProgramArgs(args);
    loadDataFromStorage();
    while (true) {
        System.out.print("Enter command: ");
        String userCommand = SCANNER.nextLine();
        userCommand = userCommand.trim();
        showToUser(userCommand);
        String feedback = executeCommand(userCommand);
        showResultToUser(feedback);
    }
}
...
/**
 * Show a message to the user
 */
private static void showToUser(String message) {
  System.out.println(LINE_PREFIX + m);
}
```

<div slot="hint">

Some relevant points:

* Similar things should be named similarly (consistency helps readability)
* Use singular names for variables that handle single values
* SLAP: The code of a method should be written as high-level as possible, and at the same level of abstraction
* The first sentence of a method header comment should follow a certain phrasing (refer to coding standard)
* Constant names don't follow camelCase (refer coding standard) 
* Indentation should be consistent

</div>

</question>
</panel>

<panel header=":lock: Classes for CityConnect app">
<question has-input="true">

Assume you are writing a CLI program called **`CityConnect`** for storing and querying distances between cities. The behavior is as follows:

```
Welcome to CityConnect!

Enter command: addroute Clementi BuonaVista 12
Route from Clementi to BuonaVista with distance 12km added

Enter command: getdistance Clementi BuonaVista
Distance from Clementi to BuonaVista is 12

Enter command: getdistance Clementi JurongWest
No route exists from Clementi to JurongWest!

Enter command: addroute Clementi JurongWest 24
Route from Clementi to JurongWest with distance 24km added

Enter command: getdistance Clementi JurongWest
Distance from Clementi to JurongWest is 24

Enter command: exit

```
What classes would you have in your code if you write your program based on the OOP paradigm?

<div slot="hint">

One class you can have is `Route`

</div>

</question>

</panel>

**E-learning**: [[OOP - Basics](http://www.comp.nus.edu.sg/~cs2103/AY1718S2/elearn/E3P1.%20OOP%20-%20Basics.mp4)] [[OOP - Basic UML](http://www.comp.nus.edu.sg/~cs2103/AY1718S2/elearn/E3P2.%20OOP%20-%20Basic%20UML.mp4)]

[[slides](http://www.comp.nus.edu.sg/~cs2103/AY1718S2/slides/L3.pptx)]
