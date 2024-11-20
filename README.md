# Reminder App
![Screenshot 2024-11-20 164854](https://github.com/user-attachments/assets/8321b371-d47d-418c-aa9b-6db51f981615)


This is a simple Reminder App built using Tally, Forms, Pabbly, and Gmail. The app allows users to submit reminders via forms and automatically sends email notifications to remind them about the tasks at specified intervals.
## Project Doc
[view Reminder App](https://tally.so/r/3EBx2L)

## Overview

The app is designed to help users create, track, and get reminders about their important tasks or events. It uses various tools like Tally for form submissions, Pabbly for workflow automation, and Gmail for sending reminders to users.
### Key Features:
- Submit reminder details using a simple form (Tally).
- Automatically trigger reminder emails via Gmail at the specified times.
- Fully automated workflow through Pabbly integration.
- Easily customize reminder frequency and notification details.

## Setup Instructions

1. **Form Creation (Tally):**
   - Create a form to gather reminder details such as task name, date, time, and email.
   - Customize the form fields as per your requirements.

2. **Pabbly Workflow Integration:**
   - Integrate your Tally form with Pabbly for automation.
   - Set up a workflow to send an email notification via Gmail when a reminder date is reached.
   - Use Pabbly’s scheduling features to control when emails should be sent (e.g., 24 hours before, on the day, or any custom timing).

3. **Gmail Integration:**
   - Set up your Gmail account to send automated reminder emails through Pabbly.
   - Create an email template for reminders, including dynamic fields like task name and due date.

4. **Testing:**
   - Test your reminder by submitting a form and checking if the email is sent at the correct time.

## Example Use Cases

### Use Case 1: Daily Task Reminders
- **Scenario:** A user needs to receive a reminder every day at 9 AM to complete a daily report.
- **Workflow:**
  - The user submits the task "Complete daily report" with the due time set to 9:00 AM daily.
  - The reminder email is sent every day at the scheduled time with the task name and description.

### Use Case 2: Event Reminder
- **Scenario:** A user submits a reminder to prepare for an event happening in 3 days.
- **Workflow:**
  - The user sets the reminder to "Prepare for the annual meeting" with the date set to 3 days from now.
  - The app automatically sends an email reminder 3 days before the event.

### Use Case 3: One-Time Appointment Reminder
- **Scenario:** A user submits a reminder for an appointment tomorrow at 10:00 AM.
- **Workflow:**
  - The user submits the reminder through the form.
  - The app sends an email reminder at the scheduled time, reminding the user of the appointment.

## Technologies Used
- **Tally Forms**: For creating the form where users can input their reminder details.
- **Pabbly**: For automating the reminder workflows.
- **Gmail**: To send email notifications for reminders.

## Contributing
If you have suggestions or improvements for the app, feel free to fork this repository, make changes, and submit a pull request. Contributions are always welcome!

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


