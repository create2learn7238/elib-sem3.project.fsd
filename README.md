# BookHeaven E-Library Project

## 👤 User Features
1. **Register / Login**: Secure authentication for users.
2. **Browse / Search Books**: Find books easily using the search bar or category filters.
3. **Read / Download Free Books**: Access free content immediately.
4. **Purchase Premium Books**: Buy specific titles to read.
5. **Purchase Membership**: Subscribe to plans for unlimited access.
6. **Make Payment**: Integrated payment simulation (Card/QR).
7. **View Profile**: Check membership status and book history.
8. **Logout**: End user session.

## 🛡️ Admin Features
1. **Admin Login**: Secure access for administrators.
2. **Manage Books**: Add, Edit, and Remove books from the library.
3. **Check Payment Logs**: View all transaction history.
4. **Check User Details**: Manage registered users and view their plans.
5. **Add Carousel Slide**: Customize the homepage hero section.
6. **Logout**: End admin session.

## 💻 Languages & Technologies Used

### Backend
- **Runtime**: Node.js
- **Logic**: JavaScript

### Frontend
- **Structure**: HTML
- **Styling**: CSS, Bootstrap, Tailwind CSS
- **Fonts**: Google Fonts

### Database & Storage
- **Database**: MySQL (phpMyAdmin)
- **Local Storage**: Session management
- **Connection**: Node.js (mysql2)

## 📦 Backend Dependencies
| Module | Purpose in Project |
| :--- | :--- |
| **express** | The web framework used to create the server and API routes. |
| **mysql2** | Connects Node.js to the MySQL database for storing users and books. |
| **cors** | Allows the frontend to communicate with the backend API securely. |
| **body-parser** | Reads JSON data sent from the frontend (e.g., login details). |
| **nodemailer** | Sends emails (OTPs) to users for account verification. |
| **axios** | Used to proxy file downloads (fetching book PDFs). |
| **bcrypt** | Hashes passwords so they aren't stored as plain text. |
| **os** | Gets the computer's local IP address for the Mobile QR payment feature. |
| **multer** | Handles image uploads for the Admin Carousel feature. |
| **path** | Helps manage file paths for uploaded images. |
| **fs** | File System module; checks if the `uploads/` folder exists. |
