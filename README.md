# NASH Services - Professional Property & Eviction Services Portal

Modern web portal for NASH Services - a professional property management and eviction services company.

## ✨ Features

- **Responsive Design**: Mobile-friendly layout using Tailwind CSS
- **Service Portfolio**: 6 professional services with pricing
  - Trash Removal ($150)
  - Eviction Services ($2,500) - Most Requested
  - Hoarding Cleanup ($3,000+)
  - Debris Removal ($250+)
  - Estate Cleanout ($1,500+)
  - Biohazard Cleanup ($2,000+)
- **Video Backgrounds**: Hero and form sections with looping video backgrounds
- **Firebase Integration**: Secure authentication and database for service requests
- **Client Portal**: Authenticated dashboard for service tracking
- **Service Request Form**: Easy quote request submission
- **Professional Branding**: Red and white color scheme with trash icon logo

## 🚀 Getting Started

### Prerequisites
- Python 3.6+ (for local server)
- Web browser with HTML5 video support

### Installation

1. Clone the repository:
```bash
cd /workspaces/Nash_Services-
```

2. Start the development server:
```bash
python3 -m http.server 8000
```

3. Open in browser:
```
http://localhost:8000
```

## 📁 Project Structure

```
Nash_Services-/
├── index.html          # Main portal page
├── package.json        # Project metadata
├── README.md           # This file
├── .gitignore          # Git exclusions
└── videos/
    ├── bg-1.mp4        # Hero section background (add your video)
    ├── bg-2.mp4        # Request form section background (add your video)
    └── README.md       # Video setup instructions
```

## 🎥 Adding Background Videos

Two MP4 video files are needed:

1. **bg-1.mp4** - Hero section background
2. **bg-2.mp4** - Service request form section background

Place these files in the `/videos` directory. See `videos/README.md` for detailed specifications.

## 🔐 Authentication

The portal uses Firebase for secure authentication. Current demo credentials:
- Email: `user@example.com`
- Password: Set through Firebase Console

## 📝 Service Request Data

Service requests are stored in Firebase Firestore with the following fields:
- Client Name
- Email Address
- Phone Number
- Service Needs Description
- Submission Timestamp
- Status (Pending Quote)

## 🎨 Customization

### Colors
- Primary: Red (#DC2626)
- Background: Slate (#F1F5F9)
- Logo Icon: Trash can (Font Awesome)

### Modify Services
Edit the services grid in `index.html` to add/remove/update services.

### Update Admin Link
Change the admin portal URL in the top bar:
```html
<button onclick="window.open('https://your-admin-url.com', '_blank')">View Admin</button>
```

## 🚀 Deployment

### Deploy to GitHub Pages
```bash
git add .
git commit -m "Update NASH Services portal"
git push origin main
```

### Deploy to Web Server
1. Copy all files to your web server
2. Ensure Firebase credentials are correct
3. Videos must be served from `/videos/` directory

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **Tailwind CSS**: Responsive styling
- **Font Awesome**: Icon library
- **Firebase**: Authentication & Firestore database
- **JavaScript**: Client-side interactivity

## 📞 Support

For Firebase setup or deployment questions, refer to the Firebase documentation at https://firebase.google.com/docs

## 📄 License

See LICENSE file for details.

---

**Last Updated**: June 5, 2026

Template of nash services 
