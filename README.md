# Resume & Biodata Website

A fully functional, well-structured website consisting of 3 pages to showcase resume and biodata. Built with HTML5, CSS3, and JavaScript/jQuery.

## 🌐 Website Pages

### 1. **Home Page (index.html)**
- Professional welcome page with introduction
- Career objective and personal introduction
- Navigation menu to other pages
- Quick links to Resume and Contact pages

### 2. **Resume Page (resume.html)**
- **Personal Information**: Name, Address, Contact Details, Social Links
- **Education**: Educational background with timeline
- **Skills**: Technical and Soft Skills organized in categories
- **Work Experience**: Detailed job history with responsibilities
- **Projects**: Showcase of portfolio projects with descriptions

### 3. **Contact Page (contact.html)**
- Contact form with validation (Name, Email, Subject, Message)
- Contact information display
- Social media links
- Real-time form validation using JavaScript

## 🎨 Features

- ✅ **Semantic HTML5** elements (`<header>`, `<footer>`, `<main>`, `<section>`)
- ✅ **Responsive Design** using CSS Grid and Flexbox
- ✅ **Modern Styling** with CSS variables, gradients, and animations
- ✅ **Interactive Elements**:
  - Smooth scrolling navigation
  - Hover effects on links and buttons
  - Form validation with error messages
  - Scroll animations
  - Active page highlighting in navigation
- ✅ **Cross-browser Compatible**
- ✅ **Mobile-friendly** responsive layout

## 📁 Project Structure

```
wt assignment/
├── index.html          # Home page
├── resume.html         # Resume page
├── contact.html        # Contact page
├── styles.css          # CSS styling file
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## 🚀 Deployment on GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name your repository (e.g., `resume-website`)
5. Choose **Public** (required for free GitHub Pages)
6. **DO NOT** initialize with README, .gitignore, or license
7. Click "Create repository"

### Step 2: Initialize Git and Push Files

Open your terminal/command prompt in the project directory and run:

```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: Resume website"

# Add your GitHub repository as remote (replace YOUR_USERNAME and REPO_NAME)
git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** tab (top menu)
3. Scroll down to **Pages** section (left sidebar)
4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**

### Step 4: Access Your Website

GitHub Pages will provide you with a URL in the format:
```
https://YOUR_USERNAME.github.io/REPO_NAME/
```

**Note**: It may take a few minutes (up to 10 minutes) for the site to be available after enabling GitHub Pages.

## 🔧 Customization

### Update Personal Information

1. **index.html**: Update name, introduction, and career objective
2. **resume.html**: Modify all personal details in the Personal Information section
3. **contact.html**: Update contact details and social links

### Change Color Scheme

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #4a90e2;    /* Change primary color */
    --secondary-color: #2c3e50;  /* Change secondary color */
    --accent-color: #3498db;     /* Change accent color */
}
```

### Add Profile Image

Replace the placeholder image URL in `index.html`:
```html
<img src="your-image-url.jpg" alt="Professional Photo" class="profile-image">
```

## 📝 Form Validation

The contact form includes JavaScript validation for:
- **Name**: Required, minimum 2 characters, letters only
- **Email**: Required, valid email format
- **Subject**: Required, minimum 3 characters
- **Message**: Required, minimum 10 characters

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Grid, Flexbox, Animations
- **JavaScript**: Form validation, smooth scrolling, interactive features

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This project is created for educational purposes. Feel free to use and modify as needed.

## 🤝 Contributing

Feel free to fork this project and make it your own! Customize the content, colors, and layout to match your personal brand.

---

**Created by**: Prince  
**Date**: 2024

