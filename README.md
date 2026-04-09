
👉 Prevents useless compiled files from uploading

---

# ⚖️ STEP 4: Add LICENSE

Choose **MIT License (recommended)**

Just create a file named `LICENSE` and paste from:
👉 https://opensource.org/licenses/MIT

---

# 🌐 STEP 5: Upload to GitHub (IMPORTANT)

Since you already created repo with README, do this:

### Option A (EASIEST – via website)

1. Open your GitHub repo
2. Click **"Add file" → "Upload files"**
3. Upload:
   - `smart_city_route_optimization.cpp`
   - `.gitignore`
4. Commit → Done ✅

---

### Option B (Best for learning – using Git)

Open terminal in your project folder:

```bash
git init
git add .
git commit -m "Initial commit - Smart City DAA Project"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
