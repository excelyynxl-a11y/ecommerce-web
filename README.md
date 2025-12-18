# 🛒 Next.js E-Commerce Platform

A modern **full-stack e-commerce web application** built with **Next.js 15**, **Tailwind CSS**, **Zustand**, and **Stripe**.  
The platform supports a complete shopping flow including cart management and secure checkout using Stripe.

> ⚠️ **Note:** The application is currently configured to run in **Stripe Test Mode** due to account limitations (baby girl still doesnt have a MyTIN).  
> With a fully verified Stripe account, **real payments can be processed without any code changes**.

---

## ✨ Features

- 🛍️ Product listing page
- 🧺 Shopping cart 
- 💳 Secure checkout with Stripe
- 🧾 Order summary & payment confirmation
- 📱 Rsponsive UI
- 🎨 Clean UI with Tailwind CSS
- ⚡ App Router & Server Actions (Next.js 15)

---

## 🧠 Tech Stack

| Technology     | Usage |
|----------------|-------|
| **Next.js 15** | App Router, Server Components |
| **Tailwind CSS** | Styling & responsive layout |
| **Zustand** | Global state management (cart) |
| **Stripe** | Payment processing |
| **TypeScript** | Type safety |

---

## 💳 Stripe Integration

The application uses **Stripe Checkout** for payment processing.

### Current Status
- ✅ Stripe **Test Mode** enabled
- ❌ Live payments disabled (no verified Stripe account / MyTIN)

### Important
Once a **fully verified Stripe account** is connected:
- Real payments can be accepted
- No code changes required
- Simply replace test keys with live keys

---

## 👾 Demo
For the payment section, feel free to use some mock card detail provided by Stripe as below (trust me its safe to use):
- Brand: VISA
- Number: 4242424242424242
- CVC: any 3 digits (eg: 999)
- Date: any future date (eg: 12/28)

### 👧 Try now:
**Deployed on Vercel:** ()
