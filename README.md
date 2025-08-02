# Hilda Chepkirui - Portfolio Website

A responsive, modern portfolio website showcasing the work and skills of Hilda Chepkirui, an Electronic and Computer Engineer with expertise in web development, embedded systems, and automation.

## 🚀 Features

- **Fully Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Pure HTML & CSS**: No JavaScript dependencies for optimal performance and accessibility
- **Modern Design**: Clean, professional layout with smooth hover effects and transitions
- **Interactive Navigation**: CSS-only mobile hamburger menu
- **Tabbed Content**: Pure CSS tab functionality for work experience and education sections
- **Contact Form**: Functional contact form with proper validation
- **Skills Showcase**: Visual skill cards with hover effects
- **Project Portfolio**: Highlighted projects with detailed descriptions
- **Social Media Integration**: Links to professional profiles

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # Main stylesheet
├── README.md          # Project documentation
├── images/            # Image assets
│   ├── profile.jpg
│   ├── html5.png
│   ├── css3.png
│   ├── python.png
│   ├── matlab.png
│   ├── github.png
│   ├── pcb_design.jpg
│   ├── embedded_systems.jpg
│   ├── plc_scada.jpg
│   ├── smarthome.jpg
│   ├── fourwheel.jpg
│   ├── greenhouse.jpg
│   ├── ai.jpg
│   ├── robotics.jpg
│   ├── embedded.jpg
│   ├── devops.jpg
│   ├── hiking.jpg
│   ├── phone.png
│   ├── gmail.png
│   ├── address.png
│   ├── x.png
│   └── linkedin.png
└── docs/
    └── Hilda_CV.pdf    # CV download
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with:
  - CSS Grid and Flexbox for layouts
  - CSS Custom Properties (variables)
  - CSS Transitions and Transforms
  - Media Queries for responsiveness
  - CSS-only interactive components

## 🌐 Hosting Options

This portfolio can be hosted on several platforms. Here's a comparison of the top options:

### GitHub Pages (Recommended ✅)
**Why we chose GitHub Pages:**
- **Free hosting** for public repositories
- **Automatic HTTPS** and custom domain support
- **Direct integration** with GitHub repositories
- **Simple deployment** - just push your code
- **Perfect for static sites** like this portfolio
- **Reliable** and backed by GitHub's infrastructure

**Pros:**
- Completely free with generous bandwidth
- Easy version control integration
- No build process needed for static sites
- Great for portfolios and personal websites

**Cons:**
- Only supports static sites (no server-side processing)
- Public repositories required for free tier
- Limited to 1GB storage

### Alternative Options

#### Netlify
**Best for:**
- Sites with forms (built-in form handling)
- Projects needing serverless functions
- Advanced deployment features like branch previews
- A/B testing capabilities

#### Vercel
**Best for:**
- Next.js and React applications
- Sites requiring edge functions
- Advanced performance optimization
- Image optimization features

## 🚀 Deployment to GitHub Pages

Follow these steps to host your portfolio on GitHub Pages:

