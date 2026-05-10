# 🍳 Recipe Finder (Teroka Resipi)

A simple and responsive web-based recipe finder app that allows users to search, explore, and discover meals using the [TheMealDB API](https://www.themealdb.com/).

---

## ✨ Features

- 🔍 **Search Recipes** — Search for any meal by name and browse through the results
- ➕ **Load More** — Results are paginated (3 at a time) with a "Lihat Lagi" button to load more
- 🎲 **Random Recipe** — Discover a surprise meal with the random recipe button
- 🔥 **Popular Searches** — Displays a curated list of popular meals on load (e.g. Nasi Lemak, Cheesecake, Fried Rice)
- 🌗 **Dark/Light Theme Toggle** — Switch between light and dark mode
- ▶️ **YouTube Links** — Each recipe card links directly to a YouTube cooking tutorial
- 📱 **Responsive Design** — Mobile-friendly layout that adapts to smaller screens

---

## 🚀 Getting Started

No installation or build tools required. This is a pure HTML/CSS/JavaScript project.

### Run Locally

1. Clone or download this repository
2. Open `index.html` in any modern web browser

```bash
git clone https://github.com/your-username/recipe-finder.git
cd recipe-finder
open index.html
```

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Page structure |
| CSS3 | Styling, animations, responsive layout |
| Vanilla JavaScript | Logic, API calls, DOM manipulation |
| [TheMealDB API](https://www.themealdb.com/api.php) | Recipe data source |

---

## 📡 API Reference

This project uses the free tier of **TheMealDB API**:

| Endpoint | Description |
|---|---|
| `search.php?s={name}` | Search meals by name |
| `random.php` | Fetch a random meal |

Base URL: `https://www.themealdb.com/api/json/v1/1/`

---

## 📁 Project Structure

```
recipe-finder/
└── index.html       # Main application file (HTML + CSS + JS)
```

---

## 🖼️ Preview

### Light Mode
> Search bar, recipe cards with images, and YouTube links displayed on a clean white background.

### Dark Mode
> Same layout with a dark background and adjusted accent colours for comfortable night-time browsing.

---

## 🌐 Language

The UI is primarily in **Bahasa Malaysia (Malay)**, with recipe content sourced in English from TheMealDB.

---

## 📌 Known Limitations

- Recipe data depends on TheMealDB availability; results may vary for less common dishes
- YouTube links may occasionally be missing for certain meals
- No user accounts or saved recipes feature (stateless app)

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request for improvements such as:

- Adding a favourites / bookmark feature
- Displaying full ingredient lists and cooking instructions
- Translating recipe content to Bahasa Malaysia

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> Built with ❤️ using HTML, CSS & JavaScript
