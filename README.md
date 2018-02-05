# Easy-Emailer
A Python module for sending emails with Gmail.

## Installation
```
pip install easyemailer
```
## Usage
```
easyemailer.send_gmail([gmailusername], [gmailpassword], [to], [subject], [from], [firebase database url OR None])
```

## A note on Firebase
If you want to write all emails sent with the command to a Firebase Realtime database, you will need to edit the rules:
![Screenshot](/images/firebase.png)
