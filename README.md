Digital Order Bot

A Telegram-based digital product store with automated QRIS payments, manual payment verification, product management, and automatic digital delivery.

Features

- Auto QRIS Payment — Integrated with Lz Pedia API.
- Manual Payment — Custom payment methods with admin verification.
- Product Management — Add, view, activate, deactivate, and delete products.
- Product Images — Optional product thumbnails.
- Automatic Delivery — Deliver digital products after successful payment verification.
- Order Management — Store and monitor customer orders.
- Owner Panel — Manage products, payments, API keys, and transactions directly through Telegram.
- Local File Backup — Store product files inside "product_files".
- Persistent Storage — JSON-based local database.

Requirements

- Node.js
- Telegram Bot Token
- Telegram Owner ID
- Lz Pedia API Key (for Auto QRIS)

Installation

git clone YOUR_REPOSITORY_URL
cd Digital-Order
npm install

Configure "config.js":

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

Run the bot:

npm start

Payment Methods

Method| Description
Auto QRIS| Invoice creation and automatic payment status checking
Manual| Admin verifies the submitted payment proof

Project Structure

Digital-Order/
├── config.js
├── index.js
├── package.json
├── database/
│   ├── orders.json
│   ├── products.json
│   ├── payment_methods.json
│   └── store_settings.json
├── lib/
│   ├── database.js
│   ├── payment.js
│   └── utils.js
├── media/
│   └── store_banner.png
├── plugins/
│   └── digital_store.js
└── product_files/

Developer

Created By: MexxTampan
GitHub: MexxModss

License

MIT License

Free to use, modify, and develop further. Please retain the original credits when redistributing.
