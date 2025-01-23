# 🛍️ Bandage Online Shopping  

A sleek and dynamic frontend for an online shopping platform focused on **bandage products**. This project is designed with modern UI/UX principles, offering seamless navigation, wishlist functionality, add-to-cart features, a product search bar, and dynamic data fetching using **GROQ queries** from a Sanity backend.  

---

## 📋 Table of Contents  
1. [Project Overview](#project-overview)  
2. [Features](#features)  
3. [Live Demo](#live-demo)  
4. [Technologies Used](#technologies-used)  
5. [Setup Instructions](#setup-instructions)   
7. [Performance Testing](#performance-testing)  
8. [Contributing](#contributing)  
9. [License](#license)  

---

## 🛠️ Project Overview  
This project is the **frontend** for the Bandage Online Shopping platform, showcasing modern design and interactivity. The app is fully responsive, lightweight, and optimized for high performance. It is integrated with Sanity's backend for real-time product data fetching using GROQ queries.  

---

## ✨ Features  

- **Dynamic Navigation:** Navigate easily between categories and product details.  
- **Add to Cart:** Add products to the cart, adjust quantities, and view cart items dynamically.  
- **Wishlist Management:** Save your favorite products for later.  
- **Product Search:** Search dynamically for products using GROQ queries.  
- **Dynamic Data Fetching:** Real-time fetching of product data from the Sanity backend.  
- **Fully Responsive:** Optimized for mobile, tablet, and desktop screens.  
- **Automatic Deployment:** Integration with GitHub for seamless updates.  
- **Environment Variables:** API keys and credentials securely managed.  
- **Performance Optimized:** Lighthouse tests performed for high performance scores.  
- **Security Tested:** Vulnerability scanning using tools like Postman.  
- **Fully Responsive:** Mobile-first design ensures compatibility across devices.
---

## 🌐 Live Demo  
**[View the Live App Here](https://shopping-website-next-js-gamma.vercel.app/)**  

---

## 🛠️ Technologies Used  

### Frontend  
- **Framework:** [Next.js](https://nextjs.org/)  
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)  

### Backend (for fetching data)  
- **CMS:** [Sanity.io](https://www.sanity.io/)  
- **Data Queries:** GROQ  

### Deployment  
- **Hosting Platform:** [Vercel](https://vercel.com/)  

---

## ⚙️ Setup Instructions  

### Prerequisites  
- **Node.js** (v16 or higher)  
- **Git**  

### Steps  

1. **Clone the Repository**  
   ```bash  
   git clone https://github.com/your-username/bandage-online-shopping.git  
   cd bandage-online-shopping  
Install Dependencies

bash
Copy
Edit
npm install  
Set Up Environment Variables
Create a .env.local file in the root directory and add the following:

env
Copy
Edit
NEXT_PUBLIC_SANITY_PROJECT_ID=your-sanity-project-id  
NEXT_PUBLIC_SANITY_DATASET=production  
NEXT_PUBLIC_SANITY_API_VERSION=v2023-01-01  
Run the Development Server

bash
Copy
Edit
npm run dev  
Open http://localhost:3000 in your browser to view the project locally.


---

🚀 Deployment
Deploying to Vercel
Import the project:
Go to Vercel and import your GitHub repository.

Configure environment variables:
Add the .env.local variables in Vercel under Settings > Environment Variables.

Deploy:
Vercel automatically deploys your project after every push to the main branch.

🔒 Environment Variables
Variable Name	Description
NEXT_PUBLIC_API_URL	URL for the backend API.
DATABASE_URL	Connection string for the database.
SECRET_KEY	Secret key for authentication.
Note: Always store sensitive data in environment variables and never hardcode them in your codebase.

📊 Performance & Security Testing
Performance Testing
Tool: Lighthouse
Tests performed:
Page load speed.
Accessibility.
SEO.
Best practices.
Security Testing
Tool: Thunder Client
Tests performed:
API endpoint testing for authentication and authorization.
Vulnerability scans for potential threats.
🛠️ Technologies Used
Framework: Next.js
Deployment: Vercel
Styling: Tailwind CSS
Testing Tools: Lighthouse, Postman
🤝 Contributing
Contributions are welcome! Follow these steps to contribute:

Fork the repository.
Create a new branch:
bash
Copy
Edit
git checkout -b feature/your-feature-name
Make your changes and commit them:
bash
Copy
Edit
git commit -m "Add your message here"
Push to the branch:
bash
Copy
Edit
git push origin feature/your-feature-name
Open a pull request.

📄 License
This project is licensed under the MIT License.

📬 Contact
For any queries or feedback, feel free to reach out:

Email: mariam.rauf567@gmail.com

Linkedin: https://www.linkedin.com/in/mariam-rauf-soomro-3a2046247/

GitHub: https://github.com/Mariam-Rauf01

 






