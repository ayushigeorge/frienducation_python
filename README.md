# Frienducation Python Automation Engineer : Python Automation Mailing System

# Automated Mailing System
The Python Automation System is a tool designed to automate the process of sending emails to multiple recipients using the secure SMTP protocol. The system allows the user to specify the sender email, recipient emails, subject, message content, and an unsubscribe link, providing a flexible and customizable email automation solution.

With the Python Automation System, users can easily send emails to large numbers of recipients, saving time and effort. The system's user-friendly interface and simple configuration make it accessible to users of all skill levels, allowing anyone to automate their email communication process.

This project is open source and free to use under the MIT License, making it a valuable resource for anyone looking to improve their email automation process
This is a Python script for sending automated emails to multiple recipients using the secure SMTP protocol. It allows you to specify the sender email, recipient emails, subject, message content, and an unsubscribe link.

## Prerequisites

- Python 3.x
- Required Python modules:
  - smtplib
  - ssl
  - email
  - getpass

## How to Use

1. Clone the repository or download the script to your local machine.
2. Install the required Python modules by running the following command in your terminal:

```
pip install smtplib ssl email getpass
```

3. Open the `send_mail.py` file and edit the following variables:

   - `sender_email`: The email address of the sender.
   - `password`: The password for the sender email address. If you want to avoid hardcoding the password in the script, you can use the `getpass` module to prompt the user for the password at runtime.
   - `receiver_emails`: A list of email addresses of the recipients.
   - `subject`: The subject of the email.
   - `message`: The content of the email.
   - `unsubscribe_link`: The link to unsubscribe from the email list. You can use this to comply with anti-spam laws.

4. Save the `mail.py` file.
5. Run the `mail.py` script by running the following command in your terminal:

```
python mail.py
```

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.

## Author

- [Ayushi George](https://github.com/ayushigeorge)
