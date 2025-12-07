# Responsive Web Page – README

## 📘 Project Overview
This project is a responsive web page built using **HTML5** and **CSS3**. The page adapts automatically to different screen sizes and includes interactive hover states for links and buttons. The goal is to demonstrate mastery of responsive design principles and basic UI interaction behaviors.

---

## 🎯 Requirements Implemented

### ✅ Responsive Design
- The layout switches to a **mobile version when the screen width is 480px or less**.
- Implemented using CSS media queries.

### ✅ Content Layout
- All main content is constrained to a **maximum width of 1000px**.
- Content is centered on the page using `margin: 0 auto`.

### ✅ Interactions
- **Links** change color on hover/active:  
  `#FF6565`
- **Buttons** use a subtle hover/active effect:  
  `opacity: 0.9`

---

## 🛠️ Technologies Used
- **HTML5** – Semantic structure.
- **CSS3** – Layout, styling, responsiveness.

---

## 📐 Key CSS Implementations

### Max Width & Centering
```css
.container {
    max-width: 1000px;
    margin: 0 auto;
}

@media (max-width: 480px) {
    /* Mobile layout styles here */
}

a:hover,
a:active {
    color: #FF6565;
}
button:hover,
button:active {
    opacity: 0.9;
}