### Step 1: Create GitHub Repository
1. Sign in to [GitHub](https://github.com)
2. Click "New repository" (green button or + icon)
3. Name your repository (e.g., "portfolio-website")
4. Make it **Public** (required for free GitHub Pages)
5. Don't initialize with README, .gitignore, or license
6. Click "Create repository"

### Step 2: Upload Your Files
**Option A: Web Upload (Easiest)**
1. On your empty repository page, click "uploading an existing file"
2. Drag and drop all your portfolio files or click "choose your files"
3. Ensure your main file is named `index.html`
4. Add commit message: "Initial portfolio upload"
5. Click "Commit changes"

**Option B: Git Commands**
```bash
# Navigate to your portfolio folder
cd path/to/your/portfolio

# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial portfolio upload"

# Add remote repository
git remote add origin https://github.com/yourusername/repository-name.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click the "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click "Save"

### Step 4: Access Your Live Site
- GitHub will provide your URL: `https://yourusername.github.io/repository-name`
- Wait 5-10 minutes for the site to go live
- Any future commits will automatically update your live site

### Custom Domain (Optional)
To use a custom domain like `hildachepkirui.com`:
1. Add a `CNAME` file to your repository root
2. Put your domain name in the file (no http://)
3. Configure DNS settings with your domain provider
4. Update domain in repository Settings > Pages

## 📱 Responsive Design

The portfolio is designed with a mobile-first approach and includes:

- **Desktop**: Full layout with horizontal navigation
- **Tablet**: Adapted grid layouts for medium screens
- **Mobile**: Collapsible hamburger menu and stacked layouts

### Breakpoints:
- Mobile: `max-width: 480px`
- Tablet: `max-width: 768px`
- Desktop: `max-width: 1024px` and above

## 🎨 Design Features

### Color Scheme
- **Primary**: Dark Green (`#14532d`)
- **Secondary**: Amber (`#ca8a04`)
- **Accent**: Pink (`#fbcfe8`)
- **Text**: Dark Gray (`#1f2937`)
- **Background**: Off-white (`#fdfdfd`)

### Interactive Elements
- **Hover Effects**: All cards and buttons include smooth hover transitions
- **Mobile Menu**: CSS-only hamburger menu with smooth animations
- **Tab Navigation**: Pure CSS tab switching for journey section
- **Form Validation**: HTML5 form validation with custom styling

## 🔧 Setup and Installation

1. **Clone or Download** the project files
2. **Create Directory Structure**: 
   ```
   portfolio/
   ├── index.html
   ├── css/
   │   └── styles.css
   ├── images/
   └── docs/
   ```
3. **Prepare Images**: Add all required images to the `images/` folder
4. **Add CV**: Place your CV file in the `docs/` folder as `Hilda_CV.pdf`
5. **Test Locally**: Open `index.html` in your web browser
6. **Deploy**: Follow the GitHub Pages deployment steps above

### Required Images:
- `profile.jpg` - Main profile photo
- Technology icons: `html5.png`, `css3.png`, `python.png`, `matlab.png`, `github.png`
- Engineering icons: `pcb_design.jpg`, `embedded_systems.jpg`, `plc_scada.jpg`
- Project images: `smarthome.jpg`, `fourwheel.jpg`, `greenhouse.jpg`
- Interest images: `ai.jpg`, `robotics.jpg`, `embedded.jpg`, `devops.jpg`, `hiking.jpg`
- Contact icons: `phone.png`, `gmail.png`, `address.png`, `x.png`, `linkedin.png`

## 📝 Customization

### Personal Information
Update the following sections in `index.html`:

1. **Meta Tags**: Update title and description
2. **About Section**: Modify personal introduction and links
3. **Skills Section**: Update skill levels and add/remove technologies
4. **Projects Section**: Replace with your own projects
5. **Experience/Education**: Update with your background
6. **Contact Information**: Update phone, email, and social links

### Styling
Modify CSS custom properties in the `:root` section of `styles.css` to change:
- Color scheme
- Fonts
- Spacing
- Animation timing

## 🌟 Key Sections

### 1. Hero/About Section
- Professional introduction
- Action buttons (Contact, Portfolio, GitHub, CV Download)
- Professional headshot

### 2. Skills Section
- Visual skill cards with icons
- Skill ratings with star system
- Hover effects and animations

### 3. Projects Section
- Featured project showcase
- Project descriptions and technologies used
- Responsive grid layout

### 4. Journey Section
- Tabbed interface for Work Experience and Education
- Timeline-style cards
- Pure CSS tab switching

### 5. Interests Section
- Personal interests with circular images
- Hobby descriptions
- Responsive grid layout

### 6. Contact Section
- Contact form with validation
- Contact information
- Social media links

## 📧 Contact Form

The contact form includes:
- Client-side HTML5 validation
- Required field indicators
- Responsive design
- Custom styling

**Note**: To make the form functional, you'll need to:
1. Set up a backend service (PHP, Node.js, etc.)
2. Update the `action` attribute in the form tag
3. Add server-side form processing

## 🎯 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Brave
- Mobile browsers

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👩‍💻 Author

**Hilda Chepkirui**
- Electronic and Computer Engineer
- GitHub: [@Hilda-Baraiywo](https://github.com/Hilda-Baraiywo)
- Email: baraiywohilda181@gmail.com

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you make improvements that could benefit others, pull requests are welcome!

## 📝 Notes

- All animations and interactions are CSS-only (no JavaScript)
- Images should be optimized for web use
- Test thoroughly on different devices and browsers
- Consider adding a favicon for better branding
- Ensure proper file structure with separate CSS file
- GitHub Pages may take 5-10 minutes to reflect changes after commits