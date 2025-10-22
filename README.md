# Hospital Patient Verification System 🏥

A secure, efficient patient appointment and verification system that uses facial recognition for seamless check-in and real-time doctor notifications.

![PHP](https://img.shields.io/badge/PHP-Backend-777BB4?logo=php)
![JavaScript](https://img.shields.io/badge/JavaScript-Frontend-F7DF1E?logo=javascript)
![Python](https://img.shields.io/badge/Python-Facial%20Recognition-3776AB?logo=python)
![MySQL](https://img.shields.io/badge/MySQL-Database-4479A1?logo=mysql)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-5C3EE8?logo=opencv)

## 🚀 Overview

This system revolutionizes hospital patient management by combining traditional appointment scheduling with cutting-edge facial recognition technology. Patients can book appointments online and verify their identity instantly upon arrival using facial recognition, while doctors receive real-time notifications of verified patient arrivals.

## ✨ Key Features

### 🔐 Secure Patient Verification
- **Facial Recognition Check-in**: Patients verify identity using facial recognition at hospital kiosks
- **Biometric Authentication**: Secure alternative to traditional ID checks
- **Real-time Verification**: Instant identity confirmation against registered patient data

### 📅 Smart Appointment Management
- **Online Booking Portal**: Intuitive interface for patients to schedule appointments
- **Calendar Integration**: Interactive JavaScript calendar for date/time selection
- **Automated Reminders**: Reduce no-shows with email/SMS notifications

### 👨‍⚕️ Doctor Dashboard
- **Real-time Arrival Notifications**: Instant alerts when verified patients arrive
- **Patient Queue Management**: Live view of waiting patients
- **Medical Record Access**: Secure access to patient history upon verification

### 🛡️ Security & Privacy
- **Encrypted Data Storage**: All medical records and facial data secured with encryption
- **HIPAA Compliant**: Designed to meet healthcare privacy standards
- **Audit Logs**: Comprehensive tracking of all system activities

## 🏗️ System Architecture

```mermaid
graph TB
    A[Patient Web Portal] --> B[PHP Backend]
    C[Check-in Kiosk] --> D[Python Facial Recognition]
    B --> E[MySQL Database]
    D --> E
    B --> F[Doctor Dashboard]
    D --> F
