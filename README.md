# Beyond The Stories — responsive scroll website (v3)

Open `index.html` in a browser, or serve with `python3 -m http.server 8000`.

## Changes
- Sticky 390vh cinematic hero with scroll-driven headline drift in opposite horizontal directions, zooming photo and photo layers.
- Scroll-driven horizontal editorial section, additional photographic parallax, and responsive layouts.
- Real photographic Unsplash image URLs (not AI-generated illustrations). Images require internet. Photos are editorial placeholders, **not** Shah Digital Marketing or Beyond The Stories work.
- Image URLs are deliberately easy to replace in index.html and styles.css.
- No external animation library or build step required.
- Respects reduced motion, includes keyboard-accessible menu and descriptive image alt text.

## Important before publishing
- Replace placeholder recipient `hello@example.com` in `script.js` with the actual business email. The form opens an email draft and does not submit to a backend.
- Replace third-party Unsplash photos with properly licensed, verified Shah Digital Marketing images (or supplied approved work). No source was confidently authenticated for this exact company, so no outside marketing agency's portfolio is misrepresented.
- Publish on a static host such as Vercel, Netlify or GitHub Pages.
- Test on Chrome, Safari and mobile browsers with network access. External image delivery depends on Unsplash availability.
