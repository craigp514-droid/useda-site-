# US Economic Development Association Website

Lead generation website for useconomicdevelopment.com

## Tech Stack

- **Framework:** Astro
- **Styling:** Tailwind CSS
- **Forms:** Netlify Forms
- **Hosting:** Netlify

## Local Development

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Deployment

This site is configured for Netlify deployment:

1. Push to GitHub
2. Connect repository to Netlify
3. Netlify will auto-detect Astro and configure build settings
4. Forms will work automatically with Netlify Forms

## Project Structure

```
src/
├── components/
│   ├── Header.astro
│   ├── Footer.astro
│   └── LeadForm.astro
├── layouts/
│   └── BaseLayout.astro
└── pages/
    ├── index.astro
    └── thank-you.astro
```

## Form Submissions

Form submissions go to Netlify Forms dashboard. Set up:
1. Email notifications in Netlify dashboard
2. Zapier/Make integration for Google Sheets (optional)
