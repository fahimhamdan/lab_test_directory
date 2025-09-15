# HKL Pathology Test Directory

A simple, responsive, and dynamic web-based directory for pathology tests at **Hospital Kuala Lumpur (HKL)**.  
The test list is powered by **Google Sheets** and displayed using **DataTables** with a clean blue-white HKL theme.

---

## ✨ Features
- **Dynamic data**: Automatically fetches test list from Google Sheets.
- **Searchable**: Real-time search (by test name, lab, or specimen).
- **Filterable & paginated**: Built-in DataTables filtering + pagination.
- **Responsive design**: Works seamlessly on desktop, tablet, and mobile.
- **View details modal**: Click `View` to see complete test details (excluding unique `No Test` key).
- **Polished UI/UX**: Blue & white theme consistent with HKL branding.
- **Footer branding**: Displays “Designed by Fahim Hamdan”.

---

## 🛠️ Setup

1. Clone or download this repository.
2. Open `index.html` in your browser, OR host it using GitHub Pages / any static server.
3. Ensure your Google Sheet is:
   - **Published to the web**, and
   - Accessible via **CSV/JSON link** (already configured in code).

---

## 📄 Google Sheet Requirements
- First column = **No Test** (unique key, not shown in modal).
- Other columns (e.g. Test Name, Performing Lab, Specimen Type, Turnaround Time, etc.) will automatically display in the modal.

Example structure:

| No Test | Test Name   | Performing Lab | Turnaround Time | Specimen Type |
|---------|------------|----------------|-----------------|---------------|
| 001     | Renal Test | Biochemistry   | 2 days          | Blood         |

---

## 🚀 Deployment
- **Option 1**: Embed directly in Google Sites using `<iframe>` (not recommended for full layout control).
- **Option 2**: Deploy as standalone webpage (recommended).
  - GitHub Pages
  - Netlify
  - Vercel
  - Any static hosting

---

## 👨‍💻 Developer Notes
- Built with:
  - [Bootstrap 5](https://getbootstrap.com/)
  - [jQuery](https://jquery.com/)
  - [DataTables](https://datatables.net/)
- Modify `sheetID` and `sheetName` in `index.html` if your Google Sheet changes.

---

## 📌 Credits
Designed by **Fahim Hamdan**  
