# Awesome-Giving-n-Tithing

## Top Giving & Tithing Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Online Donations, Recurring Giving, Text-to-Give, Donor Management & Church / Nonprofit Stewardship*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Giving & Tithing**. These tools help churches, ministries, and nonprofits accept one-time and recurring donations, manage donor records, generate giving statements, and support mobile or text-based giving.

**Examples** include Pushpay, Tithe.ly, Subsplash Giving, Givelify, Planning Center Giving, Realm eGiving, EasyTithe, Vanco Give, SecureGive, and Kindrid (the category leaders).

**Open-source emphasis**: Fully featured open-source equivalents to commercial church giving platforms are limited because payment processing, PCI compliance, and donor experience require significant infrastructure. However, several strong open-source church management systems include giving modules, and lightweight tools exist for tracking tithes and generating statements. This section highlights every significant active project.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Pushpay](https://pushpay.com/)**  
  Enterprise-grade giving and engagement platform popular with mid-to-large and multi-site churches, offering strong recurring giving, donor tools, and deep ChMS integrations.

- **[Tithe.ly](https://get.tithe.ly/)**  
  Widely used church giving platform with free and paid tiers, mobile app, text-to-give, recurring donations, and optional church management features.

- **[Subsplash Giving](https://www.subsplash.com/)**  
  Giving solution integrated into the broader Subsplash church app and media platform, popular with churches that want a unified mobile experience.

- **[Givelify](https://www.givelify.com/)**  
  Mobile-first giving platform with a free entry point, simple donor experience, and focus on quick adoption for churches of various sizes.

- **[Planning Center Giving](https://www.planningcenter.com/giving)**  
  Cost-effective giving module within the Planning Center suite, known for competitive transaction fees (including free ACH on some plans) and tight integration with other PCO products.

- **[Realm eGiving (ACS Technologies)](https://www.acst.com/)**  
  Giving and donor management tools within the Realm church management ecosystem, aimed at churches already using ACS/Realm.

- **[EasyTithe](https://www.easytithe.com/)**  
  Online and mobile giving platform designed specifically for churches, with recurring gifts, text giving, and reporting features.

- **[Vanco Give](https://www.vancopayments.com/)**  
  Long-standing church and nonprofit payment processor offering online, mobile, text, and kiosk giving options with various pricing models.

- **[SecureGive](https://www.securegive.com/)**  
  Church giving platform focused on secure online, mobile, and text donations along with donor management tools.

- **[Kindrid](https://www.kindrid.com/)**  
  Modern giving and stewardship platform aimed at churches seeking clean donor experiences and engagement features.

## Open-Source GitHub Projects

- **[ChurchCRM](https://github.com/ChurchCRM/CRM)**  
  Mature open-source church management system that includes giving and pledge tracking, donor profiles, financial reports, and deposit management — fully self-hosted with no licensing fees.

- **[B1.church / B1Admin](https://github.com/ChurchApps/B1Admin)**  
  Free, open-source church management software with member tracking, attendance, groups, donation recording, reports, and support for connecting external payment providers (Stripe, etc.).

- **[ChurchCMS (giving modules)](https://churchcms.app/)**  
  Open-source church platform that includes online giving, text-to-give concepts, donor records, and year-end statements, with emphasis on zero platform fees and local payment gateway support.

- **[Church Giving Manager](https://github.com/kmccb/church-giving-manager)**  
  Offline-first Windows desktop application for recording member tithes and offerings, generating tax statements, and maintaining giving history without requiring internet or a server.

- **[True-Tithe & XRPL experiments](https://github.com/mworks-proj/True-Tithe)**  
  Experimental open-source projects exploring blockchain (e.g., XRPL) based tithe and offering acceptance for religious organizations.

- **[Lightweight tithe trackers](https://github.com/IonicaBizau/tithe)**  
  Simple command-line and library tools for organizing and tracking personal or organizational tithe payments.

- **[ERPNext / Odoo nonprofit customizations](https://github.com/frappe/erpnext)**  
  Open-source ERPs that can be configured for nonprofit accounting, donation tracking, and fund management when paired with payment gateways.

### Additional Strong Open-Source Options

- **Payment gateway integrations**: Self-hosted forms and backends that connect to Stripe, PayPal, Flutterwave, M-Pesa, Paystack, or other regional processors.
- **Donor portals & statement generators**: Community scripts and modules for producing annual giving statements (tax receipts).
- **Form & landing page tools**: Open-source form builders used to create custom donation pages.
- **Accounting links**: Tools that push donation data into GnuCash, ERPNext, or other open accounting systems.
- **Mobile & SMS gateways**: Projects that enable text-to-give style flows in regions with strong mobile money adoption.
- Various church and nonprofit management systems that include basic contribution tracking.

**Frameworks for building custom systems**:  
Use **ChurchCRM** or **B1.church** as the member and giving system of record.  
Connect a PCI-compliant payment processor (Stripe or local equivalent) for card/ACH/mobile money acceptance.  
Generate statements and reports from the open-source CRM data.  
For very small congregations, an offline desktop tracker plus a simple Stripe payment link can be sufficient.  
This approach gives full data ownership and avoids per-donor or high platform fees, at the cost of more setup and maintenance.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Handling donations involves payment card compliance (PCI-DSS), tax receipting rules, data privacy, and financial controls. Churches and nonprofits remain responsible for regulatory compliance in their jurisdiction.
- Self-hosted open-source solutions still require a compliant payment processor for card transactions and proper security practices around donor data.

---

**Made for church administrators, pastors, nonprofit finance teams, and stewardship leaders.**  
Let's make generous giving supported by transparent, affordable, and community-owned tools.
