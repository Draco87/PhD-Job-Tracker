# 🎓 PhD & Job Application Tracker

A clean, modern, and self-hosted web application to organize the stressful process of applying for PhD programs and jobs. This tool provides a visual dashboard to keep track of every application's status, deadlines, and important links, with all your data stored securely in your own personal cloud database.

---

## ✨ Key Features

- **Visual Kanban Board**: View your applications in *To Apply*, *Applied*, and *Archived* columns for a clear overview of your progress.  
- **Multi-Tracking**: Easily switch between dedicated views for your PhD, job and Scholarships applications with a single click.  
- **Deadline Highlighting**: Applications with deadlines approaching within a week are automatically highlighted in yellow; overdue ones in red to help you prioritize.  
- **Confetti Celebration**: Enjoy a satisfying burst of confetti every time you mark an application as "Applied"!  
- **Cloud-Based & Persistent**: Data is saved in real-time to your personal Firebase Firestore database, ensuring it's always up-to-date.  
- **Access Anywhere**: As a web app, it's accessible from any device—laptop, tablet, or phone.  
- **Fully Responsive**: Built with Tailwind CSS to look and work great on any screen size.

---

## 🛠️ Tech Stack

**Frontend**  
- HTML5  
- Tailwind CSS  
- JavaScript  

**Backend & Database**  
- Firebase (Authentication & Firestore)

**Libraries**  
- `day.js` (date handling)  
- `canvas-confetti` (celebration animation)

---

## 🚀 Getting Started

You can easily host your own version of this tracker for free.

1. **Create a Firebase Project**  
   Follow the official [Firebase guide](https://firebase.google.com/docs/web/setup) to create a new project and enable **Anonymous Authentication**.

2. **Get Config Keys**  
   Go to your Firebase project settings and copy the `firebaseConfig` object.

3. **Update the Code**  
   Open the `index.html` file and paste your `firebaseConfig` keys into the designated section.

4. **Deploy for Free**  
   Upload the `index.html` file to a static hosting provider like [GitHub Pages](https://pages.github.com/) or [Netlify](https://www.netlify.com/).

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
