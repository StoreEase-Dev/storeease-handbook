# StoreEase Handbook

A visual, multi-page overview of StoreEase for partners, developers and whoever runs it. Plain HTML + one CSS file:
open `index.html` in a browser, no build step or server needed (fonts load from Google Fonts when online).

| Page | Covers |
|---|---|
| `index.html` | What StoreEase is, who uses it, the four repos, where things stand |
| `product.html` | A store's life, order statuses, features for owners, shoppers and the team |
| `pricing.html` | Plans, add-ons, trial / grace / suspension timeline, instant vs Razorpay mode |
| `architecture.html` | The five websites, the AWS diagram, why every app calls `/api` on its own host |
| `tenancy.html` | How stores are kept apart (RLS), DB roles, logins, the login hand-over, staff roles |
| `apps.html` | Frontend apps and packages, templates, brand and design rules |
| `backend.html` | API areas, data groups, background loops, emails, conventions, speed, tests |
| `deploy.html` | The Deploy workflow, the server, everyday commands, costs, first-deploy lessons |
| `local.html` | Running everything on a laptop, the dev gateway, test data, checks |
| `decisions.html` | Key decisions with their ids, open items, deliberately deferred work |
| `glossary.html` | Business, technical and AWS terms in plain language |

**Source of truth:** the repos' own `CLAUDE.md` and `docs/`. This handbook summarises them as of 11 Nov 2026 (round 3: shop payments, returns and replacements). When a
decision or behaviour changes, update the repo doc first, then the matching page here.

**Editing:** each page is self-contained HTML sharing `assets/handbook.css` (brand tokens from
`storeease-global/src/styles/tokens.css`) and the same left-hand page list. To add a page, copy one, then add its link
to the page list in every file.
