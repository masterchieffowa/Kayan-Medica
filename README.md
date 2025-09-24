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

## 🖥️ How to Run

### 1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/kayan-medica.git
cd kayan-medica
````

### 2. Install dependencies

Make sure you have Python 3.8+ installed. Then install required packages:

```bash
pip install -r requirements.txt
```

<details>
<summary>Click to view requirements.txt</summary>

```txt
openpyxl
pillow
```

</details>

### 3. Run the app

```bash
python system.py
```

---

## 🗂️ Project Structure

```plaintext
kayan-medica/
├── system.py         # Main application script
├── db.xlsx           # Inventory data file (auto-created)
├── logo.png          # Optional logo for the GUI
├── .gitignore
└── README.md
```

> ⚠️ `store.db`, `image.jpg`, `dist/`, and other temp files are excluded via `.gitignore`.

---

## 📷 Screenshots (Optional)

> *You can upload screenshots of the GUI and link them here for GitHub previews.*

```markdown
![Screenshot](screenshots/main.png)
```

---

## 🌐 Links

* 📘 Facebook Page: [Kayan Medica](https://www.facebook.com/masrymedical/)
* 🔗 GitHub Repo: [github.com/YOUR\_USERNAME/kayan-medica](https://github.com/YOUR_USERNAME/kayan-medica)

---

## 📄 License

This project is proprietary and developed by Kayan Medica. Contact us for licensing or collaboration.

---

## 🙋‍♂️ Author

**Mahmoud**
\[Your GitHub Profile or Email]

---

## 🔄 Future Ideas

* Backup to cloud (Google Drive or Dropbox)
* Barcode scanner integration
* Print invoice or receipt generation

````

---

## ✅ What's Next?

1. **Save the above content** into a file called `README.md` in your project directory.
2. **Update your `.gitignore`** (if not done yet) to exclude sensitive or generated files:

```bash
# .gitignore
db.xlsx
store.db
*.jpg
*.ico
build/
dist/
__pycache__/
*.pyc
````

3. Then commit and push:

```bash
git add README.md .gitignore
git commit -m "Add README and gitignore"
git push origin main
```
