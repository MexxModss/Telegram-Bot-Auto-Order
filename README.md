Telegram Digital Product AutoOrder | Node.js

Automated Telegram digital product store built with Node.js and Telegram Bot API. Supports product management, Auto QRIS payment integration, manual payment verification, and automatic digital product delivery.

Developer: "@MexxTampan" (https://t.me/MexxTampan)
GitHub: "MexxModss" (https://github.com/MexxModss)

✨ Key Features

- Product Management: Add, edit availability, view, and delete digital products directly through Telegram
- Auto QRIS Payment: Integrated with Lz Pedia API for automatic invoice generation and payment status checking
- Manual Payment: Custom payment methods with payment proof submission and owner verification
- Automatic Delivery: Automatically sends digital products after successful payment confirmation
- Product Media: Supports product photos and optional thumbnails
- Multiple Delivery Types: Text, links, documents, photos, videos, and audio
- Order Management: Track customer orders and payment status
- Owner Panel: Manage products, payment settings, and orders directly from Telegram
- Local File Backup: Stores product files in the "product_files" directory
- JSON Database: Persistent storage for products, orders, payment methods, and store settings

🛠️ Tech Stack

- Runtime: Node.js
- Framework: node-telegram-bot-api
- HTTP Client: Axios
- Database: JSON-based storage
- Payment Gateway: Lz Pedia API
- Additional Libraries: Chalk, Form-Data

🚀 Installation

VPS / RDP / Termux

1. Clone repository
   
   git clone https://github.com/MexxModss/Digital-Order.git
cd Digital-Order

2. Install dependencies
   
   npm install

3. Configure bot
   
   Open "config.js" and configure your credentials:
   
   module.exports = {
  token_Bot: 'BOT_TOKEN',
  owner_Id: 'ID_OWNER',
  botname: 'Digital Store',
  version: '1.0.0',
  saluran1: {
    text: 'Testimoni',
    url: 'https://t.me/mexxoffc'
  },
  saluran2: {
    text: 'Informasi',
    url: 'https://t.me/mexxhacking'
  },
  lzpediaApiKey: 'APIKEY_API'
};

4. Start bot
   
   npm start

Payment Configuration

- Get your API Key from "Lz Pedia" (https://app.lzpedia.my.id).
- Set the API Key in "config.js".
- Configure Auto QRIS through the Owner Panel.
- Manual payment methods can be managed directly through the bot.

📁 Project Structure

Digital-Order/
├── config.js
├── index.js
├── package.json
├── database/
├── lib/
├── media/
├── plugins/
└── product_files/

📌 Notes

- Keep your Bot Token and API Key private.
- Product and order data are stored locally.
- Back up the "database" and "product_files" directories regularly.
- Auto QRIS requires a valid Lz Pedia API Key.

📄 License

MIT License

Free to use, modify, and develop. Please keep the original developer credits.

---

<p align="center">
  <b>Digital Order</b><br>
  Simple Digital Product Automation.
</p>
