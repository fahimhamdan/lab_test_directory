# HKL Pathology Test Directory

This project provides a **dynamic test directory** for HKL Pathology Lab, powered by **Google Sheets** as the backend database.  
The webpage fetches data directly from Google Sheets and displays it in a searchable, filterable format.

---

## ✨ Features
- **Dynamic data** fetched live from Google Sheets (no need to manually update HTML).
- **Search bar + filter options**:
  - By **Test Name** (column 1)
  - By **Performing Lab** (column 2)
  - By **Specimen Type** (column 4)
- **Clean table view**: shows only *Test Name* with an **Action (View button)**.
- **Modal popup**: when clicking **View**, it shows full test details (all columns from Google Sheet).
- **Responsive UI** with modern styling.
- **Footer** credit: `Designed by Fahim Hamdan`.

---

## 🛠 How It Works
1. Data is stored in a **Google Sheet** (linked via sheet ID).  
2. The HTML page fetches the sheet data using the Google Visualization API.  
3. Data is displayed dynamically in a searchable & filterable table.  
4. Clicking on **View** opens a modal with detailed information.

---

## 📂 File Structure
- `index.html` → main webpage (open directly in a browser or host via GitHub Pages).
- `README.md` → this documentation.

---

## 🚀 Deployment Options
- **Local**: Just double-click `index.html` to open in a browser.  
- **Google Sites**: Embed using `<iframe>` if needed.  
- **GitHub Pages**: Push to a GitHub repo and enable Pages for free hosting.

---

## 📝 Notes
- Make sure your Google Sheet is **published to the web** and accessible for the data to load.  
- Column mapping used in this project:  
  - `1 = Test Name`  
  - `2 = Performing Lab`  
  - `4 = Specimen Type`  

---

## 👨‍💻 Credits
Designed by **Fahim Hamdan**
