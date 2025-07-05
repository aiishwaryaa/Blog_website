# 🚀 Flask Blog with Dark Theme & Animations

A beautiful, modern blog website built with Flask, featuring a stunning dark theme with animated particles and smooth interactions.

## ✨ Features

- **🎨 Dark Theme**: Modern cyberpunk-inspired design with gradient backgrounds
- **✨ Animations**: Floating particles, glowing effects, and smooth transitions
- **🔐 User Authentication**: Secure login/signup system with password hashing
- **📝 CRUD Operations**: Create, Read, Update, Delete blog posts
- **🎭 Interactive UI**: Hover effects, animations, and responsive design
- **📱 Bootstrap**: Mobile-responsive design
- **🔒 Security**: User authorization for post management

## 🛠️ Technologies Used

- **Backend**: Python Flask
- **Database**: SQLite with SQLAlchemy ORM
- **Authentication**: Flask-Login
- **Frontend**: HTML5, CSS3, JavaScript
- **Styling**: Bootstrap 5 + Custom CSS
- **Icons**: Font Awesome 6

## 🚀 Quick Start

### Prerequisites
- Python 3.7 or higher
- pip (Python package installer)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/flask-blog.git
   cd flask-blog
   ```

2. **Create virtual environment**
   ```bash
   python -m venv venv
   ```

3. **Activate virtual environment**
   - **Windows:**
     ```bash
     venv\Scripts\activate
     ```
   - **macOS/Linux:**
     ```bash
     source venv/bin/activate
     ```

4. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

5. **Run the application**
   ```bash
   python app.py
   ```

6. **Open your browser**
   Navigate to `http://127.0.0.1:5000/`

## 📁 Project Structure

```
flask-blog/
├── app.py                 # Main Flask application
├── requirements.txt       # Python dependencies
├── README.md             # Project documentation
├── .gitignore            # Git ignore file
├── templates/            # HTML templates
│   ├── index.html        # Home page
│   ├── login.html        # Login page
│   ├── signup.html       # Signup page
│   ├── create.html       # Create post page
│   └── edit.html         # Edit post page
└── blog.db               # SQLite database (created automatically)
```

## 🎨 Design Features

### Animations
- **Floating Particles**: 50 animated particles in the background
- **Glowing Text**: Pulsing glow effects on headings
- **Fade-in Effects**: Smooth entrance animations for cards
- **Hover Transitions**: Interactive button and card animations
- **Staggered Loading**: Cascading animation for blog posts

### Color Scheme
- **Primary**: Cyan (#00d4ff) for highlights and glow
- **Background**: Dark gradient (deep blues and purples)
- **Text**: White and light gray
- **Accents**: Various gradients for buttons and effects

## 🔧 Configuration

### Environment Variables
The application uses a simple configuration. For production, consider setting:
- `SECRET_KEY`: Change the default secret key in `app.py`
- `DATABASE_URL`: Use a production database instead of SQLite

### Customization
- Modify colors in the CSS variables
- Adjust animation speeds in the CSS keyframes
- Change particle count in the JavaScript functions

## 🚀 Deployment

### Local Development
```bash
python app.py
```

### Production Deployment
For production, consider using:
- **WSGI Server**: Gunicorn or uWSGI
- **Web Server**: Nginx or Apache
- **Database**: PostgreSQL or MySQL
- **Environment**: Docker or cloud platforms

## 📝 Usage

1. **Sign Up**: Create a new account
2. **Login**: Access your account
3. **Create Posts**: Write and publish blog posts
4. **Edit Posts**: Modify your existing posts
5. **Delete Posts**: Remove posts you no longer want
6. **View Posts**: Browse all published posts

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Flask community for the excellent framework
- Bootstrap team for the responsive CSS framework
- Font Awesome for the beautiful icons
- CSS animation inspirations from modern web design trends

---

**Made with ❤️ and lots of ☕** 