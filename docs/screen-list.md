# Screen List

## A. Merchant Admin Screens

### 1. Welcome / Onboarding Screen
**Purpose**
- Introduce the app
- Show value proposition
- Explain setup steps
- Guide merchants to the first action

**Main content**
- app introduction
- key benefits
- setup steps
- primary CTA: Create First Offer
- secondary CTA: Go to Dashboard

**Related flow**
- Merchant onboarding flow
- New merchant success path

---

### 2. Dashboard Screen
**Purpose**
- Give merchants a quick overview of performance
- Show next actions
- Help merchants monitor offer results

**Main content**
- KPI summary
- quick actions
- setup progress
- top performing offers
- weak-performing offers or recommendations
- shortcut to Analytics
- shortcut to Create Offer

**Related flow**
- Merchant onboarding flow
- Merchant analytics flow
- New merchant success path

---

### 3. Offer List Screen
**Purpose**
- Provide a central place to manage all offers

**Main content**
- search
- filters
- offer list/table
  -- offer name
  -- offer status
  -- page upsell
  -- Used
  -- Views
  -- ATCs
  -- CR
  -- Revenue
- actions: edit, duplicate, enable/disable
- CTA: Create Offer

**Related flow**
- Merchant offer creation flow
- Merchant offer management flow

---

### 4. Create Offer - Placement Selection Screen
**Purpose**
- Let merchants choose which upsell page type they want to create

**Main content**
- page upsell selection options:
  - Product Page
  - Cart Page
  - Post-purchase Page
  - Thank You Page
  - Checkout Page
- continue CTA

**Related flow**
- Merchant offer creation flow

---

### 5. Create Offer - Basic Information Screen
**Purpose**
- Let merchants define the basic information of the offer

**Main content**
- offer name input
- offer type
- schedule offer 
- navigation to next step

**Related flow**
- Merchant offer creation flow

---

### 6. Create Offer - Trigger & Conditions Screen
**Purpose**
- Let merchants configure when and where the offer should appear

**Main content**
- trigger setup
- condition builder
- display logic
- placement-related conditions
- navigation actions

**Related flow**
- Merchant offer creation flow

---

### 7. Create Offer - Offer Configuration Screen
**Purpose**
- Let merchants define the actual upsell content

**Main content**
- recommended product selection
- discount configuration
- offer preview area if applicable
- summary of selected products and discount

**Related flow**
- Merchant offer creation flow

---

### 8. Create Offer - Review & Activate Screen
**Purpose**
- Let merchants review the full offer before saving or activating

**Main content**
- offer summary
- placement summary
- trigger and conditions summary
- recommended product summary
- discount summary
- actions:
  - Peview
  - Save
  - Activate

**Related flow**
- Merchant offer creation flow

---

### 9. Offer Created Success Screen / Success State
**Purpose**
- Confirm that the offer has been saved or activated successfully

**Main content**
- success message
- quick next actions:
  - Go to Dashboard
  - View Offer List
  - Create Another Offer

**Related flow**
- Merchant offer creation flow

---

### 10. Offer Detail Screen
**Purpose**
- Show full information of an existing offer

**Main content**
- offer information
- placement
- trigger and conditions
- recommended product and discount
- status
- quick performance snapshot
- actions: edit, duplicate, enable/disable

**Related flow**
- Merchant offer management flow
- Merchant analytics flow

---

### 11. Edit Offer Screen
**Purpose**
- Let merchants update an existing offer

**Main content**
- editable offer configuration
- save changes CTA
- status control

**Related flow**
- Merchant offer management flow
- Merchant analytics flow

---

### 12. Analytics Screen
**Purpose**
- Help merchants evaluate offer performance and improve results

**Main content**
- KPI summary
- performance charts
- top performing offers
- weak-performing offers
- filters by date / offer / placement
- CTA to edit offer

**Related flow**
- Merchant analytics flow

---

## B. Buyer-Facing Upsell Screens / Blocks

### 13. Product Page Upsell Widget
**Purpose**
- Show upsell recommendation on the product page

**Main content**
- recommended product
- product info
- optional discount
- CTA to add recommended item

**Related flow**
- Buyer product page upsell flow

---

### 14. Cart Page Upsell Widget
**Purpose**
- Show upsell recommendation inside the cart experience

**Main content**
- suggested upsell item
- optional discount
- CTA to add item
- quick continue to checkout option

**Related flow**
- Buyer cart upsell flow

---

### 15. Post-purchase Page Upsell Screen / Block
**Purpose**
- Present one-click upsell after the initial purchase is completed

**Main content**
- countdown 15 min
- upsell product offer
- clear one-click action
- Pay now CTA
- supporting message explaining that payment info is reused

**Related flow**
- Buyer post purchase page upsell flow

---

### 16. Thank You Page Upsell Screen / Block
**Purpose**
- Show additional recommended products after the initial order is completed

**Main content**
- suggested upsell item
- optional discount or benefit message
- CTA to add suggested item
- continue action

**Related flow**
- Buyer thankyou page upsell flow

---

### 17. Checkout Page Upsell Screen / Block
**Purpose**
- Show relevant upsell recommendation during checkout

**Main content**
- suggested product
- concise offer content
- CTA to add item
- continue to pay now

**Related flow**
- Buyer checkout page upsell flow

---

## C. Supporting States

### 18. Empty State - Dashboard
**Purpose**
- Help new merchants understand what to do when there is no data yet

**Main content**
- empty KPI state
- explanation message
- CTA to create first offer

**Related flow**
- Merchant onboarding flow
- New merchant success path

---

### 19. Empty State - Offer List
**Purpose**
- Help merchants start when there are no offers yet

**Main content**
- no-offer message
- CTA to create first offer

**Related flow**
- Merchant onboarding flow
- Merchant offer management flow
- New merchant success path

---

### 20. Empty State - Analytics
**Purpose**
- Explain why analytics is empty and what the merchant should do next

**Main content**
- no-data message
- suggestion to activate offers and wait for traffic
- CTA to create or activate offer

**Related flow**
- Merchant analytics flow
- New merchant success path

---

### 21. Validation / Error State
**Purpose**
- Help merchants fix issues when required fields are missing or invalid

**Main content**
- inline validation
- clear error messages
- guidance to resolve setup issues

**Related flow**
- Merchant offer creation flow
- Merchant offer management flow

---

## D. Suggested Screen Groups for Design Priority

### Priority 1
- Welcome / Onboarding Screen
- Dashboard Screen
- Offer List Screen
- Create Offer Flow
- Success Screen

### Priority 2
- Offer Detail Screen
- Edit Offer Screen
- Analytics Screen

### Priority 3
- Product Page Upsell Widget
- Cart Page Upsell Widget
- Checkout Page Upsell Widget
- Post-purchase Upsell Screen
- Thank You Page Upsell Screen
- Empty / Error States
