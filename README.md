# VoiceBahamas Landing Page

Static landing page for voicebahamas.com. Designed to maximise Meta ad approval and convert Bahamian visitors to Earn Tings signups.

## Files

- `index.html` — main landing page
- `privacy.html` — Privacy Policy
- `terms.html` — Terms of Service
- `vercel.json` — Vercel deployment config (security headers, clean URLs)

## Deploy to Vercel

1. Create a Vercel account at vercel.com (free)
2. Install Vercel CLI: `npm install -g vercel`
3. From this folder run: `vercel`
4. Follow the prompts. Choose "deploy as static site"
5. Once deployed, add your custom domain `voicebahamas.com` in the Vercel project settings
6. Update your domain's DNS to point to Vercel (Vercel shows you the exact records to set)

Or even simpler:
1. Push this folder to a new GitHub repo
2. Connect the repo to Vercel via the dashboard
3. Auto-deploys on every push

## Customisation

All URLs pointing to Earn Tings include `?utm_source=voicebahamas&c=VBM-FB` so signups are tracked back to the campaign. Update `VBM-FB` if you want a different campaign code.

### Legal entity

All pages reference BahaNext Group Ltd (currently in formation). Once incorporation completes, you can remove "(in formation)" references and update the operator description if needed.

### Email

The pages reference `hello@voicebahamas.com`. Set this up via your domain registrar's email forwarding (free) or with Google Workspace once incorporated.

## Meta ad approval optimisations applied

- No third-party trademarks in copy or imagery
- No "earn" or earnings claims on the visible page
- Privacy Policy + Terms of Service linked from every page
- Clear age and residency requirements stated
- Genuine value proposition explained (not a "make money" pitch)
- Transparent about parent platform (Earn Tings) in footer
- Mobile responsive
- Fast loading (no external scripts other than fonts)
