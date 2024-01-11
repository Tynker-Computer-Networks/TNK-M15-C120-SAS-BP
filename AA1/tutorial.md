Schedule the Recurring Emails
======================
In this activity, you Schedule the recurring emails three times.

<img src= "https://s3.amazonaws.com/media-p.slid.es/uploads/1525749/images/10925828/C120_SA3.gif" width = "50%" height = "auto">




Follow the given steps to complete this activity.




1. Schedule the Recurring Emails


* Open the file `main.py`.
* Declare a variable count and set it to 0 to track recurring count.
```
count = 0
```
* Send email until the count exceeds 3.
```
while True:
    if(count < 3):
        count+=1
        self.send_single_email()
```


* Break the loop once count is greater than 3.
```
else:
    break
```


* Save and run the code to check the output.
