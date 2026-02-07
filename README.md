# JobHunt - Job Portal Website

A modern, responsive job portal website built with HTML, CSS, and JavaScript. JobHunt connects job seekers with employers, providing a seamless platform for finding and posting job opportunities.

![JobHunt Logo](images/logo-placeholder.png)

---

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Pages](#pages)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Design](#design)
- [Author](#author)
- [License](#license)

---

## 🎯 About

JobHunt is a comprehensive job portal designed to bridge the gap between employers and job seekers. The platform offers a user-friendly interface with advanced job search capabilities, allowing candidates to find relevant opportunities based on their skills, experience, and location.

### Key Objectives:
- **For Job Seekers**: Find their dream jobs with ease using advanced filters and search options
- **For Employers**: Post job openings and connect with qualified candidates
- **For Both**: Create meaningful employment relationships

---

## ✨ Features

### For Job Seekers
- 🔍 **Advanced Job Search** - Search by job title, keyword, category, or company
- 📍 **Location-based Search** - Filter jobs by city, state, or country
- 📊 **Category Browsing** - Browse jobs across various industries and sectors
- 🔔 **Save Jobs** - Save favorite jobs for later review
- 🏢 **Company Profiles** - View detailed company information and their job listings
- 📝 **Job Details** - Comprehensive job descriptions with requirements and qualifications
- ⭐ **Testimonials** - Read success stories from other job seekers
- 📞 **Contact Support** - Easy communication with the platform

### For Employers
- 📝 **Post Jobs** - Create and publish job listings with detailed requirements
- 🏢 **Company Profile** - Showcase your company to potential candidates
- 👀 **View Applications** - Review candidate applications (UI ready)
- 💼 **Dashboard** - Manage your job postings (UI ready)

### General Features
- 📱 **Responsive Design** - Works on desktop, tablet, and mobile devices
- 🎨 **Modern UI** - Clean, professional, and visually appealing design
- ⚡ **Fast Loading** - Optimized for performance
- 🔐 **User Authentication** - Login and registration system (UI ready)
- 🌙 **User-friendly Navigation** - Intuitive menu and navigation system
- 📧 **Contact Form** - Easy way to reach out for support

---

## 🛠 Tech Stack

| Technology | Description |
|------------|-------------|
| **HTML5** | Semantic markup for structure |
| **CSS3** | Styling, animations, and responsive design |
| **JavaScript** | Interactive functionality and dynamic behavior |
| **Font Awesome** | Icon library for visual elements |
| **Google Fonts** | Typography (Poppins font family) |

---

## 📁 Project Structure

```
Final-project/
├── index.html           # Home page with job search and categories
├── about.html           # About us page with testimonials
├── jobs.html            # Job listings with advanced filters
├── view_job.html        # Detailed job description page
├── view_company.html    # Company profile and their job listings
├── login.html           # User login page
├── register.html        # User registration page
├── Contact.html         # Contact form and company information
├── css/
│   └── style.css        # Main stylesheet
├── js/
│   └── script.js        # JavaScript functionality
├── images/
│   ├── about-img.avif   # About section image
│   ├── about-img.jpg   # About section image (alternative)
│   ├── avatar 1-6.jpg   # Testimonial user avatars
│   ├── home-bg.jpg      # Home page background
│   └── icon-1-6.png/jpg # Company logos
└── README.md            # Project documentation
```

---

## 📄 Pages Description

### 1. Home Page (`index.html`)
The landing page featuring:
- Hero section with job search form
- Job categories display (8 categories)
- Latest job listings (6 featured jobs)
- About us section
- Success stories/testimonials
- Footer with quick links and social media

### 2. About Page (`about.html`)
Information about the platform:
- Company mission and values
- Why choose us section
- Success stories from users
- Contact CTA

### 3. Jobs Page (`jobs.html`)
Comprehensive job listing page:
- Advanced filtering system:
  - Job title search
  - Location search
  - Date posted filter
  - Salary range filter
  - Job type filter (full-time, part-time, etc.)
  - Qualification level filter
  - Work shift filter
- Job categories sidebar
- Job listings with detailed information

### 4. View Job Page (`view_job.html`)
Detailed job information:
- Job title and company
- Location
- Salary and benefits
- Job type and schedule
- Requirements (education, age, language, experience)
- Qualifications needed
- Required skills
- Job description
- Apply button
- Save job functionality

### 5. View Company Page (`view_company.html`)
Company profile showcase:
- Company logo and information
- About company section
- Company statistics (jobs posted, employees, etc.)
- Company's open job listings

### 6. Login Page (`login.html`)
User authentication:
- Email and password login form
- "Don't have an account?" link to registration
- Professional login interface

### 7. Register Page (`register.html`)
User registration:
- Name, email, password fields
- Confirm password functionality
- Link to login for existing users

### 8. Contact Page (`Contact.html`)
Contact information and form:
- Phone numbers
- Email addresses
- Physical address
- Contact form with:
  - Name field
  - Email field
  - Phone number
  - Role selection (job seeker/employer)
  - Message textarea

---

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor for viewing/editing code (VS Code recommended)
- Optional: Local web server (e.g., Live Server extension for VS Code)

### Installation

1. **Clone or download the project:**
   ```bash
   git clone https://github.com/yourusername/Final-project.git
   cd Final-project
   ```

2. **Open in browser:**
   - Simply open `index.html` in your web browser
   - Or use a local server for better development experience:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (with http-server)
     npx http-server
     ```

3. **View the website:**
   Navigate to `http://localhost:8000` in your browser

---

## 💡 Usage

### For Job Seekers

1. **Search for Jobs:**
   - Use the search bar on the home page
   - Enter job title, keyword, category, or company
   - Enter desired location
   
2. **Browse Categories:**
   - Click on job categories (Development, Designer, Engineer, etc.)
   - View all jobs in that category

3. **Use Advanced Filters:**
   - Go to Jobs page
   - Filter by date posted, salary, job type, qualification, and shifts
   - Click on filter options to apply

4. **View Job Details:**
   - Click "View Details" on any job card
   - Read full job description
   - Check requirements and qualifications
   
5. **Save Jobs:**
   - Click the heart icon on job cards
   - Save jobs for later review

6. **Apply for Jobs:**
   - Click "Apply Now" on job details page
   - (Requires user authentication - UI ready)

### For Employers

1. **Post a Job:**
   - Click "Post Jobs" button
   - (Requires login - UI ready)

2. **View Company Profile:**
   - Companies can showcase their profile
   - Display company information and job listings

---

## 🎨 Design

### Color Scheme
- **Primary Color**: `#55878d` (Teal/Cyan)
- **Secondary Color**: `#2c3e50` (Dark Blue/Black)
- **Background**: `#eee` (Light Gray)
- **Text**: `#777` (Light Dark), `#2c3e50` (Dark)
- **White**: `#fff` (Pure White for cards and containers)

### Typography
- **Font Family**: Poppins (Google Fonts)
- **Weights**: 100, 300, 400, 500, 600

### Responsive Breakpoints
- **Desktop**: > 991px
- **Tablet**: 768px - 991px
- **Mobile**: < 768px
- **Small Mobile**: < 450px

### Key Design Features
- CSS Variables for consistent theming
- Flexbox and CSS Grid for layouts
- Smooth animations and transitions
- Hover effects on interactive elements
- Mobile-friendly navigation with hamburger menu
- Card-based design for job listings
- Icon integration with Font Awesome

---

## ⚙️ JavaScript Functionality

### Current Features
1. **Mobile Navigation Toggle**
   - Hamburger menu for mobile devices
   - Smooth open/close animation

2. **Input Validation**
   - Phone number length validation
   - Prevents exceeding maxlength attributes

3. **Dropdown Filters**
   - Interactive job filter dropdowns
   - Click to select filter options
   - Smooth expand/collapse animations

### Planned Enhancements
- Form validation and submission
- User authentication logic
- Job application system
- Local storage for saved jobs
- Dynamic job loading
- Search functionality
- User dashboard

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📧 Contact

**Oyebanji Abdullah**
- Email: oyebanjiabdullah09@gmail.com
- Instagram: [@abdul_banji](https://www.instagram.com/abdul_banji/)
- YouTube: [@AbdullahOyebanji](https://www.youtube.com/@AbdullahOyebanji-sz9pw)
- Project Link: [https://github.com/yourusername/Final-project](https://github.com/yourusername/Final-project)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- [Font Awesome](https://fontawesome.com/) for the icon library
- [Google Fonts](https://fonts.google.com/) for the typography
- [FlatIcon](https://www.flaticon.com/) for the icons and images
- All contributors and users of the platform

---

## 📈 Project Status

**Current Status**: Frontend Development Complete
- ✅ HTML Structure
- ✅ CSS Styling
- ✅ JavaScript Interactivity
- 🔄 Backend Integration (Planned)
- 🔄 Database Integration (Planned)
- 🔄 User Authentication System (UI Ready)

---

## 🐛 Known Issues

- No backend integration (frontend only)
- Forms don't submit data (UI only)
- No actual user authentication
- Saved jobs not persisted (requires backend/storage)

---

## 🔮 Future Enhancements

- Backend implementation (Node.js, PHP, or Python)
- Database integration (MongoDB, MySQL, etc.)
- User authentication system
- Real job posting and application system
- Admin dashboard
- Email notifications
- Resume upload functionality
- Job recommendations based on user profile
- Analytics dashboard for employers

---

**Built with ❤️ by Oyebanji Abdullah © 2024**

*JobHunt - Find Your Dream Job Today!*

