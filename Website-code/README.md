# Obarly - E-commerce Website

A Flask-based e-commerce website with MongoDB Atlas integration.

## Features
- Product catalog
- User authentication
- Shopping cart
- Order management
- Admin dashboard

## Tech Stack
- Flask
- MongoDB Atlas
- Python
- HTML/CSS/JavaScript

## Local Development Setup

1. Clone the repository
2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: .\venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Create a .env file with:
   ```
   MONGODB_URI=mongodb+srv://nik84810:Niku_2004@obarly.xwq8r3k.mongodb.net/
   DATABASE_NAME=Inventory
   SECRET_KEY=your-secret-key-here
   ```
5. Run the application:
   ```bash
   python main.py
   ```

## Deployment

The application is deployed on Render. To deploy:

1. Push changes to GitHub
2. Render will automatically deploy the latest version
3. Environment variables are managed in Render dashboard

## Environment Variables

- `MONGODB_URI`: MongoDB Atlas connection string
- `DATABASE_NAME`: Database name (default: Inventory)
- `SECRET_KEY`: Flask secret key for session management

## Security Notes

- Never commit .env file
- Keep MongoDB credentials secure
- Use environment variables in production
=======
# OBARLY – B2B E-commerce Platform

---

## Team Members
- **Alka** – Frontend Development and UI Design
- **Nikhil** – Full-Stack Development and Integration
- **Pabitra** – Backend Development and Database Connection

---

## Project Description
OBARLY is a B2B e-commerce platform designed to help restaurants, bars, cloud kitchens, and similar businesses easily place bulk orders.  
Our platform provides an intuitive interface for vendors to browse, select, and order products in bulk, with future plans to integrate advanced features like analytics and AI-driven insights.

---

## Technologies Used
- **Frontend:**
  - HTML
  - Tailwind CSS
  - JavaScript
- **Backend:**
  - Python (Flask Framework)
- **Database:**
  - MongoDB Compass
- **Other Tools:**
  - GitHub for version control
  - VS Code for development

---

## Steps to Run/Execute the Project
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Alka709/alka_santhosh_secB-Obarly
   ```
2. **Navigate into the project directory:**
   ```bash
   cd https://github.com/Alka709/alka_santhosh_secB-Obarly
   ```
3. **Install required Python packages:**
   ```bash
   pip install flask pymongo
   ```
4. **Ensure MongoDB Compass/Server is running locally.**

5. **Run the Flask app:**
   ```bash
   python app.py
   ```
6. **Open your browser and visit:**
  
   ```

---

## Future Scope
- Add analytics and order history to the admin dashboard.
- Integrate machine learning for product recommendations.
- Implement real-time stock updates and inventory management.

---

# Thank you for exploring our project!
>>>>>>> 5d1809cb9cf56eafebff9d224d5386d510a71da0
