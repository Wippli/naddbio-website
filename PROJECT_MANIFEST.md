<style>@import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Sans:wght@400;500;600&display=swap'); body { font-family: 'IBM Plex Sans', sans-serif; }</style>

![Brannium](../4-ASSETS_Website_Refresh_Jan_2026/brannium_logo_no_Tx.svg)

# NADDBio Website - Project Manifest

**Project:** NADDBio Website Refresh
**Client:** Kingsley Urakpo / NADDBio
**Completed:** February 2026
**Developed by:** Brannium

---

## Project Overview

Brannium delivered a complete website refresh for NADDBio, a biopharmaceutical R&D consultancy based in Cambridge, Massachusetts. The project included full redesign and development of 7 responsive pages, deployment to Microsoft Azure cloud infrastructure, SEO optimisation, and a functional contact form.

The website is now hosted on Azure Static Web Apps with enterprise-grade security, global CDN delivery, and zero monthly hosting costs. The stack is designed for easy handover, future scalability, and seamless integration with Wippli services.

**Included: 30 days post-launch support** for bug fixes, minor adjustments, and technical questions.

---

## Live URLs

| Environment | URL |
|-------------|-----|
| **Production** | https://www.naddbio.com |
| **Azure Default** | https://red-glacier-00a34cd0f.2.azurestaticapps.net |

---

## Pages Delivered

| Page | Desktop | Mobile | Description |
|------|---------|--------|-------------|
| Homepage | index.html | index_mobile.html | Hero video, services overview, client logos |
| Services | naddbio_services.html | naddbio_services_mobile.html | R&D consulting services |
| About | naddbio-about-mockup.html | naddbio-about-mockup_mobile.html | Company story and mission |
| Contact | naddbio_contact.html | naddbio_contact_mobile.html | Contact form and details |
| Therapeutic Areas | naddbio_therapeutic_areas.html | naddbio_therapeutic_areas_mobile.html | Areas of expertise |
| Meet the Team | naddbio_meet_the_team.html | naddbio_meet_the_team_mobile.html | Team members |
| Leadership | naddbio_leadership.html | naddbio_leadership_mobile.html | Leadership profiles |

**Total: 7 pages (14 files including mobile versions)**

---

## Features Implemented

### Responsive Design
- Dedicated mobile versions for all pages
- Automatic device detection and redirect
- Touch-optimized navigation and buttons
- Mobile-first typography and spacing

### SEO Optimization
- Meta descriptions and keywords on all pages
- Open Graph tags for social media sharing
- Twitter Card meta tags
- Canonical URLs
- XML Sitemap (`sitemap.xml`)
- Robots file (`robots.txt`)
- Semantic HTML structure

### Contact Form
- Functional contact form using Web3Forms
- Submissions sent directly to client email
- Form fields: Name, Email, Company, Area of Interest, Message
- Success confirmation on submission

### Performance & Security
- Static site architecture (fast load times)
- HTTPS enforced with free SSL certificate
- Security headers configured (X-Frame-Options, XSS Protection)
- CDN delivery via Azure global network

---

## Technology Stack

| Component | Technology |
|-----------|------------|
| **Hosting** | Azure Static Web Apps (Free Tier) |
| **Frontend** | HTML5, CSS3, Vanilla JavaScript |
| **Fonts** | Google Fonts (Cormorant, Work Sans) |
| **Form Backend** | Web3Forms |
| **Assets CDN** | Azure Blob Storage |
| **DNS Provider** | Network Solutions |
| **SSL Certificate** | Azure-managed (automatic) |

---

## Azure Benefits

### Why Azure Static Web Apps?

1. **Free Tier** - No monthly hosting costs for static websites
2. **Global CDN** - Content delivered from nearest edge location worldwide
3. **Automatic HTTPS** - Free SSL certificates, auto-renewed
4. **Custom Domains** - Easy domain configuration with validation
5. **High Availability** - 99.95% uptime SLA
6. **Scalability** - Handles traffic spikes automatically
7. **Security** - DDoS protection included, security headers
8. **Enterprise Ready** - Part of NADDBio's Azure subscription

### Expected Monthly Costs

| Service | Cost |
|---------|------|
| Azure Static Web Apps (Free Tier) | **$0.00** |
| Custom Domain SSL | **$0.00** (included) |
| Bandwidth (first 100GB) | **$0.00** (included) |
| Web3Forms (250 submissions/month) | **$0.00** |
| **Total Monthly Cost** | **$0.00** |

