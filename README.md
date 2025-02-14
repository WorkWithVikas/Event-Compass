# Event-Compass
# Event Compass - Event Finder Application

## Overview
Event Compass is an event finder application that allows users to search for and discover upcoming events in their city. The application provides a user-friendly interface built with **JavaFX** and utilizes **MySQL** for data storage. Users can view event details, filter events based on categories, and even register as event organizers to manage their own listings.

## Features

### User Features
- **Event Discovery**: Browse a list of upcoming events categorized by type, location, and date.
- **Search & Filter**: Easily find events using keywords, categories, and location filters.
- **Event Details Page**: View detailed event information including date, time, venue, and description.
- **User Authentication**: Secure login and registration system for users and organizers.
- **Bookmark Events**: Save events to a personal list for future reference.

### Organizer Features
- **Event Management**: Create, edit, and delete event listings.
- **Event Analytics (Future Enhancement)**: Track engagement metrics for hosted events.

### Additional Features
- **Google Maps Integration (Optional)**: Show event locations on an interactive map.
- **Notification System (Future Enhancement)**: Send reminders and updates to registered users.

## Technology Stack
- **Frontend**: JavaFX (FXML for UI layout)
- **Backend**: Java (JDBC for MySQL connectivity)
- **Database**: MySQL
- **Development Tools**: Apache NetBeans, Eclipse IDE, XAMPP for MySQL
- **Additional APIs**: Google Maps API (optional for event location visualization)

## Database Schema
### Tables:
- **Users** (`id`, `name`, `email`, `password`, `role`)
- **Events** (`id`, `title`, `description`, `date`, `time`, `location`, `category`, `organizer_id`)
- **Bookings** (`id`, `user_id`, `event_id`, `status`)

## Installation & Setup
### Prerequisites:
- Install **JDK 17+**
- Install **Apache NetBeans** or **Eclipse IDE**
- Install **XAMPP** (for MySQL database)

### Steps:
1. **Clone the Repository**
   ```sh
   git clone https://github.com/yourusername/event-compass.git
   cd event-compass
   ```
2. **Set Up the Database**
   - Start XAMPP and open **phpMyAdmin**
   - Create a new database named `event_compass`
   - Import the provided `event_compass.sql` file
3. **Configure Database Connection**
   - Update `DatabaseConfig.java` with your MySQL credentials.
4. **Run the Application**
   - Open the project in NetBeans/Eclipse
   - Run `Main.java`

## Contribution Guidelines
- Fork the repository and create a new branch.
- Make necessary changes and commit with a meaningful message.
- Create a pull request with detailed descriptions of changes.

## Future Enhancements
- Mobile App version
- AI-based event recommendations
- Social media sharing for events
- Ticket booking and payment integration

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any queries, feel free to reach out:
- **Email**: support@eventcompass.com
- **GitHub**: [github.com/yourusername](https://github.com/yourusername)

---
Enjoy discovering new events with **Event Compass**! 🚀

