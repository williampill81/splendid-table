# Splendid Table - Northwestern University

A community-building web application designed to bring Northwestern Wildcats together through shared dining experiences. Built with Flask and featuring a modern, responsive design with Northwestern University branding.

## About the Project

Splendid Table is a human connection initiative that encourages Northwestern students to step out of their comfort zones and build meaningful relationships through impromptu dining experiences. The project was founded by William Chang, a Biological Sciences student (Class of 2029), inspired by his experience with Toastmasters International.

## Features

- **Home Page**: Welcoming hero section featuring Northwestern University campus imagery and clear call-to-action
- **About Us Page**: Personal story of founder William Chang, team information, and project mission
- **Splendors Page**: Community building section showcasing the people and connections made through the initiative
- **Sign Up Page**: Integrated Calendly booking system for scheduling dining meetings
- **Responsive Design**: Mobile-friendly design using Bootstrap 5 and modern CSS
- **Northwestern Branding**: Purple and cream color scheme matching university colors
- **Smooth Animations**: AOS (Animate On Scroll) library for engaging user experience

## Core Mission

- **Impromptu Connections**: Exercise communication skills and appreciate diverse perspectives
- **Memorable Conversations**: Unstructured bonding over meals, finding the good in each other
- **Inclusive Community**: Welcome Wildcats of all backgrounds to contribute their voices
- **Personal Growth**: Transform perspectives through uplifting and constructive community experiences

## Setup Instructions

### 1. Install Dependencies

Navigate to the Splendid Table folder and install dependencies:

```bash
cd "Splendid Table"
pip install -r requirements.txt
```

### 2. Run the Website

From the Splendid Table folder:

```bash
python splendid_table.py
```

The website will be available at `http://localhost:5000`

## File Structure

```
Splendid Table/              # Main project folder
├── splendid_table.py        # Main Flask application
├── requirements.txt          # Python dependencies
├── README.md                # This file
├── static/                  # Static assets
│   ├── banner.jpg          # Website banner image
│   ├── williamchang.jpg    # William Chang profile image
│   └── williamchang2.jpg   # William Chang alternate image
└── templates/               # HTML templates
    ├── base.html            # Base template with navigation and styling
    ├── index.html           # Home page
    ├── about.html           # About Us page with team information
    ├── splendors.html       # Community and connections page
    └── signup.html          # Sign Up page with Calendly integration
```

## Key Pages

### Home Page (`/`)
- Northwestern University hero section
- Three core value propositions
- Call-to-action for joining the community

### About Us (`/about`)
- William Chang's personal story and inspiration
- Team member profiles (Corey Zhang and William Chang)
- Project mission and values

### Splendors (`/splendors`)
- Community building focus
- People and connections showcase
- Northwestern-themed imagery

### Sign Up (`/signup`)
- Calendly integration for easy booking
- Operating hours (Tuesday-Sunday, 5:00 PM - 10:00 PM)
- Contact information and meeting details
- Group size options (2-4 guests)

## Customization

### Northwestern University Colors
The website uses Northwestern's official color palette defined in CSS custom properties:

```css
:root {
    --primary-color: #4E2A84;      /* Northwestern Purple */
    --secondary-color: #8B5A96;    /* Lavender Purple */
    --accent-color: #F8F5F0;       /* Northwestern Cream */
    --text-color: #2F2F2F;
    --light-bg: #F8F5F0;
}
```

### Content Updates
- Team member information in `about.html`
- Contact details and operating hours in `signup.html`
- Hero images and background styling
- Mission statements and value propositions

### Calendly Integration
The signup page includes a Calendly integration button:
- Current link: `https://calendly.com/williamchang2029-u/splendidtable`
- Easy to update in `templates/signup.html`

## Team

- **William Chang**: Founder, Biological Sciences Class of 2029, Science Educator, Musician, Cultural Ambassador
- **Corey Zhang**: Team member and community builder

## Technologies Used

- **Backend**: Flask (Python)
- **Frontend**: HTML5, CSS3, JavaScript
- **Styling**: Bootstrap 5, Font Awesome 6.0.0
- **Animations**: AOS (Animate On Scroll) library
- **Booking**: Calendly integration
- **Images**: Northwestern University campus photos and Unsplash stock images

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contact Information

- **Corey Zhang**: coreyzhang2029@u.northwestern.edu
- **William Chang**: williamchang2029@u.northwestern.edu

## License

This project is open source and available under the MIT License. 