> **Note:** The Free Tier includes 100GB bandwidth/month and 2 custom domains. This is sufficient for most business websites. If traffic exceeds limits, Standard Tier is ~$9/month.

---

## Scalability & Future Growth

### Easy Vendor Collaboration
- Clean, documented codebase that can be handed off to any web developer
- Standard HTML/CSS/JS stack - no proprietary frameworks or lock-in
- All assets and configurations included in project folder
- This manifest provides full handover documentation

### Microsoft Enterprise Security
- Azure provides top-class enterprise security infrastructure
- DDoS protection included at no extra cost
- Automatic HTTPS with managed SSL certificates
- Built-in security headers (XSS protection, clickjacking prevention)
- Compliant with major security standards (ISO 27001, SOC 2)

### Wippli Integration Ready
- Azure stack is fully compatible with Wippli services
- Can connect to Wippli AI tools and analytics
- Shared Azure tenant enables seamless integration
- Future automation and workflows can be added

### Ready for Growth
The current setup can easily expand to include:
- **Blog / News section** - Add content management
- **Client Portal** - Secure document sharing
- **API Integration** - Connect to CRM, email marketing, analytics
- **E-commerce** - Add payment processing if needed
- **Multi-language** - Internationalisation support
- **Advanced Analytics** - Azure Application Insights integration

All future additions stay within the same Azure ecosystem, maintaining security and simplicity.

---

## DNS Configuration

**Domain Registrar:** Network Solutions

| Record Type | Host | Value |
|-------------|------|-------|
| CNAME | www | red-glacier-00a34cd0f.2.azurestaticapps.net |

---

## Access Credentials

### Azure Portal
- **Portal:** https://portal.azure.com
- **Tenant:** NADDBio (5cde1a90-82a9-442f-9dac-3f7626b4fbbf)
- **Subscription:** Azure subscription 1
- **Resource Group:** naddbio-rg
- **Static Web App:** naddbio-website

### Web3Forms (Contact Form)
- **Current Access Key:** 81584337-1236-4188-a518-022bab9f9dcd
- **Currently sends to:** design@brannium.com (Brannium will forward)
- **Dashboard:** https://web3forms.com/

#### ACTION REQUIRED: To Receive Form Submissions Directly

**Kingsley** - to have contact form submissions sent directly to your inbox:

1. Go to https://web3forms.com
2. Enter your email: `kingsley.urakpo@naddbio.com`
3. Click "Create Access Key"
4. You'll instantly receive an access key (looks like: `xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx`)
5. Send this key to Brannium at design@brannium.com
6. Brannium will update the website and redeploy

This takes 2 minutes and is completely free. Until then, Brannium will forward any form submissions to you.

### Deployment
- **Method:** Azure SWA CLI
- **Deployment Token:** Stored securely (contact Brannium for redeployment)

---

## Maintenance Notes

### To Update Website Content
1. Edit HTML files locally
2. Run deployment command via Azure SWA CLI
3. Changes go live within 1-2 minutes

### To Change Contact Form Recipient
1. Edit `naddbio_contact.html` and `naddbio_contact_mobile.html`
2. Create new Web3Forms access key for new email
3. Replace access key in both files
4. Redeploy

### To Add New Pages
1. Create desktop and mobile HTML versions
2. Add routes to `staticwebapp.config.json`
3. Update sitemap.xml
4. Redeploy

---

## File Structure

```
2-PROOFS_Website_Refresh_Jan_2026/
├── index.html                          # Homepage (desktop)
├── index_mobile.html                   # Homepage (mobile)
├── naddbio_services.html               # Services page
├── naddbio_services_mobile.html
├── naddbio-about-mockup.html           # About page
├── naddbio-about-mockup_mobile.html
├── naddbio_contact.html                # Contact page
├── naddbio_contact_mobile.html
├── naddbio_therapeutic_areas.html      # Therapeutic areas
├── naddbio_therapeutic_areas_mobile.html
├── naddbio_meet_the_team.html          # Team page
├── naddbio_meet_the_team_mobile.html
├── naddbio_leadership.html             # Leadership page
├── naddbio_leadership_mobile.html
├── staticwebapp.config.json            # Azure routing config
├── sitemap.xml                         # SEO sitemap
├── robots.txt                          # Search engine directives
├── favicon.svg                         # Site favicon
└── logos/                              # Client logo assets
```

---

## Support Contact

**Brannium**
design@brannium.com

---

*Document generated: February 2026*
