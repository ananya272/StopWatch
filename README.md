# StopWatch

Creating a stopwatch using HTML, CSS, and JavaScript involves setting up the user interface in HTML, styling it with CSS, and using JavaScript to handle the stopwatch functionality.

HTML: We create a div with the class stopwatch that contains another div with the class display to show the time. The controls div contains two buttons for starting/stopping and resetting the stopwatch.

CSS:
The body is styled to center the stopwatch on the page.
The .container class styles the stopwatch container, giving it a clean look with padding, border, background color, and shadow.
The .time class styles the display area where the time is shown.
The button styles give the buttons a consistent look, with padding, font size, border-radius, background color, and a hover effect.

JavaScript:
We declare variables to keep track of the start time, updated time, time difference, and whether the stopwatch is running.
We get references to the buttons and time display elements.
The startStopBtn click event listener toggles the stopwatch between running and stopped states, starting or stopping the timer interval accordingly.
The resetBtn click event listener stops the timer and resets the time display to 00:00:00.
The updateTimer function calculates the elapsed time and updates the display every 10 milliseconds.
This code will create a functional stopwatch that can start, stop, and reset, displaying the elapsed time in minutes, seconds, and milliseconds.
