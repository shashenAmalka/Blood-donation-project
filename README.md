# Blood Donation Management System

A web-based blood donation management system that connects donors, recipients, and administrators to facilitate blood donation and requests efficiently.

## Features

### For Donors
- User registration and login
- Profile management with health details
- Blood donation appointment scheduling
- Donation history tracking
- Appointment history viewing
- Event information and updates
- Feedback submission

### For Recipients
- Blood request submission
- Track request status
- View available blood inventory
- Contact support

### For Administrators
- Manage users, donors, and staff
- Approve/reject donation appointments
- Approve/reject blood requests
- Manage blood inventory
- Organize donation events
- Send notifications
- Manage feedback
- View analytics and reports

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript, jQuery
- **Backend**: PHP
- **Database**: MySQL
- **Libraries**: ScrollReveal.js, Font Awesome

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Blood-donation-project.git
   ```

2. Import the database:
   - Open phpMyAdmin or MySQL client
   - Create a new database (e.g., `hopeflow`)
   - Import `database/hopeflow.sql` or `blood data base/blooddonation.sql`

3. Configure database connection:
   - Edit `database/conn.php` with your database credentials

4. Deploy to web server:
   - Copy project files to your web server directory (e.g., `htdocs` for XAMPP)
   - Ensure PHP and MySQL are properly configured

5. Access the application:
   - Open your browser and navigate to `http://localhost/Blood-donation-project`

## Usage

### User Registration
1. Navigate to the registration page
2. Fill in required details including health information
3. Submit the form to create an account

### Making an Appointment
1. Log in to your account
2. Go to the appointment section
3. Select date and time for donation
4. Submit appointment request
5. Wait for admin approval

### Requesting Blood
1. Navigate to the request page
2. Fill in blood type and quantity needed
3. Provide contact information
4. Submit request

### Admin Access
- Access admin panel at `/admin/login/`
- Use admin credentials to log in
- Manage all aspects of the system from the dashboard

## Project Structure

```
├── admin/              # Admin panel
├── account/            # User account management
├── appointment/        # Appointment booking
├── request/            # Blood request system
├── events/             # Event management
├── database/           # Database files and connection
├── css/                # Stylesheets
├── script/             # JavaScript files
├── images/             # Image assets
└── partials/           # Reusable components
```

## Security Features

- Password encryption
- Session management
- SQL injection prevention
- XSS protection
- Admin authentication

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the MIT License.

## Contact

For any queries or support, please use the contact form on the website.

## Acknowledgments

- Thanks to all contributors
- Inspired by the need for efficient blood donation management
- Built with ❤️ for saving lives