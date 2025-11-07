# 🚗 Car Rental System

A full-stack web application designed to simplify the process of renting cars online. The system allows users to browse available cars, make bookings, manage rentals, and view details — while admins can manage vehicles, bookings, and customer data efficiently.

---

## 🌟 Features

### 👤 User Features
- User registration and login system  
- Browse and search available cars  
- View detailed car information  
- Book and manage car rentals  
- View booking history  
- Responsive and user-friendly interface  

### 🛠️ Admin Features
- Admin dashboard for full control  
- Add, edit, or delete car details  
- View and manage bookings  
- Manage registered users  
- Monitor system activity and data  

---

## 🧩 Technologies Used

**Frontend:**  
- HTML5, CSS3, JavaScript  
- Bootstrap 5  
- Font Awesome for icons  

**Backend:**  
- PHP (Core / OOP)  
- MySQL Database  

**Server:**  
- Apache (via XAMPP / WAMP)

---

## ⚙️ Installation and Setup

### Step 1: Clone or Download the Repository
```bash
git clone https://github.com/yourusername/car-rental-main.git
```
Or extract the ZIP file you downloaded.

### Step 2: Move to Server Directory
Move the folder `car-rental-main` to your server root directory:
- For **XAMPP** → `C:\xampp\htdocs\`
- For **WAMP** → `C:\wamp\www\`

### Step 3: Import the Database
1. Open **phpMyAdmin**  
2. Create a new database, e.g., `car_rental`  
3. Import the file `car_rental.sql` located in the project folder

### Step 4: Configure the Database Connection
Edit the file:
```
/config/config.php
```
Update your database credentials:
```php
$host = "localhost";
$user = "root";
$pass = "";
$dbname = "car_rental";
```

### Step 5: Run the Application
Open your browser and go to:
```
http://localhost/car-rental-main/
```

---

## 📁 Folder Structure

```
car-rental-main/
│
├── admin/              # Admin dashboard & management pages
├── assets/             # CSS, JS, and images
├── config/             # Database configuration files
├── includes/           # Header, footer, and reusable components
├── pages/              # Main user-facing pages
├── car_rental.sql      # Database file
└── index.php           # Homepage entry point
```

---

## 🚀 Future Enhancements
- Add online payment integration  
- Include booking cancellation and refund system  
- Implement OTP-based authentication  
- Introduce analytics for admins  

---

## 🧑‍💻 Contributors
- **Meet Zadafiya** — Developer & Designer  

---

## 📜 License
This project is licensed under the **MIT License** — free to use and modify for educational purposes.

---

### 💡 Note
Make sure XAMPP/WAMP is running (Apache and MySQL services) before accessing the application.
