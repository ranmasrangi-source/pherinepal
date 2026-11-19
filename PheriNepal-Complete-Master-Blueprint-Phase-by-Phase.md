# PHERINEPAL — COMPLETE MASTER BLUEPRINT

**Scope:** Complete product, travel lifecycle, service catalogue, premium UI/UX, operating model, technical architecture, security, data, operations, governance and phase-by-phase implementation contract.
**Document status:** Master blueprint; owner decisions and external approvals remain explicitly labelled.

## How to read this document

| Code | Meaning |
|---|---|
| **FINAL** | Owner decision or settled requirement from the master instructions |
| **RECOMMENDED** | Design choice open to review |
| **PENDING** | Depends on a written answer, approval, licence, provider agreement, or verification not yet done |
| **GATED** | Not started until the named approval is received in writing |
| **REPOSITORY-VERIFIED** | Built and verified in the Phases 1 repository |

Nothing marked PENDING or GATED is treated as confirmed. Legal, payment, and licensing points in this document are planning notes, not legal advice.

---

## 1. Vision and brand

PheriNepal is a Nepal-focused travel super platform. It covers the whole trip: before you go (discovery, planning, booking, documents), while you explore (navigation, support, safety), and after you return (memories, reviews, rewards).

**Brand (FINAL):**
- "Your Complete Nepal Travel Companion"
- "Before You Go. While You Explore. After You Return. PheriNepal Is With You."
- "One Account. One Trip. One Support System. Entire Nepal."

**Core promise (RECOMMENDED):** Every service is shown with its true status. Every price is shown in full before payment. Every booking is with a verified partner. Payment is protected until the service is delivered.

**Positioning (RECOMMENDED):** Not a generic hotel-booking site. The differentiators are verified local partners, real photos and host stories, transparent money flow, and honest status for every service.

---

## 2. Market context (2026)

### 2.1 Demand

- Nepal's international arrivals in 2026 so far show recovery. <!-- source: NTB monthly figures reported by The Himalayan Times, Himal Press, and Onlinekhabar -->
- January 2026: 92,573. February: 105,441. March: 120,516. April: 107,934. May: 102,626 (up 19% year on year). June: 91,363 by air (up 19.5%). July: 71,775 (up 2.3%).
- Jan to May 2026 total: 529,090 (up 5.6%). Full year 2025: 1,158,459.
- India is the largest source market. China grew 61% in July 2026 year on year.
- SAARC arrivals fell 11.93% in July 2026, while other Asian markets grew.
- Europe and the Americas were broadly flat, and NTB linked this to West Asia tensions.

**Planning note (RECOMMENDED):** Use these figures as context only. Do not project revenue from them without a bottom-up model.

### 2.2 Weaknesses the platform can address

| Weakness | Evidence (2026 research) | Platform response |
|---|---|---|
| Trekking infrastructure is thin | Sudurpaschim trails lack rescue points, info boards, and rest areas | Route information, rescue and contact directory (verified), trail status from official sources |
| Guide and porter trust | Rising complaints about bad guides and agencies; no official complaint form | Licence-checked partners, reviews, dispute process |
| Safety and climate risk | Floods and landslides, including the 26 August 2026 floods; monitoring damaged | Weather alerts from official sources only, no fake 24/7 claim, disaster-aware status |
| Digital gap in villages | Homestay owners often lack English and internet | Assisted onboarding by field agent, phone and WhatsApp listing, Nepali-first |
| Low spending per visitor | Visitors staying longer but spending less; hotel rooms added faster than demand | Experience and local spending, value-based packages, honest pricing |
| Commission concerns | Local operators say international platforms can take 20 to 40% | Transparent commission and split shown to partners and travelers. Figure to be verified |
| Information confusion | Travelers unclear on routes, permits, transport, guides | Trip planner, permit guide, checklists, verified directory |
| Transport and aviation safety | Recurring concerns about road and air safety | Show operator verification and safety info; do not sell unverified transport |

**Source note:** Several points come from blogs, operator websites, or opinion pieces. They are listed as context and must be verified before public claims.

---

## 3. Competitive landscape

| Competitor | Strength | Gap PheriNepal can address |
|---|---|---|
| **Booking.com** | Large inventory, strong brand, includes Nepal homestays | Not Nepal-specific for trekking, permits, guides, or community impact |
| **Airbnb** | Homestays across Nepal, host community | Onboarding can be hard for village hosts; no Nepal trek or guide layer |
| **eSewa Hotels** | Local payment integration, hotel deals | Hotel-focused; limited experience and community content |
| **ghumNepal** | Nepali platform with curated local experiences and community homestays | **Closest competitor.** Needs direct comparison of features, verification, pricing, and reach before launch |
| **Hop Nepal and local agencies** | Personal service, affiliate homestays | Manual booking; limited scale and digital tools |
| **Hotel Nepal (app)** | Simple hotel search | Hotel-only; user numbers self-reported |

**Action (PENDING):** Before final positioning, test each competitor's listing process, verification, pricing transparency, review quality, and support. Record results with screenshots and dates.

**Positioning answer (RECOMMENDED):** PheriNepal is the Nepal-built platform where every stay, guide, and transport option is verified, every price is complete before payment, and every trip is tied to a community benefit that travelers can see.

---

## 4. Users and personas

| User | Needs | Key actions |
|---|---|---|
| **International traveler** | Trusted stay, clear price, trek information, safety | Discover, plan, book, pay, check in, review |
| **Diaspora and domestic traveler** | Visiting family, local experiences, Nepali UI | Plan, book, share trip with group |
| **Hotel and homestay partner** | Steady bookings, fair fees, simple tools | Onboard, list, manage calendar and price, accept bookings, get paid |
| **Guide and porter** | Licence recognition, work, safety | Onboard with licence, get assigned, show availability |
| **Transport partner** | Bookings, fleet management | List vehicles, schedule, bookings |
| **Adventure operator** | Verified listing, safety compliance, insurance | Onboard, list activities, time slots, manage capacity |
| **Shopping seller** | Product listings, orders, delivery | List products, manage inventory, orders, returns |
| **Restaurant and local experience partner** | Reservations, bookings | List, manage reservations and events |
| **Admin and operations** | Verify partners, control status, handle support and disputes | All admin functions in section 10 |
| **Owner / founder** | Business health, launch decisions | Readiness approval, metrics |

---

## 5. Product principles (FINAL)

1. **Show everything from day one.** All 31 planned categories appear on the website, each with a clear status.
2. **No fake availability.** Coming Soon services never show prices, availability, or booking buttons.
3. **No booking without readiness.** A booking is possible only after the service has licences, legal approvals, partner agreements, payment arrangements, safety requirements, and operations in place.
4. **Status changes without code deployment.** Admin changes the status per category and location.
5. **Payment does not confirm a booking by itself.** Confirmation comes from the booking engine after all conditions pass.
6. **Information-only services are never sold.** Planning, maps, and safety information are free and not bookable.
7. **Honest safety.** No 24/7 emergency claim unless a staffed, verified operation exists.

---

## 6. Service catalogue (31 categories)

Launch state is the state at first public launch. Every category is visible from the first public launch.

| Group | Category code | Category | Transactional | Launch state (initial) |
|---|---|---|---|---|
| Stay | hotels | Hotels and resorts | Yes | Coming Soon, then Available after the applicable booking readiness gate |
| Stay | homestays | Homestays | Yes | Coming Soon, then Available after the applicable booking readiness gate (pilot first) |
| Adventure | adventures | Adventures and experiences | Yes | Coming Soon (GATED on insurance and safety) |
| Adventure | trekking | Trekking | Yes | Partner Registration Open (GATED on operations) |
| Adventure | peak-climbing | Peak climbing | Yes | Coming Soon (GATED) |
| Travel | guides | Tour operators and guides | Yes | Partner Registration Open (GATED on licence verification) |
| Travel | transport | Transport (bus, car, jeep, taxi, rental, airport transfer) | Yes | Coming Soon (GATED on operator checks) |
| Travel | flights | Flights | Yes | Coming Soon (GATED on provider agreement) |
| Travel | luggage | Luggage services | Yes | Coming Soon |
| Travel | nearby-services | Nearby services (hospitals, pharmacies, ATMs, banks, fuel) | No | Testing (data source PENDING) |
| Connectivity | esim | eSIM | Yes | Coming Soon (GATED on provider agreement) |
| Connectivity | sim-info | SIM information | No | Coming Soon |
| Connectivity | offline-maps | Offline maps and navigation | No | Coming Soon (GATED on map licence) |
| Shop | shopping | Shopping marketplace | Yes | Coming Soon (GATED on seller and product compliance) |
| Local | restaurants | Restaurants and reservations | Yes | Coming Soon (GATED on partner agreements) |
| Local | local-experiences | Local experiences and community tourism | Yes | Coming Soon (GATED on partner verification) |
| Local | hidden-nepal | Hidden Nepal | No | Coming Soon (content) |
| Planning | ai-guide | AI travel guide | No | Coming Soon (GATED on provider terms) |
| Planning | trip-planning | Trip planner (visa, permits, packing, budget) | No | Testing |
| Safety | weather-alerts | Weather and safety alerts | No | Coming Soon (official data sources PENDING) |
| Safety | sos | SOS and emergency assistance | No | Coming Soon (public activation GATED on staffing) |
| Community | qr-scan | QR Scan Nepal | No | Coming Soon |
| Community | passport | Digital Travel Passport | No | Coming Soon |
| Community | memories | Pheri Memories | No | Coming Soon |
| Community | reviews | Reviews and TrustScore | No | Coming Soon |
| Community | rewards | Rewards and referrals | No | Coming Soon |
| Community | lost-found | Lost and Found | No | Coming Soon |
| Community | companion-matching | Travel companion matching | No | Coming Soon (GATED on safety and legal review) |
| Community | group-travel | Group travel | No | Coming Soon |
| Platform | travel-wallet | Travel wallet | No | Coming Soon (ledger GATED) |
| Platform | support | Support and disputes | No | Coming Soon |

**Note:** The transactional flags above follow the category data in the repository. Verify them against `packages/domain/src/categories.ts` before relying on this table.

---

## 7. Feature matrix

Priority: P0 = needed for the first booking launch, P1 = needed for growth, P2 = later or optional.

| Feature | Users | Visible at launch | State at launch | Legal / ops / tech dependency | Revenue potential | Phase | Priority |
|---|---|---|---|---|---|---|---|
| Homepage (EN, NE) | All | Yes | Operational | None | Indirect | the relevant phase defined in Part II | P0 |
| Service catalogue and status | All | Yes | Operational | None | Indirect | the relevant phase defined in Part II | P0 |
| Notify Me with consent | Traveler | Yes | Coming Soon | Consent text reviewed; retention PENDING | Indirect | the relevant phase defined in Part II | P0 |
| Partner registration | Partner | Yes | Partner Registration Open | Partner terms PENDING | Indirect | the relevant phase defined in Part II | P0 |
| Admin status control | Admin | Internal | Operational | Two-person approval | None | the relevant phase defined in Part II | P0 |
| Authentication and roles | All | Yes | Operational | MFA; data protection | None | the relevant phase defined in Part II | P0 |
| Homestay listing | Partner, traveler | Yes (pilot) | Available in pilot region only | Partner verification; tourism registration PENDING | Commission | partner onboarding and booking phases | P0 |
| Hotel listing | Partner, traveler | Yes | Coming Soon, then Available | Hotel licence PENDING | Commission | partner onboarding and booking phases | P0 |
| Instant Booking | Traveler, partner | Yes | After the applicable phase exit gate | Booking terms; payment for instant mode | Commission | the relevant phase defined in Part II | P0 |
| Approval Booking | Traveler, partner | Yes | After the applicable phase exit gate | Booking terms; response time rule | Commission | the relevant phase defined in Part II | P0 |
| Inventory and calendar | Partner | Partner dashboard | After Phase 07 booking gate | None beyond tech | Indirect | Phase 07 | P0 |
| My Trip (one itinerary) | Traveler | Yes | After the relevant trip-planning/booking gate | Data retention PENDING | Indirect | Phases 05, 07 and 11 | P0 |
| Payment (hold, release at check-in) | Traveler, partner | Yes | After the applicable phase exit gate | Gateway approval, legal terms PENDING | Enabler | the relevant phase defined in Part II | P0 |
| Refunds and cancellations | Traveler, partner | Yes | After the applicable phase exit gate | Refund policy PENDING lawyer | Enabler | the relevant phase defined in Part II | P0 |
| Commission and payouts | Partner, admin | Partner dashboard | After the applicable phase exit gate | Tax rules; accountant | Main revenue | the relevant phase defined in Part II | P0 |
| Reviews (stay-verified only) | Traveler, partner | Yes | After an eligible completed service | Moderation policy | Indirect | Phase 14 | P1 |
| Trek and adventure listings | Operator, traveler | Coming Soon | After the applicable phase exit gate | Licences, insurance, safety, permits | Commission | the relevant phase defined in Part II | P1 |
| Guide booking | Guide, traveler | Partner Registration Open | After the applicable phase exit gate | Licence verification process PENDING | Commission | the relevant phase defined in Part II | P1 |
| Transport and airport transfer | Operator, traveler | Coming Soon | After the applicable phase exit gate | Operator licence; provider agreements | Commission | the relevant phase defined in Part II | P1 |
| Flight information | Traveler | Coming Soon | After the applicable phase exit gate | Provider agreement GATED | Affiliate | the relevant phase defined in Part II | P2 |
| Luggage services | Traveler, provider | Coming Soon | After provider and operational readiness | Provider agreement | Commission | Phase 09 | P2 |
| eSIM sales | Traveler | Coming Soon | After the applicable phase exit gate | Provider agreement and technical integration GATED | Commission | the relevant phase defined in Part II | P1 |
| SIM information | Traveler | Yes | Operational (information) | None | Indirect | the relevant phase defined in Part II | P1 |
| Offline maps | Traveler | Coming Soon | After the applicable phase exit gate | Map licence GATED | Indirect | the relevant phase defined in Part II | P1 |
| AI travel guide | Traveler | Coming Soon | After the applicable phase exit gate | AI provider terms; grounding rules | Subscription or sponsorship (PENDING) | the relevant phase defined in Part II | P1 |
| Trip planner | Traveler | Yes | Testing | Content review by native speakers | Indirect | the relevant phase defined in Part II | P0 |
| Budget calculator | Traveler | Yes | Operational after the relevant content and readiness checks | Price data source PENDING | Indirect | the relevant phase defined in Part II | P0 |
| Checklists (packing, documents) | Traveler | Yes | Operational after the relevant content and readiness checks | Permit info verified against official source | Indirect | the relevant phase defined in Part II | P0 |
| Permit information | Traveler | Yes | Operational after the relevant content and readiness checks | Official source verification | Indirect | the relevant phase defined in Part II | P0 |
| SOS button | Traveler | Coming Soon | Activation GATED on staffing | Staffing, verified numbers, response process | Indirect | the relevant phase defined in Part II | P0 (safety) |
| Emergency contacts | Traveler | Yes after verification | Operational after the applicable safety/provider readiness gate | Verified numbers only | None | the relevant phase defined in Part II | P0 (safety) |
| Nearby services | Traveler | Yes | Testing | Data source PENDING | Affiliate | the relevant phase defined in Part II | P1 |
| Weather alerts | Traveler | Coming Soon | After official data-source approval | Official data source PENDING | None | Phase 11 | P1 |
| Shopping marketplace | Seller, buyer | Coming Soon | After the applicable phase exit gate | E-commerce rules; seller verification; product rules | Commission | the relevant phase defined in Part II | P2 |
| Restaurant reservations | Restaurant, traveler | Coming Soon | After the applicable phase exit gate | Partner agreements | Commission | the relevant phase defined in Part II | P2 |
| Local experiences | Provider, traveler | Coming Soon | After the applicable phase exit gate | Partner verification | Commission | the relevant phase defined in Part II | P1 |
| Support tickets and disputes | Traveler, partner | Yes | After minimum support operations are staffed | Support hours PENDING | None | Phase 13 | P0 |
| Group travel | Traveler | Coming Soon | After the relevant phase exit gate | Privacy design | Indirect | the relevant phase defined in Part II | P2 |
| Digital Travel Passport | Traveler | Coming Soon | After the relevant phase exit gate | Privacy and data design | Indirect | the relevant phase defined in Part II | P2 |
| Pheri Memories | Traveler | Coming Soon | After the relevant phase exit gate | Media moderation; storage | Indirect | the relevant phase defined in Part II | P2 |
| Rewards and referrals | Traveler | Coming Soon | After the relevant phase exit gate | Separate reward ledger; promotion rules | Indirect | the relevant phase defined in Part II | P2 |
| Lost and Found | Traveler | Coming Soon | After the relevant phase exit gate | Safety design | Indirect | the relevant phase defined in Part II | P2 |
| QR Scan Nepal | Traveler | Coming Soon | After the relevant phase exit gate | Content and data source | Indirect | the relevant phase defined in Part II | P2 |
| Hidden Nepal | Traveler | Coming Soon | After the relevant phase exit gate | Content creation | Indirect | the relevant phase defined in Part II | P2 |
| Companion matching | Traveler | Coming Soon | GATED on safety and legal review | Safety, privacy, moderation | Unclear | the relevant phase defined in Part II | P2 (optional) |
| Partner subscriptions | Partner | Not at launch | Later | Pricing research PENDING | Subscription | a later approved phase | P2 |
| Featured listings (labelled) | Partner | Not at launch | Later | Labelling rule | Ad-like | a later approved phase | P2 |
| Multi-currency display | Traveler | Yes | Planned | Currency codes PENDING | Indirect | the relevant phase defined in Part II | P1 |
| Mobile app (Android, iOS) | All | Not at launch | a later approved phase | Reuses API | Indirect | Later | P2 |

---

## 8. Experience journeys

### 8.1 Before travel

Traveler can:
- Discover destinations and filter by province and district
- Plan a trip (budget, permits, packing, season, weather)
- Explore stays and experiences (where available)
- Save destinations and stays
- Build an itinerary
- Book (after the relevant service is Available)

### 8.2 During travel

- My Trip dashboard with confirmed bookings and QR tickets
- Travel documents and offline copies
- Offline maps (when licensed)
- AI guide (when activated)
- Nearby services and emergency contacts
- Weather and safety information
- SOS (only when activated)
- Support chat or call (hours PENDING)
- Expense tracking
- Itinerary changes (booking rules apply)

### 8.3 After travel

