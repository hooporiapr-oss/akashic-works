# 🧠 Akashic Works Marketing Site

Official marketing website for Akashic Works - Six scientifically-backed cognitive training programs.

**Live Site:** https://akashic-works.github.io/ (or https://akashic.works)  
**Support:** support@akashic.works  
**Location:** San Juan, Puerto Rico 🇵🇷

---

## 📄 What's Included

### Pages
- **Homepage** - Tabbed interface for B2C and B2B audiences
- **Healthcare Facilities** - B2B landing page for senior care facilities
- **Facility Pricing Sheet** - Printable cost comparison document
- **Facility License Agreement** - Legal terms for facility subscriptions
- **Privacy Policy** - Data handling and privacy terms
- **Terms of Service** - General terms for all users

### Features
- ✅ Fully bilingual (English + Spanish toggle)
- ✅ Responsive design (mobile, tablet, desktop)
- ✅ Animated background with twinkling stars
- ✅ Tab-based navigation (Individual vs. Facilities)
- ✅ Free trial promotion (3 sessions/day per program)

---

## 🎮 Six Cognitive Training Programs

1. **🔢 Number Memory** - Expand your digit span with increasingly long sequences
2. **🎯 Sequence Memory** - Master sequential patterns with colored buttons
3. **🃏 Memory Match** - Classic pairs matching game
4. **⚡ Reaction Time** - Measure and improve reaction speed
5. **🎯 Reflex Training** - 30-second hand-eye coordination challenges
6. **🔍 Word Search** - Visual scanning and vocabulary (English + Spanish versions)

**Free Trial:** 3 sessions per day per program (18 total daily sessions)  
**All programs link to:** `hooporiapr-oss.github.io/[program-name]`

---

## 💰 Pricing

### Individual Plans (B2C)
| Plan | Price | Features |
|------|-------|----------|
| **Free Trial** | $0 | 3 sessions/day per program (18 total daily) |
| **Pro Unlimited** | $99/year | Unlimited access to all 6 programs |

### Healthcare Facility Plans (B2B)
| Plan | Price | Resident Capacity | Per Resident Cost |
|------|-------|-------------------|-------------------|
| **Starter** | $499/year | Up to 25 | $19.96/year |
| **Standard** ⭐ | $999/year | Up to 75 | $13.32/year |
| **Premium** | $1,999/year | Up to 200 | $9.99/year |
| **Enterprise** | Custom | 200+ | Contact sales |

**Value Proposition:** Save $88,000 - $178,000 per year vs. traditional cognitive therapy ($90K-180K annually)

---

## 🏥 B2B Target Market

### Primary Audience
- Assisted living facilities
- Memory care centers
- Nursing homes
- Senior healthcare facilities

### Key Features for Facilities
- 99% cost reduction vs. traditional therapy
- Unlimited sessions for all residents
- Bilingual interface (English + Spanish)
- HIPAA compliant data handling
- Progress tracking and reporting
- Medicare activity documentation
- 30-day free trial (up to 25 residents)

---

## 🌐 Tech Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Hosting:** GitHub Pages
- **Domain:** (Configure custom domain: akashic.works)
- **Languages:** English + Spanish (localStorage-based toggle)
- **Analytics:** (Add Google Analytics when ready)
- **No frameworks:** Pure HTML/CSS/JS for maximum performance

---

## 📁 File Structure

```
akashic-works.github.io/
├── index.html                          # Homepage with B2C/B2B tabs
├── healthcare-facilities.html          # B2B facility landing page
├── facility-pricing-sheet.html         # Printable comparison sheet
├── facility-license-agreement.html     # Legal terms for facilities
├── privacy-policy.html                 # Privacy policy
├── terms-of-service.html               # Terms of service
├── sales-email-templates.md            # Sales outreach templates (internal)
└── README.md                           # This file
```

---

## 🚀 Local Development

### Serve Locally
```bash
# Clone the repository
git clone https://github.com/akashic-works/akashic-works.github.io.git
cd akashic-works.github.io

# Serve with Python
python3 -m http.server 8000

# Or with Node.js
npx http-server -p 8000

# Open in browser
open http://localhost:8000
```

### Make Changes
1. Edit HTML files directly
2. Test changes locally
3. Commit and push to `main` branch
4. GitHub Pages auto-deploys (usually within 1-2 minutes)

---

## 🎨 Design System

### Color Palette
- **Primary Gold:** `#ffd700` (buttons, headers, accents)
- **Secondary Orange:** `#ff8c00` (gradients, CTAs)
- **Accent Purple:** `#8a2be2` (backgrounds)
- **Success Green:** `#51cf66` (badges, positive messaging)
- **Background Gradient:** `#0a0e27` → `#1a1034` → `#2d1b4e`
- **Text Light:** `#e8e8f0` (body text)
- **Text Medium:** `#c4c4d8` (secondary text)
- **Text Gold:** `#d4af37` (subtitles)

### Typography
- **Font Family:** Georgia, serif
- **Headers:** Gold gradient with animation
- **Body:** 16px base, 1.6 line-height
- **Buttons:** Bold, rounded corners (30px border-radius)

