# 🎓 UoH Alumni Directory Scraper

## 📌 Project Overview

This project is a **web scraping application** built using **Node.js, Express, Puppeteer, and jQuery** to extract and display alumni information from the University of Hyderabad alumni portal.

The system collects alumni data such as:

* Name
* Graduation Year
* Degree

The scraped data is:

* Stored in **CSV format**
* Served via an **API**
* Displayed on a **dynamic frontend dashboard**

---

## 🚀 Features

* 🔐 Automated login & scraping using Puppeteer
* 📊 Alumni data extraction (Name, Year, Degree)
* 📁 CSV file generation
* 🌐 REST API (`/api/alumni`)
* 💻 Interactive frontend with:

  * Search 🔍
  * Filters 🎯
  * Sorting 📊
  * Pagination 📄
* ⬇️ CSV download option

---

## 🛠️ Tech Stack

* **Backend:** Node.js, Express
* **Web Scraping:** Puppeteer
* **Frontend:** HTML, CSS, JavaScript (jQuery)
* **CSV Handling:** File System (fs), PapaParse

---

## 📂 Project Structure

```
project-folder/
│
├── server.js
├── package.json
├── public/
│   ├── index.html
│   ├── script.js
│   ├── style.css
│   └── alumni_data.csv
├── .gitignore
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone <your-repo-link>
cd project-folder
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Run the Application

```bash
node server.js
```

---

## 🌐 Usage

### Backend API

* Access alumni data:

```
http://localhost:3000/api/alumni
```

### Frontend

* Open in browser:

```
http://localhost:3000
```

---

## 📸 Project Output

### ✔ Scraping Process

* Automated login & navigation
* Batch-wise and department-wise data extraction

### ✔ Generated CSV

* Stored at:

```
public/alumni_data.csv
```

### ✔ Frontend Dashboard

* Displays alumni records dynamically
* Includes search, filters, pagination

---

## 🧠 How It Works

### 1. Scraping

The scraper uses Puppeteer to:

* Open alumni portal
* Login
* Navigate batches & departments
* Extract alumni details

👉 Implemented in:


---

### 2. Data Processing

* Extracted data stored in array
* Converted into CSV format
* Saved locally

---

### 3. API

Express server provides:

```
GET /api/alumni
```

Returns JSON data

---

### 4. Frontend

* Loads CSV using fetch
* Parses using PapaParse
* Displays in table

👉 UI Code:



---

## ⚠️ Important Notes

* Do NOT expose real credentials in code
* Use `.env` file for security
* Ensure scraping follows website policies

---

## 📦 Submission Requirements

The final submission ZIP file should contain:

* ✔ Source Code
* ✔ CSV Output File
* ✔ Screenshots of Execution
* ✔ README.md

👉 ZIP file name:

```
<YOUR_STUDENT_ID>.zip
```

---

## 📈 Future Enhancements

* Add company details (LinkedIn scraping if permitted)
* Deploy on cloud (Render / Vercel)
* Add authentication system
* Improve scraping efficiency

---

## 👨‍💻 Author

**Amartya Kunta**
University of Hyderabad
Integrated M.Tech CSE (2023–2028)

---

## ✅ Conclusion

This project demonstrates:

* Web scraping automation
* Backend API development
* Frontend data visualization
* Real-world data processing pipeline

---
