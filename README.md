
Built by https://www.blackbox.ai

---

```markdown
# Raahi - Ride Sharing Platform

## Project Overview
Raahi is a web application designed as a ride-sharing platform specifically for students at Bennett University. The platform allows users to share their rides with fellow students, thereby facilitating cost-effective and eco-friendly commuting. The application features user authentication, ride posting and searching functionality, and a profile management system, all aimed at creating a trusted carpooling community.

## Installation
To set up the project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone <YOUR_REPOSITORY_URL>
   cd raahi
   ```

2. **Open `index.html` in your web browser:**
   - Simply double-click `index.html` or open it through your browser to see the application in action.

## Usage
- **Login and Signup:** Users can log in using their Bennett University email or sign up if they are new to the platform.
- **Find a Ride:** Users can search for available rides based on their pickup location and destination.
- **Offer a Ride:** Users can post a ride with details like route, date, time, and available seats.
- **Profile Management:** After logging in, users can manage their profiles and vehicle information.

## Features
- **User Authentication:** Secure login/signup process for users.
- **Ride Management:** Allows users to find and offer rides based on specified routes and times.
- **Eco-Friendly:** Encourages users to share rides, contributing to a reduced carbon footprint.
- **User Ratings:** Drivers and passengers can rate each other.
- **Notification System:** Alerts users of updates regarding their rides and requests.

## Dependencies
The project utilizes several dependencies, primarily for styling and icons. Below is a list of dependencies referenced in the project files:

- **Tailwind CSS:** For styling the application. To use it, add the following script in your HTML head:
  ```html
  <script src="https://cdn.tailwindcss.com"></script>
  ```
- **Font Awesome:** For icons functionality. Link it as follows:
  ```html
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  ```
- **Google Fonts:** For custom font usage. You can include the Inter font using:
  ```html
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
  ```

## Project Structure
Here is an overview of the project's file structure:

```
/raahi
|-- index.html               # Landing page with ride-sharing info
|-- login.html               # Login page for users
|-- login-updated.html       # Updated login page with OTP functionality
|-- home.html                # User dashboard after login
|-- my-rides.html            # Page displaying user's ride history
|-- profile.html             # User profile management page
|-- offer-ride.html          # Form for users to offer rides
|-- find-ride.html           # Page for users to find available rides
|-- fuel-saved.html          # Page displaying fuel savings statistics
|-- profile-setup.html       # Form to set up user profiles
|-- login-new.html           # Alternative login page
|-- find-ride-new.html       # Updated find-a-ride page with new design
|-- styles.css               # Custom styles (if any)
```

Each HTML file serves a specific purpose in the overall application user flow. Additional functionalities may be added to enhance the user experience further.

## Conclusion
Raahi aims to provide a sustainable and convenient solution for students at Bennett University. By utilizing shared transportation, users not only save costs but also contribute to the environment. 

For contributions, feedback, or issues, please raise an issue or submit a pull request in the repository. Thank you for checking out Raahi!
```