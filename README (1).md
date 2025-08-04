
# 🚀 Responsive Navbar using HTML & CSS

This project is a **modern, responsive navigation bar** built using **only HTML and CSS**, without any JavaScript. It includes an image-based logo, smooth hover effects, and a clean design suitable for any website.

---

## 📸 Preview

![Navbar Preview](./images/logo.png) 

---

## 📁 Project Structure

```
responsive-landing-page/
├── index.html
├── style.css
└── images/
    └── logo.png
```

---

## 🌟 Features

- ✅ Fully responsive on all screen sizes  
- ✅ Logo image instead of text  
- ✅ Navigation links with hover effects  
- ✅ No JavaScript  
- 🎨 Easily customizable

---

## 🧪 Technologies Used

- **HTML5**
- **CSS3**
  - Flexbox
  - Media Queries
  - Transitions

---

## 🖥 Demo

You can preview the navbar locally by opening the `index.html` file in any browser:

```
Right-click → Open with → Browser
```

---

## 🔧 How to Customize


### ✍️ Edit Links
<ul class="nav-links">
  <li><a href="#home">Home</a></li>
  <li><a href="#about">About</a></li>
  <li><a href="#services">Services</a></li>
  <li><a href="#contact">Contact</a></li>
</ul>
```

### 🎨 Change Colors, Fonts, Layout
Open `style.css` and modify:
```css
:root {
  --main-color: #007bff;
  --text-color: #fff;
  --hover-color: #0056b3;
  --font-family: 'Poppins', sans-serif;
}
```

---

## 📜 Sample HTML Snippet

```html
<header class="navbar">
  <div class="logo">
    <img src="images/logo.png" alt="Elevate labs">
  </div>
  <nav>
    <ul class="nav-links">
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Projects</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>
</header>
```

---

## 💡 Responsive Tips

- `@media` queries are used for small screen adjustments.
- You can add a hamburger menu with CSS `:checked` trick if needed (still no JS).

---

## 🛠️ Future Improvements

- Add dropdown menus (CSS-only)
- Hamburger menu for mobile (checkbox hack)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙌 Author

Made with ❤️ by [Arvind Kumar](https://github.com/arvindthakur21)
