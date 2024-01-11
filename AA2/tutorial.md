Limit the Recurring Emails
======================
In this activity, you will limit the recurring emails to five emails.


<img src= "https://s3.amazonaws.com/media-p.slid.es/uploads/1525749/images/10925828/C120_SA3.gif" width = "50%" height = "auto">


Follow the given steps to complete this activity.


1. Limit the Recurring Emails
* Open the file `main.py`.
* Replace count with self.count and comment `count = 0 and set its value.
```
self.count = 0
```
* Change the email subject line to "Reminder Email!" after sending three recurring emails.
if (self.count > 3):
    subject = "Reminder Email!!"
```
* Break the loop after sending 5 recurring emails along with a reminder.
```
while True:
    if (self.count < 5):
        self.count += 1
        self.send_single_email()
        time.sleep(send_after_seconds)
    else:
        break
```


* Save and run the code to check the output.
