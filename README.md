# 🖼️ UiPath Script for Bulk NFT Minting on Mintable.com
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)


This repository contains a **UiPath automation workflow** designed to **bulk mint NFTs** on [Mintable.com](https://mintable.com) efficiently.  
It automates repetitive tasks such as uploading files, filling metadata, and confirming minting actions — saving hours of manual work.

---

## 🚀 Features

- **Bulk NFT Minting** – Automates the process of uploading multiple NFTs.
- **Custom Metadata Support** – Add title, description, category, and tags automatically.
- **Error Handling** – Skips failed entries and logs errors for review.
- **CSV Integration** – Reads NFT data from a CSV/Excel file for structured bulk uploads.
- **Mintable.com Integration** – Works with Mintable's web interface via UiPath automation.

---

## 📂 Project Structure

📁 UiPath-Bulk-NFT-Minting  
├── Main.xaml &nbsp;&nbsp;# Main UiPath workflow  
├── Config.xlsx &nbsp;&nbsp;# NFT metadata configuration file  
├── Assets/ &nbsp;&nbsp;# NFT images or files to be minted  
├── Logs/ &nbsp;&nbsp;# Execution logs  
└── README.md &nbsp;&nbsp;# Project documentation  


---

## ⚙️ Requirements

- [UiPath Studio](https://www.uipath.com/product/studio) (tested on version 2023.x)
- Mintable.com account (with wallet connected)
- Stable internet connection
- NFT files ready for upload (images, videos, etc.)
- Metadata file in CSV/Excel format

---

## 📌 How It Works

1. **Prepare your NFT assets** in the `Assets` folder.  
2. **Fill metadata** (title, description, tags) in `Config.xlsx` or your CSV file.  
3. **Open UiPath Studio** and run `Main.xaml`.  
4. The bot will:
   - Log in to Mintable.com
   - Navigate to the minting section
   - Upload each NFT
   - Fill in metadata and confirm minting
   - Log any errors for review

---

## 🔒 Notes

- The script only automates **publicly available UI interactions** — it does **not** hack or bypass any security measures.
- Use this automation **only with your own content** to comply with copyright laws.
- Minting fees (if applicable) are the responsibility of the user.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
