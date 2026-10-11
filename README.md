# Ella Train Times – Ella Railway Station Web Portal
# ඇල්ල දුම්රිය ස්ථානය වෙබ් අඩවිය

Official-styled tourism and train schedule web portal for Ella Railway Station, Sri Lanka.

## 🚀 GitHub Pages මඟින් නොමිලේ වෙබ් අඩවිය පළකිරීම (Deploying to GitHub Pages)

මෙම Repository එක ඔබගේ GitHub ගිණුමට Push කළ පසු පහත පියවර අනුගමනය කරන්න:

1. GitHub වෙබ් අඩවියේ ඔබගේ Repository එක වෙත යන්න (`Settings` ටැබ් එක මත ක්ලික් කරන්න).
2. වම් පස ඇති මෙනුවේ **Pages** තෝරන්න.
3. **Build and deployment** යටතේ **Source** සඳහා **GitHub Actions** තෝරන්න.
4. Repository එකට `main` හෝ `master` ශාඛාවට (branch) කේත push වූ වහාම, `.github/workflows/deploy.yml` මඟින් වෙබ් අඩවිය ස්වයංක්‍රීයව Build වී Live වෙබ් අඩවියක් ලෙස ක්‍රියාත්මක වේ.

---

## 💻 Local පරිගණකයේ ක්‍රියාත්මක කිරීම (Run Locally)

1. මෙම ෆෝල්ඩරය පරිගණකයට බාගත කරගන්න (Download ZIP).
2. Terminal / Command Prompt විවෘත කර Dependencies ස්ථාපනය කරන්න:
   ```bash
   npm install
   ```
3. Development server එක ධාවනය කරන්න:
   ```bash
   npm run dev
   ```
4. වෙබ් අඩවිය සඳහා Production Static HTML ගොනු සෑදීමට (Build static HTML):
   ```bash
   npm run build
   ```
   *සාදන ලද `dist/` ෆෝල්ඩරය තුළ සම්පූර්ණ Static HTML, CSS, JavaScript සහ ඡායාරූප (Images) අඩංගු වේ.*

---

## 📁 ගොනු ව්‍යුහය (Project Structure)
- `dist/` - GitHub Pages හෝ ඕනෑම Hosting එකකට දැමීමට සූදානම් කර ඇති Build ගොනු (index.html, assets).
- `src/` - React සහ Tailwind CSS මූල කේත (Source code).
- `src/assets/images/` - උසස් තත්ත්වයේ ඇල්ල අවට නැරඹුම් ස්ථාන සහ Cover ඡායාරූප.
