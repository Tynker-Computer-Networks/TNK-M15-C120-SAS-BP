Add Recurring Email Label and Checkbox
======================
In this activity, you will add the checkbox and label for recurring email options.

<img src= "https://s3.amazonaws.com/media-p.slid.es/uploads/1525749/images/10925750/C120_SA2.gif" width = "50%" height = "auto">




Follow the given steps to complete this activity.




1. Add Recurring Mail Label and Checkbutton
* Open the file `main.py`.
* Initialize an .is_recurring variable and set its type to accept a boolean value "True" or "False" using a BooleanVar() method.
```
self.is_recurring = BooleanVar()
```


* Set the .is_recurring value to "False" using the .set() method to disable the recurring email option without selection.
```
self.is_recurring.set(False)
```
Add the label text "Recurring Email" using the label() method and position it using the .grid() method.
```
Label(self.frame, text="Recurring Email:").grid(column=0, row=6, sticky="w")
```
* Save and run the code to check the output.
