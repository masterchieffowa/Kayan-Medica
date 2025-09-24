# 🏥 Kayan Medica Inventory & Sales Management System

A simple yet powerful desktop application built using Python and Excel for managing inventory, purchases, and sales in small to medium-sized medical or retail businesses.

**Developed by [Kayan Medica](https://www.facebook.com/masrymedical/)**

---

## 📌 Overview

This application is designed to be an all-in-one solution for managing inventory, tracking purchases, recording sales, and generating reports. It provides a user-friendly **Arabic interface** and stores all data in a local Excel file (`db.xlsx`), making it extremely portable and easy to back up.

---

## 🎯 Features

- 📦 **Inventory Management**: Add, update, and view stock details with full and current quantity.
- 🛒 **Purchase Logging**: Add new stock, automatically update existing inventory.
- 💸 **Sales Recording**: Register sales with profit calculation and payment methods.
- 📊 **Reports**: Filter reports by date and item, export as CSV or Excel.
- 🖼️ **Logo Support**: Add your company logo (`logo.png`) to the GUI.
- 🌐 **All UI in Arabic** for better accessibility in local businesses.

---

## 🖥️ How to Run the App

### 1. Requirements

- ✅ Python **3.8 or newer**
- ✅ The following Python libraries:
  - `openpyxl`
  - `pillow` (for image/logo support)

Install them via pip:

```bash
pip install openpyxl pillow
````

---

### 2. Download the Project Files

Simply download the following files into a folder:

* `file1.py` → Main application file
* `logo.png` → (Optional) Your business logo
* `db.xlsx` → No need to create; it will be auto-generated on first run

Alternatively, if hosted on GitHub:

```bash
git clone https://github.com/masterchieffowa/Kayan-Medica.git
cd kayan-medica
```

---

### 3. Run the App

In the same directory where `file1.py` is located, run:

```bash
python file1.py
```

That’s it! The application GUI will launch, and you can begin managing your inventory.

---

## 🗂️ Project Structure

```plaintext
kayan-medica/
├── file1.py          # Main application script
├── db.xlsx           # Inventory data file (auto-created if missing)
├── logo.png          # Optional logo for the GUI
├── README.md         # You're reading it
└── .gitignore        # Optional, for version control
```

> ⚠️ Do not delete `db.xlsx` unless you want to reset all stored data.

---

## 🌐 Links

* 📘 Facebook Page: [Kayan Medica](https://www.facebook.com/masrymedical/)
* 🔗 GitHub Repo: [github.com/masterchieffowa/Kayan-Medica](https://github.com/masterchieffowa/Kayan-Medica)

---

## 📄 License

This project is **proprietary** and developed by **Kayan Medica**.
Contact us for licensing, custom features, or collaboration.

---

## 🙋‍♂️ Author

**Mahmoud**
📧 \[mahmmoudadel607@gmail.com](mailto:mahmmoudadel607@gmail.com)
🔗 [GitHub Profile](https://github.com/masterchieffowa)

---

## 🔄 Future Features (Ideas)

* Backup to cloud (Google Drive, Dropbox)
* Barcode scanner support
* Receipt or invoice printing
* Multi-user access with permissions

---

## ✅ Quick Notes

* The app is fully local (no internet required after install)
* Excel file can be backed up or shared easily
* Best suited for **Arabic-speaking local businesses**

````
