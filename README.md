
# n8n Link Assets Repository

This repository is used by an **n8n automation workflow** to store and serve public assets for shortened links.  
The workflow uploads files here so that Switchy.io (and social media platforms) can display correct **OpenGraph previews**, **screenshots**, and **favicons** when sharing links.

---

## 📂 Repository Structure
/screenshots/ → Screenshots of target URLs
/og-images/ → Generated or fetched OG images (social preview images)
/favicons/ → Website favicons or brand icons


Each folder may contain images uploaded automatically by the n8n workflow. Files are committed directly to the `main` branch.

---

## 🔗 Why this repo?

- **Public hosting (CDN-like):** Assets stored here can be accessed by Switchy.io and social platforms via raw GitHub URLs.
- **Automation-friendly:** The n8n workflow commits files automatically using the GitHub API.
- **Organization:** Dedicated folders keep screenshots, OG images, and favicons separate.

---

## ⚙️ Workflow Integration

1. The n8n workflow parses a long URL.
2. Metadata (title, description, OG tags) is scraped.
3. Screenshots, OG images, and favicons are uploaded here.
4. A short link is created/updated in **Switchy.io**, referencing these assets.

---

## 🌐 Example Raw URLs

Replace `Aarnav2510` with your GitHub username:

- Screenshot:  https://raw.githubusercontent.com/Aarnav2510/n8n-link-assets/main/screenshots/example.png

- Favicon:https://raw.githubusercontent.com/Aarnav2510/n8n-link-assets/main/favicons/example.ico
- 

