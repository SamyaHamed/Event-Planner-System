# 📅 Event Planner System

A **Java console-based application** designed to manage events and user accounts (Users, Service Providers, and Admins). The system supports event creation, search, booking, profile management, and full administrative control.



## 📚 Table of Contents

- [📌 Introduction](#introduction)
- [✨ Features](#features)
  - [🔑 General Features](#general-features)
  - [👤 User Features](#user-features)
  - [🏢 Service Provider Features](#service-provider-features)
  - [🛠️ Admin Features](#admin-features)
- [🚀 Getting Started](#getting-started)
  - [📦 Prerequisites](#prerequisites)
  - [⚙️ Installation](#installation)
  - [▶️ Running the Application](#running-the-application)
- [🗂️ File Structure](#file-structure)
- [🤝 Contributing](#contributing)
- [📄 License](#license)



## 📌 Introduction

The **Event Planner System** is a command-line based event management system implemented in Java. It provides a multi-role experience with functionality tailored to:

- Regular Users (view & book events)
- Service Providers (create & manage events)
- Admins (system oversight and analytics)



## ✨ Features

### 🔑 General Features

- User authentication (Login / Signup)
- Role-based access (User / Service Provider / Admin)
- Profile editing (first name, last name, email, password)



### 👤 User Features

- 🔍 **Search Events** by:
  - Name
  - Name + Location
  - Name + Price Range
  - Name + Location + Price Range
- 📆 View all available events
- ✅ Book events (with a payment process)
- ❌ Cancel booked events
- 🔔 View booking notifications and general announcements
- 🖼️ View event images



### 🏢 Service Provider Features

- 📝 Add, edit, or delete events (name, ID, cost, location, capacity, timings, etc.)
- 🖼️ Upload images for events
- 📈 Analyze:
  - Total events
  - Booked/unbooked events
  - Profits from bookings
- 📅 View upcoming events in a calendar view
- 🔔 Manage reservation requests (accept/reject)



### 🛠️ Admin Features

- 📊 System-wide statistics:
  - Registered users & providers
  - Event count & average cost
  - Total profits
  - Most popular booking times
- ✅ Manage service provider registration requests
- 📢 Send announcements to all users



## 🚀 Getting Started

### 📦 Prerequisites

- Java Development Kit (**JDK 8 or higher**)
- Java IDE (e.g., **IntelliJ IDEA**, **Eclipse**) – optional but recommended

---

### ⚙️ Installation

1. **Clone the repository**:

   ```bash
   git clone <https://github.com/SamyaHamed/Event-Planner-System.git>
   cd EventPlannerSystem
