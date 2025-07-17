# 🎉 Automatic Birthday Wisher through Email 🎂

Welcome to the Automatic Birthday Wisher through Email! This project sends personalized birthday wishes via email, ensuring that your friends and loved ones always feel special on their special day.

## ✨ Features
- **Automated Emails:** Sends personalized birthday greetings automatically.
- **Customizable Messages:** Modify the message content to suit your style.
- **Scheduling:** Set specific times for the emails to be sent.
- **Secure:** Uses environment variables to keep email credentials safe.

## 🚀 Getting Started

### Prerequisites
To run this project, you'll need the following:
- Python 3.7 or later
- An email account (Gmail, Outlook, etc.)
- A list of contacts with their birthdays and email addresses

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/automatic-birthday-wisher.git
   cd automatic-birthday-wisher
   ```

2. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up environment variables:**
   Create a `.env` file in the root directory with the following content:
   ```bash
   EMAIL_HOST=smtp.your-email-provider.com
   EMAIL_PORT=your-email-port
   EMAIL_ADDRESS=your-email@example.com
   EMAIL_PASSWORD=your-email-password
   ```

   > **Note:** Use a dedicated email account or an app-specific password for security.

### Configuration

1. **Prepare your contact list:**
   Create a `contacts.csv` file with the following format:
   ```csv
   name,email,year,month,day
   Test,test@email.com,1983,06,01
   [Fill this in!]
   ```

2. **Customize your message:**
   Edit the letter templates to personalize the email content.

### Running the Script

To run the birthday wisher, use the following command:

```bash
python main.py
```

This will send out emails to the contacts whose birthdays match the current date.

## 📬 Contact

For any questions, feel free to reach out:

- Email: shyamkolisetty@gmail.com, neethusrinedh@gmail.com
- GitHub: [@Shyam-18](https://github.com/Shyam-18)

---

Feel free to adjust the sections and content to better fit your project specifics. The key is to provide clear instructions and make the README user-friendly.
