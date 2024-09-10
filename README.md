# Job Application Tracker

## Overview

The Job Application Tracker is a desktop application built using Python and Tkinter. It helps users efficiently manage and track their job applications, providing a user-friendly interface for data entry, visualization, and analysis.

## Features

- **Application Management**: 
  - Add, update, and delete job applications with ease.
  - Track key information such as company name, position, application date, status, notes, reminder dates, and location.
- **Interactive User Interface**: 
  - Clean and intuitive Tkinter-based GUI for smooth user interaction.
  - Color-coded application status for quick visual reference.
- **Data Persistence**: 
  - SQLite database integration for reliable storage and retrieval of application data.
- **Reminder System**: 
  - Set and manage reminders for follow-up actions on your applications.
  - Automatically sends follow-up email reminders when the reminder date for an application is due.
  - Popup window to alert when the reminder date for an application is due.
- **Email Notifications**:
  - Configure email settings to receive reminders about application follow-ups.
  - Enable or disable email reminders through the settings menu.
- **Advanced Analytics and Visualization**: 
  - Real-time statistics and charts for insightful analysis of your job search progress.
  - Pie chart for application status distribution.
  - Bar charts for applications per month, company, and position.
  - Additional statistics including total applications, average applications per month, success rate, and average response time.
- **Sorting Functionality**: 
  - Sort applications by any column for easy data organization.
- **Map View**: 
  - Open a map view showing job application locations with interactive markers.
  - Visualize application locations on a map, centered on Israel, using Folium and Webview.
- **Settings**:
  - Customize application settings, including email preferences.

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/job-application-tracker.git
   ```

2. Navigate to the project directory:
   ```
   cd job-application-tracker
   ```

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Run the application:
   ```
   python main.py
   ```

## Dependencies

See `requirements.txt` for a full list of dependencies.

## How to Use

1. **Adding a New Application**: 
   - Fill in the application details in the input fields.
   - Click "Add/Update Application" to save the entry.

2. **Editing an Application**: 
   - Select an application from the list.
   - Modify the details in the input fields.
   - Click "Add/Update Application" to save changes.

3. **Deleting an Application**: 
   - Select an application from the list.
   - Click "Delete Selected" to remove the entry.

4. **Setting Reminders**: 
   - Enter a reminder date when adding or updating an application.
   - The system will notify you when it's time to follow up.

5. **Viewing Analytics**: 
   - Click "View Analytics" to open the analytics window.
   - Explore various charts and statistics about your job applications.

6. **Sorting Applications**: 
   - Click on any column header in the main view to sort applications by that criteria.

7. **Viewing the Map**: 
   - Click "Open Map" to view the map with markers for job application locations.
   - The map opens in a new window and shows application locations centered on Israel.

8. **Configuring Settings**:
   - Click "Settings" to open the settings window.
   - Enter your email address and enable/disable email reminders.

## Project Structure

- `main.py`: Entry point of the application
- `views.py`: Main GUI implementation, analytics view, and settings window
- `controllers.py`: Logic for adding, updating, and deleting applications
- `models.py`: Definition of the JobApplication class
- `database.py`: SQLite database operations
- `utils.py`: Utility functions for reminders, statistics generation, and email sending

## Contributing

Contributions to improve the Job Application Tracker are welcome. Please follow these steps to contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make your changes and commit them (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Create a new Pull Request

## examples
![Application Screenshot](C:\Users\galme\תואר\projects\Job-Apliction-tracker\output\screenshot)

