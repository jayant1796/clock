Digital Clock using Tkinter<br>
This is a simple digital clock application built using Python's Tkinter library. The clock updates every second and displays the current time in HH:MM
AM/PM format. The interface is designed with a digital font and features a black background with cyan text.

Features
Displays time in 12-hour format (AM/PM).
Updates every second automatically.
Simple and clean UI with digital-style font.
Prerequisites
Before running the application, ensure you have Python installed on your system.

To install Tkinter (if not already installed), you can use:

     bash
     pip install tk
How to Run
Clone the repository or download the source code.
Navigate to the directory containing the script.
Run the script using Python:

      bash
      python clock.py
Code Overview
Tkinter: Used for creating the GUI.
strftime: Used to fetch the current system time.
The time is updated every second using label.after(1000, time).



Customization
You can change the font, size, and color of the clock by modifying the Label widget.
The clock format can be adjusted by changing the format string in the strftime function.
         
          string = strftime('%H:%M:%S %p')  # Modify this to change the format
