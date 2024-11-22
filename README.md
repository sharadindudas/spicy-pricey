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
    -   Repository: [Spicy Pricey CORS Middleware](https://github.com/sharadindudas/spicy-pricey-cors).

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
    cd spicy-pricey
    ```

2. **📦 Install Dependencies**

    ```bash
    npm install
    ```

3. **📝 Set Up Environment Variables**  
   Create a `.env` file in the root directory with the following variables:

    ```env
     VITE_FIREBASE_API =
     VITE_FIREBASE_AUTHDOMAIN =
     VITE_PROJECT_ID =
     VITE_STORAGE_BUCKET =
     VITE_MESS_SEND_ID =
     VITE_APP_ID =
     VITE_RAZORPAY_KEY_ID =
     VITE_RAZORPAY_KEY_SECRET =
     VITE_BASE_URL =
    ```

4. **CORS Middleware**:  
   Clone the CORS middleware repository and follow the instructions provided in the [Spicy Pricey CORS Middleware](https://github.com/sharadindudas/spicy-pricey-cors) repository.

5. **▶️ Start the Development Server**

    ```bash
    npm start
    ```

6. **🌐 Access the Application**  
   Open [http://localhost:5173](http://localhost:5173) in your browser.

---

## **🗂️ Project Structure**

-   📁 **src/components**: Reusable React components.
-   🔧 **src/utils**: Redux slices and store configuration.
-   📁 **src/pages**: Page-level components such as Home, Cart, and Checkout.
-   🎨 **src/css**: Tailwind CSS setup and custom styles.
-   📁 **src/hooks**: Reusable logics for each pages.
-   🔧 **src/config**: Configuration files for the app.

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

For queries or suggestions, feel free to reach out:

-   📧 **Email**: sharadindudas774@gmail.com
-   🐙 **GitHub**: [Your GitHub Profile](https://github.com/sharadindudas)

---

Elevate your food ordering experience with **🌶️ Spicy Pricey**! 🍽️
