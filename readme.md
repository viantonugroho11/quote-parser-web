# Comma & Quote Parser

![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen?logo=github)
![License](https://img.shields.io/badge/License-MIT-blue.svg)

A simple **frontend-only** web tool to convert text separated by **newline / comma / space** into:
- Quoted comma-separated values (`"`, `'`, `` ` ``)
- JSON array

Designed for developers who often need to quickly format UUIDs, IDs, or raw text for **SQL**, **API payloads**, or **config files**.

🔗 **Live Demo (GitHub Pages)**  
`(https://viantonugroho11.github.io/quote-parser-web/)`

---

## ✨ Features

- ✅ Multiple input separators (checkbox-based)
  - Newline
  - Comma
  - Space
- ✅ Quote output options
  - Double quotes `"value"`
  - Single quotes `'value'`
  - Backticks `` `value` ``
- ✅ Auto-remove duplicate values (optional)
- ✅ Generate JSON array
- ✅ Copy output / copy JSON to clipboard
- ✅ Frontend-only (no backend, no build step)
- ✅ Works perfectly on **GitHub Pages**

---

## 📸 Example

**Input**
```
2a72aa85-95d7-4417-beef-86222dba265f
41c72dce-a36e-4f16-9a81-57aa72fc77ce
```

**Output (Double Quotes)**
```
"2a72aa85-95d7-4417-beef-86222dba265f","41c72dce-a36e-4f16-9a81-57aa72fc77ce"
```

**JSON Output**
```json
[
  "2a72aa85-95d7-4417-beef-86222dba265f",
  "41c72dce-a36e-4f16-9a81-57aa72fc77ce"
]
```

---

## 🚀 Deploy to GitHub Pages

1. Create a new GitHub repository
2. Add the `index.html` file to the root of the repo
3. Go to **Settings → Pages**
4. Set:
   - Source: `Deploy from a branch`
   - Branch: `main` / root
5. Save

Your site will be available at:
```
https://<your-username>.github.io/<repo-name>/
```

---

## 🛠️ Tech Stack

- HTML5
- Vanilla JavaScript
- CSS (no framework)

No dependencies, no bundler, no backend.

---

## 🎯 Use Cases

- Formatting UUIDs for `SQL IN (...)`
- Preparing JSON arrays for API requests
- Cleaning copied data from spreadsheets
- Quick developer utility / scratchpad

---

## 📄 License

MIT License

---

## 🙌 Contributing

Feel free to open issues or submit PRs for:
- New presets (SQL IN, No-Quote mode)
- Validation (UUID / number detection)
- UI improvements
- Additional separators

Happy hacking! 🚀

