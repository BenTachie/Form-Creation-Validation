# 📝 Form Creation & Validation

Project Type: Frontend | Tech Stack: HTML5 · CSS3 · JavaScript (Vanilla)

A beginner-friendly yet practical project that demonstrates how to build user input forms with proper structure, styling, and real-time validation using only vanilla JavaScript. This section forms the foundation of many modern web applications where user input accuracy is essential.

---

## 📌 Project Highlights

✅ Custom form built from scratch  
✅ Real-time validation with visual feedback  
✅ Clean, responsive UI  
✅ Accessibility and usability considered  
✅ Extensible for backend integration or advanced validations

---

## 📂 File Structure
```
Form-Creation-Validation/
│
├── form.html # Main HTML structure of the form
├── form.css # Styling for layout and responsiveness
└── form.js # JavaScript logic for form validation
```

---

## 🧠 Features
```
| Feature                     | Description                                              |
|----------------------------|----------------------------------------------------------|
| 👁️ Real-time Feedback       | Instant feedback on required fields                      |
| 🔐 Input Validation         | Email format, password length, matching confirmation     |
| ✨ Styling Enhancements     | Clean layout with visual cues for success/errors         |
| 🚫 Prevent Default Behavior | Prevents form submission if errors exist                 |
```
---

## 📸 Sample Fields in the Form

<img width="1005" height="498" alt="image" src="https://github.com/user-attachments/assets/4b4d7eb1-eaf0-438f-9bfe-055683cb65b3" />

- Full Name
- Email Address
- Password & Confirm Password
- Gender (radio buttons)
- Country (dropdown)
- Terms & Conditions (checkbox)

---

## 🛠️ Technologies Used

- **HTML5** – for semantic structure  
- **CSS3** – for styling, layout, and responsiveness  
- **JavaScript** – for validation and interactivity

---

## 🚀 How to Run
```
1. Clone the repository or download the `Form-Creation-Validation` folder.
2. Open `form.html` in any modern browser.
3. Fill out the form to see validations in action.
4. Errors will be displayed inline; submit is blocked until all conditions are met.
```
---

## 🔍 Example Validation Logic

```
// Example: Email format validation
const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
if (!emailRegex.test(emailInput.value)) {
    showError("Invalid email format.");
}
```

## 🧪 Validation Rules Summary

- Field	Rule	Required?
- Full Name	Non-empty	✅
- Email	Must match email pattern	✅
- Password	Min. 6 characters	✅
- Confirm Password	Must match password	✅
- Gender	One must be selected	✅
- Country	Must be chosen (not default)	✅
- Terms Checkbox	Must be checked	✅

## 💡 Future Enhancements
✅ Integration with backend API for real submissions

🔐 Strength meter for passwords

🌐 i18n (multilingual support)

📱 Better mobile UX with input types

## 👨‍💻 Author
Benedict Tachie
Software Developer | Data Scientist | Digital Transformation Advocate
📬 GitHub Profile

>“Good software is like a well-written story—clear, engaging, and meaningful.”
