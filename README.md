
# 🪑 E-Commerce App (Flutter + Firebase)

A full-featured furniture e-commerce app developed using Flutter. This application includes user and admin functionalities, supporting login/signup, product listing, cart/wishlist management, order tracking, and real-time chat – all integrated with Firebase services.

---

## 📱 Features

### 👥 User
- Sign up / Login (Firebase Auth)
- Browse products by category
- Add items to Cart and Wishlist
- Place orders
- Chat with Admin
- View order history
- Tracks own orders

### 🛠️ Admin
- Add/Edit/Delete Products
- View and manage orders
- Respond to customer chats
- Tells users about their orders

---

## 🧱 Architecture

Follows the **MVVM (Model-View-ViewModel)** architecture for clean separation of concerns:

- **Model**: Defines data structures (`cart_item.dart`, `product.dart`, etc.)
- **Repository**: Handles Firebase/database interactions
- **ViewModel**: Business logic and state management
- **UI**: Widgets and screen implementations

---

## 🛠️ Tech Stack

- **Flutter**
- **Firebase** (Auth, Firestore, Storage)
- **MVVM Architecture**
- **Provider** (or any state management library used)
- **Dart**

---

## 📂 Project Structure

```
lib/
├── main.dart
├── firebase_options.dart
├── data/
│   └── AuthRepository.dart, media_repository.dart, ...
├── models/
│   └── product.dart, cart_item.dart, wishlist_item.dart, ...
├── ui/
│   ├── admin/
│   │   └── product/, orders/, chats/, ...
│   └── user/
│       └── home/, cart/, wishlist/, profile/, ...
```

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/furniture-app.git
cd furniture-app
```

### 2. Install Dependencies
```bash
flutter pub get
```

### 3. Setup Firebase
- Download `google-services.json` (Android) and `GoogleService-Info.plist` (iOS) from Firebase Console
- Replace in the respective platform folders
- Update Firebase settings in `firebase_options.dart` if needed

### 4. Run the App
```bash
flutter run
```

---

## 📸 Screenshots

User Home Side

![image](https://github.com/user-attachments/assets/3cf564c9-d745-4646-b181-82fb46205963)

Drawer

![image-2](https://github.com/user-attachments/assets/5ccdcd7e-46da-4fd0-afa9-9c98b51ffeb8)

Wishlist

![image-3](https://github.com/user-attachments/assets/94b8ac96-4c76-4db8-9252-bf0f051660dd)

Details Page

![image-4](https://github.com/user-attachments/assets/39bf70d4-ac43-4767-809b-cfd8a548c92a)

Cart Page

![image](https://github.com/user-attachments/assets/4d54f4fc-5bc1-4048-bc56-ee5d0c99b30c)

Checkout Page

![image](https://github.com/user-attachments/assets/94e17728-243d-40ee-bc36-fd3d627d4ca4)

User Orders

![image](https://github.com/user-attachments/assets/f4dc5d2c-cb06-4a92-8546-297ad58dbb9a)

Customer Support

![image](https://github.com/user-attachments/assets/28ec32d2-efc9-45c4-abc4-782e140300fa)

Admin Home Page

![image](https://github.com/user-attachments/assets/7aea1069-bfa8-4e66-bd8d-0ca5c7ab6aee)

Drawer

![image](https://github.com/user-attachments/assets/811cd843-ce31-44fe-997e-a7e60d1c665c)

Admin Orders Page

![image](https://github.com/user-attachments/assets/9e40a962-fe8d-4cae-8593-b52fb38acfbf)

Admin Chats

![image](https://github.com/user-attachments/assets/45dcfb75-4cdc-43c3-b521-bccd8717d056)

Specific Chat with Customer

![image](https://github.com/user-attachments/assets/0f3e5f74-7ae2-4397-90b7-e548e16f8e1e)




---

## 🤝 Contributing

Feel free to open issues or submit pull requests to improve the app. Contributions are welcome!

---

## 📃 License

This project is licensed under the [MIT License](LICENSE).

---

## 📬 Contact

Maintainer: Danish Riasat

GitHub: DanishR07

Email: danishriasat792@gmail.com
