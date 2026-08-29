# MDIC Arts & Crafts Club Website

Prototype website for the Arts & Crafts Club of Manarat Dhaka International School & College.

## Files
- `index.html` — main page
- `style.css` — design and responsive layout
- `script.js` — mobile navigation and small interactions

## Publish free with GitHub Pages

1. Create a new GitHub repository, for example `mdic-arts-crafts-club`.
2. Upload `index.html`, `style.css`, and `script.js` to the repository root.
3. Open the repository on GitHub.
4. Go to **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**.
7. Click **Save**.
8. GitHub will give you a public website URL after deployment.

## Important before official publication
This is a prototype. Ask the school/club for approval before presenting it as an official school website.

The hero currently loads a public photo of the Manarat campus from:
https://files.thedailycampus.com/assets/english/img/202506/1750939605_7ae4c21c7da7c7b39f3e.jpg

For a real school website, replace it with a school-owned photograph:
1. Put your photo inside `images/`, for example `images/manarat-school.jpg`
2. In `style.css`, find the `.hero` section.
3. Replace the image URL with:
   url("images/manarat-school.jpg")

Also replace demo event dates, club email and gallery cards with real content.
