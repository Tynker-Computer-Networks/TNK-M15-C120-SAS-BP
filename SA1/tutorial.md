Attach the Files
======================
In this activity, you will attach the files to an email.

<img src= "https://s3.amazonaws.com/media-p.slid.es/uploads/1525749/images/10925519/C120_SA1.gif" width = "50%" height = "auto">




Follow the given steps to complete this activity.




1. Attach the files
* Open the file `main.py`.
* Import the filedialog module to save the file path and create a list of files to be stored.
```
from tkinter import filedialog
self.attached_files = []
```


* Save the file path using filedialog.askopenfilename() and append the file path if it exists.
```
def attach_file(self):
    file_path = filedialog.askopenfilename()
    if file_path:
        self.attached_files.append(file_path)
```
* Extract the filename from the file path, store it, and configure the label.
```
def attach_file(self):
    attached_files_text = "\n".join([file.split("/")[-1] for file in self.attached_files])
    self.attached_files_label.
config(text=f"Attached Files:\n{attached_files_text}")
```
* Update and display the file label by calling the .update_attached_files_label() function.
```
self.update_attached_files_label()
```
* Attach the file by calling the .attach_file() function when the "Attach File Button" is clicked.
```
self.attach_button = Button(self.frame, text="Attach File", command=self.attach_file)
```
* Save and run the code to check the output.
