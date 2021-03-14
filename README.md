# Keylogger-in-Python

A simple keylogger code written in python, with a bit of file handling, learnt via youtube tutorials.

I used a library file called pynput which is to detect or control input devices. Key and Listener were 2 of its sub-libraries, from the keyboard device. 

Count is used to make sure our data is logged in from time-to-time (which you could change basd on your preference) as a precaution incase the user accidently terminates the code in a different manner other than pressed the 'esc' key.

Create a text file to save the log as 'log.txt' or any other name you prefer. 

You can change the mode to 'w' (write) instead of 'a' (append) initially to automatically create the file but you would have to change it back to 'a' afterwards.


