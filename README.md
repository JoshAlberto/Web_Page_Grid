# Web_Page_Grid

This project is a **2×2 web viewer grid** that allows you to load and display multiple web pages at the same time inside a single screen using `iframe` elements.

Each cell in the grid works as an independent panel with its own controls and state.

---

## ✨ Features

- **Responsive 2×2 grid layout**, automatically adapts to the screen size.
- **Four independent web panels**, each with its own URL, zoom level, and refresh state.
- **URL input field** to load any website.
- **Go button** to navigate to the entered URL.
- **Refresh button (↻)** to reload the current page.
- **Zoom controls (+ / −)** per panel to scale the iframe content.
- **Loading spinner overlay** displayed while the page is loading.
- **Automatic URL normalization**, adds `http://` when missing.
- **Modern dark UI** with a clean and minimal interface.

---

## 🚀 How It Works

Each panel is built dynamically from an HTML `<template>` and contains:

- A control bar with input and action buttons.
- An `iframe` container to display the loaded website.
- A loading overlay that activates while the iframe is fetching content.

The JavaScript logic handles:

- URL normalization.
- Independent zoom management per panel.
- Reloading content.
- Displaying and hiding the loading indicator.

---

## 🧭 Use Cases

This tool is perfect for:

- Monitoring multiple websites at once.
- Comparing different versions or environments of a web application.
- Viewing multiple dashboards or admin panels in parallel.
- Performing visual QA tests without opening multiple browser tabs.

---

## 🛠 Tech Stack

- **HTML5**
- **CSS Grid & modern UI styling**
- **Vanilla JavaScript (no frameworks)**

---

## 📸 Preview

Open the HTML file in your browser and start loading websites into each panel.

Enjoy your multi-site monitoring dashboard! 😎