- Travel memories and photos (with consent and moderation)
- Digital Travel Passport (privacy design first)
- Reviews from verified bookings only
- Complaints and feedback
- Lost and Found
- Rewards and referrals (separate ledger)
- Future trip suggestions

---

## 9. Customer and partner journeys

### 9.1 Traveler booking journey (the relevant phase defined in Part II)

1. Search by location, date, guests
2. View listing: photos, host story, verified badge, units, facilities
3. Choose date and unit; see total price with tax and service charge
4. See cancellation and refund policy before the booking button
5. Choose Instant or Approval mode (where offered)
6. Enter details and accept terms
7. Payment hold (after the applicable payment readiness gate) or request sent (approval mode)
8. Confirmation message with host details and directions
9. Check-in and stay
10. Review after check-out (verified booking only)

### 9.2 Homestay partner onboarding (the relevant phase defined in Part II)

1. Interest form or field visit
2. Identity and business or tourism document upload (private storage)
3. Verification by admin (site visit where possible)
4. Listing with photos (minimum 5), story, and rules
5. Calendar and pricing set
6. Readiness record with two approvers
7. Listing goes live when status is Available for that location

### 9.3 Guide onboarding (the relevant phase defined in Part II)

1. Licence and identity upload
2. Licence verification against the issuing authority (process PENDING)
3. Profile with languages, specialities, and references
4. Availability calendar
5. Activation after readiness

### 9.4 Coming Soon behaviour

- Label: Coming Soon
- Description of what the service will offer
- Notify Me with consent (email or phone), with consent record
- Partner registration button (where status allows)
- No fake prices, no fake availability, no booking button

---

## 10. Dashboards and admin control

### 10.1 Eight user dashboards

| # | Dashboard | Main functions | Phase ownership |
|---|---|---|---|
| \1 | \2 | \3 | See authoritative phase plan in Part II |
| \1 | \2 | \3 | See authoritative phase plan in Part II |
| \1 | \2 | \3 | See authoritative phase plan in Part II |
| \1 | \2 | \3 | See authoritative phase plan in Part II |
| \1 | \2 | \3 | See authoritative phase plan in Part II |
| \1 | \2 | \3 | See authoritative phase plan in Part II |
| \1 | \2 | \3 | See authoritative phase plan in Part II |
| \1 | \2 | \3 | See authoritative phase plan in Part II |

### 10.2 Admin control (17 areas)

1. Users
2. Partners
3. Verification queue
4. Service categories
5. Coming Soon and service statuses (with audit and two-person approval)
6. Bookings
7. Payments
8. Refunds
9. Commissions
10. Payouts
11. Reviews
12. Complaints
13. Customer support
14. SEO content
15. Notifications
16. Analytics
17. Fraud prevention, audit logs, and system settings

**Permissions (RECOMMENDED):** Role-based. Roles include super admin, operations, verification, finance, support, content, and read-only. Partner data is isolated to that partner. Every admin action writes to the audit log.

---

## 11. Booking model and engine

### 11.1 Booking modes (FINAL)

- **Instant Booking:** Accepted and confirmed once payment hold is successful and inventory is reserved.
- **Approval Booking:** Request goes to partner. Partner accepts or declines within a set time. If accepted, payment is held. If declined or expired, nothing is charged.

Both modes are mandatory in long-term architecture.

### 11.2 Booking gate (in code today, REPOSITORY-VERIFIED)

A booking is accepted only when all are true:
1. Global switch `BOOKING_ENABLED` is on (default off)
2. The category is transactional
3. The status for that location is Available
4. The requested mode is enabled for that status
5. The readiness record is complete with two distinct approvers

### 11.3 Engine rules (RECOMMENDED, to be built in Phase 07 and Phase 08)

- **Inventory holds:** A selected unit and dates are held for a short window (e.g. 10 to 15 minutes, value PENDING tests) during checkout.
- **Atomic reservation:** Database constraints and locking prevent double booking. Test with concurrent requests.
- **Expiry worker:** Expired holds are released automatically.
- **Idempotency:** Payment webhooks and booking requests carry idempotency keys. Repeated events do not create duplicate bookings or charges.
- **Payment failure:** Booking stays unconfirmed. The hold is released. The traveler is told clearly.
- **Confirmation:** Only after booking and payment conditions pass. Never on a button click.
- **Cancellation:** Rules set per listing, shown before booking. Each cancellation writes a record.
- **Refund:** Partial or full, as per policy. Tracked in the refund table.
- **Partner payout:** Released per schedule after the stay (schedule PENDING accountant).
- **Dispute hold:** Payout held while a dispute is open.

### 11.4 Booking states (RECOMMENDED)

Requested, Held, Approved, Auto-confirmed, Paid (held), Checked-in, Completed, Reviewed. Terminal branches: Declined, Expired, Cancelled, Refunded, No-show.

Each traveler has one Trip ID. Each service in the trip is a separate booking record with its own status, payment, refund, and audit trail (FINAL).

---

## 12. Payments, revenue, and money

### 12.1 Revenue sources (evaluate each; no figures invented)

| Source | Status |
|---|---|
| Hotel and homestay commission | Planned. Rate PENDING |
| Adventure and trek commission | Planned. GATED |
| Guide and tour commission | Planned. GATED |
| Transport commission | Planned. GATED |
| Tour package commission | Planned |
| eSIM commission | Planned. GATED |
| Shopping commission | Planned. GATED |
| Local experience commission | Planned |
| Restaurant reservation commission | Planned. GATED |
| Partner subscription | Later. Pricing research PENDING |
| Labelled featured listings | Later. Must be clearly marked as paid |
| Affiliate fees (flights, hotels outside platform) | Possible. Terms PENDING |

### 12.2 Payment design

- **Gateways:** eSewa, Khalti, Fonepay (local); Stripe or equivalent (international). All require merchant approval (PENDING).
- **Hold model:** Authorisation or manual capture, released at check-in (PENDING gateway capability).
- **Split and allocation:** Single collection with allocation per booking record, or gateway split. Decision PENDING gateway and legal answers.
- **Ledger:** Double-entry, append-only. Chart of accounts PENDING accountant.
- **Reward points:** Separate ledger from money.
- **Currency:** Display in several currencies; settle in one (FINAL rule). Currency codes PENDING.
- **Tax:** VAT and any tourism-related levies PENDING accountant.

### 12.3 Visible money rules (RECOMMENDED)

- Total price with all taxes and fees shown before payment.
- Refund policy shown before the booking button.
- Partner sees the commission and net amount before accepting a booking.
- Traveler receipt and invoice available in My Trip.

---

## 13. Trust, safety, and emergency

### 13.1 Trust

- Partner verification (identity, business or licence)
- Verified badge only after checks pass
- Reviews only from verified bookings; moderation rules; partner reply allowed
- TrustScore built from verified reviews, response time, dispute record (formula PENDING)
- Complaint and dispute process with timeline (support hours PENDING)

### 13.2 Safety

- **SOS:** Public activation GATED on staffing, verified contact numbers, response procedure, and incident management (the relevant phase defined in Part II). Until then, the button shows status and guidance, not a live emergency line.
- **Emergency numbers:** Shown only after verification. No emergency numbers are displayed until verified against an authoritative source.
- **Location sharing:** Only with explicit permission. Geolocation off by default.
- **Weather and disaster alerts:** Only from official sources (PENDING). Show time of data.
- **Route status:** Show closures and risk only from verified sources.
- **Insurance:** Minimum cover for trekking and adventure (PENDING insurer quotation). Show requirement to travelers.
- **No false claims:** No "24/7" or "instant rescue" wording unless backed by a staffed and tested operation.

### 13.3 Incident handling (the relevant phase defined in Part II)

Incident record, assigned responder, status tracking, escalation, closure and review. Staffing model PENDING.

---

## 14. Architecture

### 14.1 Principles

- One source of business rules (domain package, no framework dependency, tested)
- API-first so the web app, admin tools, partner tools, and future mobile apps use the same logic
- Security and audit built in from the start
- Database enforces critical rules (booking modes, append-only history, capacity)

### 14.2 Stack (with reasons)

| Layer | Choice | Reason | Status |
|---|---|---|---|
| Web | Next.js 14 (App Router), TypeScript | Server-rendered pages help SEO and mobile speed; TypeScript catches errors early | RECOMMENDED. Patched to 14.2.35 (repository) |
| Styling | Tailwind CSS, shadcn/ui (optional) | Fast, consistent design system | RECOMMENDED |
| Domain logic | Plain TypeScript package | Reusable across web, API, and mobile; easy to test | RECOMMENDED. Implementation status must be verified in the repository |
| API (initial web API, with future API extraction only if justified) | Next.js route handlers | Keeps the initial web stack runnable without extra services | RECOMMENDED. Implementation status must be verified in the repository |
| API (as complexity grows, subject to an architecture decision) | NestJS service for admin and partner APIs | Structured modules, guards, and validation as complexity grows. Adopt when admin and partner APIs justify it | RECOMMENDED. Decide at the relevant phase defined in Part II |
| Database | PostgreSQL 13 or later | Strong constraints, transactions, row-level security, JSON where needed | RECOMMENDED. Implementation status must be verified in the repository (migrations) |
| Hosting database | Managed PostgreSQL (provider PENDING) | Backups, updates, and security handled by provider | PENDING choice |
| Auth | Email OTP and password, MFA for admin and partner | Secure, familiar to Nepali users | RECOMMENDED. Built in the relevant phase defined in Part II |
| Cache | Redis only when needed (search, rate limits) | Avoid complexity until traffic justifies it | RECOMMENDED. Later |
| File storage | Object storage with private and public buckets | Documents private; listing photos public with resizing | RECOMMENDED. the relevant phase defined in Part II |
| Maps | Map provider PENDING licence and cost review | Licence and pricing differ by use | PENDING |
| AI | AI provider PENDING terms | Grounding and cost control required | GATED |
| Payments | Local and international gateways (see section 12) | Local trust and reach | GATED |
| Email | Transactional email provider | Confirmations and notices | PENDING choice |
| SMS and WhatsApp | Provider PENDING | Nepal reach; WhatsApp widely used | PENDING |
| Monitoring | Error tracking and product analytics | Find problems early | RECOMMENDED. the relevant phase defined in Part II |
| Hosting app | Vercel or equivalent | Simple deploys and previews | RECOMMENDED. Decide at the relevant phase defined in Part II |

### 14.3 Components

```
Browser (EN / NE, mobile-first) Partner and admin web
 \ /
 \ /
 apps/web (Next.js) ---- api service (NestJS, in the relevant phase defined in Part II)
 | |
 +-------- packages/domain (rules) --------+
 | |
 packages/db (PostgreSQL) Notifications, payments,
 AI, maps (via adapters)
```

**Adapters:** Payment, notification, maps, AI, and eSIM providers are behind adapter interfaces so providers can be swapped without rewriting business logic.

### 14.4 Environments

Development, staging, and production. Separate databases, secrets, and payment sandboxes. No production data in development.

---

## 15. Data model

### 15.1 Initial repository baseline (verification scope must be independently confirmed)

| Table | Purpose |
|---|---|
| service_categories | 31 categories, bilingual, group, transactional flag |
| locations | Locations (sample only; pilot region PENDING) |
| service_statuses | Status per category and location; booking mode flags |
| service_status_history | Append-only status changes with reason |
| readiness_records | Readiness checklist per category and location |
| readiness_approvals | Two distinct approvers per readiness record |
| audit_logs | Append-only admin and system actions |

### 15.2 Planned

| Domain | Tables | Phases |
|---|---|---|
| Identity | users, roles, sessions, mfa_factors, consent_records, notification_preferences | the relevant phase defined in Part II |
| Partners | partner_profiles, partner_documents (private), verification_checks, guide_licences | the relevant phase defined in Part II |
| Destinations | provinces, districts, destinations (coordinates, best season, permit notes, sources) | the relevant phase defined in Part II |
| Inventory | properties, units, rate_plans, availability_days, price_days, minimum_stay | the relevant phase defined in Part II |
| Trips and bookings | trips (Trip ID), booking_records, booking_items, holds, check_ins, reviews | the relevant phase defined in Part II |
| Money | payments, payment_allocations, ledger_entries, refunds, disputes, commissions, payouts, payout_items | the relevant phase defined in Part II |
| Transport and activities | vehicles, routes, schedules, activities, time_slots, capacity | the relevant phase defined in Part II |
| Connectivity | esim_products, esim_orders (provider data) | the relevant phase defined in Part II |
| Safety | emergency_contacts (verified), incidents, incident_updates, responders | the relevant phase defined in Part II |
| Shopping | sellers, products, product_variants, orders, order_items, returns | the relevant phase defined in Part II |
| Support | tickets, ticket_messages, complaints | the relevant phase defined in Part II |
| Community | passport_stamps, memories, media (moderation status), rewards_ledger, lost_found_reports, groups, group_members | the relevant phase defined in Part II |

**Rules:** Money in a separate ledger from rewards. Partner data isolated. Personal data minimised. Every admin change audited.

---

## 16. API planning

### 16.1 Principles

- Versioned from the start (`/api/v1`)
- Public read endpoints return no inventory, prices, or internal reasons unless needed for booking
- Write endpoints require authentication and role checks
- Idempotency key on booking and payment endpoints
- Rate limits on public endpoints
- Errors use consistent codes (e.g. `UNKNOWN_LOCATION`)

### 16.2 Endpoint groups (planning)

| Group | Examples | Auth | Phases |
|---|---|---|---|
| Catalogue | GET categories, GET category by code, GET catalogue by location | Public | catalogue shell first, database-backed catalogue in its assigned phase |
| Notify and consent | POST notify request (with consent record) | Public, rate limited | the relevant phase defined in Part II |
| Auth | POST login request, POST verify OTP, POST logout | Public or session | the relevant phase defined in Part II |
| Admin statuses | PATCH status, GET history | Admin, two-person approval | the relevant phase defined in Part II |
| Partners | POST registration, GET/PATCH profile, POST document | Partner | the relevant phase defined in Part II |
| Listings and inventory | CRUD listings, PUT availability, PUT prices | Partner | partner onboarding and booking phases |
| Search | GET listings by location, date, guests | Public | the relevant phase defined in Part II |
| Bookings | POST hold, POST booking (Instant), POST request (Approval), PATCH accept or decline, POST cancel | Traveler or partner | the relevant phase defined in Part II |
| Payments | POST payment intent, POST webhook (signed, idempotent) | Traveler; provider | the relevant phase defined in Part II |
| Refunds and disputes | POST refund, POST dispute | Admin, traveler | the relevant phase defined in Part II |
| Trips | GET my trip, GET booking documents | Traveler | the relevant phase defined in Part II |
| Reviews | POST review (verified booking), POST reply | Traveler, partner | the relevant phase defined in Part II |
| Support | POST ticket, GET ticket | Traveler, partner, admin | the relevant phase defined in Part II |
| Emergency | GET verified contacts, POST incident | Public (contacts), traveler (incident) | the relevant phase defined in Part II (GATED) |

---

## 17. Security and privacy

### 17.1 Security

- **Authentication:** OTP or password with secure hashing; MFA for admin and partner accounts; session expiry and device logout (the relevant phase defined in Part II).
- **Authorisation:** Role-based access with row-level security or equivalent. Partners see only their own data.
- **Secrets:** Environment variables only. No secrets in frontend code or repository.
- **Webhooks:** Verified signatures; idempotent processing.
- **Input validation:** Server-side on every write.
- **Headers (REPOSITORY-VERIFIED):** nosniff, frame deny, referrer policy, permissions policy.
- **Dependencies:** Regular updates; security advisories checked (Next.js patched in the relevant phase defined in Part II).
- **Logging:** No personal data or secrets in logs.
- **Backups:** Daily; restore tested before launch (the relevant phase defined in Part II).
- **Penetration test and independent review:** Before public launch (the relevant phase defined in Part II). Reviewer PENDING.

### 17.2 Privacy

- **Data minimisation:** No passport or government ID from travelers unless legally required.
- **Consent:** Notify Me and marketing consent recorded with time and version.
- **Documents:** Partner identity and business documents in private storage; admin access only; access logged.
- **Location:** Off by default. Requested only for SOS or nearby services, with clear reason.
- **Retention:** Periods for consent, logs, personal data, and documents PENDING lawyer.
- **Data subject rights:** Access, correction, and deletion requests process (PENDING legal review).
- **Nepal data protection:** Legal review PENDING. Do not claim compliance until confirmed.
- **Cross-border data:** Hosting location and transfer rules PENDING legal review.

---

## 18. Localisation

- **Launch (FINAL):** English and Nepali.
- **Later:** Up to 12 languages in phases. Priority based on arrivals and target markets (e.g. Chinese, Japanese, Korean, French, German, Spanish, Hindi, and others). Order to be decided with data.
- **Nepali quality (FINAL requirement):** Native-speaker review of every string before launch. Initial text is a first draft; review PENDING.
- **Architecture:** Strings keyed in i18n files; no hard-coded text. Right-to-left layout only if a RTL language is added.
- **Formats:** Dates, numbers, and currency follow locale.
- **Fonts:** Devanagari support (Noto Sans or system fallback).

---

## 19. SEO and content

### 19.1 Strategy

- Pages indexed only when the service is Available and the content is original (REPOSITORY-VERIFIED rule for category pages).
- Coming Soon and thin pages are noindex until they have real content (RECOMMENDED).
- Destination guides by province and district (the relevant phase defined in Part II), written with original content and verified facts.
- Trekking and adventure guides with safety and permit notes (the relevant phase defined in Part II).
- Homestay and hotel pages once live (the relevant phase defined in Part II).
- English and Nepali content, separate URLs, hreflang.
- Structured data where eligible (organisation, local business, breadcrumbs, FAQ where accurate).
- Sitemap, robots.txt, canonical URLs (the relevant phase defined in Part II).
- Search Console and analytics set up before launch.

### 19.2 Guardrails

- No thin, duplicated, or mass-generated pages.
- No promise of first-page or first-position rankings.
- Every factual claim about permits, fees, or routes linked to an official or verified source, and dated.

---

## 20. Design and UX

### 20.1 Feel and look (RECOMMENDED)

- Warm, calm, trustworthy, authentic. Not flashy.
- Colours: warm terracotta or maroon (primary), Himalayan blue and off-white (support), one accent for primary actions.
- Contrast WCAG 2.2 AA.
- Typography: one family for Devanagari and Latin (Noto Sans or Inter). Body 16px minimum.
- Photos lead. Real partner photos, no stock.
- Nepali patterns only as small borders or icons.
- Mobile-first at 375px. Maximum 4 to 5 main navigation items. Sticky bottom action on listing pages when booking is open.
- One primary action per screen.

