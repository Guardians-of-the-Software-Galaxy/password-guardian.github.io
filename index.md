
<img class="ui right floated image" src="public/images/guardians.png"> 

## Description

Password Guardian is a simple yet powerful python application that acts as an encrypted database for login credentials. Simply remember your **Password Guardian** login name and credential to gain access to your online credential manager. Reduce exposure to data collection used by google and other services manage your login credentials by storing them locally and encrypted on your machine! 

## Dependencies

Please run **pip install pytimedinput** to enable the time out feature. This feature times out the application in 30 seconds if no input is detected from within the user interface loop. This feature is aimed at preventing unwarranted use of the application in situations where the user may be distracted from use.

### Pyperclip

In addition, passwords are automatically copied to your clipboard so they can be easily passed into the proper field to minimize risk of the password being visible; this is done using the pyperclip library. In addition, the less sensitive login name can be viewed if desired.

### Fernet

All encryption is done using the fernet library. 

### GetPass

Linux style password output masking is done using the getpass library.

