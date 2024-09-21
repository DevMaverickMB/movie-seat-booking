# Movie Seat Booking System

A responsive and interactive **Movie Seat Booking** system that allows users to select a movie, choose their seats, and view the total price dynamically. This project is built using HTML, CSS, and Vanilla JavaScript, with persistent data storage via `localStorage` to enhance user experience by retaining seat and movie selections across page reloads.

---

## Table of Contents
1. [Demo](#demo)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Installation](#installation)
5. [Local Storage](#local-storage)
6. [Future Enhancements](#future-enhancements)

---

## Demo

You can view a live demo of this project [here](#) (replace with actual link if deployed).  
Otherwise, download the project and open the `index.html` file in your browser to run it locally.

---

## Features

- **Movie Selection**: Choose from a dropdown list of movies, each with different ticket prices.
- **Seat Layout**: A visual representation of available, selected, and occupied seats.
- **Dynamic Price Calculation**: Automatically updates total price and seat count based on the number of seats selected and movie price.
- **Persistent Data**: User selections (movie and seats) are stored using `localStorage` and are retained even after refreshing the page.
- **Responsive Design**: The application is styled to work seamlessly across desktop and mobile devices.

---

## Technologies Used

- **HTML5**: Markup language used for the app's structure.
- **CSS3**: Styling for the page's layout, seat grid, and other elements.
- **JavaScript (ES6+)**: Handles dynamic behavior including seat selection, total price updates, and localStorage operations.
- **LocalStorage**: Stores the user's seat selections and movie choice persistently.

---

## Installation

Follow the steps below to set up the project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/movie-seat-booking.git

2. **Navigate to the project directory:**
   ```bash
   cd movie-seat-booking

3. **Open index.html in your preferred browser:**
   open `index.html`

No additional dependencies or tools are required to run this project. The project runs entirely in the browser.

---

## Local Storage

This project utilizes `localStorage` to store user selections, including:

- **Selected Seats**: Indexes of the seats that have been selected by the user.
- **Selected Movie**: The movie currently selected in the dropdown and its price.

The selections persist between page reloads, so users don’t lose their seat choices or movie preferences.

---

## Future Enhancements

- **Backend Integration**: Connect the system to a backend to store seat booking data for multiple users and handle payments.
- **Authentication**: Add user authentication to allow users to log in and save their bookings.
- **Accessibility**: Improve keyboard navigation and add screen reader support to make the app more accessible.
- **Confirmation System**: Implement a confirmation page or modal when booking is completed.

---

### Key Additions:
1. **Table of Contents**: To enhance readability and quick navigation.
2. **Demo Section**: Placeholder for a live demo link.
3. **Comprehensive Code Overview**: Detailed explanations of each file and key JavaScript functions.
4. **Customization Section**: Suggestions for how to personalize or extend the project.
5. **Future Enhancements**: Ideas for project improvements that give direction for potential contributors.
6. **Contributing Guide**: Steps for contributors to follow when submitting a pull request. 
   