### 20.2 Accessibility

- Skip link, visible focus, labels, status shown as text and icon, reduced motion respected (implementation status unverified).
- Audit with axe or Lighthouse and a screen-reader pass before launch (PENDING).
- Keyboard-only test on all pages (PENDING).

### 20.3 Low-connectivity mode

- Light pages and images (compressed WebP, lazy loading).
- Offline booking details and emergency info saved in the app when built (the relevant phase defined in Part II).

---

## 21. Operations and support

### 21.1 Team (solo founder now)

- **Now:** Founder does product, technology, and operations.
- **First hire (RECOMMENDED):** Host operations (Nepali and English): onboarding, photos, confirmations, support.
- **Second:** Developer (freelance or agency first).
- **Third:** Marketing and content.
- **Team model:** PENDING (in-house, contractor, or mixed).

### 21.2 Operations

- **Host onboarding:** Call or visit, document check, photo shoot, listing after approval.
- **Support:** WhatsApp, email, phone. Languages and hours PENDING. No 24/7 claim until staffed.
- **Dispute:** Clear steps and timeline for guest and partner.
- **Refunds:** Process owned by finance or ops; SLA PENDING.
- **Incident response:** Procedure for booking problems, data incidents, safety incidents (the relevant phase defined in Part II).
- **Runbooks:** Written for each process before the process goes live.

### 21.3 Staff contracts (Nepal)

Clear scope, hours, and payment. Company owns code and design. Least-privilege access. SSF and TDS obligations checked with an accountant. Labour law review PENDING.

---

## 22. Legal and licensing checklist (PENDING verification)

This is a planning checklist. Each item needs current official source verification and, where noted, professional advice. Nothing here is confirmed.

| Area | Items to verify | Source type | Status |
|---|---|---|---|
| Company | Registration type, signatory authority, name availability | Company registrar | PENDING |
| Tax | PAN, VAT registration and threshold, tourism-related levies | Tax authority; accountant | PENDING |
| Banking | Business bank account, merchant accounts | Bank; gateway | PENDING |
| Tourism business | Licence needed for hotels, homestays, travel agency, trekking agency, guide | Nepal Tourism Board; relevant ministry | PENDING |
| Homestay | Registration rules for homestay operators | Tourism authority | PENDING |
| Trekking and guides | Licence for guides and porters; agency requirements; insurance rules | Tourism board; TAAN (verify current role) | PENDING |
| Adventure | Operator licence per activity; safety standards; insurance | Relevant authorities | PENDING |
| Transport | Operator licence and vehicle permits | Transport authority | PENDING |
| Flights and airlines | Agency rules; provider agreements | Civil aviation authority; airline | PENDING |
| eSIM and telecom | Rules for reselling eSIM; provider agreement | Telecom regulator; provider | PENDING |
| Maps | Licence for offline map data | Map provider | PENDING |
| E-commerce and marketplace | Seller rules, product rules, consumer protection | Relevant ministry; lawyer | PENDING |
| Payments | Merchant approval, settlement, cross-border rules | Gateway; central bank rules | PENDING |
| Consumer protection | Refund and cancellation obligations | Relevant authority; lawyer | PENDING |
| Data protection | Nepal data protection and privacy obligations; location data | Official text; lawyer | PENDING |
| Content | Terms, privacy policy, refund policy text | Lawyer | PENDING |
| Insurance | Liability cover for platform and partners | Insurer | PENDING |
| Online booking | 2019 government directive on online booking and hospitality (noted in research); current status | Official text; lawyer | PENDING |

**Rule:** Do not assume one licence covers every category. Each category has its own gate.

---

## 23. Phase-by-phase development plan

The authoritative delivery sequence is the 18-phase plan in Part II, Sections 36–55. The project is developed phase by phase; no phases-based delivery model is used. Each phase has a feature inventory, dependencies, deliverables, acceptance criteria and an evidence-based exit gate.

---

## 24. Budget (assumptions only)

**No cost figures are confirmed.** Costs depend on team model, vendor quotes, and approvals. Use this section as a checklist of cost areas, not as a budget.

| Cost area | Notes | Estimate status |
|---|---|---|
| Company registration and legal review | Lawyer fees for terms, partner agreement, privacy | Quote PENDING |
| Accounting and tax | Accountant, VAT setup | Quote PENDING |
| Hosting (app, database, storage) | Usage-based; free tiers for early stage | Quote PENDING |
| Domain, email, SMS, WhatsApp | Usage-based | Quote PENDING |
| Payment gateway fees | Per transaction; approval fees if any | Gateway terms PENDING |
| Maps and AI APIs | Usage-based; licence terms affect offline use | Provider terms PENDING |
| Insurance | Platform and partner liability | Insurer quote PENDING |
| Design | Figma and design work | Hours to be decided |
| Development | Founder time or contractor | Depends on team model |
| Security review and penetration test | Independent reviewer | Quote PENDING |
| Marketing | Content, social, paid trials | Budget decision PENDING |
| Staff | Host operations first | Salary and contract PENDING |
| Contingency | Unplanned legal, technical, or pilot costs | Percentage PENDING |

**Scenarios (PENDING owner choice):** Lean (founder-led, minimal paid tools), Standard (founder plus operations hire, contractor developer), Growth (full team and marketing). Each to be costed after vendor quotes.

---

## 25. Metrics

- **Supply:** Partners verified; listings live; share of listings with 5+ photos; time from application to live
- **Demand:** Search to listing view; listing to booking conversion; booking to completed stay
- **Trust:** Average rating; review response rate; dispute rate; refund rate; verified review share
- **Money:** Payment success rate; average booking value; commission earned; payout timeliness (after the applicable payment readiness gate)
- **Retention:** Repeat travelers; partner retention (target to be set after pilot; earlier draft figures are not confirmed)
- **Quality:** Mobile page speed; uptime; support response time; bug escape rate
- **Safety:** Incidents logged; time to acknowledge (after the applicable safety/provider readiness gate)

---

## 26. Risk register

| # | Risk | Likelihood | Impact | Mitigation | Owner |
|---|---|---|---|---|---|
| 1 | Fake or unsafe listings | Medium | High | Verification, photo checks, review moderation, status control | Ops |
| 2 | Payment dispute or fraud | Medium | High | Hold model, clear refund policy, idempotent webhooks, reconciliation | Finance |
| 3 | Double booking | Medium | High | Database constraints, holds, locking, concurrency tests | Tech |
| 4 | Regulatory or licence gap | Medium | High | Legal review per category; gated launch | Founder |
| 5 | False safety expectation (SOS) | Low to medium | Very high | SOS off until staffed; honest wording; incident process | Founder, Ops |
| 6 | Weak connectivity in hills | High | Medium | Offline info; low-data mode; offline maps after licence | Tech |
| 7 | Climate and disaster disruption | High | High | Official alerts; cancellation rules; route status | Ops |
| 8 | Solo founder bandwidth | High | High | Phases gates; scope discipline; early operations hire | Founder |
| 9 | Competitor (ghumNepal, Booking.com, Airbnb) | High | Medium | Verified local trust; transparent money; community impact | Founder |
| 10 | Nepali translation quality | Medium | Medium | Native-speaker review before launch | Content |
| 11 | Security incident | Low to medium | Very high | Pen test; least privilege; audit log; tested backups | Tech |
| 12 | Scope creep | High | Medium | Each feature in a phases with exit criterion | Founder |
| 13 | Partner onboarding friction for villagers | High | Medium | Assisted onboarding; phone and WhatsApp; field agent | Ops |
| 14 | Commission and pricing disputes with partners | Medium | Medium | Clear terms; visible commission before acceptance | Founder |
| 15 | Overbuilding homestay and hotel supply in a market with weaker demand | Low to medium | Medium | Pilot region with demand evidence; partner data | Founder |
| 16 | Regulatory change (online booking rules) | Medium | High | Legal watch; monitor official sources | Founder |
| 17 | Data protection breach or non-compliance | Low to medium | Very high | Minimisation; consent; retention; legal review | Tech, Legal |

---

## 27. Launch and pilot strategy

### 27.1 Pilot criteria

- **Region:** Owner decision (PENDING). Choose by partner supply, trek and stay demand, and operational reach.
- **Partners:** 5 to 10 verified homestays or hotels.
- **Bookings:** Target 50 real bookings before public launch (RECOMMENDED).
- **Quality gate:** Payment success rate, dispute rate, and partner satisfaction recorded and reviewed.
- **Exit:** Pilot passes its metrics and the owner approves the public launch.

### 27.2 Category pilots

Each category opens separately when it meets its gate. Homestays and hotels first. Adventure and transport after their licence and insurance checks. Shopping and restaurants last.

### 27.3 Public launch

- Announce only Available services as bookable.
- Coming Soon services shown with honest status and Notify Me.
- Support channels live before launch.
- Monitoring and incident process live before launch.

---

## 28. Open decisions for the owner

1. Source of truth for phases: this 18-phase plan with phase ownership mapping (RECOMMENDED), or another structure?
2. Pilot region (province and district).
3. First booking category: homestays (RECOMMENDED) or hotels.
4. Commission rate and base (gross or net of tax).
5. Company type and registration status.
6. Team model and budget scenario.
7. Hours per week available for building.
8. Gateway applications to start first.
9. Hosting provider for the database.
10. Support hours and languages.
11. Tagline and brand mood (Himal, Gaun, or Adventure).
12. Whether to pursue companion matching at all.
13. Whether to launch SOS with staffing or delay until staffed.
14. Whether to use NestJS in the relevant phase defined in Part II, or keep Next.js route handlers longer.

---

## 29. Immediate next steps

1. Owner answers section 28 (items 1 to 3 first).
2. Verify the repository on Node 20, a real PostgreSQL server, and a browser at 375, 768, and 1280 px.
3. Native-speaker review of Nepali strings.
4. Legal and payment questions sent to lawyer and gateways; answers filed in DECISIONS.md.
5. Competitor test (section 3 action) with dated screenshots.
6. Write the Product Requirements Document (PRD) from this blueprint, feature by feature.
7. Design direction chosen; Figma wireframes for listing detail, booking, and homepage.
8. Begin implementation only after the required owner decisions are settled.

---

## 30. Glossary

- **Available:** Service open for booking in a location.
- **Booking gate:** The single rule deciding whether a booking can be accepted.
- **Readiness record:** Checklist that must be complete, with two approvers, before a service goes live.
- **Transactional category:** A service involving money or reservations.
- **My Trip:** One itinerary per traveler, with a separate booking record per service.
- **Hold:** Temporary reservation of inventory during checkout.
- **Idempotency key:** A unique key ensuring a repeated request or webhook is processed once.
- **GATED:** Not started until the named approval is received in writing.
- **PENDING:** Not confirmed; depends on an answer or verification.

---

## 31. Technical architecture and engineering specification

### 31.1 Architecture principles and system boundaries

#### 31.1.1 Architecture style

Use a modular monolith as the default initial architecture. This is an implementation recommendation, not a change to the this blueprint product scope.

- Keep business logic in explicit domain modules, independent of the web framework.
- Keep the web application, API transport layer, background workers and provider adapters as separate boundaries even if they initially deploy together.
- Do not introduce microservices merely for fashion or speculative scale.
- A module may be extracted into a separate service only when measured load, team ownership, security isolation, deployment independence or provider constraints justify it.
- Do not duplicate business rules in UI components, API handlers, workers and provider callbacks.

#### 31.1.2 Logical system components

The system must have clear boundaries for:

1. Web presentation and localization.
2. Authentication and session management.
3. Authorization and role/tenant policy.
4. Service catalogue and location-specific status.
5. Partner onboarding and verification.
6. Readiness and two-person approval.
7. Inventory and availability.
8. Booking orchestration.
9. Payment orchestration and provider adapters.
10. Financial ledger, commissions, refunds and payouts.
11. Notifications and consent.
12. Reviews, complaints and disputes.
13. Travel itinerary / My Trip.
14. Safety information and gated SOS operations.
15. Search, destination content and SEO.
16. Audit trail and operational observability.
17. Background jobs and scheduled processing.
18. External integrations (maps, weather, SMS/email, payment gateways and AI providers).

Each module must document its owner, data it owns, public interfaces, events emitted/consumed, permissions, failure modes and tests.

#### 31.1.3 Dependency direction

- Domain modules must not import UI components or framework route handlers.
- Domain rules must not depend directly on a payment, maps, messaging or AI vendor SDK.
- Provider-specific code belongs behind typed adapters.
- Modules communicate through documented application services or versioned domain events; avoid direct cross-module table mutation.
- A module may read another module's public query interface, but may not bypass its invariants by writing directly to its tables.
- Shared packages must remain small and must not become an unstructured dumping ground.

#### 31.1.4 Deployment topology

The initial deployment topology is `PENDING` until the owner selects hosting providers. The implementation must nevertheless support:

- Web/API application.
- PostgreSQL database.
- Background worker process.
- Scheduled-job runner.
- Private object storage for partner documents and other restricted files.
- Centralized logs, metrics and error reporting.
- Separate development, test/staging and production environments.

Do not assume a specific cloud vendor, region, paid plan or service availability. Record the selected provider, data region, contractual terms, backup policy and exit strategy in `DECISIONS.md`.

---

### 31.2 Database architecture and data integrity

#### 31.2.1 Database baseline

PostgreSQL remains the the selected database. The minimum supported version must be selected and pinned by the engineering owner before implementation; the broad `PostgreSQL 13+` statement is not a substitute for a tested version policy.

Every migration must be:
- Version-controlled and immutable after deployment.
- Reviewed before production.
- Tested against an empty database and an upgrade from the previous supported schema.
- Safe to retry where possible.
- Accompanied by rollback or forward-fix instructions.
- Tested for data preservation and lock/downtime impact.

Never rely only on application validation for critical financial, booking, ownership or uniqueness invariants. Enforce them in PostgreSQL where feasible.

#### 31.3.2 Required schema documentation

Before Phase 07 booking implementation, publish an ERD and a data dictionary covering at least:

- Table and column names.
- Data types, nullability and defaults.
- Primary keys and foreign keys.
- Unique constraints and check constraints.
- Indexes and expected query patterns.
- Ownership and tenant scope.
- Created/updated/deleted timestamps and actor attribution.
- Retention and deletion policy.
- Sensitive-data classification.
- Allowed state values and transition ownership.

The existing this blueprint initial database tables remain in scope: `service_categories`, `locations`, `service_statuses`, `service_status_history`, `readiness_records`, `readiness_approvals` and `audit_logs`. Their implementation must be checked against the repository before claiming they exist or are correct.

#### 31.3.3 Data ownership and tenancy

- Every partner-owned resource must have an explicit owning partner/tenant relationship.
- Every customer-owned resource must have an explicit customer relationship.
- Authorization must be checked on every read and write, not only by hiding UI controls.
- A partner must never access another partner's listings, inventory, bookings, documents, payout data or customer data unless a documented operational permission allows it.
- Admin access must be role-scoped and audited.
- If PostgreSQL Row-Level Security is used, document policies and test them with both allowed and denied identities. RLS does not replace application authorization.

#### 31.3.4 Deletion and history

- Financial ledger entries, booking state history, payment events and audit records must not be destructively edited to conceal history.
- Corrections use compensating/reversal records.
- Soft deletion is not a substitute for a retention policy.
- Define how personal data is anonymized or deleted when legally permitted while preserving required accounting/audit records.
- Exact retention periods remain `PENDING` legal review.

#### 31.3.5 Required indexes and constraints

The schema review must consider indexes for:
- Foreign-key joins and tenant-scoped queries.
- Listing search by location, category and status.
- Inventory by resource and date/time range.
- Booking lookup by public reference, customer, partner and state.
- Payment/provider reference and idempotency key.
- Ledger account and transaction sequence.
- Webhook event deduplication.
- Consent lookup and notification suppression.
- Audit log actor, entity and timestamp.

Use unique constraints for provider event IDs, idempotency scopes, public references and other uniqueness invariants. Do not add speculative indexes without query evidence; capture `EXPLAIN (ANALYZE, BUFFERS)` for important production-like queries.

---

### 31.3 Booking engine — required state and transaction rules

The booking gates and Instant/Approval modes must be implemented as specified. This section makes their implementation testable.

#### 31.3.1 Separate state dimensions

Do not collapse booking, inventory hold and payment into one overloaded status field. Maintain distinct state machines.

**Booking state (minimum proposed vocabulary):**

`DRAFT → REQUESTED → PENDING_PARTNER → ACCEPTED → CONFIRMED → IN_SERVICE → COMPLETED`

Terminal or exception states include:

`REJECTED`, `EXPIRED`, `CANCELLED`, `FAILED`, `DISPUTED`, `NO_SHOW`.

The exact state names and allowed transitions must be approved in the booking specification before implementation. A state may be skipped only through an explicitly documented transition. Never let clients submit arbitrary target states.

**Inventory hold state:**

`ACTIVE`, `CONSUMED`, `RELEASED`, `EXPIRED`.

**Payment state:**

`NOT_REQUIRED`, `REQUIRES_ACTION`, `AUTHORIZED`, `CAPTURE_PENDING`, `CAPTURED`, `PARTIALLY_REFUNDED`, `REFUNDED`, `FAILED`, `CANCELLED`, `UNKNOWN`.

These are proposed technical vocabularies, not owner decisions about commercial policy. Finalize them in `BOOKING_ENGINE.md` and `PAYMENT_LEDGER.md`.

#### 31.4.2 Booking gate — mandatory server-side rule

A booking command must fail closed unless all applicable conditions are true at the moment of acceptance:

1. Global `BOOKING_ENABLED` is enabled.
2. Category is transactional.
3. Category and requested location status are `Available`.
4. Requested booking mode is enabled for that category/location.
5. Partner and listing are verified and active.
6. Required licence, insurance, legal, provider and operational readiness evidence is current.
7. Readiness checklist is complete.
8. Two distinct authorized approvers have approved the current readiness revision.
9. Inventory is available and can be atomically reserved.
10. Required price, cancellation terms, taxes/fees and customer consent are present.
11. No suspension, safety block, expiry or emergency disable rule applies.

The server must re-check the gate during the final transaction; a previously rendered page or cached availability result is not authorization to book.

#### 31.4.3 Instant Booking flow

