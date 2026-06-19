# HEMANTH OS v2.0 — GitHub Profile Banner

## Folder Structure

```
github-profile/
├── banner.svg          ← Place this in your repo root
└── README.md           ← Your GitHub profile README
```

---

## README Integration

Paste this at the very top of your `README.md`:

```html
<div align="center">
  <img src="./banner.svg" width="100%" alt="HEMANTH OS v2.0" />
</div>
```

Or if you prefer a raw GitHub URL (after pushing):

```html
<div align="center">
  <img src="https://raw.githubusercontent.com/hemanthgit1221/hemanthgit1221/main/banner.svg" width="100%" alt="HEMANTH OS v2.0" />
</div>
```

---

## Setup Steps

1. Create a **public repository** named exactly as your GitHub username
   - e.g., if your username is `hemanth-kumar`, repo name = `hemanth-kumar`

2. Place `banner.svg` in the **root** of that repository

3. Create or edit `README.md` and paste the integration snippet above

4. Commit and push — GitHub will auto-render it on your profile

---

## Notes

- SVG is fully self-contained — no external dependencies
- GitHub caches SVGs; if you update the file, append `?v=2` to bust cache:
  ```html
  <img src="./banner.svg?v=2" width="100%" />
  ```
- Animation plays on load and loops every ~10 seconds
- The banner is responsive — it scales with the viewer's screen width
- Tested compatible with GitHub's SVG rendering sandbox
