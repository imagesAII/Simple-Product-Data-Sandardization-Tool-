# Product Data Standardization Tool

A lightweight, browser-based **Product Data Standardization Tool** built using **HTML, CSS, and JavaScript**. This tool works like a mini CMS designed to clean, validate, normalize, and export product data for e-commerce, cataloging, and data quality use cases.

---

## 🚀 Features

### ✅ Product Management

* Add new products manually
* Inline editing directly inside the table
* Edit product details via a modal inspector
* Delete selected products
* Import products from a JSON file
* Quick-add products using a JSON array input
* View selected product details in real-time JSON format

### 🧪 Validation

* Detect missing required fields: `title`, `sku`, `price`, `category`
* Detect invalid values:

  * Non-numeric price
  * Bad SKU formatting (allowed: A–Z, 0–9, -, _)
* Shows real-time summary of missing, invalid, and mapped products

### 🔧 Normalization

* Trims extra spaces from all product fields
* Converts product titles to Title Case
* Converts SKU to uppercase
* Formats price to two decimals

### 🗂️ Category Mapping

* Auto-detect product category based on keywords in the title/description
* Mapping examples:

  * "tshirt" → Clothing
  * "charger" → Electronics
  * "shampoo" → Personal Care

### 🪄 Auto-fill Missing Fields

* Generates SKU when missing
* Auto-creates title from description
* Sets default price if missing
* Attempts automatic category mapping

### 💾 Import / Export

* Import products via `.json` file
* Export all products into a structured JSON file

---

## 🎨 UI / UX Enhancements

The advanced UI includes:

* Dark navy-blue gradient theme
* Glass-morphism cards
* Neon blue accents
* Smooth hover animations
* Glow effect on button click

---

## 📁 Project Structure

```
/ (root)
│
├── index.html        # Main UI + full logic
├── README.md         # Project documentation
└── assets/ (optional) # Any future assets or images
```

---

## 🧩 How It Works

### 1. Add a Product

Click **Add Product** → Edit details → Save.

### 2. Validate

Checks for missing/invalid fields and shows badge in table.

### 3. Normalize

Cleans and formats data for consistency.

### 4. Map Categories

Automatically assigns categories using keyword rules.

### 5. Export JSON

Downloads the entire product list as a `.json` file.

### 6. Import JSON

Select any valid `.json` file containing a product array.

---

## 🔧 Technologies Used

* **HTML5** – Structure
* **CSS3** – Styling, animations, glow effects
* **JavaScript (Vanilla)** – All logic, validation, normalization, CRUD operations

No frameworks, no back-end — everything runs in the browser.

---

## 🛠️ Setup Instructions

1. Download or clone the repository:

   ```bash
   git clone https://github.com/yourusername/product-standardization-tool.git
   ```
2. Open `index.html` in any modern browser.
3. Start adding, validating, cleaning, and exporting product data.

---

## 📷 Screenshots (Optional)

You can add screenshots here after hosting or pushing to GitHub.

---

## 📝 Future Enhancements (Optional Ideas)

* CSV and Excel import/export
* Duplicate product detection
* Bulk edit mode
* AI-based category prediction
* Cloud database sync
* Dark/Light mode toggle

---

## 👨‍💻 Author

Developed by **Pratik Salve using ChatGPT**.

If you use this tool or enhance it, feel free to contribute or open issues!

---

## ⭐ Show Your Support

If you found this useful, please star ⭐ the repository on GitHub!