1. Validate identity, authorization, terms, price and gate.
2. Start a database transaction.
3. Lock or atomically claim the relevant inventory unit/date range.
4. Confirm capacity remains available.
5. Create an expiring hold and booking attempt.
6. Persist an idempotency record.
7. Commit the reservation attempt.
8. Execute the payment authorization/required payment action through the payment orchestration layer.
9. Reconcile the provider result using verified webhook and/or provider status lookup.
10. Confirm booking only when all booking, inventory, readiness and payment conditions are satisfied.
11. Consume the hold on confirmation; otherwise release it according to the documented failure/expiry policy.
12. Notify customer and partner using an outbox-backed notification process.

A browser redirect, success screen, client callback or unverified webhook must never independently confirm a booking.

#### 31.4.4 Approval Booking flow

1. Validate the booking gate and inventory.
2. Create a request with an explicit partner response deadline.
3. Define whether inventory is held while awaiting partner approval; this policy is `PENDING` and must be chosen per category.
4. Partner accepts or rejects through an authenticated, authorized action.
5. Acceptance revalidates inventory and readiness within a transaction.
6. If payment is required, proceed through the documented payment authorization/capture policy.
7. Confirm only after all conditions pass.
8. On rejection, timeout or failed payment, release any active hold and record the reason.

#### 31.4.5 Concurrency and overbooking prevention

- Use database transactions and an appropriate locking/constraint strategy for each inventory model.
- A read-then-write availability check without a database-level concurrency guard is insufficient.
- Define how overlapping date ranges, units, capacity, time slots and quantity inventory are represented.
- Use PostgreSQL exclusion constraints where appropriate for non-overlapping reservations; otherwise document and test the chosen atomic counter/row-lock design.
- Define isolation level and retry policy for serialization/deadlock errors.
- Retry only safe idempotent operations.
- Run concurrent booking tests that attempt to reserve the final available unit; exactly the permitted capacity may succeed.

#### 31.4.6 Expiry and recovery

- Holds must have an explicit expiry timestamp and a durable release mechanism.
- A scheduled worker must find and process expired holds; correctness must not depend on a user returning to the website.
- Worker jobs must be idempotent and safe to retry.
- Monitor delayed jobs, repeated failures and stuck holds.
- A reconciliation job must identify bookings whose payment and booking states disagree.

#### 31.4.7 Required edge cases

Acceptance tests must cover:
- Double click / duplicate booking submission.
- Two users attempting the last unit simultaneously.
- Partner rejection after request.
- Partner does not respond before deadline.
- Payment authorization timeout or unknown provider result.
- Payment succeeds but browser closes or client never receives response.
- Duplicate, delayed, out-of-order and invalid-signature webhook.
- Hold expires while payment is processing.
- Booking is cancelled while payment is pending.
- Partial refund and full refund.
- Partner suspension after listing page was opened.
- Readiness approval revoked or expired before booking.
- Date/time-zone and daylight-saving boundary where applicable.
- Worker outage and recovery.
- Manual admin intervention with audit trail.

#### 31.4.8 Cancellation, no-show and dispute

Cancellation windows, fees, partner response deadlines, no-show rules and dispute outcomes remain `PENDING` owner/legal decisions. The technical system must support versioned policy snapshots attached to each booking so a later policy edit cannot silently rewrite an existing booking's terms.

---

### 31.4 Payment, ledger, refunds and payout architecture

#### 31.4.1 Provider isolation

Keep eSewa, Khalti, Fonepay, Stripe or any future provider behind separate adapters implementing a common internal contract. Provider selection, merchant eligibility, cross-border availability and commercial terms remain `PENDING` until confirmed in writing.

Never store raw card credentials. Never expose provider secrets to the browser. Verify signatures and timestamps for webhooks and reject invalid or replayed events.

#### 31.5.2 Payment orchestration

- Persist an internal payment attempt before calling the provider.
- Use a unique idempotency key scoped to the operation and merchant/account.
- Persist provider transaction references and raw webhook payloads only where lawful and necessary; protect and redact sensitive fields.
- Treat timeouts as `UNKNOWN` until reconciled, not automatically failed.
- Deduplicate provider events using a unique provider event identifier.
- Process provider events transactionally with state changes and ledger/outbox records.
- Never trust the amount, currency, booking ID or status supplied by an untrusted client callback.
- Compare provider amount/currency/reference against the internal expected payment before accepting success.
- Define capture, void, release and refund semantics per provider.

#### 31.5.3 Double-entry ledger

Before Phase 08 payment implementation, specify a double-entry append-only ledger with:

- Chart of accounts and account ownership.
- Currency-specific accounts; do not net unlike currencies.
- Debit/credit equality per journal transaction and currency.
- Integer minor units or an explicitly approved fixed-precision decimal strategy; never use binary floating point for money.
- Immutable posted journal entries.
- Reversal/correction entries rather than editing posted entries.
- Source reference to booking, payment, refund, fee, commission or payout.
- Idempotency and uniqueness constraints.
- Pending, available, held and payable balances as defined accounting concepts, not arbitrary mutable totals.
- Reconciliation between provider settlements, bank statements and internal ledger.

A balance shown to users must be derived from ledger entries or a rigorously maintained projection that can be rebuilt and reconciled.

#### 31.5.4 Money flow and release policy

the platform's intent to protect payment until service delivery remains. The exact legal mechanism (authorization hold, escrow-like arrangement, delayed capture, marketplace settlement or another lawful structure) is `PENDING` provider and legal confirmation. Do not describe the platform as holding escrow funds unless the legal and provider model explicitly permits it.

Before launch, document:
- When customer is charged/captured.
- Who is merchant of record.
- Who legally receives funds.
- When partner becomes payable.
- What event authorizes release.
- How taxes, gateway fees, commission and refunds are allocated.
- What happens if the service is not delivered.
- How negative balances, chargebacks and reserves are handled.

#### 31.5.5 Refunds and payouts

- Every refund references the original payment and booking.
- Partial refunds must not exceed the remaining refundable amount.
- Duplicate refund requests must be idempotent.
- Refund status must distinguish requested, submitted, succeeded, failed and unknown.
- Payouts require eligibility checks, a unique payout reference and ledger posting.
- Failed payouts remain visible and reconcilable; never silently mark as paid.
- Manual adjustments require reason, actor, approval and audit history.
- Reward points/credits use the separate reward ledger defined for the platform and must not be mixed with monetary balances.

#### 31.5.6 Financial reconciliation

Daily or otherwise risk-appropriate reconciliation must compare:
1. Internal payment attempts and provider transactions.
2. Provider settlement reports and bank credits.
3. Internal ledger balances and partner payable balances.
4. Refunds, chargebacks, fees, commissions and payouts.

Unmatched records must enter an exception queue with owner, age, amount/currency and resolution history. Reconciliation frequency and operational owner are `PENDING`.

---

### 31.5 API contract and integration rules

#### 31.5.1 API baseline

Retain the versioned `/api/v1` approach. Publish an OpenAPI specification for all externally consumed endpoints and keep it synchronized with runtime validation.

Each endpoint must specify:
- Method and path.
- Authentication and required permissions.
- Request schema and response schema.
- Validation and business errors.
- Pagination/filter/sort behaviour.
- Idempotency requirement.
- Rate limit.
- Audit/event side effects.
- Data classification.
- Compatibility/deprecation policy.

#### 31.6.2 API response and error conventions

Adopt one consistent envelope for success and one for errors. The exact JSON shape must be finalized in `API_SPECIFICATION.md`; do not let each route invent its own format.

Errors must include a stable machine-readable code, safe human-readable message, request/correlation ID and field-level validation details where appropriate. Never return stack traces, secrets, SQL errors or private partner/customer information.

#### 31.6.3 Security on every endpoint

- Validate authentication and authorization server-side.
- Validate tenant/resource ownership for every object identifier (prevent IDOR/BOLA).
- Validate input with shared schemas at the API boundary.
- Apply rate limits to login, OTP, search, booking, payment and public submission endpoints.
- Use CSRF protection where cookie-based authentication requires it.
- Configure CORS narrowly.
- Prevent mass assignment by explicit input allowlists.
- Do not rely on UI visibility for permissions.
- Public read endpoints expose only intentionally public fields.

#### 31.6.4 Idempotency

For booking, payment, refund, payout and webhook operations:
- Require or generate a stable idempotency key.
- Store operation scope, key, request hash, state, response reference and expiry/retention rule.
- Reject reuse of the same key with a materially different payload.
- Return the original result for a valid duplicate.
- Protect with a database uniqueness constraint.

#### 31.6.5 Pagination and search

Use stable cursor pagination for large or changing result sets where appropriate. Define maximum page size, allowed sort fields, filters and deterministic tie-breakers. Never accept arbitrary SQL sort or filter expressions from clients.

#### 31.6.6 Provider adapter contract

Every adapter must define:
- Typed input/output.
- Authentication and secret rotation.
- Timeout and retry policy.
- Idempotency support or internal deduplication.
- Webhook verification.
- Error mapping.
- Rate limits and quotas.
- Sandbox and production test procedure.
- Data residency/retention and contractual dependencies.
- Operational fallback and provider outage behaviour.

---

### 31.6 Identity, authorization and security architecture

#### 31.6.1 Role and permission matrix

Before Phase 03 identity/admin implementation, create a permission matrix for at least:
- Anonymous visitor.
- Customer/traveler.
- Hotel/homestay partner.
- Guide/porter.
- Transport partner.
- Adventure operator.
- Shopping seller.
- Restaurant/local-experience partner.
- Support agent.
- Verification operator.
- Finance operator.
- Admin.
- Owner/founder.

Define permissions by resource and action (read, create, update, approve, suspend, refund, payout, export, delete). Separate sensitive duties: a user who creates or edits a readiness record must not be the sole second approver for that same record. Financial approval thresholds and dual control remain owner/accountant decisions.

#### 31.7.2 Authentication

Authentication provider and exact method remain `PENDING`. Regardless of provider:
- Secure password hashing if passwords are used.
- OTP expiry, attempt limits, resend throttling and abuse detection.
- Secure session rotation and revocation.
- MFA for privileged/admin and finance roles before sensitive production operations.
- Account recovery that does not bypass MFA or partner verification.
- Login and security event audit.
- No secrets or OTP values in logs.

#### 31.7.3 Threat model and security tests

Create a threat model before public booking launch. Include:
- Broken access control / IDOR / tenant leakage.
- Account takeover, OTP brute force and credential stuffing.
- CSRF, XSS, SSRF, SQL injection and unsafe file upload.
- Webhook spoofing, replay and duplicate processing.
- Payment tampering and price manipulation.
- Privilege escalation and approval collusion.
- Sensitive document exposure.
- Denial of service and scraping.
- Prompt injection and data leakage in AI features.
- Supply-chain and dependency compromise.
- Backup theft and production secret leakage.

For each threat, record assets, attack path, mitigation, owner and test evidence.

#### 31.7.4 File and document security

- Store partner identity/licence documents in private object storage.
- Use short-lived signed access links after authorization.
- Validate file type by content, size and allowed extension.
- Malware-scan uploads before making them available to staff.
- Prevent public indexing and direct unauthenticated access.
- Log access to sensitive documents.
- Define retention and deletion with legal review.

#### 31.7.5 Security operations

Before public launch, document:
- Secret rotation and emergency revocation.
- Dependency and container scanning.
- Vulnerability triage and patch SLAs.
- Incident response and breach escalation.
- Backup encryption and access control.
- Security contact and responsible disclosure process.
- Independent penetration test and remediation evidence.

The the platform security requirements remain in force; this section adds implementation and evidence requirements.

---

### 31.7 Background jobs, events and notifications

#### 31.7.1 Durable asynchronous processing

Use a durable job/outbox approach for actions that must survive process restarts, including:
- Hold expiry.
- Payment reconciliation.
- Webhook processing.
- Partner response deadline.
- Email/SMS/WhatsApp notification delivery.
- Refund/payout status polling.
- Review invitation.
- Weather or official-source refresh where enabled.
- Retention/anonymization tasks when legally approved.

The chosen queue technology is `PENDING`; a database-backed outbox is acceptable initially if it meets reliability and throughput needs.

#### 31.8.2 Outbox/inbox rules

- Commit the business state change and outgoing event record in the same database transaction.
- Workers deliver events at least once; consumers must be idempotent.
- Persist inbound webhook/event IDs to prevent duplicate processing.
- Track attempts, last error, next retry, dead-letter/manual-review status and completion.
- Never assume exactly-once delivery from a queue or external provider.

#### 31.8.3 Notification policy

- Store consent separately from delivery status.
- Distinguish transactional notifications from marketing.
- Respect opt-outs for marketing; do not suppress legally/operationally necessary booking notices without an approved policy.
- Record template version and language.
- Retry transient failures with bounded backoff; route permanent failures to review.
- Do not put sensitive personal, identity or payment data in notification content.
- Provider choice, support hours and languages remain `PENDING`.

---

### 31.8 Search, content, location and data freshness

#### 31.8.1 Location model

Define canonical province, district, municipality and destination identifiers with aliases and transliterations. Preserve source and last-verified date for factual location data. Avoid treating free-text spelling variants as separate destinations.

#### 31.9.2 Search behaviour

Document searchable fields, filters, ranking, language handling, typo tolerance, pagination and visibility rules. Search results must respect category/location status, partner suspension and inventory freshness. Search ranking must not override safety, verification or availability gates.

#### 31.9.3 Official information provenance

For permits, fees, routes, emergency contacts, weather and safety:
- Store source organization and source URL/reference.
- Record last checked timestamp and next review date.
- Display an update date where useful.
- Mark stale or unverified information clearly.
- Disable or withdraw information when its source is no longer trustworthy.
- Do not invent live route/weather/emergency data.
- Legal and operational review remains required for public safety claims.

---

### 31.9 AI travel guide and intelligent features

The the AI guide remains gated on provider terms. Before activation, define:

- Approved knowledge sources and their owners.
- Retrieval/index refresh and deletion process.
- Citation/source display for factual travel answers.
- Rules for uncertainty and refusal to guess.
- Prompt-injection isolation for retrieved web/user content.
- Protection of personal and partner data.
- No autonomous booking, payment, refund, SOS dispatch or partner approval without explicit authorized user confirmation and deterministic policy checks.
- Human escalation for high-risk safety/legal/medical questions.
- Evaluation dataset covering permits, prices, routes, weather, emergency information, multilingual queries and adversarial prompts.
- Hallucination, citation correctness, privacy, latency and cost thresholds.
- Rate limits, abuse controls, fallback and provider outage behaviour.

AI must not override the category booking gate, official-source freshness checks or SOS staffing gate.

---

### 31.10 Testing and acceptance strategy

#### 31.10.1 Test layers

Every phases must include applicable:
- Unit tests for domain rules and state transitions.
- Integration tests against a real PostgreSQL instance.
- API contract tests.
- End-to-end browser tests at mobile, tablet and desktop breakpoints.
- Authorization and tenant-isolation tests.
- Concurrency tests for inventory and financial operations.
- Webhook replay/idempotency tests.
- Migration upgrade and rollback/forward-fix tests.
- Accessibility and keyboard/screen-reader checks.
- Localization and RTL regression tests when RTL languages are introduced.
- Security tests and dependency scanning.
- Performance/load tests for launch-critical paths.
- Backup restoration and disaster recovery tests before launch.

Mocks may supplement but must not replace critical integration tests against real database constraints and provider sandboxes.

#### 31.11.2 Minimum acceptance evidence

Every phases completion report must contain:
1. Commit hash and branch.
2. Exact environment and runtime versions.
3. Commands executed.
4. Test counts: passed, failed, skipped.
5. Build/typecheck/lint results.
6. Database migration and integration results.
7. Browser/device viewport evidence.
8. Security scan results and unresolved findings.
9. Known limitations and `PENDING` decisions.
10. Reviewer/owner approval.

A green build alone is not phases acceptance.

#### 31.11.3 Booking and payment acceptance

Before the applicable pilot phase:
- Concurrent final-inventory test proves no overbooking.
- Duplicate requests and webhooks do not duplicate bookings or money movement.
- Every booking state transition is validated and audited.
- Payment success/unknown/failure cases reconcile correctly.
- Refund and payout accounting balances.
- Partner and customer cannot access another tenant's data.
- Admin override and manual financial adjustments are authorized and audited.
- A recovery drill demonstrates how stuck holds/payments are resolved.

---

### 31.11 DevOps, reliability and observability

#### 31.11.1 Environments and delivery

- Separate development, test/staging and production credentials and data.
- Never copy production personal data into development without an approved anonymization process.
- CI must run formatting/lint, typecheck, unit tests, integration tests, migration checks, security/dependency scans and production build.
- Production deployment requires reviewed changes and successful CI.
- Use backward-compatible expand/migrate/contract database changes where feasible.
- Define rollback and forward-fix procedures for both application and schema changes.
- Keep secrets out of repository, build artifacts, client bundles and logs.

#### 31.12.2 Observability

Implement structured logs, metrics and traces/correlation IDs. Monitor at minimum:
- Request error rate and latency.
- Database availability, connections and slow queries.
- Queue depth, job age and dead-letter count.
- Booking failures, stuck holds and overbooking attempts.
- Payment unknown/failure rate and reconciliation exceptions.
- Refund/payout backlog.
- Notification delivery failures.
- Authentication abuse and authorization denials.
- External provider latency/outages.
- SOS-related operational health only if/when SOS is activated.

#### 31.12.3 Reliability objectives

Before production launch, owner and engineering must approve service-level objectives for availability, latency, booking/payment processing and support. Define RPO, RTO, backup frequency, restore test frequency, incident severity and escalation. These targets are `PENDING`; do not invent or advertise uptime guarantees.

#### 31.12.4 Capacity and performance

Define workload assumptions for concurrent users, searches, booking attempts, webhook volume, partner dashboards and media uploads. Load tests must use realistic data distribution and identify bottlenecks. Do not claim scalability based only on architecture diagrams.

---

### 31.12 UI/UX and design delivery specification

All the approved design direction remains intact: warm, calm, trustworthy and authentic; terracotta/maroon, Himalayan blue and off-white; real partner photography; mobile-first at 375px; WCAG 2.2 AA; clear status and one primary action per screen.

v3 adds the following design deliverables without selecting a new brand direction:

1. Information architecture and navigation map.
2. User flows for traveler discovery, listing detail, booking, cancellation, My Trip, partner onboarding, partner booking management and admin readiness approval.
3. Low-fidelity wireframes for each flow.
4. High-fidelity responsive screens at 375px, 768px and 1280px.
5. Design tokens for color, typography, spacing, radius, elevation, borders and focus states.
6. Component inventory with states: default, hover, focus, disabled, loading, empty, error, success and permission denied.
7. Status components for Available, Coming Soon, Partner Registration Open, Testing and other approved statuses.
8. Form validation and error copy in English and Nepali.
9. Accessibility annotations and keyboard order.
10. Prototype demonstrating critical end-to-end flows.
11. Developer handoff with assets, tokens, component behaviour and responsive rules.
12. Visual regression and UI acceptance checklist.

