# RR Fashions – Ladies & Kids Boutique Website

A modern **fashion boutique website** built for **RR Fashions** to showcase and manage ladies' and kids' clothing collections online.
The website allows customers to browse products and contact the store via WhatsApp, while the admin can securely add or delete products using Firebase authentication.

---

## 🌐 Live Features

### 👗 Customer Features

* Browse **Ladies & Kids fashion collections**
* View **product details and images**
* **Category filtering** (Ladies / Kids)
* **WhatsApp buy button** to contact the shop instantly
* Mobile-friendly responsive design
* View full product image in modal
* Smooth scrolling and UI animations

### 🔐 Admin Features

* Secure **Admin Login**
* **Add new products**
* **Delete products**
* Real-time updates using **Firebase Firestore**
* Admin-only controls

---

## 🛠️ Technologies Used

* **HTML5**
* **Tailwind CSS**
* **JavaScript (ES Modules)**
* **Firebase**

  * Firebase Authentication
  * Firebase Firestore Database
* **Google Fonts**
* **Responsive UI Design**

---

## 📂 Project Structure

```
RR-Fashions/
│
├── index.html        # Main website file
├── logo.jpg          # Website logo
├── README.md         # Project documentation
```

---

## ⚙️ Firebase Setup

1. Go to **Firebase Console**

2. Create a new project

3. Enable:

   * **Authentication → Email/Password**
   * **Cloud Firestore Database**

4. Replace the configuration in the script with your Firebase config:

```javascript
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT.appspot.com",
  messagingSenderId: "XXXX",
  appId: "XXXX"
};
```

---

## 👤 Admin Access

Admin panel becomes visible when logged in with the **admin email**.

Example:

```
Email: admin@rrfashions.com
Password: (your Firebase password)
```

Only this admin account can:

* Add products
* Delete products

---

## 🛍️ Product Data Structure

Products are stored in **Firestore collection: `products`**

Example document:

```
{
  name: "Floral Kurti",
  price: 799,
  description: "Comfortable cotton kurti with floral design",
  image: "https://example.com/image.jpg",
  category: "Ladies"
}
```

---

## 📱 WhatsApp Integration

Customers can directly contact the shop using WhatsApp.

Example message format:

```
Hello, I'm interested in buying this product:

Floral Kurti
Price: ₹799

Can you please provide more details?
```

---

## 📍 Store Location

RR Fashions
Garidi Ganesha Complex
Railway Station Road
Mukkidipeta, Hindupuram
Andhra Pradesh – 515201

---

## 🚀 How to Run the Project

1. Download or clone the repository

```
git clone https://github.com/yourusername/rr-fashions.git
```

2. Open the project folder

3. Run using a local server (recommended)

Example using VS Code Live Server.

---

## 📸 Website Sections

* Hero section
* Product collection grid
* Category filters
* Product detail page
* Admin dashboard
* WhatsApp purchase button
* Footer with contact information

---

## 💡 Future Improvements

* Product search feature
* Product image upload (Firebase Storage)
* Online payment integration
* Order management system
* Customer accounts
* Admin dashboard analytics

---

## ❤️ Credits

Designed and developed for **RR Fashions Boutique**.

Built with modern web technologies to create a smooth shopping experience for customers.

---

## 📄 License

This project is open-source and free to use for learning and small business websites.
