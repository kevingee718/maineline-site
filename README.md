# Maineline Sewer and Drain Service – Static Site
Simple, fast static site. Edit HTML/CSS directly and redeploy.

## Local Edits
- Update phone/email in `index.html`
- - Adjust colors/services in `styles.css` and sections
 
  - ## Deploy
  - 1) Vercel (recommended): Import GitHub repo, set root `/`, framework = "Other".
    2) 2) Netlify: "New site from Git", default build settings (no build command), publish directory `/`.
       3) 3) Cloudflare Pages: Connect repo, framework preset "None".
          4) 4) GitHub Pages: Settings → Pages → Source "Deploy from a branch", Branch `main` root.
            
             5) ## Forms
             6) - Netlify auto-handles the form via `data-netlify="true"`. On other hosts, rely on the mailto link in Contact.
