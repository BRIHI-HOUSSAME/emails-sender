# Email Sender Tool

This project is a TypeScript-based tool for sending emails to multiple recipients using Node.js and Nodemailer. It reads recipient emails from a JSON file and sends a pre-configured email message to each one.



## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/BRIHI-HOUSSAME/emails-sender.git
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure the Email List in `emails.json`

Ensure you have a list of recipient emails.
Replace `"example1@example.com"` and `"example2@example.com"` with the actual email addresses you want to send to.

### 4. Configure Credentials and Email Content

In `SendEmails.ts`, replace `your-email@gmail.com` and `your-email-password` with your actual Gmail credentials, and customize the email subject and body .

Note: If using Gmail, enable App Passwords for enhanced security.


### 5. Run the Script

Execute the main script to send emails to all recipients listed in `emails.json`:

```bash
npx ts-node SendEmails.ts
```
This command directly executes the TypeScript file without needing to compile separately.





