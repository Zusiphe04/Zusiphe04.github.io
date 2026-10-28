# 5. Agile Logbook — Evidence

[← Back to portfolio](../README.md) · [Reflection](reflection.md)

| | |
|---|---|
| **Student** | Zusiphe Precious Mvovo |
| **Student Number** | 230816851 |
| **Module** | Project Presentation 3 (PRP370S) |
| **Project** | LocalPro (Local Service Directory Platform) |

**Source:** Development activities, taskboard walkthroughs, and weekly stand-up records tracked during the LocalPro development cycles.

---

## Taskboard Summary

| Product Backlog (To Do) | In Progress | Completed |
|---|---|---|
| Mobile push notification integration | None | LocalPro homepage & search header UI |
| Advanced category analytics | | Category quick-links & "How It Works" guide |
| Multi-location business profiles | | Top-rated Featured Pros directory listings |
| | | Interactive 5-step quote request wizard modal |
| | | Business profile page & customer review displays |
| | | Business owner dashboard (Inquiries & Leads management) |
| | | Business profile details & media management forms |
| | | Billing & subscription tier UI (Basic R0 vs Pro R299/mo) |
| | | Payment options configuration (Bank EFT & PayFast links) |

---

## Taskboard Walkthrough

**1. What do I need to do to advance this piece of work?**
I needed to establish the core user flows for LocalPro, starting with customer directory search and quote requests, followed by business owner registration, lead dashboards, and subscription tier management (Basic vs Pro R299/month).

**2. Am I working on anything that is not on the board?**
I also spent time testing responsive layout behavior across desktop and mobile screens, fixing multi-step form state persistence in the quote wizard, and verifying PayFast input validation.

**3. What do I need to finish as a developer?**
I completed all core planned MVP features, including homepage search, category filters, quote request modals, lead inquiry viewing, profile editing, subscription plan comparisons, and payment settings.

**4. Are there any bottlenecks or blockers to the flow of work?**
Managing state across the 5-step quote wizard and ensuring cover photo locks were properly linked to the Pro tier required investigation during Sprint 2, but these were resolved before final deployment testing.

---

## Weekly Stand-Up Logbook

| Week / Period | What did I complete since the last stand-up? | What am I planning to complete next? | Impediments / Risks |
|---|---|---|---|
| **Week 1 (14–18 Jul)** | Initiated the LocalPro concept, defined project vision, and created the initial user stories for directory search. | Design the homepage hero banner, search input fields, and category quick-links. | Aligning directory category structures with South African service provider needs. |
| **Week 2 (21–25 Jul)** | Built the homepage search header, category cards (Plumbing, Electrical, Solar), and "How It Works" section. | Develop the Featured Pros directory cards and "Verified Pro" badge displays. | Layout alignment issues on smaller mobile viewports. |
| **Week 3 (28 Jul–1 Aug)** | Implemented the Featured Pros listing cards with contact buttons and star ratings. | Build the interactive step-by-step quote request wizard modal. | Ensuring modal overlay closes correctly without losing user input. |
| **Week 4 (4–8 Aug)** | Developed the 5-step quote request wizard and connected job detail input fields. | Create the full business profile view and customer review section. | Managing multi-step modal state transitions smoothly. |
| **Week 5 (11–15 Aug)** | Built the business profile page featuring operating hours, contact details, and customer reviews (Ana P., Tom R.). | Begin working on the business owner dashboard for leads and inquiries. | Handling empty review states gracefully for new providers. |
| **Week 6 (18–22 Aug)** | Implemented the provider dashboard showing profile views, quote request counters, and customer inquiry cards (Zusiphe's lead). | Build the business profile editing form and media upload controls. | Validating lead email formats and quick quote action triggers. |
| **Week 7 (25–29 Aug)** | Developed the Business Details form for updating operating hours, phone numbers, and cover photo upload locks. | Implement the Billing & Subscription page for Basic vs Pro plan comparisons. | Restricting cover photo uploads for non-subscribed (Basic tier) users. |
| **Week 8 (1–5 Sep)** | Built the Billing & Subscription view comparing Basic (R0/mo) vs Pro (R299/mo) plan features. | Add payment options configuration for accepted payment methods and PayFast links. | Formatting pricing text and feature checks clearly for comparison. |
| **Week 9 (8–12 Sep)** | Completed the Payment Options & Billing Details form with EFT fields, SnapScan QR uploads, and PayFast link inputs. | Conduct end-to-end testing across all customer and provider user flows. | Verifying URL syntax validation for custom PayFast links. |
| **Week 10 (15–19 Sep)** | Conducted end-to-end user flow testing, fixed UI bugs, and documented screenshot evidence across all 5 portfolio sections. | Finalize GitHub repository structure, Markdown files, and portfolio submission links. | Ensuring relative image paths (`../assets/`) render correctly on GitHub Pages. |

---

[← Back to portfolio](../README.md) · [Reflection](reflection.md)
