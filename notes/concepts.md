\# Week 1 Concepts — Event Driven Programming



\## 1. Event Driven Programming



Event Driven Programming is a programming approach where the flow of a program is determined by events.



An event can be something such as:



\* A mouse click

\* A key press

\* A form loading

\* A timer reaching zero



The program waits for an event and responds when the event occurs.



\## 2. Procedural Programming



Procedural programming normally follows a predetermined sequence.



```text

Step 1

&nbsp; ↓

Step 2

&nbsp; ↓

Step 3

&nbsp; ↓

Step 4

```



The programmer determines the order.



\## 3. Event Driven Programming



Event driven programming allows events to determine what happens next.



```text

Program starts

&nbsp;     ↓

Program waits

&nbsp;     ↓

Event occurs

&nbsp;     ↓

Event handler responds

&nbsp;     ↓

Program waits again

```



\## 4. Event



An event is an action or occurrence detected by a program.



Examples:



\* Click

\* KeyPress

\* Load

\* Timer event



\## 5. Event Handler



An event handler is the block of code that runs when a particular event occurs.



Example:



```vb

Private Sub btnGreet\_Click(sender As Object, e As EventArgs) Handles btnGreet.Click



&nbsp;   lblMessage.Text = "Welcome to MKU"



End Sub

```



\## 6. Event Listener



An event listener is the mechanism that monitors an object and waits for an event.



\## 7. Control



A control is a visual component placed on a Windows Form.



Examples:



\* Button

\* Label

\* TextBox

\* ListBox

\* ComboBox



\## 8. Property



A property describes an object or controls how it appears or behaves.



Examples:



```text

Text

Name

Width

BackColor

```



Example:



```vb

lblMessage.Text = "Welcome to MKU"

```



Here, `Text` is a property.



\## 9. Method



A method is an action that an object can perform.



Examples:



```vb

Close()

Show()

Focus()

```



\## 10. Event Loop



The event loop is the cycle through which a GUI application waits for events.



```text

Start application

&nbsp;      ↓

Display form

&nbsp;      ↓

Wait

&nbsp;      ↓

Event occurs

&nbsp;      ↓

Check for handler

&nbsp;      ↓

Handler executes

&nbsp;      ↓

Return to waiting

&nbsp;      ↓

Continue until shutdown

```



\## 11. VB.NET



Visual Basic .NET is the programming language used for this practical work.



The Week 1 practical work uses Windows Forms inside Visual Studio.



\## 12. Handles



The `Handles` keyword connects an event procedure to a specific control and event.



Example:



```vb

Handles btnGreet.Click

```



This means the procedure responds to the Click event of `btnGreet`.



\## 13. Important Difference



\### Property



Describes an object.



Example:



```vb

Button1.Text

```



\### Method



Represents an action performed by an object.



Example:



```vb

Form1.Close()

```



\## 14. Big Picture



```text

Object / Control

&nbsp;      ↓

&nbsp;    Event

&nbsp;      ↓

&nbsp;Event Handler

&nbsp;      ↓

&nbsp;   Action

&nbsp;      ↓

Program waits again

```



This is the main idea I need to understand from Week 1.



