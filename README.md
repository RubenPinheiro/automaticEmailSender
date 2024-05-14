# automaticEmailSender

an automatic Happy Birthday wisher email sender, hosted on pythonanywhere.com

this script runs through an Excel file containing birthdates, names and emails and compares if the date time of today matches any birthdates. If so, the body message for the email is randomly selected between 3 files, and the string [NAME] is replaced by the actual name.

For the script to run automatically every day, it was hosted on pythonanywhere.com. It was necessary to upload all present files, batch the main.py file and set a scheduler (run main.py once daily) in the Task tab.
