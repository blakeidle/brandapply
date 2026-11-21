# BrandApply

One-click brand kit apply for freelancers and small marketing teams. Client-side SPA: kit editor, 4 live preview templates, PNG/SVG/HTML export, localStorage persistence.

## Pricing (product)

- **Solo — $15/mo**
- **Team — $39/mo**

Replace `STRIPE_SOLO_LINK` / `STRIPE_TEAM_LINK` in `index.html` after Blake confirms live Stripe products on Axon Stewardship, LLC.

## Local preview

```bash
cd /workspace/brandapply-app && python3 -m http.server 8787
# open http://127.0.0.1:8787
```

## One-command deploy (when Vercel + GitHub are reconnected)

```bash
cd /workspace/brandapply-app && npx --yes vercel --prod --yes
```
