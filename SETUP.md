# Roadmap App — Setup Instructions

## What's Built (Done)
- ✅ Landing page with hero, path cards, features, pricing
- ✅ Questionnaire flow (4 common Qs + path-specific Qs)
- ✅ Roadmap generation engine (5 career paths)
- ✅ Ad placement spots (2 per roadmap page)
- ✅ Pro tier upsell with pricing
- ✅ ADHD detection and personalized tips
- ✅ Responsive design (mobile-ready)
- ✅ Checkboxes on roadmap items

## What You Need To Do

### Step 1: Create GitHub Repo & Deploy (5 minutes)

1. Go to **https://github.com/new**
2. Repository name: `roadmap-app`
3. Keep it **Public**
4. Don't check any boxes
5. Click **Create Repository**

Then come back to Windsurf/Terminal and tell me — I'll push the code and enable Pages.

---

### Step 2: Purchase a Domain (10 minutes, ~$12/year)

**Recommended domains** (check availability):
- `myroadmap.app` (~$15/yr)
- `getroadmap.io` (~$30/yr)  
- `roadmappath.com` (~$12/yr)
- `youroadmap.co` (~$12/yr)

**Where to buy:**
1. Go to **https://www.namecheap.com** or **https://domains.google.com**
2. Search for your preferred domain
3. Purchase (cheapest is fine, you can always upgrade)
4. After purchase, point it to GitHub Pages:
   - In domain settings, add a **CNAME record**:
   - Host: `@` or `www`
   - Value: `davidatashjian.github.io`
   - TTL: Automatic

Then in your GitHub repo Settings > Pages > Custom domain: enter your domain.

---

### Step 3: Set Up Stripe (Payment Processing) (15 minutes)

This lets you charge $9.99/mo for the Pro tier.

1. Go to **https://dashboard.stripe.com/register**
2. Create account with your personal email
3. Complete identity verification (SSN, bank account for payouts)
4. Once verified, go to **Products** > Create Product:
   - Name: "Roadmap Pro"
   - Price: $9.99/month (recurring)
   - Also add: $79/year (recurring) as alternate price
5. Go to **Payment Links** > Create payment link for the product
6. Copy the payment link URL
7. Tell me the URL — I'll replace the placeholder button with your real Stripe checkout

**Stripe fees:** 2.9% + $0.30 per transaction. On $9.99, you keep ~$9.40.

---

### Step 4: Set Up Google AdSense (20 minutes + wait for approval)

This lets you earn ad revenue from free-tier users.

1. Go to **https://www.google.com/adsense/start/**
2. Sign in with a Google account
3. Enter your website URL (your domain from Step 2)
4. Complete the application:
   - Your name + address
   - Phone verification
   - Connect your bank account for payouts
5. Google will review your site (takes 1-14 days)
6. Once approved, you'll get an **AdSense publisher ID** (looks like `ca-pub-1234567890`)
7. Tell me the ID — I'll replace the placeholder ad divs with real AdSense code

**Typical earnings:** $2-8 per 1,000 pageviews (varies by niche). Pre-med/law/finance niches pay well.

---

### Step 5: Set Up Analytics (5 minutes)

Track how many people visit and use your app.

**Option A: Google Analytics (free, most features)**
1. Go to **https://analytics.google.com**
2. Create a property for your domain
3. Copy the tracking ID (G-XXXXXXXXXX)
4. Tell me — I'll add it to the site

**Option B: Plausible (paid, privacy-friendly, simpler)**
1. Go to **https://plausible.io** — $9/mo
2. Add your domain
3. Copy the script tag
4. Tell me — I'll add it

---

### Step 6: Social Media / Marketing (ongoing)

**Platforms to target:**
- **Reddit:** Post in r/premed, r/MCAT, r/lawschooladmissions, r/FinancialCareers, r/consulting
  - Don't spam. Provide value first. "I built a free tool that..."
- **Twitter/X:** Post screenshots, tips, and link to the tool
- **TikTok:** Short videos showing the questionnaire → roadmap flow
- **Pre-med Facebook groups:** Post with permission

**Messaging template:**
> "I built a free personalized career roadmap tool. Answer a few questions about your situation and it generates a complete plan — timeline, resources, study tools, everything. Works for pre-med, pre-law, IB, consulting. Check it out: [URL]"

---

### Step 7: Legal (Optional but Recommended)

If you're making money, consider:
- **Privacy Policy** — I can generate one for you
- **Terms of Service** — I can generate one  
- **Business entity** — LLC protects personal assets ($500/yr in MA for LLC)
  - Form at: https://www.sec.state.ma.us/cor/coridx.htm

---

## Revenue Projections

| Users/month | Free (ads) | Pro conversions (3%) | Monthly Revenue |
|---|---|---|---|
| 1,000 | ~$5 | 30 × $9.99 = $300 | ~$305 |
| 5,000 | ~$25 | 150 × $9.99 = $1,500 | ~$1,525 |
| 10,000 | ~$50 | 300 × $9.99 = $3,000 | ~$3,050 |
| 50,000 | ~$250 | 1,500 × $9.99 = $15,000 | ~$15,250 |

**Realistic first 6 months:** 500-2,000 users/month with consistent Reddit/social posting. ~$150-600/mo revenue.

---

## Next Steps (Tell Me When Ready)

1. Create the GitHub repo (`roadmap-app`)
2. I'll push and deploy
3. Buy a domain
4. Set up Stripe
5. Apply for AdSense
6. I'll integrate everything once you have the IDs
7. Launch on Reddit/social media
