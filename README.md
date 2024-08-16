# Ecommerce Website with NLP Recommendation System

## Project Overview

This project is a submission for Sparkathon 2024, presenting an Ecommerce website for Walmart. The key feature of this platform is the implementation of a Natural Language Processing (NLP) based recommendation system, along with price optimization to enhance user experience and maximize savings.

### Tech Stack

- **Frontend:**
  - React.js

- **Backend:**
  - Flask
  - MongoDB

- **NLP:**
  - NLTK (Natural Language Toolkit)
  - TfidfVectorizer

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/AnuragJha003/Sparkathon2024.git
   ```

2. Install dependencies for frontend and backend:

   ```bash
   # Navigate to client folder
   cd client
   npm install

   # Navigate to server folder
   cd ../server
   pip install -r requirements.txt
   ```

3. Set up MongoDB:

   - Ensure MongoDB is installed and running.

4. Run the application:

   ```bash
   # Run frontend (from the client folder)
   npm start

   # Run backend (from the server folder)
   python app.py
   ```

   The application should now be accessible at `http://localhost:3000`.

### Features

- **User Authentication:** Users can create accounts, log in, and enjoy a personalized experience.

- **NLP Recommendation System:** Leveraging NLTK and TfidfVectorizer, the recommendation system suggests products based on user preferences and historical data.

- **Price Optimization:** Utilizing algorithms to optimize product prices for maximum savings.

- **Cart Functionality:** Users can add products to their shopping cart, review items, and proceed to checkout.
