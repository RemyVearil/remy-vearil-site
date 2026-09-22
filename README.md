# Remy Vearil — personal site

A single static page. No build step, no framework.

```
index.html              the whole site (content + styles)
Remy_Vearil_Resume.pdf  linked from the Resume buttons
headshot.jpg            your photo, shown in the circle at the top
images/                 photos for the "Beyond engineering" section
```

## Put it online (about 10 minutes)

1. **GitHub:** sign in at github.com → **New repository** → name it something like `remy-vearil-site` → Create.
   On the empty repo page, click **uploading an existing file**, drag in everything in this folder (including the images folder), and click **Commit changes**.
2. **Vercel:** go to vercel.com → **Sign up** with your GitHub account (choose the free Hobby plan) →
   **Add New → Project** → pick `remy-vearil-site` → **Import**. Leave the framework preset as **Other** and click **Deploy**.
3. You'll get an address like `remy-vearil-site.vercel.app`. To change it, go to the project's **Settings → Domains**.
   If you buy your own domain (e.g. remyvearil.com), add it on the same page and follow Vercel's DNS instructions.

Button names can shift a little as GitHub and Vercel update their sites.

## Making changes

Every time you commit a change on GitHub, Vercel redeploys the site automatically within a minute or so.

- **Change your photo:** upload a new square image named exactly `headshot.jpg` (about 800×800 px) to replace the old one.
- **Update the resume:** upload the new PDF with the same name, `Remy_Vearil_Resume.pdf`, to replace the old one.
- **Edit text:** open `index.html` on GitHub, click the pencil icon, change the text, and commit.
  Each project is one `<article class="card">` block; the "Now" list is near the top.

## After OCP

Update the Edged card ("launching at the OCP Global Summit") and the first item in the Now list to say it launched, and add any screenshots you're allowed to share.
