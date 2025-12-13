# OfflineWallet – React Native Offline-First Wallet App

A **Mini Offline Wallet App** built using **React Native CLI + TypeScript**, focused on **offline-first architecture, payment simulation, background sync, and crash-safe transaction handling**.

This project is intentionally **logic-heavy**, not UI-focused, and is designed to demonstrate **production-ready React Native engineering**.

---

## 🚀 Key Objectives

- Offline-first payment creation
- Crash & app-kill safe transaction handling
- Automatic background sync on network recovery
- No duplicate transactions
- Secure authentication handling
- High-performance transaction list (5,000+ items)
- Native Android module integration

---

## 🧱 Tech Stack

- **React Native CLI**
- **TypeScript**
- **Redux Toolkit**
- **SQLite** (offline persistence)
- **react-native-keychain** (secure storage)
- **@react-native-community/netinfo**
- **Android Native Module (Kotlin)**

🚫 **Expo is NOT used**

---

## 📂 Project Structure

```txt
src/
 ├── api/          # Mock APIs (auth, payment)
 ├── storage/      # SQLite & secure storage
 ├── store/        # Redux store & slices
 ├── services/     # Payment engine & sync logic
 ├── hooks/        # Custom hooks
 ├── screens/      # App screens
 ├── components/   # Reusable components
 ├── native/       # Native module bindings
 └── utils/        # Helpers & constants
