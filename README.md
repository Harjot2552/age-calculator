# Age Calculator ⏰

## 🔗 Project Overview
The **Age Calculator** is a simple web-based tool built with HTML, CSS, and JavaScript. It allows users to input their date of birth and instantly get their exact age in years, months, and days.

---

## 🔧 Features
- ✨ Clean and user-friendly interface.
- ⌚ Calculates the user's precise age based on the current date.
- ⏳ Automatic date validation to prevent selecting future dates.

---

## 🔒 How to Use
1. Open the **Age Calculator** in your browser.
2. Select your **date of birth** using the date picker.
3. Click on the **Calculate** button.
4. View your age in **years, months, and days**.

---

## 🗒 Code Explanation

### HTML Structure
- Contains a `div` container with the calculator title, input field for selecting the date, and a button to trigger the calculation.
- Displays the calculated result in a `p` element.

### JavaScript Logic
- **Event Handling:** Triggers the age calculation when the button is clicked.
- **Age Calculation:**
  - Extracts and compares the current date with the selected birth date.
  - Computes the difference in years, months, and days.
  - Handles edge cases such as leap years and month boundary adjustments.
- **Date Validation:** Ensures users cannot select dates in the future by setting the `max` attribute of the date input field to today's date.

### Key Functions
- `calculateAge()`: Main function to calculate and display the user's age.
- `getDaysInMonths(year, month)`: Helper function to get the number of days in a given month.

---

## 📊 Example Output
```
You are 25 years, 3 months, and 15 days old.
```

---

## 🎨 Styling
The calculator uses **CSS** to style the layout, providing a visually clean design with:
- Proper alignment of elements.
- Highlighted results for better readability.

---

## 🚀 Future Improvements
- Add support for multiple date formats.
- Include animations for a smoother user experience.
- Display the user's next birthday countdown.

---

## 📚 Project Structure
```
Age Calculator
├── index.html   # Main HTML file
├── style.css    # Styles for the calculator UI
└── index.js     # JavaScript for age calculation logic
```

---

## 🎉 Conclusion
This project demonstrates how basic web technologies can be combined to create useful, interactive tools. Happy coding! ✨

