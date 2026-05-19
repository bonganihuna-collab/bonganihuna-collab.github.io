# Bongani Huna - Personal Portfolio

A modern, responsive personal website and portfolio built with HTML, CSS, and JavaScript. Perfect for showcasing your projects, blog posts, skills, and getting in touch with clients.

## 🎨 Features

- ✨ **Modern Design** - Clean and professional interface with smooth animations
- 📱 **Fully Responsive** - Works seamlessly on desktop, tablet, and mobile devices
- 🏠 **Home Section** - Eye-catching hero section with call-to-action buttons
- 👤 **About Section** - Tell your story and showcase your professional bio
- 💼 **Projects Showcase** - Display your best work with descriptions and links
- 🎯 **Skills Section** - Organize and display your technical skills by category
- 📝 **Blog** - Share your knowledge with a dedicated blog section with multiple posts
- 📧 **Contact Form** - Functional contact form with validation
- 🌐 **GitHub Pages Ready** - Easily deployable to GitHub Pages
- 🎭 **Smooth Animations** - Professional animations and transitions throughout

## 📁 Folder Structure

```
portfolio/
├── index.html              # Main portfolio page
├── styles.css              # All styling
├── script.js               # JavaScript functionality
├── README.md               # This file
├── blog/
│   ├── index.html          # Blog archive page
│   └── post1.html          # Sample blog post
└── images/                 # Folder for your images
    ├── profile.jpg         # Your profile picture
    ├── project1.jpg        # Project screenshots
    ├── project2.jpg
    └── project3.jpg
```

## 🚀 Getting Started

### Prerequisites
- A GitHub account
- Git installed on your computer
- A text editor (VS Code, Sublime Text, etc.)

### Installation

1. **Clone or download this repository**
   ```bash
   git clone https://github.com/bonganihuna-collab/bonganihuna-collab.github.io.git
   cd bonganihuna-collab.github.io
   ```

2. **Add your content**
   - Open `index.html` and customize:
     - Your name and tagline
     - About section text
     - Project details and links
     - Contact information
     - Social media links

3. **Add your images**
   - Create an `images/` folder if it doesn't exist
   - Add your profile picture as `profile.jpg`
   - Add project screenshots as `project1.jpg`, `project2.jpg`, `project3.jpg`

4. **Customize the blog**
   - Edit blog post content in `blog/post1.html`
   - Create new blog posts following the same template
   - Update links in `blog/index.html`

5. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Initial portfolio setup"
   git push origin main
   ```

6. **View your site**
   - Navigate to: `https://bonganihuna-collab.github.io`
   - (Note: It may take a few minutes for GitHub Pages to deploy your site)

## 🎨 Customization

### Colors
Edit the CSS variables in `styles.css` to change the color scheme:

```css
:root {
    --primary-color: #2563eb;      /* Change primary blue */
    --secondary-color: #10b981;    /* Change secondary green */
    --text-color: #1f2937;         /* Change text color */
    --light-bg: #f9fafb;           /* Change light background */
}
```

### Fonts
The portfolio uses 'Segoe UI' font family. You can change this in `styles.css` by modifying the `body` selector:

```css
body {
    font-family: 'Your Font Here', sans-serif;
}
```

## 📝 Creating Blog Posts

1. **Create a new HTML file** in the `blog/` folder (e.g., `post2.html`)
2. **Use `post1.html` as a template**
3. **Update the content** with your blog post
4. **Add a link** in `blog/index.html`:
   ```html
   <article class="blog-card">
       <h3>Your Post Title</h3>
       <p class="blog-date">Date</p>
       <p>Short description...</p>
       <a href="blog/post2.html" class="read-more">Read More →</a>
   </article>
   ```

## 🔧 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with animations and gradients
- **JavaScript (Vanilla)** - Form validation, smooth scrolling, and animations
- **Font Awesome** - Icon library
- **GitHub Pages** - Free hosting

## 📱 Responsive Design

The portfolio is fully responsive with breakpoints for:
- Desktop (1024px and above)
- Tablet (768px - 1023px)
- Mobile (below 768px)

## 🎯 SEO Optimization

- Semantic HTML structure
- Meta tags for social sharing
- Proper heading hierarchy
- Mobile-friendly design

## ⚙️ Features Explained

### Contact Form
- Client-side validation
- Email validation
- Success feedback message
- Prevents empty submissions

### Smooth Scrolling
- Navigation links scroll smoothly to sections
- Intersection Observer for fade-in animations

### Mobile Menu
- Hamburger menu on mobile devices
- Click to toggle navigation
- Smooth transitions

## 🐛 Troubleshooting

**Site not showing up after push?**
- GitHub Pages can take 5-10 minutes to deploy
- Check your repository settings to ensure GitHub Pages is enabled
- Verify the branch is set to 'main'

**Images not loading?**
- Ensure image filenames match exactly (case-sensitive on GitHub)
- Place images in the correct `images/` folder
- Use relative paths in HTML

**Form not working?**
- The form shows a success message but doesn't actually send emails
- To enable email functionality, use a service like Formspree or Netlify Forms

## 📧 Adding Email Functionality

To make the contact form actually send emails, integrate with a service like:
- [Formspree](https://formspree.io/)
- [Netlify Forms](https://www.netlify.com/products/forms/)
- [EmailJS](https://www.emailjs.com/)

## 📄 License

This portfolio template is free to use and modify for personal use.

## 🤝 Contributing

Feel free to customize and improve this template for your needs!

## 📞 Support

For questions or issues, please create an issue in the repository or contact through the portfolio.

---

**Made with ❤️ by Bongani Huna**

Live at: https://bonganihuna-collab.github.io