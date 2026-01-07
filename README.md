# ✅ Angular Reactive Form — Profile Submission & Validation

A focused **Angular** application built with **Reactive Forms** that collects user contact details, validates inputs with strict rules, and displays the submitted data in a clean summary table.

This project showcases practical form engineering: strong validation, clear error messaging, and a simple multi-page flow.

---

## ✨ Features

- 🧾 Reactive form with:
  - First Name (required)
  - Last Name (required)
  - Phone Number (optional, validated when provided)
  - Email (validated with Angular email validator)
- 🛡️ Validation rules:
  - First/Last Name: **required**
  - Phone (if provided):
    - **exactly 10 digits**
    - **1st and 4th digits are not `0`**
  - Email: must match a **valid email pattern**
- 🚦 Inline error messages for invalid input
- 📄 On successful submit, navigates to a new page and renders the user data in a **table**

---

## 🛠 Tech Stack

- **Angular**
- **TypeScript**
- **Reactive Forms (FormBuilder, Validators)**
- **HTML / CSS**

---

## 🚀 Run Locally

```bash
npm install
ng serve
```

Open: `http://localhost:4200`

---

## 🧠 What This Project Demonstrates

- Building robust **Reactive Forms**
- Custom validation logic (phone rules beyond basic patterns)
- UX-friendly form feedback (clear errors + valid submission flow)
- Simple routing for multi-page submission → review experience


---

📌 *A clean Angular form project focused on validation quality and user feedback.*
