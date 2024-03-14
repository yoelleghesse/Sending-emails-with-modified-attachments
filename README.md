The Automated Bill Reminder is a Python script that sends personalized bill reminder emails to recipients listed in a CSV file. It utilizes the yagmail library for sending emails, the pandas library for reading data from a CSV file, and generates bill files for each recipient.

Clone the repo:

``git clone https://github.com/your-username/automated-bill-reminder.git``

Install the dependencies:

``pip install yagmail pandas``

Set up the environment variables:

- Ensure you have set up your Gmail address as the sender (sender).
- Use a Gmail app password as the password for the yagmail SMTP connection.

Prepare the contacts CSV file:

- Create a CSV file named contacts.csv with columns for name, email, and amount.
- Populate the CSV file with the names, email addresses, and amounts owed by recipients.

Run the script:

```python automated_bill_reminder.py```