### UI Patterns
- Glassmorphism (backdrop-filter blur)
- Animated gradient backgrounds
- Hover lift effects (translateY(-3px))
- Twinkling star animation
- Smooth fade-in animations

---

## 🔗 Related Repositories

### Game Applications (External)
- [Number Memory](https://github.com/hooporiapr-oss/number-memory)
- [Sequence Memory](https://github.com/hooporiapr-oss/akashic-sequence)
- [Memory Match](https://github.com/hooporiapr-oss/memory-match)
- [Reaction Time](https://github.com/hooporiapr-oss/akashic-reaction-time)
- [Reflex Training](https://github.com/hooporiapr-oss/akashic-reflex)
- [Word Search (English)](https://github.com/hooporiapr-oss/word-search)
- [Word Search (Spanish)](https://github.com/hooporiapr-oss/word-search-es)

---

## 📊 Marketing Strategy

### B2C (Individual Consumers)
- **Funnel:** Free trial → Pro subscription ($99/year)
- **Target:** Adults 25-65 interested in cognitive fitness
- **Channels:** Organic search, word-of-mouth, social media

### B2B (Healthcare Facilities)
- **Funnel:** Demo request → 30-day trial → Paid subscription
- **Target:** Assisted living, memory care, nursing facilities (Puerto Rico)
- **Channels:** Email outreach, industry conferences, referrals
- **Decision makers:** Facility administrators, activity directors

### Sales Materials
- Facility pricing comparison sheet (printable)
- Email templates (9 templates for outreach)
- Demo presentation (30-minute script)
- License agreement (legal terms)

---

## 📈 Analytics & KPIs

### B2C Metrics (Coming Soon)
- Free trial activations per day
- Free → Pro conversion rate (target: 10%)
- Average sessions per user
- Most popular programs

### B2B Metrics (Coming Soon)
- Demo requests per month
- Trial activations
- Trial → Paid conversion (target: 30%)
- Average contract value
- Customer acquisition cost

---

## 🌍 Bilingual Support

### Language Toggle
- Fixed position (top-right)
- Persists via localStorage (`akashic_lang`)
- All text uses `data-en` and `data-es` attributes
- Instant switching with JavaScript

### Spanish Translation
- All pages fully translated
- Puerto Rico-focused (local idioms)
- Professional tone for B2B content
- Casual tone for B2C content

---

## ⚙️ Configuration

### Custom Domain Setup (When Ready)
1. Purchase domain (akashic.works recommended)
2. Add CNAME file to repo root:
   ```
   akashic.works
   ```
3. Configure DNS with domain provider:
   ```
   Type: CNAME
   Name: @
   Value: akashic-works.github.io
   ```
4. Enable HTTPS in GitHub Pages settings

### Google Analytics (When Ready)
Add tracking code to all HTML files before `</head>`:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

---

## 🛠️ Maintenance

### Regular Updates
- ✅ Test all program links monthly
- ✅ Update pricing if changed
- ✅ Refresh testimonials (when available)
- ✅ Check mobile responsiveness
- ✅ Update copyright year annually

### SEO Checklist
- ✅ Descriptive meta descriptions
- ✅ Proper heading hierarchy (H1, H2, H3)
- ✅ Alt text for images (when added)
- ✅ Fast load times (< 2 seconds)
- ✅ Mobile-friendly design
- ✅ Submit sitemap to Google Search Console

---

## 🤝 Contributing

This is a private marketing repository. For support or inquiries:

**Technical Issues:**  
Create a GitHub issue in this repository

**General Inquiries:**  
Email: support@akashic.works

**Sales/Partnerships:**  
Email: support@akashic.works

---

## 📜 License & Legal

© 2024 Akashic Works. All rights reserved.

### Legal Documents
- Privacy Policy: Compliant with GDPR, CCPA, Puerto Rico law
- Terms of Service: Standard consumer agreement
- Facility License Agreement: B2B subscription terms, HIPAA compliance

---

## 📞 Contact Information

**Akashic Works**  
San Juan, Puerto Rico  

**Email:** support@akashic.works  
**Website:** https://akashic-works.github.io/  
**Target Markets:** Puerto Rico (expanding)

---

## 🎯 Next Steps

### Immediate (Week 1)
- [ ] Upload all files to GitHub
- [ ] Enable GitHub Pages
- [ ] Test all links and functionality
- [ ] Set up support@akashic.works email

### Short-term (Month 1)
- [ ] Purchase custom domain (akashic.works)
- [ ] Configure DNS and HTTPS
- [ ] Add Google Analytics
- [ ] Create facility contact list (Puerto Rico)
- [ ] Launch B2B email outreach

### Medium-term (Months 2-3)
- [ ] Collect testimonials
- [ ] Add case studies (after first facility customer)
- [ ] Create demo video
- [ ] Expand to Florida market

---

**Last Updated:** November 25, 2024  
**Version:** 1.0  
**Status:** Production Ready 🚀
