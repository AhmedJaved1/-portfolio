
**
Portfolio Website - Full Stack Developer & AI Specialist**
A clean, professional portfolio website showcasing full-stack development and AI/ML projects. Built with pure HTML, CSS, and JavaScript - no frameworks required.
🌟 Features

Responsive Design - Works seamlessly on desktop, tablet, and mobile devices
Professional Layout - Clean, minimalist design focused on content
Interactive Project Gallery - Click to view detailed project information
Fullscreen Image Preview - Click project images to view in fullscreen
Smooth Navigation - Sticky navigation bar for easy access to all sections
Contact Section - Multiple ways for potential clients to reach you

📋 Sections

Header - Profile photo and professional introduction
About Me - Professional background and expertise overview
Why Choose Me - 6 compelling reasons highlighting your unique value
Technical Skills - Organized by Frontend, Backend, Databases, and AI/ML
Projects Portfolio - Interactive project showcase with detailed views
Contact - Links to email, LinkedIn, GitHub, and WhatsApp

🚀 Getting Started
Installation

Download the HTML file
Save it as index.html in your desired folder
Open with any modern web browser

No build process, dependencies, or server required!
Customization
1. Personal Information
Replace the following placeholders:
html<!-- Header Section -->
<h1>[Your Name]</h1>

<!-- Footer -->
<p>&copy; 2025 [Your Name]...</p>
2. Profile Image
Replace the placeholder image URL in the header:
html<img src="https://via.placeholder.com/150" alt="Your Photo" class="profile-image">
Change to:
html<img src="path/to/your-photo.jpg" alt="Your Photo" class="profile-image">
3. Contact Links
Update contact information in the Contact section:
html<a href="mailto:your.email@example.com" class="contact-link">Email</a>
<a href="https://linkedin.com/in/yourprofile" class="contact-link">LinkedIn</a>
<a href="https://github.com/yourusername" class="contact-link">GitHub</a>
<a href="https://wa.me/92XXXXXXXXXX" class="contact-link">WhatsApp</a>
4. Project Images
Find the projectsData array in the JavaScript section and update image URLs:
javascript{
    title: "Your Project Name",
    description: "Project description here",
    images: [
        "path/to/image1.jpg",
        "path/to/image2.jpg",
        "path/to/image3.jpg"
    ],
    features: [
        "Feature 1",
        "Feature 2",
        "Feature 3"
    ]
}
5. Skills
Update the skills section to match your expertise:
html<div class="skill-category">
    <h3>Frontend Development</h3>
    <ul>
        <li>Your Skill 1</li>
        <li>Your Skill 2</li>
        <!-- Add more skills -->
    </ul>
</div>
6. Project Thumbnails
Update project card images in the Projects section:
html<img src="path/to/thumbnail.jpg" alt="Project Name">
```

## 📁 File Structure
```
portfolio/
│
├── index.html          # Main portfolio file (all-in-one)
│
└── images/            # Your images folder (create this)
    ├── profile.jpg
    ├── project1-thumb.jpg
    ├── project1-1.jpg
    ├── project1-2.jpg
    ├── project1-3.jpg
    └── ...
🎨 Color Scheme
The portfolio uses a professional blue-gray color scheme:

Primary: #2c3e50 (Dark blue-gray)
Secondary: #34495e (Medium gray)
Accent: #3498db (Bright blue)
Background: #f5f5f5 (Light gray)
Text: #333 (Dark gray)

To change colors, update the CSS color values throughout the stylesheet.
💡 Usage Tips
Adding New Projects

Add project thumbnail in the Projects section HTML
Add project data to projectsData array in JavaScript
Update the onclick handler with the correct index number

Image Recommendations

Profile Photo: 150x150px (square, professional headshot)
Project Thumbnails: 300x200px (3:2 ratio)
Project Detail Images: 400x300px or larger (4:3 ratio recommended)
Format: JPG or PNG
Optimize: Compress images for faster loading

Best Practices

Keep descriptions concise and professional
Use high-quality project screenshots
Update skills regularly as you learn new technologies
Test responsiveness on multiple devices
Proofread all content before publishing

🌐 Deployment
GitHub Pages (Free)

Create a GitHub repository
Upload your index.html and images folder
Go to Settings → Pages
Select main branch as source
Your site will be live at https://yourusername.github.io/repository-name

Netlify (Free)

Sign up at netlify.com
Drag and drop your project folder
Get instant deployment with custom domain support

Traditional Web Hosting
Upload all files via FTP to your hosting provider's public_html folder.
📱 Browser Support

Chrome (recommended)
Firefox
Safari
Edge
Opera

Works on all modern browsers with JavaScript enabled.
🔧 Troubleshooting
Images not showing?

Check file paths are correct
Ensure images are in the same directory or correct folder
Use relative paths: ./images/photo.jpg

Modal not opening?

Ensure JavaScript is enabled in browser
Check console for errors (F12)
Verify onclick handlers are properly set

Layout issues on mobile?

Clear browser cache
Test in browser's device emulation mode
Check viewport meta tag is present

📄 License
This portfolio template is free to use for personal and commercial projects. No attribution required.
🤝 Contributing
Feel free to customize and improve this template for your needs!
📞 Support
For questions or issues, please contact through the portfolio contact section.

✨ Quick Start Checklist

 Replace [Your Name] with your actual name
 Upload and link your profile photo
 Update all contact links (email, LinkedIn, GitHub, WhatsApp)
 Add your project images
 Update project descriptions and features
 Customize skills section
 Update About Me section
 Test all links and functionality
 Test responsiveness on mobile devices
 Deploy to hosting platform


Version: 1.0
Last Updated: October 2025
Created For: Full Stack Developers & AI Specialists
