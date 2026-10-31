# My Favorite Person ♡

A small romantic website: a kitten welcome, a museum of favorite things, a red thread, a Heart Arcade of three tiny games with secret notes, and a final letter.

Live address: https://anabil-das.github.io/my-favorite-person/

## Files
- `index.html` — the whole website: the text, the styles, the games and the scripts. It works on its own.
- `assets/` — the pictures, the piano music and the icons. The page also carries built-in copies of these, so it still shows its pictures and plays its music if the folder is not available.

## Run it on your computer
Unzip the folder, then open `index.html` in a browser. Everything works offline, except the Google Fonts, which fall back to Georgia-style fonts.

## Publish on GitHub Pages
1. Create a public repository named `my-favorite-person` under your account (`anabil-das`).
2. Upload the **contents** of the `my-favorite-person` folder to the repository's top level, so that `index.html` and `assets/` sit directly in the root of the repository.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select the `main` branch and the `/ (root)` folder, then click **Save**.
5. Wait about one minute, then open https://anabil-das.github.io/my-favorite-person/

## Change the words
Open `index.html` in a text editor and search for `window.SITE_TEXT`. The block below it holds the three secret notes, the heart collection message and the final card. Keep the quotation marks and commas. Save the file and upload it again.

## Notes
- The music starts only after you press **YES ♡** or the **♪ Play music** button, never automatically.
- The page asks search engines not to list it (`noindex`).
