# 💳 Razorpay Payment Gateway Integration

This project demonstrates how to integrate **Razorpay Payment Gateway** into a web application for secure and seamless online transactions.  
It allows users to make payments through Razorpay’s checkout interface, ensuring fast, simple, and safe processing.

---

## 🚀 Features

- 🔐 Secure online payment using **Razorpay API**
- 💵 Supports multiple payment modes (UPI, Card, Net Banking, Wallets)
- ⚙️ Fully functional **backend integration** with Razorpay order creation
- 🧩 Easy to integrate with any frontend (HTML, React, etc.)
- 📜 Clear success and failure response handling

---

## 🛠️ Tech Stack

**Frontend:** HTML, CSS, JavaScript (or React.js)  
**Backend:** Node.js, Express.js  
**Payment Gateway:** Razorpay API  
**Server:** Localhost or any deployment platform (Render / Vercel / etc.)

---

## 📂 Project Structure

razorpay-payment-gateway/
│
├── backend/
│ ├── server.js # Express server and Razorpay order API
│ ├── package.json # Backend dependencies
│
├── frontend/
│ ├── index.html # Payment UI
│ ├── script.js # Razorpay Checkout integration
│
├── .gitignore
├── README.md
└── LICENSE (optional)

yaml
Copy code

---

## ⚙️ Setup Instructions

### 1️⃣ Clone this repository
```bash
git clone https://github.com/Harsh8543/razorpay-payment-gateway.git
2️⃣ Install dependencies
bash
Copy code
cd backend
npm install
3️⃣ Set up environment variables
Create a .env file in the backend folder and add your Razorpay credentials:

env
Copy code
RAZORPAY_KEY_ID=your_key_id
RAZORPAY_KEY_SECRET=your_secret_key
4️⃣ Run the backend server
bash
Copy code
npm start
5️⃣ Open the frontend
Open index.html in your browser

Click on Pay Now button to test the payment flow

🧪 Test Mode
To test payments without real transactions, use Razorpay’s Test Mode credentials.
You can generate these in your Razorpay Dashboard → Settings → API Keys.

📸 Demo Screenshot
(Add a screenshot or GIF of your payment interface here)

<img width="616" height="862" alt="Screenshot 2025-10-26 175921-Picsart-AiImageEnhancer" src="https://github.com/user-attachments/assets/d222a720-526c-46f9-876c-5a9f39214b0c" />
<img width="1574" height="1352" alt="Screenshot 2025-10-26 180139-Picsart-AiImageEnhancer" src="https://github.com/user-attachments/assets/7c7e8532-916d-41fa-bcda-c55dbc35f9d5" />
<img width="453" height="307" alt="Screenshot 2025-10-26 180234" src="https://github.com/user-attachments/assets/764e4649-b7da-4b83-ac32-5d43668e1c66" />



🤝 Contributing
Contributions, issues, and feature requests are welcome!
Feel free to open a Pull Request or Issue.

🧑‍💻 Author
Harsh Singh
🎓 B.Tech CSE Student | 💻 Web Developer | ⚡ Problem Solver
🌐 GitHub

📜 License
This project is licensed under the MIT License – feel free to use and modify it.

⭐ If you found this helpful, don’t forget to give it a star on GitHub!

yaml
Copy code

---

Chaaho to main iska **React-based version** ke hisaab se thoda modify karke likh du (jaise frontend
