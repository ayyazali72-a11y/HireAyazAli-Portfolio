# HireAyazAli website

A static, multi-page site (no build step). Pages: Home, About, Work (portfolio), five case studies, Services, Testimonials, Contact.

## Run locally
Open `index.html` in a browser, or run `python3 -m http.server 8000` in this folder.

## Deploy
1. Create a GitHub repository and upload the contents of this folder (the files, not the folder itself, at the top level).
2. In Vercel, choose "Add New Project", import the repository, leave the framework as "Other", and deploy. No build command or output directory is needed.
3. In Vercel, add the domain `hireayazali.online` under Project > Settings > Domains.
4. Submit `https://hireayazali.online/sitemap.xml` in Google Search Console once the domain is live.

## Before publishing
- Resolve every item marked "to confirm" (yellow dashed tags). Search for `class="tbc"` to find them all.
- Add analytics (GA4 / Google Tag Manager) only after IDs are supplied and a cookie consent step is in place. The placeholder is a comment in each page's `<head>`.
- The contact form opens the visitor's email app. It does not send messages from the site. A server-side form can be added later if needed.
