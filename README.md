# **🌶️ Spicy Pricey 🌟**

A Swiggy-inspired web application designed to provide a seamless and engaging food ordering experience.

---

## **✨ Features**

-   🔐 **Authentication**: Secure Google Login using Firebase Authentication.
-   🥗 **Real-Time API Integration**: Access Swiggy’s live data to explore restaurants, menus, and dishes.
-   🛒 **Cart Functionality**: Add, update, or delete food items in a dynamic cart.
-   ✅ **Checkout System**: A user-friendly checkout page for order management.
-   💳 **Payment Integration**: Razorpay integration (frontend) for smooth payment processing.
-   🛠️ **Proxy Middleware**: Custom middleware to bypass CORS issues with Swiggy’s API.

---

## **🛠️ Tech Stack**

-   **Frontend**:

    -   ⚛️ **React.js**: Responsive and interactive user interface.
    -   📦 **Redux**: State management for efficient data flow.
    -   🎨 **ShadCN UI**: Sleek and modern UI components for accessibility and consistency.
    -   🌈 **Tailwind CSS**: Highly customizable styling with a modern design approach.

-   **Middleware for CORS**:

    -   🌐 **CORS Bypass**: Implemented via a custom proxy middleware.
    -   Repository: [Food Delivery CORS Middleware](https://github.com/sharadindudas/food-delivery-cors).

-   **Authentication**:

    -   🔑 **Firebase Authentication**: Secure Google login for user authentication.

-   **Payment**:
    -   💸 **Razorpay Integration (Frontend)**: Simplifies payment handling on the user side.

---

## **🚀 Hosted Link**

👉 Access the live version of **Spicy Pricey** here: [🌶️ Spicy Pricey](https://spicy-pricey.sharadindudas.com)

---

## **📋 How to Run the Project**

### **🔧 Prerequisites**

-   🖥️ Node.js and npm installed.
-   🔥 Firebase project set up with Google Authentication enabled.
-   💳 Razorpay account for payment integration.

### **⚙️ Steps to Install and Run Locally**

1. **📂 Clone the Repository**

    ```bash
    git clone https://github.com/sharadindudas/spicy-pricey.git
    cd spicy pricey
    ```

2. **📦 Install Dependencies**

    ```bash
    npm install
    ```

3. **📝 Set Up Environment Variables**  
   Create a `.env` file in the root directory with the following variables:
   
    ```env
        VITE_FIREBASE_API=<your-firebase-api-key>
        VITE_FIREBASE_AUTHDOMAIN=<your-firebase-auth-domain>
        VITE_PROJECT_ID=<your-firebase-project-id>
        VITE_STORAGE_BUCKET=<your-firebase-storage-bucket>
        VITE_MESS_SEND_ID=<your-firebase-messaging-sender-id>
        VITE_APP_ID=<your-firebase-app-id>
        VITE_RAZORPAY_KEY_ID=<your-razorpay-key-id>
        VITE_RAZORPAY_KEY_SECRET=<your-razorpay-key-secret>
        VITE_BASE_URL=<your-proxy-middleware-base-url>
    ```

4. **CORS Middleware**:  
   Clone the CORS middleware repository and follow the instructions provided in the [Food Delivery CORS Middleware](https://github.com/sharadindudas/food-delivery-cors).
   
6. **▶️ Start the Development Server**

    ```bash
    npm run dev
    ```

7. **🌐 Access the Application**  
   Open [http://localhost:5173](http://localhost:5173) in your browser.

---

## **🌟 Future Enhancements**

-   🗃️ Backend integration for storing orders and user history.
-   🔍 Enhanced search and filtering options for restaurants and dishes.
-   📡 Real-time order tracking.

---

## **🤝 Contributing**

Contributions are welcome! To contribute:

1. 🍴 Fork the repository.
2. 🔀 Create a feature branch:
    ```bash
    git checkout -b feature-name
    ```
3. 💾 Commit your changes:
    ```bash
    git commit -m "Add feature-name"
    ```
4. 📤 Push the branch and create a pull request.

---

## **📜 License**

This project is licensed under the [MIT License](LICENSE).

---

## **📞 Contact**

For queries, feedback, or suggestions, feel free to reach out:

-   📧 **Email**: [sharadindudas774@gmail.com](mailto:sharadindudas774@gmail.com)
-   🐙 **GitHub**: [Sharadindu Das](https://github.com/sharadindudas)

---

Elevate your food ordering experience with **🌶️ Spicy Pricey**! 🍽️