No final logo, brand color hex values, screen design or Figma file is declared approved by this document. These remain design decisions to be presented for owner approval. Do not invent real partner photos or use stock photos where the platform requires real partner photography.

---

### 31.13 Phase gates — additional acceptance criteria

The authoritative phase sequence and its feature-specific exit gates are defined in Part II, Sections 36–55. The following controls apply across every phase:

- Requirements and acceptance criteria must be traceable to stable feature IDs.
- UI/UX, data, API, security, tests, operations and documentation must be included where relevant.
- Critical booking, payment, safety, privacy and authorization paths require failure-path evidence.
- External legal, provider, staffing and licensing approvals remain `PENDING` or `GATED` until written evidence exists.
- No phase is complete solely because code was generated or a build succeeds.
- The owner accepts each phase only after reviewing its completion report and evidence.

---

### 31.14 Required companion specifications

The master blueprint is the governing document. The following files should be created as implementation specifications, not as competing product blueprints:

| File | Required contents |
|---|---|
| `SYSTEM_ARCHITECTURE.md` | Components, module boundaries, deployment, dependencies, events and architecture decisions |
| `DATABASE_ARCHITECTURE.md` | ERD, data dictionary, constraints, indexes, tenancy, migrations and retention |
| `BOOKING_ENGINE.md` | Booking modes, state machines, gate, inventory, holds, concurrency, cancellation and edge cases |
| `PAYMENT_LEDGER.md` | Provider adapters, payment states, double-entry ledger, refunds, payouts and reconciliation |
| `API_SPECIFICATION.md` | OpenAPI, schemas, auth, errors, pagination, idempotency and rate limits |
| `SECURITY_ARCHITECTURE.md` | Threat model, roles, permissions, privacy, file security and incident response |
| `INTEGRATION_ARCHITECTURE.md` | Provider contracts, webhooks, retries, quotas, fallback and data provenance |
| `TESTING_STRATEGY.md` | Test layers, fixtures, concurrency, security, accessibility and acceptance evidence |
| `DEVOPS_AND_SRE.md` | CI/CD, environments, observability, SLO, RPO/RTO, backup and recovery |
| `UI_UX_SPECIFICATION.md` | IA, user flows, wireframes, design system, responsive screens and handoff |
| `Phases_ACCEPTANCE.md` | 18-phase gates, commands, evidence templates and sign-off rules |
| `DECISIONS.md` | Owner decisions, open questions, conflicts, evidence, approver and dates |

Each companion file must link back to the relevant section and must not contradict it. When a detailed file needs a new owner decision, record it as `PENDING` in `DECISIONS.md` and keep implementation gated.

---

### 31.15 Contradiction and clarification register

The following product and technical ambiguities require explicit resolution:

| ID | Blueprint sections / issue | Required action | Current status |
|---|---|---|---|
| C-01 | Category catalogue vs feature matrix: nearby-services and SIM information show different launch states/timing | Owner/product review; align source of truth while preserving intended functionality | `PENDING` |
| C-02 | Support category is Coming Soon while support tickets/disputes appear earlier in the feature matrix and booking launch needs operational support | Define minimum support capability required before any live booking; do not claim 24/7 | `PENDING` |
| C-03 | Reviews are described as a non-transactional category but also as verified-stay reviews after the applicable booking readiness gate | Separate free review feature from booking-linked eligibility and moderation rules | `PENDING` |
| C-04 | Repository verification claims may be confused with blueprint requirements | Treat every implementation claim as unverified until repository evidence is attached | `PENDING` |
| C-05 | Web and native mobile delivery scope may be confused | Follow Phase 16 for native mobile apps; web launch hardening is Phase 17 | `PENDING` |
| C-06 | Payment hold/release wording may imply escrow or custody | Legal/provider review must define lawful funds flow and customer-facing wording | `PENDING` |
| C-07 | Phase ownership and dependencies may change as external approvals are received | Record any approved change in the decision and feature registers; preserve one authoritative phase plan | `PENDING` |
| C-08 | Database baseline says PostgreSQL 13+ without pinned supported version | Pin version based on hosting support and tested migrations | `PENDING` |
| C-09 | Booking Approval mode response deadline and inventory hold policy are unspecified | Owner/product decision per category before Phase 07 | `PENDING` |
| C-10 | SOS is P0 safety priority but operationally gated to Phase 13 | Keep visible only with truthful Coming Soon/approved information; do not activate until all gates pass | `GATED` |

---

### 31.16 Open decisions — owner decisions

The following owner decisions remain open unless the owner has separately answered them in writing. This blueprint does not choose:
- Phase ownership, dependencies and scope-change approval.
- Pilot region.
- First booking category.
- Commission rate/base.
- Company type/registration.
- Team model/budget.
- Weekly development hours.
- First payment gateway applications.
- Database hosting provider.
- Support hours/languages.
- Final tagline/brand mood selection.
- Whether companion matching will be pursued.
- SOS activation timing and staffing.
- NestJS versus continued Next.js route handlers.

Additional technical decisions that remain `PENDING` include:
- Supported Node.js and PostgreSQL versions.
- Hosting, storage, queue and monitoring providers.
- Authentication provider and MFA implementation.
- Exact booking and payment state names/transitions.
- Inventory model per service category.
- Lawful payment capture/settlement model.
- Currency and rounding policy.
- Data retention and cross-border data handling.
- SLO, RPO and RTO targets.
- API error envelope and pagination contract.

---

### 31.17 Implementation instruction for AI coding agents

Any AI agent working on PheriNepal must follow these rules:

1. Read this entire master blueprint and the relevant companion specification before editing code.
2. Treat all product requirements in this master blueprint as binding; do not delete or weaken them.
3. Do not invent owner decisions, legal approvals, licences, provider agreements, production credentials, partner data or test results.
4. Keep `PENDING` and `GATED` items visibly unresolved.
5. Before coding, identify the exact phases scope and acceptance criteria.
6. Inspect the existing repository and current tests before proposing changes.
7. Reproduce defects before fixing them; cite exact file paths, symbols, commands and test evidence.
8. Do not claim a test passed unless it was actually executed and its output is available.
9. Implement the smallest safe change that satisfies the approved requirement; avoid unrelated refactors.
10. Add tests for new behaviour, including negative, authorization, concurrency and failure paths where relevant.
11. Never bypass database constraints, booking gates, approval separation, audit logging or financial invariants for convenience.
12. Never put secrets or personal data in source code, logs, screenshots or reports.
13. Report changed files, migrations, commands, results, unresolved risks and decisions needed.
14. Stop at the phases boundary and request owner approval before moving to the next phases.
15. If the blueprint is ambiguous or contradictory, add a proposed resolution to `DECISIONS.md`; do not silently choose.

#### Required completion report format

- Phases and scope:
- Source requirements:
- Repository commit/branch:
- Files changed:
- Database migrations:
- Tests executed (exact commands):
- Test results (passed/failed/skipped):
- Security and authorization checks:
- Browser/device checks:
- Known limitations:
- `PENDING` / `GATED` items:
- Evidence references:
- Owner decision or approval required:

---

## 32. Additional technical gaps and mandatory design decisions

The following areas require explicit design before the relevant phases is implemented. They are added as requirements for specification and testing; they do not authorize unapproved business or legal decisions.

### 32.1 Pricing, quotes and currency integrity

- Define a canonical price breakdown: base price, quantity, duration, taxes, platform fee, partner fee, gateway fee, discount, reward redemption and final payable amount.
- Store money as integer minor units or approved fixed-precision decimal values; never use binary floating point.
- Store currency explicitly on every amount. Never add, compare or net amounts across currencies without an approved exchange-rate record and conversion policy.
- A quote must have an expiry and an immutable snapshot of price components, currency, applicable taxes/fees, cancellation terms and policy version.
- Recalculate and validate the quote on the server before payment. The browser must never be the source of truth for price.
- Define FX rate source, timestamp, spread, rounding, settlement currency and refund conversion policy. These are `PENDING` owner/accountant/provider decisions.
- Test price changes between search, checkout, payment authorization and booking confirmation.

### 32.2 Inventory models by service category

A single generic inventory table may not safely represent all 31 categories. Define and approve inventory models for each transactional category, such as:
- Unit/night inventory for hotels and homestays.
- Person/seat capacity for guides, transport and group activities.
- Vehicle/time-slot capacity for transport.
- Departure/permit/capacity inventory for trekking and climbing.
- Quantity/variant stock for shopping.
- Table/time-slot capacity for restaurants and local experiences.
- Provider-issued stock/activation limits for eSIM products.

For each model, specify availability source, timezone, cutoff, blackout dates, minimum/maximum quantity, overbooking policy (default: prevent), hold expiry and reconciliation with partner/provider systems. Do not expose a category as bookable until its inventory model is implemented and tested.

### 32.3 Time, timezone and date correctness

- Store event timestamps in UTC and preserve the relevant IANA timezone for the destination, property or service.
- Define whether booking dates are destination-local dates or UTC instants; accommodation check-in/check-out and timed activities require different semantics.
- Validate daylight-saving transitions for international users and timezone boundaries.
- Store the timezone and local-time interpretation used when the booking was created.
- Use server-generated timestamps for financial and state transitions.
- Test midnight boundaries, leap days, timezone changes and daylight-saving gaps/overlaps where applicable.

### 32.4 Partner onboarding, verification and suspension

- Define a partner lifecycle: application, identity/business verification, licence checks, document review, approval, active, suspended, expired and rejected.
- Track each verification item independently with issuer/source, reference, expiry, reviewer, decision, evidence and next review date.
- Expired or revoked licences must trigger a defined listing/booking restriction.
- Suspension must block new bookings immediately and define treatment of existing bookings, customer notifications, refunds and partner payouts.
- Re-verification and appeal processes require an audit trail.
- The exact legal documents and verification criteria remain `PENDING` legal and category-specific review.

### 32.5 Fraud, abuse and risk controls

Before payments and marketplace operations go live, define controls for:
- Account takeover and suspicious login patterns.
- Fake partner listings and document fraud.
- Promo/reward abuse and referral manipulation.
- Payment card testing, repeated failed payments and refund abuse.
- Fake bookings, review manipulation and collusion.
- Account/device/IP velocity limits with privacy safeguards.
- Manual review queues, reason codes, evidence retention and appeal process.
- False-positive handling and staff access restrictions.

Do not automatically reject or penalize users solely on an opaque risk score. High-impact actions need explainable rules and human review.

### 32.6 Content moderation and user-generated content

For reviews, memories, photos, groups, lost-and-found and companion features, define:
- Content types and allowed formats.
- Upload size/type limits and malware scanning.
- Moderation states, report reasons and reviewer permissions.
- Prohibited content and escalation rules.
- Takedown, appeal and repeat-offender process.
- Copyright/consent requirements for images and personal information.
- Retention and evidence policy for reported content.
- Abuse prevention for messaging and group interactions.

These features must remain gated until moderation staffing and operational procedures exist.

### 32.7 Feature flags and operational configuration

- Separate feature availability from category/location booking readiness.
- Use server-side feature flags for controlled rollout, pilot cohorts and emergency disable.
- Record who changed a flag, when, why, previous value and new value.
- Restrict production configuration changes by role and require dual approval for high-risk flags such as booking, payment, payout and SOS.
- Avoid storing secrets or provider credentials in ordinary feature-flag values.
- Define cache invalidation and propagation time for emergency disable controls.
- Provide a tested global kill switch for new booking attempts without corrupting existing bookings or payment reconciliation.

### 32.8 Data governance and privacy engineering

Create a data inventory before implementation that records:
- Data element, purpose, source, owner and lawful basis/consent where applicable.
- Sensitivity class and systems where it is stored or transmitted.
- Access roles, encryption requirements and audit requirements.
- Retention trigger and deletion/anonymization method.
- Third-party recipients, hosting region and cross-border transfer.
- User access/correction/deletion request workflow and response owner.

Use data minimization, encryption in transit and at rest where supported, key rotation, restricted exports and audited privileged access. Exact legal bases, retention periods and transfer requirements remain subject to qualified Nepal and relevant jurisdiction legal review.

### 32.9 Disaster recovery and business continuity

- Define recovery objectives (RPO/RTO) with the owner before launch.
- Document database backup, point-in-time recovery, object-storage recovery and key/secret recovery.
- Keep backup credentials separate from production application credentials.
- Encrypt backups and restrict restore permissions.
- Test restoration into an isolated environment at a defined frequency.
- Document provider outage, database corruption, accidental deletion, credential compromise and regional outage runbooks.
- Maintain manual operational fallback for active bookings and customer support.
- A backup is not considered valid until a restore test succeeds.

### 32.10 Analytics, reporting and financial correctness

- Separate operational analytics, product analytics and financial/accounting reports.
- Define event names, properties, ownership, consent rules and schema versioning.
- Do not send passport, identity, payment credential or unnecessary personal data to analytics providers.
- Financial reports must reconcile to the ledger; analytics aggregates are not the accounting source of truth.
- Define metric formulas and cohort/timezone rules before comparing conversion, cancellation, partner performance or revenue.
- Track data freshness and missing events; document backfill behaviour.
- Avoid presenting estimates as audited financial totals.

### 32.11 External integration contracts and provider failure

For each external provider, document:
- Service owner and business purpose.
- Contract, licence, data-processing terms and permitted usage.
- Sandbox/production credentials and rotation process.
- API limits, timeout, retry, circuit-breaker and fallback.
- Webhook signing, replay protection and event ordering.
- Data format/version compatibility and deprecation notice.
- Provider outage detection and customer-facing status.
- Exit strategy and data export/migration plan.

Do not make a third-party provider a hidden single point of failure for critical booking, payment or safety workflows.

### 32.12 Accessibility, localization and low-connectivity acceptance

- Test keyboard-only navigation, visible focus, semantic headings, labels, error announcements and contrast.
- Test screen-reader flows for search, booking, payment result, cancellation and partner dashboards.
- Avoid communicating status by colour alone.
- Test Nepali Devanagari shaping, line wrapping, numerals, date/currency formatting and mixed-language content.
- Keep translation keys stable and detect missing/untranslated strings in CI.
- Define offline behaviour explicitly: cached public content may be shown with a freshness timestamp; booking, payment and SOS actions must not falsely appear successful while offline.
- Test slow network, interrupted requests, retry and duplicate submission behaviour.

### 32.13 API and schema lifecycle

- Define compatibility rules for `/api/v1`, additive changes, breaking changes and deprecation.
- Version event schemas independently where asynchronous consumers require it.
- Validate API request/response schemas in CI against the OpenAPI contract.
- Define database migration ownership, migration lock strategy and long-running migration procedures.
- Use expand-and-contract migrations for changes that span multiple deployments.
- Define rollback versus forward-fix criteria; never assume a destructive migration can be rolled back after writes.
- Maintain a data migration verification report for every production migration.

### 32.15 Service-specific functional contracts for all 31 categories

The catalogue names all 31 service categories, but a category name and a roadmap phases are not sufficient implementation specifications. Before a category enters development, create a category contract containing:

- User problem, target users and explicit in-scope/out-of-scope features.
- Whether it is informational, transactional, community, safety-critical or a combination.
- Public visibility and exact status behaviour.
- Required user inputs, eligibility checks and consent.
- Listing/provider data model and ownership.
- Search filters, ranking and location behaviour.
- Inventory/capacity model, if transactional.
- Price/quote model, taxes/fees and currency behaviour, if money is involved.
- Booking/order/request lifecycle and allowed state transitions.
- Fulfilment evidence and definition of service completion.
- Cancellation, refund, dispute and no-show rules.
- Partner verification, licences, insurance and expiry rules.
- Safety risks, escalation path and operational staffing.
- Notifications, support workflow and service-level expectations.
- Personal data collected, retention and access permissions.
- External providers, licences, API dependencies and failure behaviour.
- Analytics events, acceptance criteria and test cases.
- Launch gate, owner and evidence required to activate the category.

A shared platform engine may be reused, but category-specific rules must not be forced into a generic workflow where the business process differs. Do not mark a category Available until its category contract, implementation, operational owner and acceptance evidence are approved.

### 32.16 Catalogue status lifecycle and emergency controls

Define a canonical status dictionary and permitted transitions for every catalogue status used by the product, including `Available`, `Coming Soon`, `Testing`, `Partner Registration Open` and any other status present in the feature matrix.

For each status, document:
- Whether the category/location is visible in public search.
- Whether prices, inventory and partner details may be displayed.
- Whether a user may submit a notify request, enquiry, application, order or booking.
- Whether payment is permitted.
- Which role may set or approve the status.
- Required reason, evidence and effective date.
- Whether two-person approval is mandatory.
- Customer and partner notification requirements.
- How existing bookings are handled when a status is downgraded or suspended.

A status label must map to deterministic server-side permissions; UI wording alone is not a control. Emergency disable must stop new transactions promptly while preserving existing booking, refund, ledger and audit workflows.

### 32.14 Operational ownership and support readiness

Before each live category, name the operational owner for:
- Partner verification and expiry follow-up.
- Booking exceptions and partner non-response.
- Payment reconciliation and refund queue.
- Customer complaints and disputes.
- Safety incidents (only for activated safety services).
- Content moderation and abuse reports.
- Provider outage and technical incident response.

Specify support hours, supported languages, escalation paths, response targets and out-of-hours wording. Do not publish support or rescue availability that is not staffed and tested.

---

## 33. Technical readiness checklist by launch-critical domain

