# 🎂 Tuba Birthday Surprise

A complete, GitHub Pages-ready birthday website for **Tuba**.

## Files

- `index.html` — the full website (HTML + CSS + JavaScript in one file)
- `assets/tuba.jpg` — the supplied birthday photo
- `assets/birthday-song.mp3` — the supplied instrumental song

Image size used: **864 × 1536 px**  
Audio file size: **3.07 MB**

## How it works

1. The page opens with a **3 → 2 → 1** countdown.
2. The birthday hero screen appears with Tuba's photo.
3. The button says **“Open This ✨”**.
4. When the button is pressed, the full birthday wishes and dua appear.
5. The supplied song starts **only after the button is clicked**, which also satisfies browser autoplay restrictions.
6. Floating hearts, flowers and sparkles animate around the page.
7. The ending shows **“Your Friend Irfan Joiya”** in large type.

## Put it on GitHub Pages

1. Create a new GitHub repository.
2. Upload **`index.html`** and the entire **`assets`** folder.
3. Open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**.
5. Select the branch containing `index.html` (usually `main`) and the `/ (root)` folder.
6. Save. GitHub will give you the website link.

### Important

Do not upload only `index.html`. The `assets` folder must stay beside it, with these exact paths:

```text
index.html
assets/
  tuba.jpg
  birthday-song.mp3
```

The code uses a relative path, so it works directly on GitHub Pages without changing the HTML.

## Optional customization

All main wording is already written in the page. To change the displayed friend name, search the HTML for:

```text
Your Friend Irfan Joiya
```

To change the page title, search for:

```text
Happy Birthday Tuba ✨
```
