# Serenity Wellness - Spiritual & Wellness Services Website

A warm, old-fashioned styled website for spiritual and wellness services built with HTML, CSS, and DaisyUI components.

## Features

- 🌅 Warm, old-fashioned design with earthy color palette
- 📱 Fully responsive design for all devices
- 🎨 DaisyUI components with custom styling
- 🖼️ Placeholder images from Unsplash
- 📝 Contact form and service information
- ⭐ Client testimonials section
- 🔗 Social media integration

## Technologies Used

- HTML5
- CSS3 with custom styling
- [DaisyUI](https://daisyui.com/) - Tailwind CSS component library
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- Google Fonts (Playfair Display & Crimson Text)

## GitHub Pages Deployment

To deploy this site to GitHub Pages:

1. **Push to GitHub Repository**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Serenity Wellness website"
   git branch -M main
   git remote add origin https://github.com/yourusername/your-repo-name.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click on "Settings" tab
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Select "main" branch and "/ (root)" folder
   - Click "Save"

3. **Access Your Site**
   - Your site will be available at: `https://yourusername.github.io/your-repo-name`
   - It may take a few minutes for the site to become available

## Customization

### Colors
The warm color palette is defined in `styles.css`:
- Primary: Warm amber (#d97706)
- Secondary: Warm brown (#dc8a52)
- Accent: Golden yellow (#f59e0b)
- Base: Cream tones

### Content
- Update the service descriptions in the Services section
- Replace placeholder images with actual photos
- Modify contact information in the Contact section
- Update testimonials with real client feedback

### Images
Current placeholder images are from Unsplash. Replace with:
- Professional photos of the practitioner
- Images of the wellness space/studio
- Service-specific imagery
- Authentic testimonial photos

## File Structure

```
├── index.html          # Main HTML file
├── styles.css          # Custom CSS styling
└── README.md          # This file
```

## Making the Contact Form Work

The contact form is configured to use **Web3Forms**, a reliable service for static websites:

### Web3Forms Setup (Current Configuration)
1. Go to [web3forms.com](https://web3forms.com)
2. Sign up for a free account (100 submissions/month)
3. Get your access key from the dashboard
4. Replace `YOUR_ACCESS_KEY` in `index.html` with your actual access key
5. Deploy to GitHub Pages - form submissions will be emailed to you

**Features:**
- ✅ No server required
- ✅ Spam protection included
- ✅ Email notifications
- ✅ Works with GitHub Pages
- ✅ Custom redirect pages supported
- ✅ File uploads supported

### Alternative Options
If you prefer different services:

- **Formspree**: Another popular option with similar features
- **Netlify Forms**: If deploying to Netlify instead of GitHub Pages
- **EmailJS**: JavaScript-based email sending
- **Google Forms**: Simple but loses custom styling

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)
- Responsive design works on all screen sizes

## License

This project is open source and available under the [MIT License](LICENSE).