| Domain | Must be specified | Must be tested | Launch blocked if |
|---|---|---|---|
| Identity and access | Roles, permissions, recovery, MFA | Cross-tenant and privilege tests | Unauthorized access is possible |
| Partner verification | Evidence, expiry, suspension | Expired/revoked licence cases | Unverified partner can transact |
| Catalogue/readiness | Status lifecycle, category contracts, approval separation | Status transitions, emergency disable and approval audit | Gated service can be booked |
| Inventory | Category-specific model, timezone, capacity | Concurrent last-unit test for each inventory type | Overbooking can occur |
| Booking | Category contract, state transitions, timeout, cancellation | Duplicate, timeout and recovery tests for each booking mode | Invalid transition can confirm booking |
| Pricing | Quote snapshot, currency, fees | Price tampering and stale quote tests | Client can alter payable amount |
| Payments | Provider contract, webhook, ledger | Duplicate/out-of-order webhook and reconciliation | Money can be duplicated or lost without detection |
| Refunds/payouts | Eligibility, approvals, accounting | Partial/full refund and failed payout | Ledger does not balance |
| Notifications | Consent, templates, retries | Duplicate and failed delivery | Critical booking status is silently lost |
| Privacy/security | Data map, retention, access | Access, export, deletion and leakage tests | Sensitive data is exposed |
| Safety/SOS | Staffing, official sources, incident runbook | Tabletop and operational drill | Unsupported rescue promise is made |
| AI | Grounded sources, evaluation, escalation | Hallucination, prompt-injection and privacy tests | AI can invent critical safety facts or act without authorization |
| Reliability | SLO, RPO/RTO, runbooks | Restore and incident drills | Recovery has not been demonstrated |
| UX/accessibility | Responsive flows, language, WCAG checks | Keyboard, screen-reader, slow-network tests | Critical flow is inaccessible or misleading |

---

## 34. Governance, ownership and change management

- The founder/owner is the final authority for product scope, commercial policy, launch decisions and unresolved business choices.
- Engineering owns technical design proposals, implementation quality, test evidence and operational documentation.
- Legal, accounting, payment and safety professionals must validate matters within their expertise; AI-generated text is not professional approval.
- Every material decision must be recorded in `DECISIONS.md` with ID, date, question, options, decision, rationale, approver, evidence and affected sections.
- Every requirement must have a stable ID and map to implementation tasks and acceptance tests before its phases begins.
- Every release must include a change summary, migration notes, known risks and rollback/forward-fix plan.
- No team member or AI agent may mark a phases complete without the evidence required in the acceptance section.
- Emergency changes must be logged and reviewed after the incident; emergency controls must not bypass ledger integrity or audit history.

## 35. Final AI implementation contract

Any AI coding agent working on PheriNepal must:

1. Read the complete master blueprint and the relevant detailed specification before editing.
2. Treat all `FINAL` requirements as binding.
3. Keep `PENDING` and `GATED` items unresolved until evidence and approval exist.
4. Inspect the repository, runtime versions, migrations and tests before making claims.
5. Reproduce a reported defect before changing code whenever practical.
6. Identify exact files, symbols, commands and test evidence for every finding.
7. Make the smallest safe change that satisfies the approved scope.
8. Add positive, negative, authorization, concurrency and failure-path tests as appropriate.
9. Never bypass booking gates, approval separation, database constraints, audit logging or financial invariants.
10. Never invent partner records, legal approvals, provider credentials, test results or production readiness.
11. Stop at the phases boundary and request owner approval before proceeding.
12. Report changed files, migrations, commands, results, unresolved risks and decisions required.

### Required AI completion report

- Phases and approved scope:
- Requirement IDs addressed:
- Repository branch and commit:
- Files changed:
- Database migrations:
- Exact commands executed:
- Tests passed / failed / skipped:
- Build, typecheck and lint:
- Authorization and security evidence:
- Browser/device and accessibility evidence:
- Performance and recovery evidence, where applicable:
- Known limitations:
- `PENDING` / `GATED` items:
- Risks and owner decisions required:
- Evidence references:
- Phases recommendation: `PASS`, `FAIL` or `BLOCKED` (with reasons)


---

# PART II — AUTHORITATIVE PHASE-BY-PHASE PRODUCT AND ENGINEERING PLAN

## 36. Delivery model and non-negotiable rules

This project is developed phase by phase. The phase sequence below is the single source of truth. A phase may contain multiple internal tasks, all tracked under that phase.

### 36.1 What “feature count” means

For scope control, this blueprint counts **feature modules**, not buttons, fields, pages, API endpoints, or database tables. A feature module is a user-visible or operational capability with its own requirements, UI states, backend rules, data ownership, security controls, tests, and acceptance criteria. Sub-functions are listed under the module and do not inflate the count.

The phase register below contains **240 feature modules** across 18 phases. This is a planning inventory, not a claim that all 240 are already built. The 31 service categories are a separate catalogue count and are not added to the 240 module count. If implementation discovers a genuinely new capability, record it in the change register, assign exactly one owning phase, update the total, and document dependencies before coding.

### 36.2 Global implementation rules

1. Preserve the complete product vision, all 31 categories, all eight dashboards, and all approved technical rules in this document.
2. Build premium UI/UX and the design system from the beginning. Do not postpone design until after backend development.
3. For each feature, complete discovery, requirements, UX flow, screen states, data model, API contract, implementation, automated tests, security review, accessibility review, and documentation.
4. Implement one phase at a time. Do not begin the next phase until the current phase passes its exit gate and the owner accepts the evidence.
5. A phase may be marked **Blocked** where an external legal, licensing, payment, safety, provider, staffing, or data-source dependency is unresolved. Do not fake completion to bypass a gate.
6. Do not build fake data into production. Seed data must be explicitly labelled as demo/test data and isolated from production.
7. Do not invent prices, availability, ratings, reviews, partner verification, live status, official contacts, safety coverage, or provider integrations.
8. No feature is complete merely because its page renders. It must work end to end, including failure paths.
9. All user-facing functions must work on supported mobile, tablet, and desktop breakpoints, and support English and Nepali at minimum.
10. The web app is the first client. Keep domain logic and API contracts reusable for future Android/iOS apps.
11. Google AI must not silently change the approved stack, database schema, security policy, feature scope, or business rules. Propose a written decision first.
12. AI-generated code, content, translations, tests, and database migrations are untrusted until validated.
13. Human approval is mandatory for legal interpretations, payment/payout activation, partner approval policy, safety operations, emergency activation, and public launch.
14. Keep a `DECISIONS.md`, `FEATURE_REGISTER.md`, `PHASE_STATUS.md`, `RISK_REGISTER.md`, `DATA_SOURCES.md`, and `CHANGELOG.md` current.
15. All phase completion claims must cite repository paths, test commands, test output, screenshots where relevant, and known limitations.

### 36.3 Definition of Done for every feature module

A feature module is complete only when all applicable checks pass:

- Product requirement and acceptance criteria are written.
- Traveler, partner, admin, and support journeys are mapped where relevant.
- Desktop and mobile UI designs exist and match implementation.
- Loading, empty, error, success, disabled, offline, permission-denied, and retry states are designed where applicable.
- Database schema, ownership, retention, indexes, constraints, and migrations are documented.
- API request/response schemas, auth requirements, validation, error codes, idempotency, and rate limits are documented.
- Server-side authorization and tenant isolation are tested.
- Unit, integration, end-to-end, accessibility, localization, and regression tests are added as appropriate.
- Logs, metrics, alerts, audit records, and operational runbooks exist for critical paths.
- No secrets, personal data, payment data, or sensitive documents leak into logs.
- Documentation and support guidance are updated.
- Human approval is recorded for any external or high-risk dependency.

---

## 37. Master scope and feature accounting

### 37.1 Product scope totals

| Scope item | Count | Counting rule |
|---|---:|---|
| Service catalogue categories | 31 | The 31 catalogue entries in Section 6 |
| Feature modules in the phase register | 240 | Unique modules listed in Sections 38–55 |
| Primary user/operations dashboards | 8 | Section 10.1 |
| Core travel lifecycle stages | 3 | Before, During, After |
| Core languages at initial release | 2 | English and Nepali |
| Core responsive targets | 3 | Mobile, tablet, desktop |
| Delivery phases | 18 | Phase 00 through Phase 17 |
| Quality and release gates | 1 per phase | Each phase has its own evidence-based exit gate |

The feature-module count is a controlled baseline. Do not claim the project contains only 240 total code features: each module contains many sub-functions, screens, API routes, jobs, validations, and tests.

### 37.2 Phase summary and feature counts

| Phase | Name | Feature modules |
|---|---|---:|
| 00 | Product discovery, governance and technical foundation | 12 |
| 01 | Premium brand, UI/UX and design system | 16 |
| 02 | Platform foundation, database and developer experience | 14 |
| 03 | Identity, accounts, roles and consent | 12 |
| 04 | Catalogue, destination content and information intelligence | 16 |
| 05 | Search, maps, discovery and trip planning | 16 |
| 06 | Partner onboarding, verification and supply management | 14 |
| 07 | Stay inventory and booking engine | 16 |
| 08 | Payments, ledger, refunds and financial operations | 14 |
| 09 | Adventure, trekking, guides and transport | 16 |
| 10 | Restaurants, local experiences, shopping and luggage | 14 |
| 11 | During-trip tools, connectivity, offline and translation | 14 |
| 12 | AI travel intelligence and personalization | 12 |
| 13 | Safety, emergency, incidents and traveler support | 14 |
| 14 | After-trip, reviews, memories, passport and rewards | 12 |
| 15 | Group travel, community, companion and advanced features | 12 |
| 16 | Mobile apps, integrations, analytics and expansion | 10 |
| 17 | Production hardening, launch and continuous operations | 6 |
| **Total** | **18 phases** | **240** |

### 37.3 Dependency rules

- Phase 00 and Phase 01 start first and overlap only where product discovery informs design.
- Phase 02 establishes the architecture and platform required by all later phases.
- Phase 03 is required before personal data, saved trips, partner portals, bookings, and payments are exposed.
- Phase 04 creates authoritative category and destination data; Phase 05 consumes it.
- Phase 06 creates verified supply; transactional features remain gated until partner readiness is approved.
- Phase 07 must pass booking concurrency and cancellation tests before Phase 08 activates real money.
- Phase 08 requires written payment provider, legal, tax, refund, and payout decisions.
- Phases 09–10 activate each category independently only after category-specific compliance and operational approval.
- Phase 11 uses licensed providers and verified data. Offline maps require explicit licensing.
- Phase 12 must use grounded, evaluated AI. AI must not independently confirm bookings, approve partners, transfer money, or dispatch emergency services.
- Phase 13 SOS is disabled for public use until staffed response operations, verified contacts, escalation and drills are approved.
- Phases 14–16 require moderation, privacy and data-retention policies.
- Phase 17 is not a substitute for earlier quality work; security, accessibility, tests, monitoring and documentation are continuous.

---

## 38. Phase 00 — Product discovery, governance and technical foundation

**Feature modules: 12**

1. **PH00-F001** — Product vision, positioning and measurable outcomes.
2. **PH00-F002** — Traveler and partner persona validation.
3. **PH00-F003** — Full before/during/after journey maps.
4. **PH00-F004** — 31-category service taxonomy and category ownership.
5. **PH00-F005** — Product requirement and acceptance-criteria template.
6. **PH00-F006** — Feature register with unique IDs and phase ownership.
7. **PH00-F007** — Decision log and unresolved-decision workflow.
8. **PH00-F008** — Risk, dependency and assumption register.
9. **PH00-F009** — Content source and verification policy.
10. **PH00-F010** — Legal, licensing, insurance and tax question register.
11. **PH00-F011** — Pilot-region and pilot-category selection framework.
12. **PH00-F012** — Google AI coding-agent operating contract and evidence-report format.

**Work performed:** Interview representative domestic travelers, international travelers, diaspora travelers, homestays, hotels, guides, transport operators, restaurants, local experience providers, and support staff. Validate actual workflows instead of assuming them. Identify what PheriNepal can operate directly versus what must be supplied by partners.

**Deliverables:** Product requirements baseline, persona set, journey maps, 31-category matrix, feature register, risk register, decision log, data-source register, legal questions for qualified Nepal counsel, and implementation rules.

**Exit gate:** Owner approves the product scope, phase map, feature register, pilot assumptions, and unresolved decisions. No market claim is published without a dated reliable source.

---

## 39. Phase 01 — Premium brand, UI/UX and design system

**Feature modules: 16**

1. **PH01-F001** — Brand strategy, positioning and brand voice.
2. **PH01-F002** — Logo system and brand asset rules.
3. **PH01-F003** — Color system with semantic tokens and contrast rules.
4. **PH01-F004** — Typography system with Nepali and Latin font testing.
5. **PH01-F005** — Spacing, grid, sizing, elevation and border-radius tokens.
6. **PH01-F006** — Iconography and illustration direction.
7. **PH01-F007** — Photography and media art direction.
8. **PH01-F008** — Reusable component library.
9. **PH01-F009** — Navigation, header, footer and responsive menu.
10. **PH01-F010** — Responsive layout system for mobile, tablet and desktop.
11. **PH01-F011** — Light and dark themes with accessible contrast.
12. **PH01-F012** — Form, validation, feedback and notification patterns.
13. **PH01-F013** — Data table, filter, search, card and map patterns.
14. **PH01-F014** — Design tokens and developer handoff.
15. **PH01-F015** — Interaction, motion and micro-interaction guidelines.
16. **PH01-F016** — Accessibility-first design patterns and WCAG 2.2 AA target.

**Required screens and templates:** Homepage; category directory; category detail; destination listing; destination detail; search results; listing detail; sign-up/login; user profile; trip overview; booking flow; payment flow; customer dashboard; partner dashboard; guide dashboard; transport dashboard; adventure dashboard; seller dashboard; restaurant/local partner dashboard; admin dashboard; support center; notifications; settings; privacy/consent; error/empty/loading pages.

**Before/During/After design:** Create separate user journey maps and responsive screen flows for all three travel stages. Each category must show what is available before booking, during service delivery, and after completion. Do not imply every category has all three transactional states; information-only categories have appropriate information and feedback journeys.

**Design acceptance:** Figma or equivalent source file, component inventory, design tokens, interaction prototype, mobile-first screenshots, accessibility annotations, and approved design-to-code handoff. A homepage alone is not a completed design phase.

---

## 40. Phase 02 — Platform foundation, database and developer experience

**Feature modules: 14**

1. **PH02-F001** — Repository structure and package boundaries.
2. **PH02-F002** — Environment configuration and validation.
3. **PH02-F003** — Local development and reproducible setup.
4. **PH02-F004** — PostgreSQL schema and migration framework.
5. **PH02-F005** — Database constraints, indexes and transaction policy.
6. **PH02-F006** — Domain layer and service boundaries.
7. **PH02-F007** — API framework and versioning baseline.
8. **PH02-F008** — Typed validation and shared schemas.
9. **PH02-F009** — Error model and correlation IDs.
10. **PH02-F010** — Logging, metrics and tracing baseline.
11. **PH02-F011** — File and object storage abstraction.
12. **PH02-F012** — Background job and event-processing foundation.
13. **PH02-F013** — CI pipeline, code quality and dependency scanning.
14. **PH02-F014** — Seed data, fixtures and test infrastructure.

**Technical baseline:** TypeScript strict mode; supported stable Node LTS pinned in project files; PostgreSQL supported version pinned; migrations committed and reviewed; API-first domain boundaries; providers behind adapters. Use a modular monolith until measured needs justify separate services. Do not introduce microservices or Redis without a documented requirement.

**Exit gate:** Clean checkout can install, migrate, seed test data, run tests, typecheck, lint and build reproducibly. Backup and restore procedure is documented and tested in a non-production environment.

---

## 41. Phase 03 — Identity, accounts, roles and consent

**Feature modules: 12**

1. **PH03-F001** — Traveler registration and account creation.
2. **PH03-F002** — Email/phone verification and OTP lifecycle.
3. **PH03-F003** — Secure login, logout and session management.
4. **PH03-F004** — Password management and secure recovery.
5. **PH03-F005** — MFA for privileged accounts.
6. **PH03-F006** — Role-based access control.
7. **PH03-F007** — Organization and partner membership.
8. **PH03-F008** — Tenant and record-level isolation.
9. **PH03-F009** — Profile and traveler preferences.
10. **PH03-F010** — Consent, privacy preferences and notification preferences.
11. **PH03-F011** — Account export, correction, deletion and retention workflow.
12. **PH03-F012** — Session/device management and suspicious-login controls.

**Roles:** Traveler, partner owner, partner staff, guide, transport operator, adventure operator, seller, restaurant/local provider, support agent, content editor, verifier, finance operator, safety operator, admin, and owner. Define permission matrices and least privilege; do not rely on frontend hiding.

**Exit gate:** Negative authorization tests prove users cannot read or mutate another user's, partner's, or tenant's records. Account recovery, OTP abuse controls, MFA, consent records and data lifecycle tests pass.

---

## 42. Phase 04 — Catalogue, destination content and information intelligence

**Feature modules: 16**

1. **PH04-F001** — 31-category catalogue and category metadata.
2. **PH04-F002** — Category/location availability status.
3. **PH04-F003** — Service status history and audit trail.
4. **PH04-F004** — Category-specific information templates.
5. **PH04-F005** — Destination profiles and editorial pages.
6. **PH04-F006** — Province, district, municipality and locality taxonomy.
7. **PH04-F007** — Attraction and point-of-interest records.
8. **PH04-F008** — Destination history, culture and local etiquette.
9. **PH04-F009** — Best-season and climate information.
10. **PH04-F010** — Permit, visa and entry information library.
11. **PH04-F011** — Official contact and public-service directory.
12. **PH04-F012** — Source registry, citations and verification workflow.
13. **PH04-F013** — Content freshness, expiry and review scheduling.
14. **PH04-F014** — English/Nepali editorial workflow.
15. **PH04-F015** — Image/video/media rights and moderation.
16. **PH04-F016** — SEO metadata, canonical URLs and structured data.

**Content quality:** Each factual record stores source, source type, checked date, expiry/review date, geography, confidence, editor, and verification status. Clearly distinguish official facts, partner-supplied facts, editorial guidance, estimates and user-generated content. Do not state permit rules, visa rules, opening hours, emergency numbers or access conditions as facts without a source and checked date.

**Exit gate:** All 31 categories have honest status and category-specific landing structure. Initial destination pages pass factual, editorial, localization, image-rights and SEO review.

---

## 43. Phase 05 — Search, maps, discovery and trip planning

**Feature modules: 16**

1. **PH05-F001** — Global search across categories and destinations.
2. **PH05-F002** — Search suggestions and typo tolerance.
3. **PH05-F003** — Filter and sort framework.
4. **PH05-F004** — Map-based discovery.
5. **PH05-F005** — Distance and geospatial search.
6. **PH05-F006** — Nearby services discovery.
7. **PH05-F007** — Destination comparison.
8. **PH05-F008** — Attraction and activity discovery.
9. **PH05-F009** — Date, guest and requirement-aware search.
10. **PH05-F010** — Saved places and wishlists.
11. **PH05-F011** — Trip itinerary builder.
12. **PH05-F012** — Day-by-day schedule and timeline.
13. **PH05-F013** — Travel time, distance and route planning.
14. **PH05-F014** — Budget calculator and cost breakdown.
15. **PH05-F015** — Packing and preparation checklists.
16. **PH05-F016** — Permit/document planning checklist.

