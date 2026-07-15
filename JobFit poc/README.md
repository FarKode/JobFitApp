# JobFit — Privacy Policy & Legal Pages

A minimal static site hosting the **Privacy Policy** and **Terms of Service** pages for the [JobFit](https://play.google.com/store/apps/details?id=com.jobfit.jobfit) Android application.

These pages are required by the **Google Play Store** for app publication and Data Safety compliance.

---

## 📂 Structure

```
poc/
├── privacy-policy.html   # Full privacy policy (Google Play Store required)
├── terms-of-service.html # Terms of service page
├── index.html            # Landing page linking to both documents
└── README.md             # This file
```

## 🚀 Hosting Options

### Option 1: GitHub Pages (Recommended — Free)

1. Create a new GitHub repository (e.g., `jobfit-legal`)
2. Copy all files from this `poc/` folder into the repository root
3. Go to **Settings → Pages → Source** → select `main` branch
4. Your pages will be live at: `https://<your-username>.github.io/jobfit-legal/privacy-policy.html`
5. Use this URL in your Google Play Console under **App Content → Privacy Policy**

### Option 2: Firebase Hosting (Free tier)

```bash
npm install -g firebase-tools
firebase init hosting    # Select this directory
firebase deploy
```

### Option 3: Netlify (Free tier)

1. Push this folder to a GitHub repo
2. Connect the repo to [Netlify](https://netlify.com)
3. It deploys automatically on every push

---

## 📋 Google Play Console Setup

1. Go to [Google Play Console](https://play.google.com/console)
2. Navigate to your app → **Policy → App content**
3. Under **Privacy policy**, paste the hosted URL of `privacy-policy.html`
4. Under **Data safety**, fill in the form:
   - **Does your app collect or share user data?** → Yes (due to AdMob)
   - **Data types collected:** Device identifiers, Advertising ID (via AdMob)
   - **Is data encrypted in transit?** → Yes (HTTPS)
   - **Can users request data deletion?** → Yes (via "Clear All Data" in Settings)

---

## 📅 Last Updated

**July 15, 2026**

---

## 📄 License

These legal documents are proprietary to JobFit. All rights reserved.
