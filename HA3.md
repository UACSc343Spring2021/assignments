## Homework Assignment 3 - Due Tuesday February 23

Version History: 

- 2021/02/16: Released

In this assignment, we are exercising:

- Improving an interface to adhere to design principles
- Writing design rationales
- Getting more practice GUI programming in HTML/CSS/Javascript
- Getting more practice with the MVC design pattern

For this assignment, we iterate on the UI from HA2 using suggestions from
class in accordance with design principles. You may start from your HA2
submission or you may start from a sample solution available under the
resources tab of Piazza.

The HTML, Javascript, and CSS should be in separate files. No style
information should be in the HTML tags outside of a `style` attribute. Do not
use HTML tags like `<center>`, `<b>`, or `<i>` to alter visual appearance.
Avoid the use of CSS `position: fixed;` because it may cause elements to
overlap and be unreadable on the grader's setup.

This assignment is not meant to require external Javascript libraries.
However, if you use external Javascript libraries, it should be included in
the repository. Do not use a library that already implements a
dayplanner/calenndar.  That is not the goal of this assignment. Do not forget
to cite any borrowed code in your `HA3.js` document near where the borrowed
code is used (other than the files from Piazza). The grader should not be
expected to install anything. 

Use the following link to create your github repository for this assignment:
[https://classroom.github.com/a/69kev4fD](https://classroom.github.com/a/69kev4fD)
Your submission git repository should contain one HTML file named `HA3.html`
as well as a CSS file `HA3.css`, a JS file `HA3.js`, any additional files
needed for your design (e.g., images, libraries) and a plain text file
`README.txt`.

The title of the webpage should be "Last Name, First Name - HA3" where your
last name and first name are used.

The `README.txt` file should contain the rationale for your design decisions
as well as any elaboration on specific design principles as noted below.

This file also includes a rough breakdown of points, though points may also be
missed for not following instructions (e.g., adherence to HTML/CSS divide,
missing name, files not at root level of directory, etc.)

**Please note: I may share screen shots or movies of your HA3 and explain how
you chose to design the solution with the class. The focus would be on
positive elements of the design, not on functionality. Please let me know if
you are uncomfortable with your assignment being shown or if you wish for it
to be anonymized (shown without attribution to your name).**

### MVC (20 pts)

Like HA2, your javascript should demonstrate the Model-View-Controller pattern
as we went over in lecture. (If you are using external libraries, they must
work in concert with this pattern.)

The application and state data should be kept by the Model which notifies any
Views upon change.

Any changes to the DOM should be managed by the Views. 

The Controller should act as the mediator, making changes to the model as
notified by the Views. The Controller does not modify any Views.


### Functionality & Design (45 pts)

The functionality from the previous homework assignment should be preserved:
Users should be able to add individual appointments to their day which have a
title, hour, and one of the following priority categories: High, Normal, or
Tentative. Users should be able to see details of the appointment summarized
and clear all items.

If you prefer to do so AND justify it in your design rationale, you can replae
an appointment's "hour" with a more specific time or the word "appointment"
with something else.

Additional functionality may be added to adhere to design principles. Again,
this mustt be justified in your design rationale.


#### Required Improvements from Class 

1. The Set Prioriy UI should be improved.

2. Needs error recovery/handling.

3. Needs reversal of actions (i.e., undo). Hint for programming an Undo feature: Consider
using a stack.

4. Allow users to correct or remove entries with mistakes.

5. Needs help/documentation. 

You are free to choose how you will implement these changes. (Design is a
collection of choices!) **However, they must be explained and justified in the
design rationale.**

Additionally, you may make any other changes to the interface design as long
as functionality is preserved. Your design, whether you make changes or not,
should be justied in the design rationale.

*These were sourced as the most important items during Lecture 9's breakout
activities. (See the Google Doc linked in Lecture 9.)*


### Design Rationale (30 pts)

Design and implement a new interface for this input. In your `README.txt`,
include a *design rationale* where you explain why you chose the design you
did. Your rationale should appeal to the design principles you're fulfilling
and explain any reasons/trade-offs for the design principles you are
violating. A good rationale will also discuss alternative designs and explain
why you chose your design over the alternatives. You may also consider other
forms of evidence, such as prior work or design patterns. Lecture 9 has slides
on design rationale, including example snippets of design rationales from
previous years.

Your new design may use elements of the old design, but they should be
justified.

Each element of the design rationale is graded on thoroughness, with maximum
points for a rationale that explains both functionality and presentation nand
uses multiple forms of evidence (e.g., beyond design principles only).
