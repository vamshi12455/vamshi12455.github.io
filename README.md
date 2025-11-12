# Professional Portfolio Website

A modern, responsive portfolio website designed for GitHub Pages. Features a clean design, smooth animations, and interactive elements to showcase your projects and skills professionally.

## ✨ Features

- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI/UX** - Clean, professional design with smooth animations
- **Interactive Elements** - Dynamic navigation, project filtering, and animated statistics
- **Smooth Scrolling** - Elegant page transitions and scroll effects
- **Contact Form** - Built-in contact form for easy communication
- **SEO Optimized** - Proper meta tags and semantic HTML structure
- **Fast Loading** - Optimized performance with minimal dependencies
- **Customizable** - Easy to personalize with your own content

## 🚀 Quick Start

### Option 1: GitHub Pages (Recommended)

1. **Fork or Clone this repository**
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. **Customize the content**
   - Edit [`index.html`](index.html) to add your personal information
   - Update project details, skills, and contact information
   - Replace placeholder links with your actual social media profiles

3. **Deploy to GitHub Pages**
   - Go to your repository settings
   - Navigate to "Pages" section
   - Select "main" branch as source
   - Your site will be live at `https://yourusername.github.io/your-repo-name/`

### Option 2: Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. **Open in browser**
   - Simply open [`index.html`](index.html) in your web browser
   - Or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   ```

3. **View your site**
   - Navigate to `http://localhost:8000` in your browser

## 📝 Customization Guide

### Personal Information

Edit the following sections in [`index.html`](index.html):

1. **Hero Section** (Lines 45-76)
   - Update your name
   - Change the subtitle and description
   - Add your social media links

2. **About Section** (Lines 93-160)
   - Write your bio
   - Update statistics (projects, experience, clients)
   - Customize feature cards

3. **Projects Section** (Lines 163-270)
   - Features 4 AI Agent projects:
     * [Text to SQL Agent](https://github.com/vamshi12455/text-to-sql-agent) - Natural language to SQL conversion
     * [Data Analysis Agent](https://github.com/vamshi12455/data-analysis-agent) - Automated data analysis and visualization
     * [Intelligent AI Personal Assistant](https://github.com/vamshi12455/ai-personal-assistant) - Voice-enabled productivity assistant
     * [Email Assistant AI Agent](https://github.com/vamshi12455/email-assistant-agent) - Smart email management and automation
   - Update project titles, descriptions, and tags
   - Add links to live demos and GitHub repositories
   - Change project categories (ai, web, automation)

4. **Skills Section** (Lines 322-428)
   - Update your skills and proficiency levels
   - Add or remove skill categories
   - Adjust percentage values

5. **Contact Section** (Lines 431-490)
   - Update email, phone, and location
   - Customize contact form fields if needed

### Styling

Modify [`styles.css`](styles.css) to change:

- **Colors** - Update CSS variables at the top of the file (Lines 7-20)
- **Fonts** - Change the Google Fonts import in [`index.html`](index.html) (Line 11)
- **Layout** - Adjust spacing, sizing, and responsive breakpoints
- **Animations** - Customize animation durations and effects

### Functionality

Edit [`script.js`](script.js) to modify:

- Navigation behavior
- Animation triggers
- Form submission handling
- Interactive features

## 🎨 Color Scheme

The default color scheme uses:

- **Primary**: `#6366f1` (Indigo)
- **Secondary**: `#ec4899` (Pink)
- **Accent**: `#14b8a6` (Teal)

To change colors, update the CSS variables in [`styles.css`](styles.css:7-20):

```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #ec4899;
    --accent-color: #14b8a6;
    /* ... other variables */
}
```

## 📱 Sections Overview

1. **Navigation** - Fixed navbar with smooth scroll links
2. **Hero** - Eye-catching introduction with animated background
3. **About** - Personal bio with animated statistics
4. **Projects** - Filterable project showcase featuring 4 AI Agent projects:
   - **Text to SQL Agent** - Converts natural language to SQL queries
   - **Data Analysis Agent** - Automated data insights and visualization
   - **Intelligent AI Personal Assistant** - Voice-enabled task automation
   - **Email Assistant AI Agent** - Smart email management system
5. **Skills** - Animated skill bars showing proficiency
6. **Contact** - Contact information and form
7. **Footer** - Social links and copyright

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript (Vanilla)** - No frameworks required
- **Font Awesome** - Icon library
- **Google Fonts** - Inter font family

## 📦 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # JavaScript functionality
└── README.md          # Documentation
```

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 💡 Tips

1. **Images**: Replace the placeholder icons with actual project screenshots
2. **SEO**: Update meta tags in the `<head>` section
3. **Analytics**: Add Google Analytics or similar tracking
4. **Performance**: Optimize images before uploading
5. **Accessibility**: Ensure all interactive elements are keyboard accessible

## 🔧 Advanced Customization

### AI Agent Projects

The portfolio showcases 4 advanced AI agent projects:

1. **Text to SQL Agent**
   - Technologies: Python, LangChain, SQL, OpenAI
   - Converts natural language queries into SQL statements
   - Repository: [text-to-sql-agent](https://github.com/vamshi12455/text-to-sql-agent)

2. **Data Analysis Agent**
   - Technologies: Python, Pandas, AI, Visualization
   - Performs automated data analysis and generates insights
   - Repository: [data-analysis-agent](https://github.com/vamshi12455/data-analysis-agent)

3. **Intelligent AI Personal Assistant**
   - Technologies: Python, NLP, Voice AI, LLM
   - Voice-enabled assistant with task automation
   - Repository: [ai-personal-assistant](https://github.com/vamshi12455/ai-personal-assistant)

4. **Email Assistant AI Agent**
   - Technologies: Python, AI, IMAP, Automation
   - Smart email categorization and response automation
   - Repository: [email-assistant-agent](https://github.com/vamshi12455/email-assistant-agent)

### Adding More Projects

To add more projects, copy a project card block in [`index.html`](index.html) and paste it within the `projects-grid` div:

```html
<div class="project-card" data-category="ai">
    <!-- Project content here -->
</div>
```

### Custom Domain

To use a custom domain with GitHub Pages:

1. Add a `CNAME` file with your domain name
2. Configure DNS settings with your domain provider
3. Enable HTTPS in GitHub Pages settings

### Contact Form Integration

The contact form currently shows an alert. To make it functional:

1. Use a service like [Formspree](https://formspree.io/) or [Netlify Forms](https://www.netlify.com/products/forms/)
2. Update the form action in [`index.html`](index.html)
3. Or implement a backend API endpoint

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 👤 Author

**Your Name**

- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Your Name](https://linkedin.com/in/yourprofile)
- Email: your.email@example.com

## ⭐ Show Your Support

Give a ⭐️ if you like this project!

---

**Note**: Remember to replace all placeholder content with your actual information before deploying!