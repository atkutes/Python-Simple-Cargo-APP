# Python-Simple-Cargo-APP

I was using Python Tkinter. Tkinter is the standard GUI library for Python. Python when combined with Tkinter provides a fast and easy way to create GUI applications.

1. First of all, you have to create excel file in the same directory as your python file.

2. Import the customtkinter module, openpyxl module, and some specific classes from the tkinter module. 
However, the customtkinter module is not a standard module in Python's standard library. Make sure you have installed the required modules (openpyxl, tkinter) in your Python environment before running the script.

3. Creating a graphical user interface (GUI) using a custom customtkinter module and the openpyxl module for working with Excel files. It defines a window titled "Cargo Entry" with specific dimensions and a background color.
The code then creates various GUI elements such as labels, entry fields, a combo box, radio buttons, and buttons. These elements are placed within a frame that is positioned inside the main window.
The clear function is defined to clear the values of the entry fields and reset the values of the combo box and radio buttons.
The submit function is defined to handle the submission of data. It checks if the required fields have been filled in, opens an Excel file named "data.xlsx" using openpyxl, retrieves the values from the GUI elements, and saves the data in the Excel file. If any required field is missing, an error message is displayed.
Finally, the main event loop app.mainloop() is started to run the GUI application.

Please note that the functionality of the code depends on the customtkinter module, which is not a standard module. Make sure you have the necessary dependencies and the customtkinter module installed correctly for the code to work as expected.
