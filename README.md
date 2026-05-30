# ShopZ — Usability Testing & Analysis
A mobile e-commerce app usability study conducted on ShopZ, a student-focused shopping platform, created as part of a UI/UX design project.

---

## Project Overview
**Project type:** Usability Testing & Analysis  
**App name:** ShopZ  
**Tagline:** Smart Shopping for Students  
**Target audience:** College and university students aged 18–25  
**Tools used:** Think-Aloud Protocol, SUS Questionnaire, Zoom, Observation Log  

---

## Screens Evaluated
| Screen | Description |
|--------|-------------|
| Splash Screen | App launch screen with branding and tagline |
| Home Screen | Search bar, student deal banner, category tabs, trending products |
| Product Screen | Product detail view with colour/size selection and add to cart |
| Wishlist Screen | Saved items with cart management and continue shopping option |
| Checkout Screen | Delivery address, coupon input, payment method, bill summary |
| Success Screen | Order confirmation screen with continue shopping CTA |


---

## Study Methodology
- Moderated remote usability testing with 5 student participants
- Think-aloud protocol for real-time qualitative data collection
- Task-based scenarios covering the full shopping journey
- Post-session System Usability Scale (SUS) questionnaire
- Exit interviews for overall impressions and pain points

---

## Sample User Persona
**Name:** Emma Myers  
**Age:** 21  
**Occupation:** Undergraduate Student, Ernakulam  
**Goals:** Find student deals quickly, complete purchases without confusion  
**Pain points:** Unclear size options, no order tracking after purchase, confusing checkout flow  

---

## Key Metrics
| Metric | Result | Benchmark |
|--------|--------|-----------|
| Task Completion Rate | 72% | 78% |
| Average Time on Task | 3.4 min | — |
| Error Rate | 28% | < 20% |
| SUS Score | 61 / 100 | > 71 (Good) |

---

## Top Findings
| Severity | Finding |
|----------|---------|
| 🔴 High | No size guide on Product screen — all users confused by S/M/L labels |
| 🔴 High | No order tracking link on Success screen |
| 🔴 High | Search bar lacks auto-suggestions — users waited 8+ seconds |
| 🔴 High | No onboarding content on Splash screen |
| 🟡 Medium | Colour swatches have poor contrast and no labels |
| 🟡 Medium | Wishlist "Add to cart" navigates away unexpectedly |
| 🟡 Medium | Payment options not visible upfront — only UPI shown |
| 🟡 Medium | No order summary before final "Place Order" CTA |
| 🟢 Low | Coupon field placement feels out of sequence |
| 🟢 Low | Category tab latency on first tap |

---

## Design Improvement Suggestions
- Add an interactive size guide popup with measurements on the Product screen
- Add order tracking link and estimated delivery date on the Success screen
- Implement type-ahead search suggestions triggering after 2 characters
- Show all payment method icons upfront and expand details on tap
- Add a collapsible order summary above the Place Order button
- Move the coupon field into the bill summary block where users expect it
- Add colour name labels next to swatches and increase swatch tap size to 36px
- Add 2–3 onboarding slides on first launch highlighting key features
- Allow Add to Cart from Wishlist without navigating away from the screen
- Investigate category tab render latency and preload data on app start

---

## Features Evaluated
- Product discovery and search experience
- Category navigation and filtering
- Product detail page — colour and size selection
- Wishlist management and cart flow
- Checkout process — coupon, payment, and billing
- Post-purchase confirmation and next steps

---

## Repository Contents
| File | Description |
|------|-------------|
| `README.md` | This file |
| `ShopZ.png` | All 6 ShopZ app screens |
| `ShopZ Report.docx` | Full usability testing report |

---

## Future Testing Recommendations
- Conduct a follow-up test after implementing high-priority fixes
- Run an accessibility audit (WCAG 2.1 compliance)
- Test with a broader age range including non-student users
- Add A/B testing for the checkout flow redesign
- Evaluate performance on low-end Android devices
- Test with regional language support for wider reach

---

*Prepared by ANGEL MARIA K B — 2026*
