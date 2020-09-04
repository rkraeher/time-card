# time-card
A time-card for calculating your time spent working and breaks. 

#Psuedo-Code

I need a row for each day of the week
Each row has a button for starting work, taking a break and ending the work for the day.
The times are displayed to the user. 
I need a counter for elapsed time between pressing start and pressing break. 
The work time is saved in a variable associated with that day.
After the user clicks the end of the day's work button, the total time is calculated. 
This total calculated time is displayed to the user for the day's total work time. 

I need an alert that triggers if more than 1.5 hours have passed without pressing break button.

At the end of the week the app calculates all the daily totals into a weekly total
The weekly total is associated with user-input specifying weekly and daily goals.
Depending on meeting these goals the app displays encouraging messages/quotes to the user. 

The app resets for the next work-week and asks for weekly goals in case the user's weekly goals are different. 



QUESTION: Can I stringify the moment.js times in order to use those times as numbers to calculate the elapsed time?

#Advanced Functionality
The app allows the user to have multiple time clocks for different categories of work (e.g, I could have a time
clock for coding, diss, and teaching).
    This would involve some level of storage that might go beyond local storage. 
