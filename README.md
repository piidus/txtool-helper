# TXTool Helper & Documentation Hub

Official public repository hosting static web documentation, legal policies, and user guides for applications developed by **TXTool** ([txtool.in](https://txtool.in)), including **Kheror Khata** (`in.txtool.kheror_khata`).

---

## 🌐 Public Live URLs (via GitHub Pages)

Once pushed to your public GitHub repository (`https://github.com/piidus/txtool-helper`), your site will be live at:

- **Portal Home:** `https://helper.txtool.in/`
- **Privacy Policy (Play Store URL):** `https://helper.txtool.in/privacy-policy.html`
- **Clean Subfolder Privacy Policy:** `https://helper.txtool.in/kheror-khata/privacy-policy.html`
- **Terms of Service:** `https://helper.txtool.in/terms.html`

> **Note for Google Play Console:**
> Enter `https://helper.txtool.in/privacy-policy.html` in the **App Content -> Privacy Policy** section of your Google Play Developer Console.

---

## 📁 Repository Structure

```
txtool-helper/
├── .nojekyll                   # Ensures GitHub Pages serves all static assets directly
├── index.html                  # Landing page showcasing TXTool apps & features
├── privacy-policy.html         # Google Play Store compliant Privacy Policy for Kheror Khata
├── terms.html                  # Terms of Service
├── kheror-khata/
│   ├── index.html              # Dedicated Kheror Khata page
│   └── privacy-policy.html     # Direct sub-path privacy policy link
└── assets/
    └── img/
        ├── app_icon_512.png    # High-resolution 512x512 app icon
        ├── screenshot_1_home.jpg
        ├── screenshot_2_cards.jpg
        ├── screenshot_3_table.jpg
        └── screenshot_4_calc.jpg
```

---

## 🚀 How to Publish to GitHub Pages

Run the following commands inside this directory (`E:\flutter_projects\txtool-helper`):

### 1. Initialize Git & Commit
```bash
git init
git add .
git commit -m "feat: initial release of TXTool Helper and Privacy Policy site"
git branch -M main
```

### 2. Create Public Repository on GitHub
1. Go to [https://github.com/new](https://github.com/new)
2. Repository name: `txtool-helper`
3. Description: `Public portal and privacy policies for TXTool apps`
4. Set visibility to **Public** (important so GitHub Pages is free and public)
5. Do **not** initialize with README or .gitignore (already included here)
6. Click **Create repository**

### 3. Link Remote & Push
```bash
git remote add origin https://github.com/piidus/txtool-helper.git
git push -u origin main
```

### 4. Enable GitHub Pages
1. On GitHub, navigate to your repo: `https://github.com/piidus/txtool-helper`
2. Go to **Settings** &gt; **Pages** (on the left menu)
3. Under **Branch**, select `main` and `/ (root)`, then click **Save**
4. Within 1-2 minutes, your website will be live at:
   `https://helper.txtool.in/`

---

## 📬 Support & Inquiries
- **Company:** TXTool
- **Website:** [https://txtool.in](https://txtool.in)
- **Email:** [support@txtool.in](mailto:support@txtool.in)