**Trip-planning requirements:** Support multi-destination, multi-day, multi-service plans; editable sequence; travel buffers; opening-time constraints where verified; cost estimates with currency/date/source; group collaboration may be delivered in Phase 15. Distinguish estimates from confirmed bookings. Do not promise live route or traffic data unless a provider supplies it.

**Exit gate:** Search relevance, geospatial correctness, date/time handling, mobile usability, keyboard accessibility, empty results, unavailable provider and stale-data states are tested.

---

## 44. Phase 06 — Partner onboarding, verification and supply management

**Feature modules: 14**

1. **PH06-F001** — Partner application and business profile.
2. **PH06-F002** — Business identity and registration evidence collection.
3. **PH06-F003** — Licence, permit and insurance evidence collection.
4. **PH06-F004** — Document review and verification queue.
5. **PH06-F005** — Two-person approval and separation of duties.
6. **PH06-F006** — Partner readiness checklist by category.
7. **PH06-F007** — Partner agreement and terms acceptance.
8. **PH06-F008** — Listing creation and editing.
9. **PH06-F009** — Listing photos, media and ownership declarations.
10. **PH06-F010** — Staff/member invitations and role assignment.
11. **PH06-F011** — Partner availability and operating schedule.
12. **PH06-F012** — Partner suspension, restriction and reinstatement.
13. **PH06-F013** — Partner performance and compliance history.
14. **PH06-F014** — Partner onboarding assistance and audit history.

**Verification rules:** Store who checked each document, source, date, expiry, result, reviewer and next action. Sensitive documents must be private, access-controlled and malware-scanned. Verification is not a badge unless all required checks are complete and current.

**Exit gate:** A partner can apply, submit evidence, be reviewed by authorized people, receive a decision, publish only after readiness approval, and be suspended with all changes audited.

---

## 45. Phase 07 — Stay inventory and booking engine

**Feature modules: 16**

1. **PH07-F001** — Property and accommodation listing model.
2. **PH07-F002** — Room/unit and occupancy model.
3. **PH07-F003** — Rate plans, taxes, fees and price breakdown.
4. **PH07-F004** — Availability calendar and inventory rules.
5. **PH07-F005** — Minimum/maximum stay and booking windows.
6. **PH07-F006** — Search-to-listing availability validation.
7. **PH07-F007** — Temporary inventory holds with expiry.
8. **PH07-F008** — Instant Booking workflow.
9. **PH07-F009** — Approval Booking workflow.
10. **PH07-F010** — Booking state machine and transition policy.
11. **PH07-F011** — Booking confirmation and traveler notifications.
12. **PH07-F012** — Check-in/check-out and service completion.
13. **PH07-F013** — Booking modification and rescheduling.
14. **PH07-F014** — Cancellation, no-show and partial fulfilment.
15. **PH07-F015** — Multi-service Trip ID with independent booking records.
16. **PH07-F016** — Booking history, vouchers and receipts.

**Critical engine rules:** Availability is rechecked on the server at the moment of booking. Database transactions, unique constraints, row locking or appropriate serializable logic prevent double booking. Holds expire automatically and release inventory. Payment and booking state are separate. A payment success callback alone never confirms a booking. Approval requests have explicit response deadlines and expiry policy.

**Exit gate:** Automated concurrency tests simulate competing customers for the last unit; no overbooking occurs. State transition, cancellation, expiry, retry, duplicate request, provider timeout and partial failure tests pass.

---

## 46. Phase 08 — Payments, ledger, refunds and financial operations

**Feature modules: 14**

1. **PH08-F001** — Payment provider adapter framework.
2. **PH08-F002** — Payment intent and checkout session.
3. **PH08-F003** — Payment status state machine.
4. **PH08-F004** — Signed, idempotent webhook processing.
5. **PH08-F005** — Double-entry financial ledger.
6. **PH08-F006** — Booking-to-payment allocation.
7. **PH08-F007** — Refund calculation and execution.
8. **PH08-F008** — Partial refund and cancellation fee rules.
9. **PH08-F009** — Commission calculation and disclosure.
10. **PH08-F010** — Partner payout and payout approval.
11. **PH08-F011** — Reconciliation and settlement reporting.
12. **PH08-F012** — Dispute, chargeback and evidence workflow.
13. **PH08-F013** — Tax, invoice and receipt records.
14. **PH08-F014** — Finance dashboard and financial audit log.

**Financial integrity:** Use integer minor units or fixed-precision decimal values; never floating point for money. Record currency on every amount. Do not mutate posted ledger entries; use reversals and adjustments. Keep rewards/wallet liabilities separate from payment-provider balances and operating revenue. Define who legally holds funds and whether any hold/escrow-like behaviour is permitted before implementation. Do not claim escrow unless the legal structure and provider support it.

**Provider gate:** eSewa, Khalti, Fonepay, card processors or international providers must be integrated only after written commercial, technical, compliance and settlement approval. Never assume Stripe or another provider is available for a Nepal entity without confirmation.

**Exit gate:** Sandbox and controlled production tests prove idempotency, signature verification, refund, partial refund, payout, reconciliation, duplicate webhook and provider outage recovery. Finance owner signs off.

---

## 47. Phase 09 — Adventure, trekking, guides and transport

**Feature modules: 16**

1. **PH09-F001** — Adventure activity catalogue and detail.
2. **PH09-F002** — Trek route and itinerary catalogue.
3. **PH09-F003** — Trekking package and departure dates.
4. **PH09-F004** — Peak-climbing product and expedition details.
5. **PH09-F005** — Guide and porter profile/qualification.
6. **PH09-F006** — Guide availability and assignment.
7. **PH09-F007** — Operator and agency profile.
8. **PH09-F008** — Group size and capacity management.
9. **PH09-F009** — Equipment and inclusion/exclusion details.
10. **PH09-F010** — Permit and restricted-area checklist integration.
11. **PH09-F011** — Safety briefing and risk acknowledgement.
12. **PH09-F012** — Vehicle, fleet and driver profiles.
13. **PH09-F013** — Transport routes, schedules and seat capacity.
14. **PH09-F014** — Airport transfer and private hire booking.
15. **PH09-F015** — Flight search/information provider integration.
16. **PH09-F016** — Luggage storage, transfer and tracking workflow.

**Category gates:** Each activity, route, operator and transport type has its own licensing, insurance, safety, capacity, cancellation and operational checklist. Flight booking requires an approved provider. Luggage custody and liability rules must be explicit.

**Exit gate:** At least one pilot provider per activated category completes a real operational rehearsal; booking capacity, cancellations, partner response, safety information and customer support are validated.

---

## 48. Phase 10 — Restaurants, local experiences, shopping and luggage

**Feature modules: 14**

1. **PH10-F001** — Restaurant profiles and menus.
2. **PH10-F002** — Restaurant table reservation and party-size rules.
3. **PH10-F003** — Restaurant reservation confirmation and cancellation.
4. **PH10-F004** — Food preferences and allergen disclosure.
5. **PH10-F005** — Local experience catalogue.
6. **PH10-F006** — Community tourism and host experience listings.
7. **PH10-F007** — Event, workshop and festival listings.
8. **PH10-F008** — Experience schedule, capacity and booking.
9. **PH10-F009** — Shopping seller onboarding.
10. **PH10-F010** — Product catalogue, variants and inventory.
11. **PH10-F011** — Shopping cart and checkout.
12. **PH10-F012** — Order fulfilment, delivery and tracking.
13. **PH10-F013** — Returns, refunds and seller disputes.
14. **PH10-F014** — Local partner settlement and payout reporting.

**Exit gate:** Restaurant, experience and marketplace categories each have separate operational readiness. Product authenticity, seller responsibility, food allergen disclosure, delivery liability, returns and consumer protection are documented.

---

## 49. Phase 11 — During-trip tools, connectivity, offline and translation

**Feature modules: 14**

1. **PH11-F001** — My Trip live trip dashboard.
2. **PH11-F002** — Trip timeline and itinerary updates.
3. **PH11-F003** — GPS location sharing with explicit consent.
4. **PH11-F004** — Route navigation and saved routes.
5. **PH11-F005** — Licensed offline map downloads.
6. **PH11-F006** — Offline trip itinerary and vouchers.
7. **PH11-F007** — Offline emergency information pack.
8. **PH11-F008** — Connectivity and SIM information.
9. **PH11-F009** — eSIM provider catalogue and purchase flow.
10. **PH11-F010** — Translation and phrase assistance.
11. **PH11-F011** — Weather and official alert feed.
12. **PH11-F012** — Travel disruption and route closure alerts.
13. **PH11-F013** — Nearby hospital, pharmacy, ATM, bank and fuel discovery.
14. **PH11-F014** — Sync queue and conflict-safe offline data synchronization.

**Offline rules:** State exactly which data is saved, when it expires, what cannot work offline, and how updates sync. Do not present cached data as live. GPS sharing is opt-in, revocable, purpose-limited and time-limited. eSIM purchase is gated on provider contract and support.

**Exit gate:** Test on low-end devices, slow networks, intermittent connectivity, airplane mode, stale cache, clock changes and interrupted sync. Map licensing is confirmed before downloads are enabled.

---

## 50. Phase 12 — AI travel intelligence and personalization

**Feature modules: 12**

1. **PH12-F001** — AI travel assistant.
2. **PH12-F002** — Grounded destination question answering.
3. **PH12-F003** — Personalized itinerary generation.
4. **PH12-F004** — Trip plan refinement and constraint checking.
5. **PH12-F005** — Budget-aware recommendations.
6. **PH12-F006** — Weather/context-aware suggestions using trusted sources.
7. **PH12-F007** — Multilingual conversational assistance.
8. **PH12-F008** — AI-assisted content drafting for human review.
9. **PH12-F009** — Recommendation ranking and explanation.
10. **PH12-F010** — User preference and personalization controls.
11. **PH12-F011** — AI evaluation, feedback and quality dashboard.
12. **PH12-F012** — AI safety, abuse, cost and provider fallback controls.

**AI safety contract:** AI must cite or identify the source and freshness of factual claims where possible. It must say “unknown” when reliable information is unavailable. It must not invent live availability, prices, permits, laws, medical advice, rescue capability, reviews or bookings. AI cannot approve partners, charge cards, issue refunds, confirm reservations, change legal records or dispatch emergency responders without deterministic rules and explicit authorized human/user confirmation. Protect against prompt injection, data exfiltration, unsafe tool calls, PII leakage and untrusted retrieved content.

**Google Gemini integration:** Use the official supported SDK/API for the selected model and pin the model/configuration. Use explicit system instructions, narrow typed tool/function schemas, structured output where appropriate, server-side validation, tool allowlists, rate limits, audit trails, human approval for consequential actions, grounding, evaluation datasets, refusal/fallback paths and cost budgets. Do not treat schema-valid output as factually correct. Keep model-provider access behind an adapter so the product can change providers.

**Exit gate:** Test factuality, source attribution, stale data, multilingual quality, prompt injection, tool misuse, privacy leakage, harmful advice, hallucinated booking actions, latency, cost and fallback. Human reviewers approve launch scope.

---

## 51. Phase 13 — Safety, emergency, incidents and traveler support

**Feature modules: 14**

1. **PH13-F001** — Safety information hub by destination/activity.
2. **PH13-F002** — Verified emergency contact directory.
3. **PH13-F003** — SOS interface and activation policy.
4. **PH13-F004** — Incident reporting and case creation.
5. **PH13-F005** — Incident severity classification and triage.
6. **PH13-F006** — Escalation and responder assignment.
7. **PH13-F007** — Emergency contact notification with consent.
8. **PH13-F008** — Incident timeline and status updates.
9. **PH13-F009** — Traveler support center and help articles.
10. **PH13-F010** — Support ticket and live chat where staffed.
11. **PH13-F011** — Complaint and dispute intake.
12. **PH13-F012** — Lost-document and lost-property assistance.
13. **PH13-F013** — Fraud/scam reporting and abuse controls.
14. **PH13-F014** — Post-incident follow-up and audit.

**Critical safety gate:** SOS cannot be marketed as emergency dispatch or 24/7 response until staffing, verified contacts, responder agreements, escalation, coverage boundaries, liability, privacy, incident drills and fallback are proven. A button without a staffed response operation is not an emergency service. The product must clearly say what it can and cannot do.

**Exit gate:** Tabletop and live drills validate acknowledgement, escalation, false alarm, no network, unavailable responder, duplicate incident, location consent, incident closure and aftercare.

---

## 52. Phase 14 — After-trip, reviews, memories, passport and rewards

**Feature modules: 12**

1. **PH14-F001** — Trip completion and post-trip summary.
2. **PH14-F002** — Actual versus estimated trip expenditure report.
3. **PH14-F003** — Booking, payment, receipt and refund history.
4. **PH14-F004** — Verified review invitation and submission.
5. **PH14-F005** — Review moderation and appeal.
6. **PH14-F006** — Partner reply and service recovery.
7. **PH14-F007** — Digital travel passport and stamps.
8. **PH14-F008** — Travel memories and private media album.
9. **PH14-F009** — Shareable trip story with privacy controls.
10. **PH14-F010** — Rewards and loyalty rules.
11. **PH14-F011** — Separate rewards ledger and redemption.
12. **PH14-F012** — Personalized repeat-trip recommendations.

**After-trip rules:** Reviews may be labelled verified only when tied to a completed eligible service. Rewards have explicit earn, expiry, reversal and redemption rules. Memories are private by default, with granular sharing controls. Media retention, export and deletion are documented.

**Exit gate:** Completed-service review eligibility, moderation, privacy, rewards accounting, refund reversal, media upload security, export and deletion tests pass.

---

## 53. Phase 15 — Group travel, community, companion and advanced features

**Feature modules: 12**

1. **PH15-F001** — Group trip creation and invitations.
2. **PH15-F002** — Shared itinerary and collaborative editing.
3. **PH15-F003** — Group member roles and permissions.
4. **PH15-F004** — Group expense splitting and settlement records.
5. **PH15-F005** — Travel community posts and questions.
6. **PH15-F006** — Community moderation and reporting.
7. **PH15-F007** — QR Scan Nepal information experience.
8. **PH15-F008** — Hidden Nepal editorial discovery.
9. **PH15-F009** — Companion discovery and matching.
10. **PH15-F010** — Companion safety checks, blocking and reporting.
11. **PH15-F011** — Sustainable/responsible travel guidance.
12. **PH15-F012** — Accessibility and inclusive-travel preference discovery.

**Companion matching gate:** Optional, disabled by default until legal, safety, privacy, moderation, age policy, reporting, blocking, identity/verification scope and incident response are approved. Never expose a user's live location by default.

**Exit gate:** Privacy and abuse testing, moderation staffing, group permission tests, expense calculation tests and safety review pass.

---

## 54. Phase 16 — Mobile apps, integrations, analytics and expansion

**Feature modules: 10**

1. **PH16-F001** — Android application using the stable API.
2. **PH16-F002** — iOS application using the stable API.
3. **PH16-F003** — Push notification integration.
4. **PH16-F004** — Deep links and universal links.
5. **PH16-F005** — Partner/provider integration hub.
6. **PH16-F006** — Public/partner API governance and webhooks.
7. **PH16-F007** — Business intelligence and operational dashboards.
8. **PH16-F008** — Multi-currency display and exchange-rate source.
9. **PH16-F009** — Corporate/group travel account support.
10. **PH16-F010** — New destination and international-market configuration.

**Rules:** Mobile apps reuse the same domain rules and server authorization. Never duplicate booking/payment logic in the client. App store compliance, privacy disclosures, accessibility, secure storage, release signing and crash reporting are required. International expansion requires country-specific legal, tax, payment, language and support review.

**Exit gate:** API contract tests pass across web and mobile; mobile security review, accessibility, offline behaviour, app-store readiness, integration failure handling and analytics privacy review pass.

---

## 55. Phase 17 — Production hardening, launch and continuous operations

**Feature modules: 6**

1. **PH17-F001** — Production deployment and environment promotion.
2. **PH17-F002** — Security assessment and penetration testing.
3. **PH17-F003** — Performance, load, stress and soak testing.
4. **PH17-F004** — Backup, disaster recovery and restore drills.
5. **PH17-F005** — Monitoring, alerting, SLOs and incident response.
6. **PH17-F006** — Controlled launch, rollback and continuous improvement.

**Release requirements:** Document SLI/SLO targets, p95/p99 latency, uptime, error budget, RPO/RTO, data retention, incident severity, on-call ownership and vendor escalation. Perform dependency and secret scanning, DAST/SAST where appropriate, access review, penetration testing, accessibility review, backup restore, payment reconciliation and production smoke tests. Use feature flags and gradual rollout. Keep a rollback plan for application and database changes.

**Exit gate:** Independent security review passed or all critical findings formally remediated; restore drill passed; production runbooks and support coverage exist; category-specific approvals are signed; rollback tested; owner authorizes launch.

---

## 56. Full 31-category lifecycle coverage matrix

Every category must have a defined Before, During and After experience. “During” and “After” may be information, support or feedback rather than a booking transaction. Do not force irrelevant features into a category.

