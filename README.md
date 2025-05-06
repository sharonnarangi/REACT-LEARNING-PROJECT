# Law Firm Landing Page App (React + Tailwind + Vite)

A responsive and interactive single-page web application built using **React**, **Tailwind CSS**, and **Vite**. This project simulates a professional law firm website, showcasing services, team details, contact form, and FAQ — ideal for real-world portfolio use.

##  Motivation
As a beginner React developer, this project was created to:
- Practice building a real-world application
- Learn and apply React fundamentals
- Use Git branching workflows effectively
- Build something relevant to legal-tech spaces

##  Features
- **Home Page** – Clean and elegant hero section introducing the law firm.
- **About Us Page** – Profiles, mission, and values of the firm.
- **Practice Areas** – Interactive cards showing key legal services.
- **Contact Page** – Form with name, email, and message inputs.
- **FAQ Page** – Accordion-style questions and answers.

## Technologies Used
- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- React Router (for page navigation)

##  Folder Structure
src/ ├── components/ │ ├── Navbar.jsx │ ├── Footer.jsx │ └── ServiceCard.jsx ├── pages/ │ ├── Home.jsx │ ├── About.jsx │ ├── Services.jsx │ ├── Contact.jsx │ └── FAQ.jsx ├── App.jsx ├── main.jsx └── index.css


##  Git Branch Strategy
| Branch Name     | Purpose                          |
|-----------------|----------------------------------|
| `main`          | Production-ready code            |
| `setup`         | Vite + Tailwind + React setup    |
| `home-page`     | Homepage layout & design         |
| `about-page`    | About Us page                    |
| `services-page` | Practice areas (services)        |
| `contact-page`  | Contact form                     |
| `faq-page`      | FAQ section                      |
| `final-polish`  | Animations, SEO, responsiveness  |

##  What I Learnt
- Functional components and props
- Basic state management
- Tailwind layout and styling
- Client-side routing with React Router
- Git branching workflow for clean development


Getting Started
 Prerequisites
- Node.js installed
- Git installed

 Installation
```bash
git clone https://github.com/your-username/law-firm-react-app.git
cd law-firm-react-app
npm install
npm run dev
