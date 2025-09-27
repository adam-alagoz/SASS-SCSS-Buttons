# SASS/SCSS Button Showcase + Dark Theme Demo

This project demonstrates two buttons styled with **SASS (SCSS)** and a **dark theme toggle (🌙)** button.

- 🟦 **Rectangular Button** → shows default, hover, and focus states
- 🔘 **Disabled Button** → shows disabled states
- 🌙 **Dark Theme Toggle** → switches between light and dark mode
- 📱 **Responsive Design** → works on smaller screens (mobile-friendly)

---

## 🚀 Getting Started

Follow the steps below to run the project locally:

### 1. Clone the repository

```bash
git clone https://github.com/your-username/SASS-SCSS Button Showcase.git
cd button-states-demo
```

### 2. Initialise the project

```bash
npm install
npm init -y
```

### 3. Install dependencies

```bash
npm install sass --save-dev
```

### 4. Add the SASS script

In your `package.json`, add the following under `"scripts"`:

```json
"scripts": {
    "sass": "sass scss/:css/ --watch"
}
```

### 5. Run SASS in watch mode

```bash
npm run sass
```

This command will watch all `.scss` files in the `scss/` folder and compile them into the `css/` folder.

### 6. Open the project in your browser

```bash
open index.html
```

or on Windows:

```bash
start index.html
```

---

or you may use Live Share VSCode extension

## 📂 Project Structure

```
button-states-demo/
│
├── index.html          # Main HTML file
├── package.json        # Project configuration
├── css/
│   ├── main.css        # Compiled CSS
│   └── main.css.map
└── scss/
    ├── main.scss       # Main SCSS file
    ├── abstracts/      # Variables and mixins
    │   ├── _variables.scss
    │   ├── _mixins.scss
    │   └── _index.scss
    ├── base/           # Reset and typography
    │   ├── _reset.scss
    │   └── _typography.scss
    └── components/     # Buttons and toggle
        ├── _buttons.scss
        └── _dark-toggle.scss
```

---

## 🎨 Features

- **Button Styles**
  - Default, hover, and focus states
  - Disabled button
- **Dark Theme**
  - Toggle button allows switching between light and dark mode
- **Responsive Design**
  - Mobile-first approach
  - Breakpoints handled via `@media` queries and mixins
- **SCSS Modular Architecture**
  - Clean folder structure with `abstracts/`, `base/`, `components/` and `layout/`

---

## ✅ Technologies Used

- **HTML5**
- **SASS (SCSS syntax)**
- **Node.js & npm (for SASS compiler)**

---
