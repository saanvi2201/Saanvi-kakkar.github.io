# Saanvi's portfolio

A static website in a single file, `index.html` (HTML, CSS and JavaScript together). No build step, no paid services.
Animations come from [Motion](https://motion.dev) (free, open source), loaded from a CDN. Fonts come from Google Fonts (free).

## Before you publish: replace these placeholders (search for `TODO` in `index.html`)
1. Hero tagline: a draft, rewrite it in your own voice.
2. CAD Risk Prediction: fill in "Works today" and "Building next".
3. The two Notebook takes: drafts I wrote. Replace them with your real opinions.
4. "Right now" line.
5. Check the three project descriptions match what you actually built, and say so in the "Built with" lines.

## Run it on your computer
Double-click `index.html`. That's it.

## Change anything later (no code)
Everything you see lives in the CONTENT block at the top of the `<script>` in `index.html`: projects, journey, reading takes, links, contact reasons, companion lines.
Edit the text between the quotes, save, refresh. To add a project or take, copy an existing `{ ... },` block and change it.
After publishing, you can edit `index.html` right on github.com (open the file, click the pencil icon, change text, commit). The site updates in about a minute.

## Publish for free (GitHub Pages)
1. Create a new public repository on github.com, for example `portfolio`.
2. Upload `index.html` (Add file, Upload files) and commit.
3. Open Settings, then Pages. Under "Build and deployment" choose "Deploy from a branch", branch `main`, folder `/ (root)`, and Save.
4. After a minute your site is live at `https://saanvi2201.github.io/portfolio/`.
(Naming the repo `saanvi2201.github.io` gives you the shorter `https://saanvi2201.github.io/`.)
Netlify and Vercel free plans also work: drag the folder in, no settings needed.

## Getting emails
No setup needed. The "Say hi" buttons open the visitor's email app addressed to saanvikakkar05@gmail.com with a subject already filled in, so replies land in your normal Gmail inbox. The "Copy email" button covers people without a mail app.
If you later want a real contact form, [Formspree](https://formspree.io) and [Web3Forms](https://web3forms.com) both have free plans. Check their current limits first.

## Things to check
- Resume link: in Google Drive set sharing to "Anyone with the link can view", or visitors will hit an access error.
- Your phone number is deliberately not on the site.
- Your credit card recommender repo is public on GitHub even though it isn't on the site. If an API key was ever committed there, rotate it or make the repo private.
- The three project repos are forks of your teammates' repos. Keep the "Built with" lines accurate.
- Day/night mode is remembered per visitor. The companion robot is a particle shape; click it for a reaction.
- Not included yet: a visual admin screen (like Sanity) and an illustrated robot. Both can be added later without changing the layout.
