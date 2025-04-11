# Personal-Portfolio-Improved-UI
# 💼 Vijayalakshmi M - Personal Portfolio Website

Welcome to my personal portfolio website! This site highlights my education, projects, certifications, skills, and experience in the field of Artificial Intelligence and Machine Learning.

## 🔗 Live Demo

You can view the live website here: [https://your-username.github.io/your-repo-name](https://your-username.github.io/your-repo-name)  

---

## 📁 Project Structure
portfolio/ ├── index.html # Main homepage with profile and sections 
           ├── contact.html # Contact page with working contact form (via EmailJS) 
           ├── resume.pdf # Resume file (linked for download)
           ├── profile.JPG # Profile picture 
           ├── README.md # This file 
           └── other assets (if any)
## 🛠️ Built With

- HTML5
- Tailwind CSS
- JavaScript (EmailJS integration)
- [EmailJS](https://www.emailjs.com/) – For sending form submissions to your email

---

## ✉️ Contact Form Setup

The contact form uses EmailJS to send messages directly to your email. Make sure to:

1. Sign up at [EmailJS](https://www.emailjs.com/).
2. Create a service, email template, and get your:
   - Service ID
   - Template ID
   - Public Key (User ID)
3. Replace the placeholders in `contact.html`:
   ```javascript
   emailjs.init("YOUR_PUBLIC_KEY");
   emailjs.sendForm("YOUR_SERVICE_ID", "YOUR_TEMPLATE_ID", form)
