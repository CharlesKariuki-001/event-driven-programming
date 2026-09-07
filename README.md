\# Event Driven Programming — Week 01



\## EDP Foundations



This repository contains my Week 1 learning and practical work for \*\*Event Driven Programming (BIT3102 / DIT2102)\*\* at Mount Kenya University.



The goal of this week was to understand how event driven programs wait for actions from the user or system and respond to those events.



\## What I Learned



During Week 1, I studied:



\* Event Driven Programming

\* Procedural vs Event Driven Programming

\* Events

\* Event handlers

\* Event listeners

\* Controls

\* Objects

\* Properties

\* Methods

\* The event loop

\* GUI programming

\* Visual Basic .NET

\* Windows Forms

\* The Visual Studio IDE



\## The Main Idea



An event driven application does not simply execute everything from top to bottom.



Instead, it waits for something to happen.



For example:



```text

Application starts

&nbsp;       ↓

Form appears

&nbsp;       ↓

Program waits

&nbsp;       ↓

User clicks Button

&nbsp;       ↓

Click event occurs

&nbsp;       ↓

Event handler runs

&nbsp;       ↓

Label text changes

&nbsp;       ↓

Program waits again

```



This event loop is one of the most important ideas I learned this week.



\## Weekly Build



\### First Event App



For my first practical build, I created a small Windows Forms application containing:



\* A Button named `btnGreet`

\* A Label named `lblMessage`



When the user clicks the button, the application displays:



```text

Welcome to MKU

```



\## Event Flow



```text

btnGreet

&nbsp;  ↓

Click event

&nbsp;  ↓

btnGreet\_Click event handler

&nbsp;  ↓

lblMessage.Text changes

&nbsp;  ↓

"Welcome to MKU"

```



\## Technologies



\* Visual Basic .NET

\* Windows Forms

\* Microsoft Visual Studio

\* Git

\* GitHub



\## Project Structure



```text

W1/

│

├── README.md

├── .gitignore

│

├── build/

│   ├── README.md

│   └── FirstEventApp/

│

├── screenshots/

│   ├── first-event-app.png

│   └── first-event-app-result.png

│

├── notes/

│   └── concepts.md

│

└── practice/

&nbsp;   └── answers.md

```



\## Evidence



Screenshots of the completed application will be placed in the `screenshots/` directory.



\## Week 1 Outcome



By the end of Week 1, I should be able to:



\* Explain Event Driven Programming

\* Explain procedural vs event driven programming

\* Define an event

\* Explain an event handler

\* Explain an event listener

\* Identify common Windows Forms controls

\* Explain properties and methods

\* Explain the event loop

\* Create a basic Windows Forms application

\* Connect a button click to an action



\## Reflection



The most important concept from Week 1 is that the program can wait for an event and then respond to it.



The small First Event App demonstrates this idea in practice rather than only in theory.



---



\*\*Learn → Practice → Build → Test → Document\*\*



