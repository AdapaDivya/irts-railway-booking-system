# 🚆 IRTS Final Implementation - Detailed Project Report

## 🎯 Overview

This project is a fully functional **console-based railway ticket booking system** developed using **Java**.  
It simulates real-world railway booking operations including ticket reservation, payment processing, booking history, and user management.

The system is designed with a focus on **clean structure, user experience, and core Java concepts**.

---

## ✨ Scrolling Text Animation 

### Applied To:

* Platform Ticket Display  
* General Ticket Display  
* Reservation Ticket Display  
* Booking History  
* "No results found" messages  

### Behavior:

* Text appears **character-by-character**
* Speed: **30ms per character**
* Ensures **smooth and readable output**

---

## 🎨 Exit Animation

### Features:

* Scrolling farewell messages  
* Train-themed ASCII art  
* Colored output using ANSI codes  
* Clean exit experience  

---

## 📚 System Features

### 🔐 User Management

* Signup & Login system  
* Update credentials:
  * Username  
  * Password  
  * Email  
  * Mobile Number  

---

### 🎟️ Ticket Booking

* **Reservation Ticket**
  * Passenger details
  * Age-based fare calculation
  * Berth preferences  

* **General Ticket**
  * Distance-based pricing  
  * Multiple passengers  

* **Platform Ticket**
  * Fixed fare per person  

---

### 💳 Payment System

* Implemented using **interface (`PaymentService`)**
* Demonstrates **Polymorphism**

#### Supported Methods:
* UPI  
* Card  
* Net Banking  

---

### 📜 Booking History

Stores last booked ticket for:

* Reservation  
* General  
* Platform  

---

## 🎨 UI Enhancements

* ANSI color styling for better visibility  
* Interactive menu system  
* Smooth scrolling animations  
* Structured console output  

---

## 🧱 Project Design

* Modular class-based architecture  
* Separation of concerns  
* Interface-based abstraction  
* Reusable components  

---

## 🧠 Concepts Used

* **Encapsulation** → Login class  
* **Inheritance** → Classes extend CSRP  
* **Polymorphism** → Payment methods  
* **Abstraction** → PaymentService interface  
* Arrays & Loops  
* Input validation  
* Scanner for user interaction  

---

## 📂 Project Structure

```
IRTS/
├── CSRP.java
├── Login.java
├── BookingHistory.java
├── ReservationTicket.java
├── GeneralTicket.java
├── PlatformTicket.java
├── Payment.java
├── PaymentService.java
├── UPIPayment.java
├── CardPayment.java
├── NetBanking.java
├── Train.java
├── Station.java
├── TicketDisplay.java
```

---

## 🚀 How to Run

### Step 1: Compile
```
javac *.java
```

### Step 2: Run
```
java CSRP
```

---

## 📍 Available Stations

* Chennai  
* Nellore  
* Ongole  
* Vijayawada  
* Khammam  
* Warangal  
* Secunderabad  

---

## 🔧 Future Enhancements

* File handling for persistent storage  
* Database integration (MySQL + JDBC)  
* GUI using Java Swing / JavaFX  
* Multi-user system  

---

## 📌 Conclusion

This project demonstrates a **real-world application of Java programming concepts** with enhanced UI and user interaction.  

It is suitable for:
* Academic submission  
* Java project portfolio  
* Understanding software design principles  

---

## 👩‍💻 Author

**Adapa Divya Sri**

---

## ✅ Final Note

✔ Clean  
✔ Complete  
✔ Professional  
✔ Ready for GitHub  
