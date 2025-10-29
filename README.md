# 📄 Modern HTML/CSS Resume

Yeh ek modern, professional, aur fully responsive 1-page resume website hai. Ise pure HTML5 aur CSS3 ka istemal karke banaya gaya hai.

Is project ka main focus advanced CSS layout techniques, animations, aur **print-friendly stylesheets** par hai.

<img width="307" height="414" alt="image" src="https://github.com/user-attachments/assets/01801791-412a-4315-a0f1-5f23cb90818f" />


## ✨ Key Features

* **Responsive 2-Column Layout:**
    * Ek sticky sidebar (`<aside>`) jo contact info aur skills dikhata hai.
    * Ek main content area (`<main>`) jismein summary, experience, aur projects hain.
    * Mobile screens par sidebar automatically main content ke upar stack ho jaata hai.

* **Animated Skills Bars:**
    * CSS variables (`--skill-percent`) aur `@keyframes` ka use karke skills visually animate hoti hain.

* **Vertical Timeline:**
    * Experience aur Education ko ek clean, vertical timeline mein dikhane ke liye CSS pseudo-elements (`::before`, `::after`) ka istemal kiya gaya hai.

* **Project Grid:**
    * CSS Grid ka use karke banayi gayi responsive card-based project gallery.

* **Print-Friendly ("Download as PDF"):**
    * `@media print` stylesheet ka istemal kiya gaya hai.
    * Jab user "Download as PDF" button par click karta hai, toh browser ka print dialog khulta hai.
    * Print stylesheet sidebar, buttons, aur social links ko hide kar deti hai, aur content ko ek clean, A4-friendly format mein style kar deti hai. User "Save as PDF" select karke resume export kar sakta hai.

---

## 🛠️ Technologies Used

* **HTML5:** Semantic tags (`<aside>`, `<main>`, `<section>`).
* **CSS3:**
    * **Flexbox:** Main 2-column layout ke liye.
    * **CSS Grid:** Project gallery ke liye.
    * **CSS Variables (`:root`):** Aasan theming aur maintenance ke liye.
    * **Pseudo-elements:** Timeline design ke liye.
    * **Animations (`@keyframes`):** Skills bars ko animate karne ke liye.
    * **Media Queries:** Responsive design (mobile, tablet, desktop) ke liye.
    * **`@media print`:** "Download as PDF" functionality ke liye.
* **Font Awesome:** Icons ke liye.

---

## 🚀 How to Use

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/sandeepyadav73/Online-Resume-Template/.git](https://github.com/sandeepyadav73/Online-Resume-Template/.git)
    ```
2.  **Open the file:**
    `index.html` file ko apne browser mein open karein.
3.  **Test the Print Feature:**
    "Download as PDF" button par click karein. Jab print dialog khule, destination ko "Save as PDF" set karein aur preview check karein.
