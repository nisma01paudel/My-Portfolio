# Nisma Paudel Portfolio

A personal portfolio website built with **React (Create React App) and Node/Express backend**, showcasing projects, tech stack, education, and work experience.  

**Live site:** [https://paudelnisma.com.np](www.paudelnisma.com.np)

---

## Features

- Home, About, Education, Tech Stack, Projects, Work Experience, and Contact sections  
- Fully responsive design for desktop and mobile  
- Interactive project showcase with live links and source code  
- Backend API for contact form (using Nodemailer and SendGrid)  
- Built with the MERN stack: **MongoDB, Express, React, Node.js**  
- Deployed on **Render** with custom domain support  

---

## Tech Stack

**Frontend:** React, HTML, CSS/SCSS, Bootstrap, Tailwind, React MUI, Figma  
**Backend:** Node.js, Express.js, Nodemailer  
**Database:** MongoDB  
**Other Tools:** Git/GitHub, Docker, Firebase  

---

## Installation / Running Locally

1. Clone the repository:  
```bash
git clone https://github.com/nisma01paudel/nismapaudel.git
cd nismapaudel
```
2. Install dependencies:
```bash
npm install
cd client
npm install
```
3.Create a .env file in the root directory with your environment variables, for example:
```
PORT=8080
SENDGRID_API_KEY=your_sendgrid_api_key
```
4.Run the development server:
```
npm run dev
```

The site will be available at http://localhost:3000.

# Building for Production
1. Build the React frontend:
```
cd client
npm run build
```
2. Start the server:
```
node server.js
```

Express will serve the static files from client/build.

# Deployment
- This project is deployed on Render.
- Custom domain configured: paudelnisma.com.np
- Live link: https://paudelnisma.com.np
# Contact
- Email: nisma@example.com
- LinkedIn: https://linkedin.com/in/nisma
- GitHub: https://github.com/nisma01paudel

#### Made & built by Nisma Paudel © 2026

