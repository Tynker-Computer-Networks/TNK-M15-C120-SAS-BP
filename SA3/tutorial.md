Add Timer for Recurring Emails
======================
In this activity, you will add a timer to send emails after specific intervals.

<img src= "https://s3.amazonaws.com/media-p.slid.es/uploads/1525749/images/10940642/C120_SA3_new.gif" width = "50%" height = "auto">




Follow the given steps to complete this activity.




1. Add a timer
* Open the file `main.py`.
* Import the time library which calculates the number of seconds since the "epoch".
```
import time
```


* Label the Time Interval Text to notify the user on entering the seconds to send at an interval and position it.
```
Label(self.frame, text="Send After (days):").grid(column=0, row=5, sticky="w")
```
* Fetch the interval for the recurring email using Entry() widget.
```
self.send_after_entry = Entry(self.frame)
```
* Position the interval input for the recurring email using the .grid() method.
```
self.send_after_entry.grid(column=1, row=5, padx=10, pady=5, columnspan=2)
```


* Save and run the code to check the output.
