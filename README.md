# V² Labs - Landing Page

Modern landing page for V² Labs, showcasing AI-powered process automation services.

## 🚀 Features

- **Modern Design**: Clean, professional layout with smooth animations
- **Responsive**: Mobile-first design that works on all devices  
- **Fast Loading**: Uses Tailwind CSS via CDN for optimal performance
- **Interactive**: Scroll animations and hover effects for better UX
- **Contact Integration**: Direct WhatsApp integration for easy communication

## 🛠 Tech Stack

- HTML5
- CSS3 (with Tailwind CSS)
- Vanilla JavaScript
- Docker for deployment

## 📦 Deployment

### Local Development
Simply open `index.html` in your browser.

### Docker Deployment

1. **Build the Docker image**:
   ```bash
   docker build -t v2-labs-landing .
   ```

2. **Run the container**:
   ```bash
   docker run -p 8080:80 v2-labs-landing
   ```

The site will be available at `http://localhost:8080`

### Production Deployment

This Docker container can be deployed to any container platform:
- **Heroku**: Using container registry
- **AWS ECS/Fargate**: Container deployment
- **DigitalOcean App Platform**: Docker deployment
- **Google Cloud Run**: Serverless container deployment
- **Netlify/Vercel**: Static site deployment (just the HTML file)

## 🎨 Customization

The design uses a dark theme with red accents. Key colors:
- Background: `#0A0A0A` (near black)
- Primary text: `#E2E8F0` (light gray)
- Accent: `#DC2626` (red)

## 📞 Contact

The site includes direct WhatsApp integration via the contact buttons.

---

© 2024 V² Labs. All rights reserved.