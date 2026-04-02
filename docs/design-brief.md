# Design Brief

## Product
Shopify Upsell

## Product summary
Shopify Upsell is a Shopify embedded app that helps merchants create and manage upsell offers across the buyer journey to improve Average Order Value (AOV) and conversion rate.

The app should feel native to the Shopify admin experience and be easy to use for merchants with low technical confidence.

---

## Design objective
Design a clean, modern, structured, and easy-to-use Shopify admin app that helps merchants:

- understand the app value quickly
- create and activate offers with low friction
- manage multiple offers confidently
- monitor performance clearly
- take the next best action without confusion

The overall experience should prioritize clarity, guidance, and fast time-to-value.

---

## App context
This product is a Shopify embedded admin app.

Design should align with Shopify admin expectations and follow Polaris-inspired patterns for:

- page structure
- spacing
- hierarchy
- forms
- tables
- status indicators
- empty states
- actions and feedback

The UI should feel practical and realistic for real merchant workflows, not concept-only or overly decorative.

---

## Target users
### Primary users
- Shopify merchants
- SMB-focused merchants
- Store owners
- E-commerce operators

### Secondary users
- Agencies managing merchant stores
- Team members responsible for store growth and merchandising

### User characteristics
- many users are non-technical
- users need guided setup
- users want quick results
- users need clear performance visibility
- users should not feel overwhelmed by configuration complexity

---

## UX priorities
- easy to scan
- clear hierarchy
- minimal friction
- strong primary CTA
- helpful empty states
- guided setup for new merchants
- action-oriented dashboard
- low cognitive load
- clear status visibility
- practical workflows over visual complexity

---

## Design style
- clean
- modern
- professional
- Shopify admin-friendly
- Polaris-inspired
- conversion-focused
- structured
- calm and easy to scan

---

## Design principles
- Simplicity first
- Show the next best action
- Avoid clutter
- Help new users succeed quickly
- Make data understandable
- Keep workflows guided and predictable
- Use progressive disclosure for complex setup
- Reduce hesitation before activation
- Make actions and states obvious

---

## Core merchant success path
The most important user journey to optimize is:

1. Merchant installs the app
2. Merchant lands on the welcome screen
3. Merchant understands the value proposition quickly
4. Merchant creates the first offer with low friction
5. Merchant activates the offer
6. Merchant returns to the dashboard
7. Merchant sees initial analytics and continues using the app

The design should strongly support this path.

---

## App navigation
Top-level navigation should feel simple and familiar.

Suggested navigation structure:

- Dashboard
- Offers
- Analytics
- Settings

Sub-pages under Offers may include:

- Offer List
- Create Offer
- Offer Detail
- Edit Offer

Navigation should support both:
- guided onboarding for new merchants
- efficient management for returning merchants

---

## Main screens to design first
1. Onboarding / Welcome
2. Dashboard
3. Offer List
4. Create Offer
5. Offer Detail / Edit Offer
6. Analytics

---

## Screen requirements

### 1. Onboarding / Welcome
**Goal**
Help new merchants understand the app quickly and take the first meaningful action.

**Should include**
- short value proposition
- setup steps or onboarding guidance
- clear primary CTA to create first offer
- optional secondary CTA to go to dashboard
- supportive content for first-time users

**UX expectations**
- lightweight
- not too text-heavy
- easy to understand within a few seconds
- focused on activation, not exploration

---

### 2. Dashboard
**Goal**
Give merchants a quick overview of performance, setup progress, and next actions.

**Should include**
- page header
- clear primary CTA to create offer
- KPI cards:
  - upsell revenue
  - impressions
  - clicks
  - conversions
- setup progress for new merchants
- recent offers
- top performing offers
- recommendations / tips / next actions

**UX expectations**
- highly scannable
- action-oriented
- useful for both new and returning merchants
- should not feel like a dense analytics page

---

### 3. Offer List
**Goal**
Provide a central place for merchants to manage all offers.

**Should include**
- searchable list/table
- filters
- status indicator
- offer name
- placement / offer type
- last updated information
- actions:
  - edit
  - duplicate
  - enable / disable

**UX expectations**
- support quick scanning
- easy to manage many offers
- make important info visible without opening each offer

---

### 4. Create Offer
**Goal**
Help merchants create a new upsell offer through a clear and structured flow.

**Should include**
- offer name
- placement selection
- condition setup
- recommended product selection
- discount setup
- summary / review structure
- save draft action
- activate action

**Supported placements**
- Product page
- Cart page
- Checkout page
- Post-purchase page
- Thank you page

