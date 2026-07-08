# 💰 Expense Tracker

**A personal expense tracking app built with Flutter — with local storage, dynamic theming, multi-currency support, and visual spending analytics.**

Track every rupee (or dollar, or euro) with a clean, modern interface designed for everyday use.

---

## ✨ Features

### 📝 Expense Management
- Add expenses with amount, title, category, date & optional note
- Edit existing expenses with pre-filled forms
- Swipe-to-delete gesture for quick removal
- Inline form validation on required fields

### 🏠 Home Dashboard
- Gradient "Total Expenses" hero card with monthly total & transaction count
- Recent transactions list with category-colored icons & pills
- Time-of-day-aware greeting

### 📊 Spending Analytics
- Month-by-month navigation
- Donut chart breakdown of spending by category
- Category-by-category list with progress bars & percentages
- 6-month bar chart trend with the current month highlighted
- Graceful empty state for months with no expenses

### 🎨 Theming
- Light, Dark & System theme modes
- Fully theme-aware across every screen
- Preference persists across app restarts

### 💱 Multi-Currency Support
- Choose your preferred display currency: ₹ INR, $ USD, € EUR, £ GBP, ¥ JPY
- All amounts update instantly with locale-correct formatting
- Preference persists across app restarts
- *Note: this is a display preference — amounts are stored as plain numbers, with no live conversion between currencies*

### 🎯 Custom Branding
- Custom purple app icon with bold two-line wordmark
- Animated splash screen (fade + scale) with tagline "Track every rupee"
- App labeled "ExpenseTrack" across Android & iOS

---

## 🎨 Design System

- Purple primary brand color throughout
- 8 color-coded categories: Food & Drinks, Transport, Shopping, Health, Entertainment, Education, Bills & Utilities, Others
- Card-based UI with soft shadows & rounded corners
- Gradient hero cards on Home & Summary screens
- Tested for consistency across both light and dark themes

---

## 📱 Screenshots

<!-- Add screenshots here -->
<!-- Example:
| Home | Add Expense | Summary |
|------|-------------|---------|
| ![Home](screenshots/home.png) | ![Add](screenshots/add.png) | ![Summary](screenshots/summary.png) |
-->

---

## 🛠️ Tech Stack

**Framework:** Flutter (Dart)
**State Management:** Provider
**Local Storage:** Hive (`hive_flutter`, `hive_generator`, `build_runner`)
**Charts:** `fl_chart`

**Key Packages:**
`provider` · `hive_flutter` · `fl_chart` · `uuid` · `intl` · `flutter_slidable` · `google_fonts` · `path_provider`

---

## 📥 Download & Install

Want to try Expense Tracker on your Android device?

1. Go to the [**Releases**](../../releases) section of this repo
2. Download the latest `app-release.apk`
3. On your Android device, enable **"Install from unknown sources"** (Settings → Security)
4. Open the downloaded APK and install
5. Launch Expense Tracker and start tracking!

> 📌 **Note:** This app is for demonstration and testing purposes.

---

## 🔒 Source Code

This repository is a **showcase page** for the Expense Tracker project. The full source code is maintained in a private repository to protect the project's implementation. This repo contains project details, screenshots, and a downloadable APK for testing purposes.

---

## 💼 Hire Me

I'm a Flutter developer specializing in cross-platform mobile apps with clean, modern UI and solid state management. If you liked what you saw, let's talk about your project.

**Contra:** [Your Contra Profile Link]

---

<p align="center">Built with ❤️ using Flutter</p>