| # | Category | Before travel | During travel | After travel | Owning phases |
|---:|---|---|---|---|---|
| 1 | Hotels and resorts | Search, room/rate comparison, amenities, policies, verified reviews, booking | Voucher, check-in/out, booking changes, support | Invoice, review, refund/dispute, trip history | 04–08, 13–14 |
| 2 | Homestays | Host story, facilities, location, house rules, availability, booking | Host contact, directions, check-in, local guidance | Host review, settlement record, memories | 04–08, 13–14 |
| 3 | Adventures and experiences | Activity detail, difficulty, risk, inclusions, insurance, booking | Briefing, schedule, guide contact, incident support | Completion, review, incident follow-up | 04, 06–09, 13–14 |
| 4 | Trekking | Route, altitude, season, permits, fitness, guide, gear, cost | Route status, itinerary, guide contact, weather, safety | Trek log, review, expense report, memories | 04–09, 11–14 |
| 5 | Peak climbing | Expedition details, permits, operator, insurance, equipment, risk | Expedition updates, schedule, safety and incident support | Completion record, review, claims follow-up | 04, 06, 09, 11, 13–14 |
| 6 | Tour operators and guides | Licence/profile, languages, itinerary, price, verification | Assignment, contact, schedule, support | Rating, complaint, payment/receipt history | 06, 09, 13–14 |
| 7 | Transport | Route, operator, vehicle, driver, schedule, price, booking | Ticket, pickup, delays, route disruption, support | Receipt, feedback, complaint | 04–09, 11, 13–14 |
| 8 | Flights | Flight information, baggage rules, airport transfer planning | Status updates only if provider data supports it, airport guidance | Itinerary history, receipt/refund follow-up where integrated | 05, 09, 11, 13–14 |
| 9 | Luggage services | Service coverage, custody rules, price, booking | Drop-off/pick-up, tracking if supported, claim process | Receipt, loss/damage claim, review | 06, 09–10, 13–14 |
| 10 | Nearby services | Find verified hospitals, pharmacies, ATMs, banks, fuel | Map, directions, call details, opening status with timestamp | Report incorrect listing, feedback | 04–05, 11, 13 |
| 11 | eSIM | Device compatibility, country/coverage, data plan, price, purchase | Install instructions, usage/support, provider status | Usage summary, provider support, feedback | 06, 08, 11, 13–14 |
| 12 | SIM information | Registration rules, required documents, provider options | Troubleshooting and top-up information | Feedback and updated information | 04, 11 |
| 13 | Offline maps | Download area, licence terms, route preparation | Offline navigation, saved points, stale-data warning | Route history if consented, map feedback | 05, 11 |
| 14 | Shopping marketplace | Seller/product discovery, comparison, delivery/return terms | Order tracking, seller contact, delivery issue | Returns, refund, review, order history | 06, 08, 10, 13–14 |
| 15 | Restaurants | Menu, location, price, allergen details, reservation | Directions, reservation, check-in, changes | Receipt, verified review, complaint | 04–08, 10, 13–14 |
| 16 | Local experiences | Host/provider, schedule, cultural guidance, inclusions, booking | Meeting point, host contact, attendance, support | Review, memories, host feedback | 04, 06, 08, 10, 13–14 |
| 17 | Hidden Nepal | Editorial discovery, access notes, season, responsible visit guidance | Route and etiquette information, safety updates | Visitor feedback, content correction | 04–05, 11, 14–15 |
| 18 | AI travel guide | Research, plan and compare with sources | Contextual guidance with freshness and uncertainty | Trip Q&A history controls and feedback | 12, with 04–05, 11, 13 |
| 19 | Trip planning | Itinerary, budget, permits, checklist, documents | Timeline, changes, navigation, expense tracking | Actual-versus-estimated report, saved plan | 05, 11, 14 |
| 20 | Weather and safety alerts | Seasonal risks, official alerts, preparation | Timely alert, source, issue time, affected area | Alert history, feedback | 04, 11, 13 |
| 21 | SOS and emergency | Explain scope, save contacts, consent and preparedness | Incident creation, acknowledgement only if staffed, escalation | Case updates, aftercare and audit | 13 |
| 22 | QR Scan Nepal | Learn QR coverage and privacy | Scan verified destination/partner QR; show source and validity | Report damaged/fake QR, scan history controls | 04, 11, 15 |
| 23 | Digital Travel Passport | Set up passport and privacy | Record eligible visits/stamps | Export, share, privacy and deletion | 03, 14 |
| 24 | Pheri Memories | Choose privacy/storage settings | Capture/save photos and notes | Album, timeline, export, delete/share | 03, 14 |
| 25 | Reviews and TrustScore | Read verified review policy and partner profiles | Submit service issue/feedback when eligible | Verified review, moderation, appeal | 06, 14 |
| 26 | Rewards and referrals | Understand rules and eligibility | Earn points after qualifying events | Redeem, expiry, reversal, ledger history | 08, 14 |
| 27 | Lost and Found | Learn reporting and contact rules | Report/search lost items, case status | Return confirmation, close case, privacy controls | 13–14 |
| 28 | Companion matching | Profile/privacy/safety controls and matching criteria | Opt-in messaging, block/report, no default live tracking | End match, report, delete profile/data | 03, 15 |
| 29 | Wallet and financial account functions | Explain supported balance type, terms, fees and limits | View ledger and eligible transactions | Statements, disputes, account closure | 03, 08, 14 |
| 30 | Travel community | Community rules, discover topics and groups | Posts, Q&A, trip group interactions, report abuse | Archive/delete/export, moderation appeal | 03, 15 |
| 31 | Travel support and dispute assistance | Help articles, policy, contact availability | Ticket, chat only when staffed, escalation | Resolution, satisfaction, appeal, case history | 13–14 |

**Important:** The original category catalogue contains 31 categories. This lifecycle matrix groups wallet and community/support as service experiences for planning traceability; it does not silently create new transactional categories. The canonical category codes in Section 6 remain authoritative. Any mismatch between this matrix and Section 6 must be resolved in the feature register before implementation.

---

## 57. Cross-cutting before/during/after information standard

Every destination, category, listing, itinerary and safety information record must use a consistent information envelope where relevant:

- Title and plain-language summary.
- Detailed description and eligibility.
- Geography and coverage area.
- Applicable traveler type and restrictions.
- Source URL/reference and source owner.
- Source type: official, provider, partner, editorial, user-generated, AI-generated.
- Verified/unverified status.
- Last checked time and next review/expiry.
- Price amount, currency, inclusions, exclusions and price-validity date if applicable.
- Availability status and whether live, cached, partner-reported or unknown.
- Safety/risk notes and escalation path.
- Language and translation review state.
- Accessibility information.
- Contact method and actual operating hours.
- Change history and responsible editor.

### 57.1 Before travel information checklist

- Destination overview, history, geography, altitude and culture.
- Seasonality, climate, weather norms and current alerts.
- Entry, visa, passport, permits and official requirements.
- Transport routes, options, journey duration and limitations.
- Stay, food, activities and local service options.
- Price estimates, fees, taxes, currency and payment options.
- Insurance options and coverage caveats.
- Health preparation and non-diagnostic safety information.
- Accessibility, child, senior and family suitability.
- Packing, connectivity, documents and emergency contacts.
- Cancellation, refund, change and disruption policies.
- Itinerary, time buffers, budget and alternative plan.

### 57.2 During travel information checklist

- Current trip plan, booked services and vouchers.
- Directions, location and route conditions where supported.
- Verified nearby services and contact details.
- Weather/safety alerts with source and timestamp.
- Booking change, delay, cancellation and disruption assistance.
- Offline itinerary, essential documents and emergency guidance.
- Local etiquette, language, food and cultural information.
- Expense tracking and payment receipts.
- Support, incident and lost-property reporting.
- Explicit privacy controls for location sharing and group visibility.

### 57.3 After travel information checklist

- Trip summary, route/places visited and timeline.
- Estimated versus actual costs.
- Booking, payment, refund, receipt and tax-document history.
- Verified review and partner feedback.
- Insurance claim and dispute follow-up where relevant.
- Lost-property case closure.
- Photos, memories, passport stamps and exports.
- Rewards, points, expiry and redemption.
- Personal data export, retention and deletion controls.
- Repeat-trip recommendations with user control.

---

## 58. Premium UI/UX implementation rules

### 58.1 Design-first, build-continuously

- Phase 01 creates the complete design language and core templates.
- Every later phase designs its own feature screens before implementation.
- UX and engineering work proceed together within the same phase.
- No feature may be implemented from a text-only prompt when interaction or layout is material; create a wireframe/prototype first.
- Do not design only the happy path.

### 58.2 Required screen states

For each interactive screen, define applicable states: initial, loading, loaded, empty, partial data, stale data, offline, permission denied, validation error, server error, provider unavailable, retrying, success, cancelled, expired, disabled, and restricted by role/readiness.

### 58.3 Responsive and accessible standards

- Mobile-first layouts with tested breakpoints.
- WCAG 2.2 AA as the target, including keyboard use, focus visibility, labels, contrast, error identification, reduced motion, screen reader semantics and touch target size.
- English/Nepali text expansion, Nepali numerals where appropriate, font rendering, date/number/currency formatting and localization testing.
- Right-to-left support is not an initial Nepal-language requirement, but architecture should not prevent future RTL locales.
- Low-end Android and slow-network testing.
- Avoid heavy animations and large images on low-bandwidth routes.

### 58.4 Design quality gate

A design reviewer compares actual implementation with approved design tokens and prototypes at mobile, tablet and desktop widths. Visual regression tests cover core journeys. Any deviation is recorded and accepted or corrected.

---

## 59. Detailed testing and quality strategy

### 59.1 Test layers

- Unit tests for domain rules and calculations.
- Component tests for UI states and accessibility.
- API contract tests for schemas and error responses.
- Database integration tests against real PostgreSQL.
- End-to-end tests for complete user journeys.
- Concurrency tests for inventory, booking, payment and rewards.
- Security tests for authorization, IDOR, injection, CSRF, XSS, SSRF, file upload and rate limits.
- Provider contract tests and sandbox integration tests.
- Localization and translation tests.
- Visual regression and responsive tests.
- Accessibility automation plus manual assistive-technology checks.
- Load, stress, spike and soak tests.
- Backup restore and disaster-recovery tests.
- AI evaluation, adversarial and prompt-injection tests.

### 59.2 Critical scenarios

- Two customers attempt to book the last unit.
- Payment succeeds but booking confirmation fails.
- Booking is accepted but payment times out.
- Duplicate webhook arrives many times.
- Provider sends events out of order.
- Approval request expires while user is paying.
- Partner is suspended while future bookings exist.
- Price changes between search and checkout.
- Cancellation occurs after partial service fulfilment.
- Refund succeeds at provider but local callback is lost.
- Payout is attempted twice.
- Reward points are earned then booking is refunded.
- Offline edits conflict with server changes.
- User revokes location sharing during an active trip.
- SOS is tapped with no network or no responder.
- AI is prompted to reveal private data or execute an unauthorized action.
- Content source is withdrawn or a permit rule changes.
- User requests account deletion while a legal/financial retention hold applies.

### 59.3 Release-blocking defects

Any unresolved critical/high security issue, money mismatch, unauthorized data access, double booking, incorrect emergency promise, destructive migration risk, or unverified legal/provider gate blocks release of the affected capability.

---

## 60. Security, privacy and data governance

Apply least privilege, secure defaults and privacy by design. At minimum:

- Threat model by feature and trust boundary.
- RBAC plus record-level and tenant-level authorization.
- MFA for privileged roles.
- Secure password hashing and account recovery.
- Session rotation, expiry, revocation and device logout.
- CSRF, XSS, SQL injection, SSRF, IDOR and open-redirect protection.
- Rate limits, bot/abuse controls and OTP throttling.
- Secure file upload, MIME validation, size limits, malware scanning and private storage.
- Signed webhooks, replay protection and idempotency.
- Encryption in transit and at rest where supported.
- Secrets manager/environment secrets; no secrets in source or logs.
- PII classification, minimization, purpose, consent and retention.
- Data export, correction, deletion and legal hold workflow.
- Audit trails for privileged actions and money movement.
- Vendor and subprocessors inventory.
- Breach detection, response, notification and evidence retention.
- AI prompt/data isolation, redaction, tool allowlists and retrieval permissions.
- Regular dependency updates and security review.

Legal obligations and retention periods must be confirmed by qualified counsel for Nepal and any other market served. This blueprint is not legal advice.

---

## 61. Operations, customer support and partner service standards

Before any category opens, define:

- Named operational owner and backup.
- Partner onboarding and verification SLA.
- Partner response-time policy.
- Customer support channels and actual operating hours.
- Emergency versus ordinary support separation.
- Refund/cancellation authority and escalation.
- Dispute and complaint workflow.
- Incident severity and escalation contacts.
- Service interruption and weather disruption playbook.
- Partner suspension and customer re-accommodation.
- Content correction and urgent alert process.
- Staff access review, training and audit.
- Support language coverage.
- Business continuity and vendor outage procedure.

Never advertise 24/7 support or rescue unless the staffing, contract, response time and geographic coverage are real and tested.

---

## 62. Analytics, business intelligence and product measurement

Measure by category, region, language, channel and user cohort where lawful and privacy-safe:

- Discovery: search volume, no-result rate, destination/category interest.
- Supply: partner applications, verification time, live listings, inventory freshness.
- Conversion: listing-to-booking, checkout abandonment, payment success.
- Operations: partner response, cancellation, fulfilment, dispute and support times.
- Finance: gross booking value, net revenue, commission, refunds, chargebacks, payout ageing and reconciliation variance.
- Trust: verified review share, complaint rate, fraud rate and resolution time.
- Safety: incident acknowledgement and closure time, only where an operational response exists.
- Product quality: crashes, latency, error rate, uptime, accessibility and translation defects.
- Retention: repeat trip creation, return travelers, partner retention.
- AI: grounded-answer rate, citation quality, refusal quality, unsafe response rate, latency and cost.

Do not collect more personal data than necessary. Do not optimize solely for bookings if doing so harms traveler safety or partner fairness.

---

## 63. External dependencies and explicit owner decisions

The following cannot be honestly decided by Google AI without owner input or qualified external confirmation:

1. Legal entity and company structure.
2. Nepal tourism, travel, trekking, transport, e-commerce and other category-specific licensing.
3. Payment gateway eligibility, merchant account, settlement and payout structure.
4. Tax/VAT, invoices, commission treatment and accounting policy.
5. Whether any payment hold or escrow-like model is legally and contractually permitted.
6. Insurance requirements and liability allocation by category.
7. Pilot province, districts and first live categories.
8. Commission, partner fees, subscriptions and refund policies.
9. Actual staffing, support hours, languages and emergency coverage.
10. SOS provider/responder contracts and operational responsibility.
11. Map, weather, flight, eSIM, messaging and AI provider contracts/licences.
12. Data residency, privacy and retention decisions with legal advice.
13. Brand assets, final logo and design approvals.
14. Budget, hosting, observability and security vendor choices.
15. Whether companion matching will be offered.
16. App-store publishing accounts and mobile release ownership.

Every decision must have an owner, due date, evidence, status and downstream phase impact.

---

## 64. Google AI master implementation contract

The following instruction is mandatory when Google AI works on this project:

> You are the implementation team for PheriNepal. This master blueprint is the source of truth. Build the project phase by phase in the exact sequence defined here.
>
> Before coding a phase, inspect the repository and report the actual state. Read all relevant source files, package scripts, migrations, tests, environment examples and documentation. Do not rely on README claims or previous AI summaries as proof.
>
> For the active phase, create or update the feature register with each feature ID, requirement, dependencies, UI/UX screens, API contract, data model, security rules, tests, acceptance criteria and status. Do not silently omit features.
>
> First complete the phase's UX flows, wireframes/prototypes and screen-state inventory. Then implement the approved design using the shared design system. Build responsive, accessible mobile/tablet/desktop experiences.
>
> Implement complete vertical slices: frontend, backend, database, authorization, provider integration, error handling, tests, analytics, operational documentation and support behaviour. Do not create decorative pages or fake interactions.
>
> Never fabricate prices, inventory, bookings, ratings, reviews, provider responses, legal requirements, emergency contacts, weather, route conditions, map data or verification results. Label mock data and keep it out of production.
>
> Never activate a gated category or high-risk feature until its legal, licence, partner, provider, safety, staffing and operational approvals are documented. Do not use a technical feature flag as a substitute for real-world readiness.
>
> Do not change the approved architecture, stack, schema, money rules, permissions, privacy policy or booking state machine without presenting a written impact analysis and receiving owner approval.
>
> Run tests against real PostgreSQL for database behaviour. Include concurrency and failure tests for booking/payment. Use static analysis, typecheck, lint, unit, integration, E2E, accessibility, localization and security checks as applicable.
>
> Do not claim a test passed unless you ran it and can show the command and actual output. Do not claim production readiness from a successful build alone.
>
> At the end of the phase, provide: (1) features completed, blocked and not started; (2) exact changed files; (3) database migrations; (4) commands run and results; (5) screenshots or recordings for UI work; (6) security and accessibility findings; (7) known defects; (8) external approvals still pending; (9) acceptance criteria evidence; and (10) a recommendation to proceed or stop.
>
> Do not begin the next phase until the owner accepts the current phase evidence. If blocked, explain the exact blocker and continue only with safe, independent work inside the approved phase.

### 64.1 Required phase completion report

For every phase, Google AI must output:

| Field | Required content |
|---|---|
| Phase | Exact phase number and name |
| Feature inventory | Total, completed, blocked, not started |
| Requirement traceability | Feature IDs mapped to acceptance criteria |
| UI/UX | Screens, states, responsive checks and design references |
| Code changes | Exact files and modules |
| Database | Migrations, constraints, indexes and rollback |
| APIs | Endpoints/contracts/auth/errors/idempotency |
| Tests | Commands, environment, counts and actual results |
| Security | Findings, severity and remediation |
| Accessibility/localization | Automated and manual results |
| Operations | Logs, metrics, alerts and runbooks |
| External dependencies | Approvals and contracts outstanding |
| Known limitations | Explicit list; no concealment |
| Exit gate | Pass/Fail/Blocked with evidence |
| Next action | Proceed only after owner acceptance |

---

## 65. Final completeness and traceability checklist

Before calling the master blueprint implementation-ready, verify:

- [ ] All 31 catalogue categories are present and use canonical codes.
- [ ] All 240 feature modules have unique IDs, phase ownership and acceptance criteria in the implementation feature register.
- [ ] Before, During and After requirements exist for all 31 categories.
- [ ] Premium UI/UX, design system and screen-state requirements are included.
- [ ] Eight dashboards and their permission matrices are included.
- [ ] Booking, inventory, payment, ledger, refund, payout and reconciliation rules are specified.
- [ ] Partner onboarding, verification, readiness, suspension and appeals are specified.
- [ ] AI grounding, prompt-injection defence, human approval, evaluation and cost controls are specified.
- [ ] Offline, localization, accessibility and low-connectivity requirements are specified.
- [ ] Safety, SOS, incident response and honest service claims are specified.
- [ ] Reviews, memories, passport, rewards, wallet and community privacy rules are specified.
- [ ] All category-specific legal, operational and provider gates are recorded.
- [ ] Database, API, background jobs, DevOps, observability and disaster recovery are specified.
- [ ] Test coverage includes concurrency, money, security, accessibility, localization and failure recovery.
- [ ] Google AI's implementation contract and evidence report are included.
- [ ] No feature is described as already implemented unless verified in the actual repository.
- [ ] All owner decisions and external approvals remain visibly PENDING until evidence is received.

**Final rule:** The 240-module inventory and 31-category catalogue define planned scope. They do not mean the product is already implemented, legally approved, staffed, integrated, or safe to launch. Completion is earned only through working software, test evidence, operational readiness and owner approval.
