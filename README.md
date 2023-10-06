
# TrendsetGo - E-commerce React App


TrendsetGo is an e-commerce web application built with Vite, ReactJS, Firebase, Tailwind CSS, and Redux.
This project allows users to explore and purchase a wide range of trendy products online.

## Requirements

Before you start, ensure you have the following requirements in place:

- [Firebase](https://firebase.google.com): Firebase is used for user authentication and storage.

- Authentication: Set up Firebase user authentication and configure it in your Firebase project.

- Environment Variables: Create a `.env` file in the project root and add the following variables:

  ```
  VITE_FB_API_KEY=your_api_key_here
  VITE_FB_AUTH=your_auth_domain_here
  VITE_FB_PRJ_ID=your_project_id_here
  VITE_FB_STORAGE=your_storage_bucket_here
  VITE_FB_MESSAGE_ID=your_messaging_sender_id_here
  VITE_FB_APP_ID=your_app_id_here
  ```

## Getting Started

In the project directory, you can run the following commands to get started:

### 1. Install Dependencies

Run the following command to install the dependencies found in the `package.json` file:

```bash
npm install
```

### 2. Run the Development Server

To start the app in development mode, run:

```bash
npm run dev
```

This will launch the development server. Open [http://localhost:5173](http://localhost:5173) in your web browser to view the application. 
The page will automatically reload when you make changes, and any lint errors will be displayed in the console.

## Features

- Browse a wide variety of trendy products.
- User authentication for a personalized shopping experience.
- Easily add products to your cart and proceed to checkout.
- View and manage your order history.
- Secure payment processing.

## Contributing

Contributions are welcome! Feel free to open issues or pull requests to improve the app.
