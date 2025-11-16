# 🏥 Med Connect

<div align="center">

![React](https://img.shields.io/badge/React-18.2.0-61DAFB?logo=react&logoColor=white)
![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![Node](https://img.shields.io/badge/Node.js-18+-339933?logo=node.js&logoColor=white)
![React Router](https://img.shields.io/badge/React%20Router-6.14.2-CA4245?logo=react-router&logoColor=white)

**A modern healthcare appointment and consultation platform built with React**

[Features](#-features) • [Installation](#-installation) • [Usage](#-usage) • [Tech Stack](#-tech-stack) • [Project Structure](#-project-structure)

</div>

---

## 📋 Table of Contents

- [About](#-about)
- [Features](#-features)
- [Installation](#-installation)
- [Usage](#-usage)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Contributing](#-contributing)
- [License](#-license)

## 🎯 About

**Med Connect** is a comprehensive healthcare platform that connects patients with healthcare providers. The platform enables users to browse doctors, read reviews, book appointments online, and access virtual consultations. Built with modern web technologies, it offers a seamless, responsive experience across all devices.

### Key Highlights

- 🩺 **Doctor Directory**: Browse through a curated list of expert doctors with ratings and reviews
- 📅 **Online Appointment Booking**: Schedule appointments with real-time validation
- 💬 **Virtual Consultations**: Support for both voice and video call consultations
- ⭐ **Patient Reviews**: Read authentic reviews from other patients
- 📱 **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- 🎨 **Modern UI/UX**: Clean, intuitive interface with smooth animations

## ✨ Features

### Core Functionality

- **Home Page**
  - Hero section with call-to-action
  - Statistics display (patients, doctors, experience)
  - Information cards highlighting key services
  - About section explaining the platform
  - Doctor listings with ratings
  - Patient testimonials and reviews
  - Newsletter subscription

- **Appointment Booking**
  - Comprehensive appointment form with validation
  - Patient information collection
  - Date and time selection
  - Consultation mode selection (Voice/Video)
  - Form validation with error messages
  - Success notifications

- **Navigation**
  - Responsive navbar with mobile menu
  - Smooth scrolling
  - Legal documentation pages
  - 404 error handling

### User Experience

- ⚡ Fast and responsive interface
- 🎨 Modern design with custom CSS
- 📱 Mobile-first responsive design
- 🔔 Toast notifications for user feedback
- 🎯 Smooth scroll animations
- ♿ Accessible form inputs

## 🚀 Installation

### Prerequisites

Make sure you have the following installed on your system:

- **Node.js** (version 18 or higher) - [Download](https://nodejs.org/)
- **npm** (comes with Node.js) or **yarn**

### Step-by-Step Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/med-connect.git
   cd med-connect
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```
   or
   ```bash
   yarn install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```
   or
   ```bash
   yarn start
   ```

4. **Open your browser**
   
   The application will automatically open at [http://localhost:3000](http://localhost:3000)

   If it doesn't open automatically, navigate to the URL manually.

### Build for Production

To create an optimized production build:

```bash
npm run build
```

This creates a `build` folder with optimized production files ready for deployment.

### Deploy to GitHub Pages

If you want to deploy to GitHub Pages:

```bash
npm run deploy
```

This will build the project and deploy it to the `gh-pages` branch.

## 💻 Usage

### Development Mode

1. Start the development server:
   ```bash
   npm start
   ```

2. The app will reload automatically when you make changes to the code.

3. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### Available Scripts

| Command | Description |
|---------|-------------|
| `npm start` | Runs the app in development mode |
| `npm run build` | Creates an optimized production build |
| `npm test` | Launches the test runner |
| `npm run eject` | Ejects from Create React App (irreversible) |
| `npm run deploy` | Builds and deploys to GitHub Pages |

### Using the Application

1. **Browse Doctors**
   - Navigate to the "Meet Our Doctors" section
   - View doctor profiles, specialties, ratings, and reviews

2. **Book an Appointment**
   - Click the "Book Appointment" button (in navbar or hero section)
   - Fill out the appointment form with:
     - Patient full name (minimum 8 characters)
     - Phone number (exactly 10 digits)
     - Gender selection
     - Preferred appointment date and time
     - Consultation mode (Voice or Video call)
   - Submit the form to receive confirmation

3. **Read Reviews**
   - Scroll to the reviews section
   - Navigate through patient testimonials
   - View ratings and feedback

4. **Subscribe to Newsletter**
   - Enter your email in the newsletter section
   - Stay updated with health tips and platform news

## 🛠 Tech Stack

### Frontend

- **React** ^18.2.0 - UI library
- **React Router DOM** ^6.14.2 - Client-side routing
- **React Toastify** ^9.1.3 - Toast notifications
- **Font Awesome** ^6.4.0 - Icons

### Build Tools

- **Create React App** - Build tooling and development server
- **React Scripts** ^5.0.1 - Build scripts

### Styling

- **Custom CSS** - Component-specific stylesheets
- **Google Fonts** - Poppins and Rubik font families
- **Responsive Design** - Mobile-first approach

### Testing

- **React Testing Library** - Component testing
- **Jest** - Test runner

## 📁 Project Structure

```
med-connect/
├── public/
│   ├── favicon/          # Favicon files
│   ├── index.html        # HTML template
│   └── robots.txt        # SEO robots file
├── src/
│   ├── Assets/           # Images and static assets
│   ├── Components/       # React components
│   │   ├── About.js
│   │   ├── AppointmentForm.js
│   │   ├── BookAppointment.js
│   │   ├── DoctorCard.js
│   │   ├── Doctors.js
│   │   ├── Footer.js
│   │   ├── Hero.js
│   │   ├── Info.js
│   │   ├── InformationCard.js
│   │   ├── LegalDocs.js
│   │   ├── Navbar.js
│   │   ├── Reviews.js
│   │   ├── SolutionStep.js
│   │   └── SubscribeNewsletter.js
│   ├── Pages/            # Page components
│   │   ├── Appointment.js
│   │   ├── Home.js
│   │   ├── Legal.js
│   │   └── NotFound.js
│   ├── Scripts/          # Utility scripts
│   │   └── reviews.js
│   ├── Styles/           # CSS stylesheets
│   │   ├── About.css
│   │   ├── AppointmentForm.css
│   │   ├── BookAppointment.css
│   │   ├── Doctors.css
│   │   ├── Footer.css
│   │   ├── Hero.css
│   │   ├── Info.css
│   │   ├── LegalDocs.css
│   │   ├── Navbar.css
│   │   └── Reviews.css
│   ├── App.js            # Main App component
│   ├── App.css           # Global styles
│   └── index.js          # Entry point
├── .gitignore
├── LICENSE
├── package.json
└── README.md
```

## 🤝 Contributing

Contributions are welcome! If you'd like to contribute to this project:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit your changes** (`git commit -m 'Add some AmazingFeature'`)
4. **Push to the branch** (`git push origin feature/AmazingFeature`)
5. **Open a Pull Request**

### Contribution Guidelines

- Follow the existing code style
- Add comments for complex logic
- Update documentation as needed
- Test your changes thoroughly
- Ensure responsive design compatibility

## 📄 License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [React](https://reactjs.org/) - The web framework used
- [Font Awesome](https://fontawesome.com/) - Icons
- [Google Fonts](https://fonts.google.com/) - Typography

---

<div align="center">

**Made with ❤️ for better healthcare**

⭐ Star this repo if you find it helpful!

</div>
