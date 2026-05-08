# Brac University Course Material (CSE)

A premium, responsive web application for Brac University students to easily access and search for course materials hosted on Google Drive.

## 🚀 Features

- **Smart Search**: Quickly find courses by name.
- **Sorting**: Organize courses alphabetically (A-Z or Z-A).
- **Responsive Design**: optimized for both desktop and mobile devices.
- **Dynamic Contact**: 
  - **PC**: Opens Gmail web interface for quick emailing.
  - **Mobile**: Automatically triggers the Gmail app (or default mail client).
- **Modern UI**: Features glassmorphism, smooth animations, and a sleek dark/light mode aesthetic.

## 🛠️ Technology Stack

- **HTML5**: Semantic structure.
- **CSS3**: Vanilla CSS with custom properties, backdrop filters, and animations.
- **JavaScript (ES6+)**: Dynamic course rendering and device detection.
- **JSON**: Data-driven architecture via `courses.json`.

## 📁 Project Structure

- `index.html`: The main application file.
- `courses.json`: Contains the course data (names, Google Drive links, and sub-links).

## 💻 How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/dev-apurbo/course-material.git
   ```
2. **Run locally**:
   Simply open `index.html` in any modern web browser.

## 📝 Adding New Courses

To add or update courses, modify the `courses.json` file:

```json
{
  "courses": [
    {
      "name": "CSE110",
      "googleDriveLink": "YOUR_LINK_HERE",
      "subLinks": [
        { "label": "Notes", "url": "LINK_1" },
        { "label": "Slides", "url": "LINK_2" }
      ]
    }
  ]
}
```

## ❤️ Contribution

If you want to contribute files or suggest changes, please contact us at [code.cse.bracu@gmail.com](mailto:code.cse.bracu@gmail.com).

---
*Made with ♥ for Bracu Students*
