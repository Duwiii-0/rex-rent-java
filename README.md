# 🚗 Rex's Rent - Car Rental Management System

**Rex's Rent** is a Java-based console application designed to manage car rentals for both admins and employees. The application stores customer, car, and rental transaction data in CSV files and offers an interactive menu-driven interface.

## 📁 Project Structure

- `Main.java` — Main entry point of the application; handles login and navigation.
- `Akun.java` — Abstract base class for both `Admin` and `Pegawai` (Employee).
- `Admin.java` — Admin class: manages car data, transaction history, and employee login credentials.
- `Pegawai.java` — Employee class: manages customer data and rental transactions.
- `Mobil.java` — Represents a car available for rent.
- `Pelanggan.java` — Represents customer data.
- `Transaksi.java` — Stores and processes rental transactions.

## 📦 Key Features

### 🔐 Login
- Admins and employees can log in with their respective credentials.

### 👨‍💼 Admin Menu
- View transaction history.
- Business evaluation (revenue summary).
- Add/Edit car data.
- Update employee login credentials.

### 👷 Employee Menu
- Add/Edit/View customer data.
- Create rental transactions.
- View available cars.
- Return cars (update car status and delete related transaction).

### 📝 Data Storage
All data is stored in CSV files:
- `daftarpelanggan.csv` — Customer data
- `daftarMobil.csv` — Car data
- `transaksi.csv` — Transaction data


