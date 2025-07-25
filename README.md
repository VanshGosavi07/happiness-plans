
# 🌐 Happiness Plans – Professional Travel & Event Management Website

> A modern, responsive website built for *Happiness Plans*, a professional travel & event management company based in Indore, Madhya Pradesh. This is a production-ready Flask web application designed with modern web development practices and ready for deployment on Vercel.

---

## 📌 Project Overview

**Happiness Plans Website** is a fully responsive and elegant Flask-powered web application featuring:

- **Modern UI** using Bootstrap 5 with custom styling
- **Fully functional Contact Form** with Gmail SMTP integration
- **Mobile-first responsive design** optimized for all devices
- **Professional sections**: Hero, Features, Services, About, Testimonials, Contact
- **Interactive Google Maps** with custom markers and animations
- **Production-ready** with Vercel deployment configuration
- **Email functionality** using Gmail SMTP for contact form submissions

---

## 🎯 Features

✔️ **Modern Landing Page**  
✔️ **Sticky Navbar with Smooth Scroll**  
✔️ **Animated Hero, Features, and Service Cards**  
✔️ **Fully Functional Contact Form with Email Sending (SMTP)**  
✔️ **Responsive Google Maps Embed + Marker Effects**  
✔️ **Testimonials & Trust Metrics**  
✔️ **Read More Toggle Effects for Sections**  
✔️ **404 & 500 Error Handlers**

---

## 🛠️ Tech Stack

| Layer       | Technology                       |
|-------------|-----------------------------------|
| Frontend    | HTML5, Bootstrap 5, CSS3, JS      |
| Backend     | Python Flask                      |
| Form Emails | Python `smtplib` with Gmail SMTP  |
| Templating  | Jinja2                            |
| Icons       | Font Awesome, Bootstrap Icons     |
| Fonts       | Google Fonts (Poppins, Open Sans) |

---

## 🗂️ Folder Structure

```
happiness_plans/
├── app.py                 # Flask app + Email logic
├── wsgi.py               # WSGI entry point for Vercel deployment
├── vercel.json           # Vercel deployment configuration
├── templates/
│   └── index.html         # Main landing page
├── requirements.txt       # Python packages
└── README.md              # Project documentation
```

---

## 🚀 Installation & Usage

### Local Development

#### 1. Clone the Repository
```bash
git clone https://github.com/VanshGosavi07/happiness-plans.git
cd happiness-plans
```

#### 2. Create and Activate Virtual Environment
```bash
python -m venv venv
# Windows:
venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate
```

#### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

#### 4. Run the Application
```bash
python app.py
```

🔗 Visit: [http://localhost:5000](http://localhost:5000)

### Vercel Deployment

This project is configured for easy deployment on Vercel:

#### 1. Fork/Clone this repository to your GitHub account

#### 2. Connect your GitHub repository to Vercel:
- Go to [vercel.com](https://vercel.com)
- Sign up/Login with GitHub
- Import your repository
- Vercel will automatically detect the configuration from `vercel.json`

#### 3. Set Environment Variables (Optional):
- Add any environment variables in Vercel dashboard if needed
- The app works without additional environment variables

#### 4. Deploy:
- Vercel will automatically build and deploy your application
- You'll get a live URL for your deployed website

🔗 **Live Demo**: [Coming Soon - Deploy to see your live URL]

---

## ✉️ Contact Form Email Setup

The contact form uses **Gmail SMTP** for sending emails:

- **SMTP Server**: `smtp.gmail.com`
- **Port**: `587`
- **From Address**: `sukheshdasari@gmail.com`

### To customize email settings:
1. Open `app.py`
2. Update `SENDER_EMAIL` and `SENDER_PASSWORD` with your Gmail credentials
3. Use Gmail [App Password](https://myaccount.google.com/apppasswords) for enhanced security
4. For production deployment, consider using environment variables for sensitive data

---

## 📋 Sections Included

- 🏠 **Home** – Hero with call-to-action buttons  
- 💡 **Features** – Why choose us  
- 🛎️ **Services** – Travel, Event, Destination weddings  
- 👨‍💼 **About Us** – Mission, team, values  
- ⭐ **Testimonials** – Client feedback  
- 🗺️ **Contact** – Address, Map, and Email Form  
- 🔻 **Footer** – Quick links, contact info, social media

---

## ✅ Requirements

- **Python 3.7+**  
- **Flask**  
- **Internet connection** (for CDN assets & map loading)
- **Gmail Account** (for contact form functionality)
- **Vercel Account** (for deployment - free tier available)

---

## 🔒 Security & Production Notes

- **Email Configuration**: Uses Gmail App Password for secure authentication
- **Environment Variables**: Consider using environment variables for sensitive data in production
- **HTTPS**: Vercel automatically provides SSL certificates for deployed applications
- **Google Maps**: Embedded via iframe for security and performance
- **Form Validation**: Both client-side and server-side validation implemented
- **Error Handling**: Comprehensive error handling for 404 and 500 errors

## 🚀 Deployment Features

- **Zero-config deployment** on Vercel
- **Automatic SSL** certificate
- **Global CDN** distribution
- **Serverless functions** for optimal performance
- **Custom domain** support (optional)

---

## 📬 Project Summary

| Feature                  | Implementation                           |
|--------------------------|------------------------------------------|
| ✅ **Frontend**          | HTML5, Bootstrap 5, CSS3, JavaScript    |
| ✅ **Backend**           | Python Flask with WSGI                  |
| ✅ **Deployment**        | Vercel-ready with `vercel.json`         |
| ✅ **Sections**          | Home, About, Services, Contact, Email   |
| ✅ **Features**          | Animations, Contact Form, Google Map    |
| ✅ **Hosting**           | Vercel (Production) + Local Development |
| ✅ **Email Service**     | Gmail SMTP integration                   |
| ✅ **Responsive**        | Mobile-first design approach            |

## 🌟 Live Demo & Repository

🔗 **GitHub Repository**: [https://github.com/VanshGosavi07/happiness-plans](https://github.com/VanshGosavi07/happiness-plans)  
🚀 **Live Website**: [Deploy to Vercel to get your live URL]

### Quick Deploy to Vercel:
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/VanshGosavi07/happiness-plans)

---

## 🙋 Author & Contact

**Developed by Vansh Sambhaji Gosavi**

📧 **Email**: [vanshgosavi7official@gmail.com](mailto:vanshgosavi7official@gmail.com)  
📞 **Phone**: +91 9359775740  
🌐 **Portfolio**: [github.com/VanshGosavi07](https://github.com/VanshGosavi07)  
💼 **LinkedIn**: [Connect on LinkedIn](https://linkedin.com/in/vanshgosavi07)

---

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

🚀 **Ready for production deployment on Vercel!** ⚡
