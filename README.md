# CRWN Clothing V2 - Redux Toolkit

## Overview

This project is a modern **e-commerce website** built with **React**, using **Redux Toolkit** for state management and **Stripe** for payment processing. It is a fork of [ZhangMYihua's repository](https://github.com/ZhangMYihua/crwn-clothing-v2-redux-toolkit), which I am following as part of a course to deepen my knowledge of React and best development practices.

My branch for this project is **my-main**.

## Features

- **React & Redux Toolkit** for state management.
- **Firebase Authentication** for user login/signup.
- **Stripe API** integration for secure payments.
- **Styled Components** for modern styling.
- **Redux Persist** for storing cart items in local storage.
- **Asynchronous Thunks** for API calls and Firebase interactions.
- **Reusability & Performance Optimization** using best practices.

## Getting Started

### Prerequisites
- Node.js (>= 14.x)
- npm or yarn

### Installation
1. **Clone the repository:**
   ```sh
   git clone https://github.com/thaisc98/crwn-clothing-v2-redux-toolkit.git
   cd crwn-clothing-v2-redux-toolkit
   ```
2. **Switch to my-main branch:**
   ```sh
   git checkout my-main-v2
   ```
3. **Install dependencies:**
   ```sh
   npm install  # or yarn install
   ```
4. **Set up Firebase:**
   - Create a Firebase project.
   - Enable authentication (Google sign-in, email/password, etc.).
   - Set up Firestore for data storage.
   - Create a `.env` file and add the folllwoing Stripe API Keys: 
    ```sh
        REACT_APP_STRIPE_PUBLISHABLE_KEY=your_publishable_key_here
        REACT_STRIPE_KEY=your_secret_key_here
    ```

5. **Run the application:**
   ```sh
   npm start  # or yarn start
   ```

6. **Open in Browser:**
   Navigate to `http://localhost:3000`.

## Learning Goals
- Improve understanding of **Redux Toolkit** and best practices.
- Gain hands-on experience with **Firebase authentication & Firestore**.
- Learn about **asynchronous state management** with thunks.
- Enhance skills in **React performance optimization**.
- Integrate **Stripe payments** into a React application.

## Technologies Used
- React
- Redux Toolkit
- Firebase (Authentication, Firestore)
- Stripe API
- Styled Components
- Redux Persist

## Acknowledgments
This project is based on [ZhangMYihua's original repository](https://github.com/ZhangMYihua/crwn-clothing-v2-redux-toolkit). Thanks to the instructor for providing in-depth knowledge and guidance through the course.

## License
This project is for educational purposes and follows the original repository's license.