**UX expectations**
- guided and sectioned
- suitable for non-technical merchants
- avoid overwhelming the user at once
- make required steps obvious
- support confident activation

---

### 5. Offer Detail / Edit Offer
**Goal**
Allow merchants to review and update an existing offer.

**Should include**
- offer information
- placement
- trigger and conditions
- product / discount configuration
- status
- quick performance summary
- save changes action
- duplicate action
- enable / disable action

**UX expectations**
- easy to review
- easy to edit without losing context
- should feel like a management screen, not a raw settings dump

---

### 6. Analytics
**Goal**
Help merchants understand which offers perform well and what to improve.

**Should include**
- KPI summary
- charts or trends
- performance by offer
- filtering by date range
- clear connection between data and action
- shortcut / CTA to edit underperforming offers

**UX expectations**
- clear and actionable
- not overly complex
- highlight insights before detailed breakdowns
- support fast decision-making

---

## Page hierarchy and action hierarchy
Each screen should have a clear hierarchy.

### Expected hierarchy
- page title
- page description or context where needed
- primary action
- main content area
- secondary actions
- supporting information

### Action hierarchy rules
- each page should have one clear primary action
- secondary actions should not visually compete with the primary CTA
- destructive actions should be separated and clearly signaled
- action labels should use simple verbs

Examples:
- Create offer
- Save draft
- Activate
- Edit
- Duplicate
- Disable

---

## Admin layout expectations
- desktop-first admin layout
- Shopify admin-like spacing and grouping
- clear section-based structure
- consistent alignment
- cards or grouped sections where useful
- layouts should feel production-ready and practical

Create Offer and Edit Offer screens should especially use strong section grouping to reduce cognitive load.

---

## Form behavior expectations
Since Create Offer is a core workflow, form UX should be clearly defined.

### Form expectations
- use grouped sections instead of one long unstructured form
- show required fields clearly
- use inline validation
- make save behavior obvious
- support Save draft and Activate
- show whether the offer is ready for activation
- allow merchants to review the offer before activation

### Form UX goals
- reduce confusion
- support progressive completion
- make setup feel safe and understandable
- minimize accidental errors

---

## Data display guidelines
### KPI cards
KPI cards should prioritize the most important metrics first:
- revenue
- impressions
- clicks
- conversions

### Charts and analytics
- charts should support fast scanning
- trends should be easy to interpret
- analytics should guide action, not only display numbers

### Tables and lists
- rows should be easy to scan
- status should be visible
- actions should be easy to access
- filtering and search should feel practical

---

## Required states
Design should include clear treatment for the following states:

### Empty states
- dashboard with no data
- offer list with no offers
- analytics with no data

Empty states should:
- explain what the page is for
- tell the merchant what to do next
- encourage first success

### Loading states
- page loading
- data loading
- table loading
- chart loading

### Success states
- offer created successfully
- offer updated successfully
- offer activated successfully

### Validation states
- missing required fields
- invalid input
- incomplete offer setup

### Warning / destructive states
- disabling an offer
- discarding changes
- deleting or destructive actions if added later

---

## Content guidelines
- use plain language
- avoid unnecessary technical jargon
- keep labels concise
- make button labels action-oriented
- explain complex concepts simply
- write empty states and helper text in a supportive tone
- focus on merchant outcomes, not system language

Examples of preferred tone:
- clear
- supportive
- direct
- practical

---

## Key components expected
- page header
- breadcrumbs where appropriate
- KPI cards
- tables / lists
- filters
- status badges or indicators
- step / progress section
- grouped form sections
- empty states
- inline validation
- success feedback
- primary and secondary actions
- side summary or grouped review section where helpful

---

## Accessibility and usability expectations
- clear text hierarchy
- readable spacing
- visible status indicators
- color should support meaning, not be the only signal
- important actions should be easy to identify
- screens should remain usable even with dense business content

---

## Notes for AI design tools
When generating screens:

- keep the layout practical for a Shopify embedded admin app
- use Polaris-inspired structure and hierarchy
- prioritize clarity over decoration
- design for merchants, not designers or developers
- avoid flashy or overly conceptual UI
- make onboarding and first offer creation especially strong
- include meaningful empty states and next-step guidance
- keep Create Offer structured and easy to complete
- make Analytics actionable, not just visual
- ensure all screens feel consistent as part of one app system

---

## Output expectation
The final design direction should feel like a real Shopify admin app that is:

- easy for merchants to understand
- fast to use
- trustworthy
- scalable for future features
- visually aligned with Shopify admin conventions
