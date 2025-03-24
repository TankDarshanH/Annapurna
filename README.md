**Annapurna Restaurant Web App 🍽️**
Annapurna is a restaurant menu and ordering web application built using React.js and Tailwind CSS. It features a dynamic menu, user authentication, a shopping cart, and a review system to enhance the customer experience.

**✨ Features**
User Authentication: Sign up, log in, and log out functionality using local storage.

Dynamic Navigation: Responsive navbar with different states for logged-in and guest users.

Menu Management: Various cuisine categories, including Gujarati, Punjabi, South Indian, Fast Food, and more.

Shopping Cart: Users can add items to their cart and proceed with an order.

Review System: Logged-in users can leave reviews.

Session Handling: User sessions are managed via sessionStorage.

Responsive Design: Styled using Tailwind CSS for a seamless experience across devices.

**🛠️ Tech Stack**
Frontend: React.js, React Router, Tailwind CSS

State Management: React Context API (CartContext, ReviewsContext)

Storage: localStorage (for user data), sessionStorage (for active sessions)

**📂 Project Structure**
css
Copy
Edit
/src
  ├── component/
  │   ├── Heading.jsx
  │   ├── Footer.jsx
  │   ├── Main.jsx
  │   ├── Cart.jsx
  │   ├── Gallery.jsx
  │   ├── Reviews.jsx
  ├── Menu pages/
  │   ├── Gujarati.jsx
  │   ├── Punjabi.jsx
  │   ├── SouthIndian.jsx
  │   ├── Fastfood.jsx
  │   ├── RiceBiryani.jsx
  │   ├── Desserts.jsx
  │   ├── Beverages.jsx
  │   ├── Popular.jsx
  ├── CartContext.js
  ├── ReviewsContext.js
  ├── App.jsx
  ├── index.js
  
**🚀 How to Run Locally**

**Clone the repository:**

bash
Copy
Edit
git clone https://github.com/your-username/annapurna-restaurant.git
cd annapurna-restaurant

**Install dependencies:**

nginx
Copy
Edit
npm install

**Start the development server:**

arduino
Copy
Edit
npm run dev

**Open your browser and visit:**

arduino
Copy
Edit
http://localhost:5173

**📌 Future Enhancements**

Integrate a backend with a database for real-time order management.

Implement payment gateway integration.

Enhance the UI/UX with more animations.
