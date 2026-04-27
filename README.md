# Image Form Website

A simple, responsive website featuring a clickable image that redirects to a contact form.

## Features

✅ **Responsive Design** - Works perfectly on all devices (mobile, tablet, desktop)  
✅ **Blue & White Theme** - Professional color scheme  
✅ **Clickable Image** - Click the image to navigate to the form  
✅ **Contact Form** - Collect user information (Name, Email, Message)  
✅ **Email Integration** - Form submissions sent to highbeecaz@gmail.com  

## Project Structure

```
image-form-website/
├── index.html       # Landing page with clickable image
├── form.html        # Contact form page
├── styles.css       # Responsive styling
└── README.md        # This file
```

## Setup Instructions

### 1. Set Up Formspree

The form uses **Formspree** to handle email submissions. Follow these steps:

1. Go to [formspree.io](https://formspree.io)
2. Sign up with your email (highbeecaz@gmail.com)
3. Create a new form project
4. Copy your form endpoint (should look like: `https://formspree.io/f/YOUR_FORM_ID`)
5. Open `form.html` and replace `YOUR_FORM_ID` in the form action with your actual form ID

**Example:**
```html
<form action="https://formspree.io/f/xyzabc123" method="POST">
```

### 2. Replace Placeholder Image

In `index.html`, replace the image source:
```html
<img src="your-image-url-here" alt="Clickable Image">
```

Use any image URL or local image file path.

### 3. Enable GitHub Pages (Optional)

To host your website for free:

1. Go to your repository settings
2. Scroll to "GitHub Pages"
3. Select `main` branch as the source
4. Your site will be available at `https://Highbee27.github.io/image-form-website`

## Usage

1. Visit the landing page
2. Click on the image
3. Fill out the contact form
4. Submit to send the message to highbeecaz@gmail.com

## Customization

You can easily customize:

- **Colors** - Edit `styles.css` to change the blue (#0066cc) and white colors
- **Form Fields** - Add more input fields in `form.html`
- **Image** - Replace the placeholder with your own image
- **Styling** - Modify `styles.css` for custom fonts, spacing, etc.

## Browser Compatibility

- ✅ Chrome
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## License

Free to use and modify.

---

Created with ❤️ by Copilot
