# Splendid Table Website

A beautiful, modern restaurant website built with Flask, featuring an About Us page and a Sign Up page with Calendly integration.

## Features

- **Home Page**: Welcoming hero section with call-to-action buttons
- **About Us Page**: Company story, values, and team information
- **Sign Up Page**: Table reservation system with Calendly integration
- **Responsive Design**: Mobile-friendly design using Bootstrap 5
- **Modern UI**: Beautiful gradients, animations, and professional styling

## Setup Instructions

### 1. Install Dependencies

Navigate to the Splendid Table folder and install dependencies:

```bash
cd "Splendid Table"
pip install -r requirements.txt
```

### 2. Customize Calendly Link

Before running the website, update the Calendly link in the signup template:

1. Open `templates/signup.html` (templates are now in the same folder)
2. Replace `https://calendly.com/your-calendly-link` with your actual Calendly URL
3. Update the link in both places where it appears

### 3. Run the Website

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
└── templates/               # Template folder (now consolidated)
    ├── base.html            # Base template with navigation and styling
    ├── index.html           # Home page
    ├── about.html           # About Us page
    └── signup.html          # Sign Up page with Calendly integration
```

## Customization

### Colors
The website uses CSS custom properties for easy color customization. Edit the `:root` section in `templates/base.html`:

```css
:root {
    --primary-color: #8B4513;      /* Change brown */
    --secondary-color: #D2691E;    /* Change orange */
    --accent-color: #FFD700;       /* Change gold */
    --text-color: #2F2F2F;         /* Change text color */
    --light-bg: #FFF8DC;           /* Change background */
}
```

### Content
- Update restaurant information in the templates
- Replace placeholder images with your own
- Modify contact details and operating hours
- Customize team member information

### Calendly Integration
The signup page includes buttons that link to Calendly. To set up:

1. Create a Calendly account
2. Set up your booking calendar
3. Replace the placeholder URLs in `templates/signup.html`
4. Test the integration

## Technologies Used

- **Backend**: Flask (Python)
- **Frontend**: HTML5, CSS3, JavaScript
- **Styling**: Bootstrap 5, Font Awesome
- **Booking**: Calendly integration
- **Images**: Unsplash (free stock photos)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the MIT License. 