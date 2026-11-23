DIGITAL ORDER BOT

A Telegram-based Digital Product Store with Automated Payment & Delivery System.

Digital Order is a Node.js Telegram bot designed to manage digital product sales, process payments, and deliver purchased products automatically.

---

Overview

Digital Order provides a simple product management and order processing system directly through Telegram. Owners can manage their product catalog, configure payment methods, and monitor customer transactions without requiring a separate dashboard.

Features

Feature| Description
Auto QRIS| Automatic invoice creation and payment verification
Manual Payment| Custom payment methods with admin verification
Product Management| Add, view, activate, deactivate, and delete products
Product Image| Optional product thumbnails
Digital Delivery| Automatic delivery after payment confirmation
Order Management| View and monitor customer orders
Owner Panel| Manage store settings directly through Telegram
File Backup| Store product files locally
Persistent Data| JSON-based database storage

Payment System

Auto QRIS

- Integrated with Lz Pedia API.
- Automatic invoice generation.
- QRIS payment display or payment link.
- Automatic payment status verification.
- Invoice expiration handling.

Manual Payment

- Add custom payment methods.
- Set payment instructions.
- Optional QR payment image.
- Customer submits payment proof.
- Owner verifies and approves or rejects payment.

Product Management

The owner can manage products directly from Telegram.

- Add new products.
- Set product name and description.
- Set product price.
- Upload optional product images.
- Add digital content for delivery.
- Activate or deactivate products.
- Delete existing products.

Supported digital delivery content:

- Text
- Links
- Documents
- Photos
- Videos
- Audio

Requirements

- Node.js
- Telegram Bot Token
- Telegram Owner ID
- Lz Pedia API Key (for Auto QRIS)

Available settings:

- Configure Auto QRIS API Key.
- Enable or disable Auto QRIS.
- Enable or disable Manual Payment.
- Add custom payment methods.
- Remove existing payment methods.

Technologies

- Node.js
- Telegram Bot API
- Axios
- JSON Database
- Lz Pedia Payment API

Developer

Created by: MexxTampan
GitHub: https://github.com/MexxModss

License

This project is licensed under the MIT License.

Free to use, modify, and develop. Please retain the original developer credits when redistributing this project.

---

<p align="center">
  <b>DIGITAL ORDER BOT</b><br>
  Built for simple and efficient digital product automation.
</p>
