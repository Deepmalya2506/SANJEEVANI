# SANJEEVANI — *We care when even seconds count*

<img src="assets\landing_pg.jpeg"/>

The most important conclusion is this:

> **SANJEEVANI should not be positioned as “a blockchain healthcare application.”**
>
> It should be positioned as a **hospital-to-hospital resource-sharing network**, where AI, geospatial intelligence, verified facility identity, rapid reservation and blockchain-backed contractual trust are combined to solve a specific operational problem: **getting critical medical equipment from a feasible nearby source before the clinical situation becomes worse.**

Blockchain is one component. It is not the product.

---

# 1. Executive definition

### SANJEEVANI

> **A B2B SaaS network that connects hospitals into a trusted resource-sharing grid, enabling verified discovery, geospatially feasible matching, rapid off-chain reservation, auditable smart-contract commitments and digital payment settlement for temporary inter-hospital equipment sharing.**

Tagline:

> **SANJEEVANI — We care when even seconds count.**

The core problem is:

```text
Hospital A
has urgent equipment shortage
        │
        ▼
Hospital B/C/D
may have unused equipment
        │
        ▼
But A doesn't know:
────────────────────────────
Who has it?
Is it actually available?
Is it functional?
Can it legally/operationally be shared?
Which hospital can deliver it fastest?
What will it cost?
Can I trust the transaction?
Has it actually been reserved?
What happens if something goes wrong?
────────────────────────────
```

SANJEEVANI attempts to turn that fragmented process into:

```text
NEED
 ↓
DISCOVER
 ↓
VERIFY
 ↓
OPTIMIZE
 ↓
PROPOSE
 ↓
RESERVE
 ↓
COMMIT
 ↓
PAY
 ↓
DISPATCH
 ↓
TRACK
 ↓
RETURN
 ↓
SETTLE
```

---

# 2. The problem — properly defined

The problem is **not simply “hospitals don't have enough equipment.”**

India already has multiple equipment-management and health-information initiatives.

The deeper problem is:

> **Capacity exists, but it is fragmented, poorly discoverable, operationally difficult to transfer, and not represented as a trusted, real-time inter-organizational resource network.**

That distinction is extremely important.

For example, India's CDAC e-Upkaran already addresses equipment inventory, asset tracking, maintenance, GIS mapping, equipment transfer and reporting. It explicitly describes medical-equipment downtime as a problem and reports that assessments found substantial proportions of equipment dysfunctional at facilities. ([C-DAC][1])

So we cannot honestly pitch:

> "Nobody has digitized hospital equipment."

That is false.

Nor:

> "Government has done nothing."

Also false.

Instead:

### Existing systems primarily address

```text
facility
   ↓
its own
inventory
   ↓
maintenance
   ↓
procurement
   ↓
asset lifecycle
```

SANJEEVANI targets:

```text
Hospital A
     ↕
Hospital B
     ↕
Hospital C
     ↕
Hospital D

INTER-HOSPITAL RESOURCE EXCHANGE
```

That is the architectural gap we are targeting.

---

# 3. What the literature tells us

The literature strongly supports several components of our architecture—but also warns us against overclaiming.

A systematic review of blockchain in healthcare reviewed 43 studies and found applications spanning healthcare ecosystems, while later reviews of blockchain-based healthcare supply chains have examined dozens of studies around traceability, provenance, transparency and transaction integrity. ([ScienceDirect][2])

A 2024 literature review examining 81 documents on healthcare supply-chain digitalization identifies benefits such as traceability, security, trust and privacy, but also highlights the need for skills, interoperability and organizational adoption. ([ScienceDirect][3])

A more recent systematic review of smart contracts in healthcare identifies medical-equipment supply chains, emergency processes and regulatory compliance among the application areas being studied. ([ScienceDirect][4])

Therefore:

### Our individual technologies are not novel.

These are established research areas:

```text
Blockchain
AI
GIS
H3
PostGIS
Smart contracts
Healthcare inventory systems
Facility registries
Digital payments
```

### Our potential novelty is architectural.

The potentially differentiated proposition is:

```text
verified facility identity
        +
live inter-hospital equipment availability
        +
AI orchestration
        +
H3 candidate pruning
        +
road/traffic-aware feasibility
        +
rapid reservation
        +
smart-contract transaction commitment
        +
payment settlement
        +
transaction monitoring
```

**That integration is where SANJEEVANI's research/product contribution should be argued.**

---

# 4. Existing Indian ecosystem — and where SANJEEVANI fits

## 4.1 ABDM Health Facility Registry

The Health Facility Registry is not something SANJEEVANI should try to recreate.

ABDM describes HFR as a comprehensive registry of verified public and private health facilities, including hospitals, clinics, laboratories, diagnostic centres and pharmacies. ([Ayushman Bharat Digital Mission][5])

Therefore:

```text
ABDM HFR
   ↓
"Does this healthcare facility exist?"
```

SANJEEVANI:

```text
SANJEEVANI
   ↓
"What can this verified facility share?"
"Is it available?"
"Can it reach another facility?"
"Under what terms?"
```

That is complementary rather than competitive.

---

# 5. e-Upkaran is an important reality check

This is perhaps the most important existing system we need to acknowledge.

CDAC describes e-Upkaran as a Medical Equipment Maintenance & Management System with:

* equipment inventory
* asset tracking
* GIS mapping
* equipment transfer management
* payment functionality
* reporting
* maintenance contracts
* QR/barcode inventory
* alerts
* RESTful integration
* RDBMS architecture. ([C-DAC][6])

A PubMed-indexed study describes e-Upkaran as a centralized inventory-management system launched in Rajasthan in 2015. ([PubMed][7])

So our claim cannot be:

> "SANJEEVANI is India's first digital medical-equipment network."

No.

The defensible claim is:

> **SANJEEVANI proposes a cross-organizational, AI-orchestrated resource-sharing network in which independently operated healthcare facilities can discover, evaluate, reserve and transact over temporarily shareable medical equipment using geospatial feasibility and blockchain-backed contractual trust.**

That is much more scientifically respectable.

---

# 6. The actual SANJEEVANI USP

I would define the USP as:

## **From equipment inventory to executable resource exchange.**

Existing inventory systems answer:

> "What equipment do we have?"

SANJEEVANI tries to answer:

> **"Which verified facility can actually provide this resource to me, within the required time, at acceptable cost and under a trusted transaction?"**

That is a very different question.

---

# 7. Why SANJEEVANI is a SaaS

SANJEEVANI is not simply a website.

Each hospital becomes a tenant/organization.

```text
                 SANJEEVANI SaaS
                       │
       ┌───────────────┼───────────────┐
       │               │               │
 Hospital A       Hospital B       Hospital C
       │               │               │
 users             users             users
 inventory         inventory         inventory
 transactions      transactions      transactions
```

Each hospital gets:

* organization profile
* users
* roles
* inventory
* transaction history
* dashboard
* wallet identity
* payment configuration
* compliance status
* activity
* monitoring

The network creates the value.

That gives us the SaaS characteristics:

```text
Multi-tenant
+
role-based access
+
subscription
+
centralized service delivery
+
API-based integrations
+
shared infrastructure
+
usage-based/transaction revenue
+
continuous updates
```

---

# 8. What SANJEEVANI actually offers

## A. Facility network

Verified healthcare organizations.

## B. Equipment marketplace

Discover available equipment across participating facilities.

## C. MCP assistant

Natural-language interaction:

> "Find a ventilator within 30 minutes."

## D. GIS intelligence

Determine:

* candidate hospitals
* feasible route
* ETA
* distance
* accessibility
* traffic
* route geometry

## E. Compliance

Determine whether the equipment/facility satisfies required conditions.

## F. Rapid reservation

Immediately lock inventory off-chain.

## G. Blockchain

Record contractual/transactional state.

## H. Payments

Eventually settle INR through payment infrastructure.

## I. Monitoring

Borrower and lender see their respective transaction states.

## J. Auditability

Immutable blockchain transaction references.

---

# 9. The definitive end-to-end workflow

This should become our architectural north star.

```text
                    LANDING PAGE
                         │
                         ▼
                    SIGN UP / LOGIN
                         │
                         ▼
                FACILITY / USER CONTEXT
                         │
                         ▼
                  SANJEEVANI DASHBOARD
                         │
             ┌───────────┴───────────┐
             │                       │
        Marketplace              MCP Chat
             │                       │
             └───────────┬───────────┘
                         ▼
                    USER REQUEST
                         │
                         ▼
                MCP ORCHESTRATOR
                         │
        ┌────────────────┼─────────────────┐
        ▼                ▼                 ▼
   PostgreSQL         Compliance          GIS
   inventory          validation          search
        │                │                 │
        └────────────────┼─────────────────┘
                         ▼
                    H3 PRUNING
                         │
                         ▼
                  ROUTE / ETA ENGINE
                         │
                         ▼
                 FEASIBILITY RANKING
                         │
                         ▼
                   LOAN PROPOSAL
                         │
                         ▼
                    USER APPROVES
                         │
                         ▼
               OFF-CHAIN RESERVATION
                         │
                  IMMEDIATE LOCK
                         │
              ┌──────────┴──────────┐
              ▼                     ▼
        BLOCKCHAIN              PAYMENT
        commitment             provider
              │                     │
              └──────────┬──────────┘
                         ▼
                     CONFIRMED
                         │
                         ▼
                     DISPATCH
                         │
                         ▼
                    DELIVERY
                         │
                         ▼
                       ACTIVE
                         │
                         ▼
                      RETURN
                         │
                         ▼
                    SETTLEMENT
                         │
                         ▼
                INVENTORY AVAILABLE
                         │
                         ▼
                  ACTIVITY / AUDIT
```

---

# 10. Microservice architecture

I would **not** create 25 microservices.

That would be classic student-project microservice inflation.

For the prototype, use **logical services**, independently testable and deployable where appropriate.

Recommended:

```text
                    FRONTEND
                       │
                       ▼
                 API GATEWAY / BFF
                       │
       ┌───────────────┼────────────────┐
       │               │                │
       ▼               ▼                ▼
   AUTH SERVICE    CORE SERVICE      MCP SERVICE
                       │                │
                       │       ┌────────┼────────┐
                       │       ▼        ▼        ▼
                       │      GIS   Compliance Blockchain
                       │
                       ▼
                    PostgreSQL
                       │
                     PostGIS
```

Payment:

```text
CORE
 │
 ▼
Payment Service
 │
 ▼
Razorpay
```

---

# 11. PostgreSQL — the new core

This is where I agree with the judges.

MongoDB was convenient for the MVP, but SANJEEVANI's domain is strongly relational.

We have:

```text
Hospital
  ├── Users
  ├── Equipment
  ├── Transactions
  ├── Reservations
  ├── Payments
  ├── Compliance
  └── Wallet
```

Those relationships matter.

PostgreSQL gives us:

* foreign keys
* transactions
* constraints
* joins
* unique constraints
* row-level security
* reliable concurrent updates

And PostGIS extends PostgreSQL with spatial storage, spatial indexing and spatial operations. ([PostGIS][8])

So:

> **PostgreSQL + PostGIS becomes SANJEEVANI's system of operational record.**

Blockchain is **not** the operational database.

---

# 12. Proposed database model

This is an important architectural freeze.

## `organizations`

Represents a hospital/facility.

```text
organization_id PK UUID
hfr_id UNIQUE nullable
name
facility_type
email
phone
address
location GEOGRAPHY(Point)
h3_cell
verification_status
wallet_address UNIQUE nullable
created_at
updated_at
```

---

# 13. `users`

A person using SANJEEVANI.

```text
user_id PK UUID
auth_provider_id UNIQUE
organization_id FK
name
email
role
status
created_at
updated_at
```

Important:

```text
USER ≠ HOSPITAL
```

One hospital can have multiple users.

```text
Hospital A
 ├── Admin
 ├── Inventory Manager
 ├── Dispatcher
 └── Finance Officer
```

---

# 14. `equipment_types`

Do not put "Oxygen Cylinder" directly into every equipment record.

```text
equipment_type_id PK
name
category
description
required_compliance_profile
```

Example:

```text
1 → Oxygen Cylinder
2 → Ventilator
3 → Infusion Pump
4 → Portable Monitor
```

---

# 15. `equipment_assets`

Individual physical equipment.

```text
asset_id PK UUID
organization_id FK
equipment_type_id FK
serial_number UNIQUE
name
manufacturer
model
condition
operational_status
sharing_status
hourly_rate
deposit_amount
location
h3_cell
compliance_status
created_at
updated_at
```

Now:

```text
Oxygen Cylinder
Type ID = 1
```

can have:

```text
Asset A
Asset B
Asset C
```

This fixes the conceptual weakness of our earlier `equipment_id` model.

---

# 16. Why individual assets matter

Suppose Hospital B owns:

```text
5 oxygen cylinders
```

but:

```text
2 AVAILABLE
1 RESERVED
1 MAINTENANCE
1 IN_USE
```

The database must represent that.

Not:

```text
oxygen_cylinder_count = 5
```

alone.

We need:

```text
Asset 1 → AVAILABLE
Asset 2 → AVAILABLE
Asset 3 → RESERVED
Asset 4 → MAINTENANCE
Asset 5 → IN_USE
```

That is much closer to a real equipment-management system.

---

# 17. `reservations`

This becomes the critical fast-operation table.

```text
reservation_id PK UUID
asset_id FK
borrower_organization_id FK
lender_organization_id FK
status
reserved_at
expires_at
created_by
```

Possible states:

```text
REQUESTED
RESERVED_OFFCHAIN
BLOCKCHAIN_PENDING
CONFIRMED
CANCELLED
EXPIRED
```

The actual locking must be transactional.

Conceptually:

```text
AVAILABLE
    ↓
RESERVED_OFFCHAIN
```

inside a PostgreSQL transaction.

This is where the judge's "seconds matter" criticism gets addressed.

---

# 18. `loans`

```text
loan_id PK UUID
reservation_id FK UNIQUE
borrower_organization_id FK
lender_organization_id FK
equipment_type_id FK
quantity
duration_hours
rent_amount
deposit_amount
currency
status
started_at
expected_return_at
returned_at
created_at
```

States:

```text
PROPOSED
RESERVED
CONFIRMED
DISPATCHED
ACTIVE
RETURN_PENDING
RETURNED
SETTLED
CANCELLED
```

---

# 19. `blockchain_transactions`

Never use transaction hash as your relational primary key.

Use:

```text
blockchain_transaction_id PK UUID
loan_id FK
network
chain_id
contract_address
transaction_hash UNIQUE
block_number
contract_loan_id
transaction_type
status
submitted_at
confirmed_at
```

Why?

Because blockchain is an external system.

Our DB owns the relationship.

---

# 20. `payments`

```text
payment_id PK UUID
loan_id FK
provider
provider_order_id
provider_payment_id
amount
currency
type
status
created_at
completed_at
```

Types:

```text
RENT
DEPOSIT
REFUND
PENALTY
SUBSCRIPTION
```

---

# 21. `compliance_attestations`

For our mock compliance service:

```text
attestation_id PK UUID
organization_id FK
asset_id FK nullable
attestation_type
issuer
payload_hash
signature
issued_at
expires_at
status
```

Examples:

```text
HFR_VERIFICATION
BMMP_MAINTENANCE
CALIBRATION
SAFETY_CHECK
```

The prototype can generate signed synthetic attestations.

We must clearly label them:

> **SIMULATED COMPLIANCE DATA — NOT GOVERNMENT VERIFIED**

Never pretend our mock HFR/BMMP service is an actual government integration.

---

# 22. `activity_events`

```text
event_id PK UUID
organization_id FK
user_id FK
loan_id FK nullable
event_type
event_payload
created_at
```

Example:

```text
LOAN_REQUESTED
RESERVATION_CREATED
BLOCKCHAIN_SUBMITTED
BLOCKCHAIN_CONFIRMED
PAYMENT_COMPLETED
DISPATCHED
DELIVERED
RETURNED
SETTLED
```

This powers the Activity page.

---

# 23. Multi-tenancy is crucial

This is one of the most important security requirements.

A Hospital A user must never retrieve Hospital B's private data.

Every private query should effectively resolve to:

```text
organization_id = authenticated_user.organization_id
```

Public/network information is different.

Users can see:

```text
Hospital name
Hospital location
Available equipment type
Available count
price
general availability
verification badge
```

But not:

```text
Hospital B's private users
Hospital B's private transactions
Hospital B's revenue
Hospital B's private audit information
Hospital B's internal patient data
```

---

# 24. GIS architecture

This is where we need to correct the previous Haversine architecture.

## Haversine is not a routing algorithm.

It calculates great-circle distance between coordinates.

It can answer approximately:

```text
"What is the straight-line distance?"
```

It cannot answer:

```text
"What is the fastest road route?"
```

or:

```text
"Can an ambulance/equipment vehicle actually travel this route?"
```

Therefore we remove Haversine as our primary routing mechanism.

---

# 25. GIS pipeline

```text
Hospital coordinates
        │
        ▼
PostGIS
        │
        ▼
H3 indexing
        │
        ▼
Candidate pruning
        │
        ▼
Road routing engine
        │
        ▼
ETA / distance
        │
        ▼
Traffic adjustment
        │
        ▼
Feasibility score
```

---

# 26. H3's role

H3 partitions geographic space into hierarchical hexagonal cells and provides neighborhood/indexing operations. ([H3Geo][9])

It is **not** the route calculator.

Its job is:

> **reduce the number of candidate hospitals that need expensive route calculations.**

For example:

```text
500 hospitals
     ↓
H3 spatial filter
     ↓
50 candidates
     ↓
road routing
     ↓
10 feasible
     ↓
MCP ranking
     ↓
best 3
```

This is exactly where H3 makes architectural sense.

---

# 27. Routing

For the prototype:

### OSRM

Use OpenStreetMap road data + OSRM for road-network routing.

But there is an important limitation:

> **OSRM should not be described as a real-time traffic engine.**

For the prototype:

```text
H3
 ↓
OSRM
 ↓
road distance
 ↓
baseline ETA
```

For production:

```text
H3
 ↓
traffic-aware routing provider
 ↓
real-time ETA
```

Google's current Routes API explicitly supports `TRAFFIC_AWARE` and `TRAFFIC_AWARE_OPTIMAL` routing modes using live traffic information. ([Google for Developers][10])

Mapbox also provides a `driving-traffic` profile using historical and live traffic data. ([Mapbox][11])

So our GIS service should expose an abstraction:

```text
RoutingProvider
    │
    ├── OSRMProvider
    │
    └── TrafficAwareProvider
```

That means we don't rewrite the system later.

---

# 28. SANJEEVANI's GIS scoring

Do NOT simply choose:

```text
minimum distance
```

Instead:

```text
Feasibility =
    ETA
  + availability
  + compliance
  + equipment condition
  + cost
  + route reliability
```

Example conceptual score:

```text
Score =
w1 * ETA
+
w2 * cost
+
w3 * reliability
+
w4 * compliance
```

But these weights must be configurable.

Do not hardcode:

```text
ETA = 40%
price = 30%
distance = 30%
```

Those become policy/configuration.

---

# 29. MCP

MCP is the intelligence/orchestration layer.

But we must use MCP properly.

The official MCP architecture distinguishes:

* **Tools** — executable functions
* **Resources** — contextual/read-only information
* **Prompts** — reusable interaction templates. ([Model Context Protocol][12])

And the MCP specification explicitly recommends human confirmation for consequential tool actions. ([Model Context Protocol][13])

That maps beautifully onto SANJEEVANI.

---

# 30. SANJEEVANI MCP tools

Keep them small.

### Discovery

```text
search_available_equipment()
```

### Facility

```text
get_facility_details()
```

### GIS

```text
find_nearest_facilities()
calculate_route()
calculate_eta()
find_best_feasible_option()
```

### Compliance

```text
verify_asset_compliance()
```

### Transaction

```text
create_loan_proposal()
```

### Reservation

```text
reserve_asset()
```

### Payment

```text
create_payment_request()
```

### Status

```text
get_transaction_status()
```

The LLM should **not** directly modify PostgreSQL.

It invokes controlled tools.

---

# 31. MCP Resources

Resources should provide contextual information such as:

```text
facility://current
inventory://available
transaction://current
policy://sharing
```

The MCP model can then reason using authorized context.

---

# 32. MCP Prompts

Useful reusable prompts:

```text
emergency_equipment_search
best_feasible_equipment
compare_equipment_options
explain_transaction
check_current_reservation
```

But don't build 100 prompts.

Keep the protocol clean.

---

# 33. Human-in-the-loop

This is non-negotiable.

MCP can:

```text
search
calculate
compare
propose
```

But it should not silently:

```text
reserve
pay
transfer
settle
```

without explicit authorization.

So:

```text
MCP
 ↓
Proposal
 ↓
USER APPROVES
 ↓
reservation tool
```

This is also directly consistent with MCP's security guidance. ([Model Context Protocol][13])

---

# 34. Blockchain architecture

Now we finally have a legitimate blockchain role.

## Blockchain stores:

```text
loan commitment
borrower wallet
lender wallet
asset reference
terms hash
reservation reference
state transitions
settlement reference
```

Not:

```text
patient records
hospital passwords
complete inventory database
GIS coordinates of everything
payment credentials
```

Those remain off-chain.

---

# 35. Wallet model

Each participating hospital gets:

```text
Hospital A
   │
   └── wallet A

Hospital B
   │
   └── wallet B
```

One wallet can participate in unlimited transactions.

```text
A → borrows from B
A → lends to C
A → borrows from D
A → lends to E
```

So:

```text
hospital : wallet = 1 : 1
```

is a reasonable initial model.

But don't hardcode that forever. Later you may want:

```text
organization
    ├── operational wallet
    ├── treasury wallet
    └── signing authority
```

---

# 36. Are hospitals blockchain nodes?

No—not necessarily.

This distinction must be used in the pitch.

```text
Hospital
     =
Blockchain participant
```

does not mean:

```text
Hospital
     =
Blockchain validator node
```

The blockchain network can have infrastructure nodes operated by SANJEEVANI and trusted consortium members.

Eventually:

```text
Hospital A ──┐
Hospital B ──┼── Consortium
Hospital C ──┤
Hospital D ──┘
```

could evolve toward distributed governance.

---

# 37. Blockchain network strategy

## MVP

Since this is a prototype:

### Local development

```text
Hardhat local network
```

or retain the existing Ganache setup temporarily.

But for a clean repository I would standardize on:

```text
Hardhat
+
local EVM
+
deterministic deployment
+
deployment manifest
```

The biggest lesson from our previous project is:

> **The contract address must be treated as deployment state, not manually copied around the application.**

---

# 38. Demo/testnet

If we want judges to see an actual public blockchain:

```text
Ethereum Sepolia
```

can be used for demonstration.

But this is still a test network.

No real money.

---

# 39. Production blockchain

I would not put hospital operational transactions directly onto Ethereum Mainnet.

Instead investigate:

> **permissioned EVM consortium infrastructure, such as Hyperledger Besu.**

Why?

Because healthcare organizations need:

* controlled participation
* predictable governance
* privacy
* known validators
* predictable costs
* enterprise integration

The production architecture becomes:

```text
SANJEEVANI consortium network
             │
      permissioned EVM
             │
     ┌───────┼────────┐
     │       │        │
 validator validator validator
```

Potentially operated by trusted participating institutions/consortium members.

This is a **future production architecture**, not something we need to build in the prototype.

---

# 40. Blockchain should NOT handle INR

This is another architectural freeze.

Don't make:

```text
₹31,300
   ↓
crypto
   ↓
wallet
```

the core business model.

Instead:

```text
Loan
 │
 ├── blockchain commitment
 │
 └── INR payment
       ↓
   Razorpay / UPI
```

Razorpay currently supports UPI checkout and UPI Intent; its documentation notes that UPI Collect is being deprecated for most new flows from February 28, 2026, making Intent/QR the relevant current direction. ([Razorpay][14])

Razorpay also documents UPI AutoPay for recurring mandates. ([Razorpay][15])

---

# 41. Where Razorpay fits

### One-time loan

```text
Loan approved
      ↓
Create payment order
      ↓
Razorpay
      ↓
UPI
      ↓
Payment confirmation
```

### Subscription

```text
SANJEEVANI SaaS plan
       ↓
UPI AutoPay
```

### Recurring equipment payment

Potentially:

```text
UPI AutoPay
```

but only if the business/payment flow actually qualifies.

---

# 42. Important Razorpay limitation

We should not assume:

> "Razorpay automatically transfers money between Hospital A and Hospital B because they are our marketplace users."

That's more complicated.

SANJEEVANI would effectively become a marketplace/platform handling payments between organizations, which can introduce onboarding, KYC, settlement and payment-product requirements.

Therefore our architecture should be:

```text
PaymentService
     │
     ├── MockPaymentProvider
     │
     └── RazorpayProvider
```

and we integrate real money only after the commercial/legal/payment architecture is established.

For the prototype:

> **₹0 real transactions.**

Razorpay currently advertises 2% + GST per transaction under its standard pricing, although commercial pricing can vary. ([Razorpay][16])

---

# 43. Authentication

I would now seriously consider **Supabase Auth + PostgreSQL** for the prototype.

Its current free tier includes a Postgres database and authentication, with 500 MB database storage and 50,000 MAUs in the listed free tier. Free projects can pause after a week of inactivity. ([Supabase][17])

That gives:

```text
Supabase Auth
       │
       ▼
JWT
       │
       ▼
SANJEEVANI backend
       │
       ▼
organization_id
```

The backend—not the frontend—determines what the user is authorized to do.

Firebase remains a valid alternative; Firebase Authentication currently has a no-cost Spark offering with stated limits, but using Supabase reduces architectural fragmentation because PostgreSQL is already our core database. ([Firebase][18])

### My choice:

> **Supabase Auth + PostgreSQL/PostGIS for the prototype.**

---

# 44. SANJEEVANI frontend wireframe

## Public

```text
/
├── Landing
├── How It Works
├── Network
├── FAQ
├── Login
└── Sign Up
```

You specifically wanted the landing page followed by FAQ, so don't turn the public site into a 15-page marketing website.

---

# 45. Authenticated application

```text
/app
│
├── dashboard
├── marketplace
├── assistant
├── monitor
├── map
├── activity
├── inventory
├── profile
└── settings
```

---

# 46. Dashboard

```text
┌────────────────────────────────────────────┐
│ SANJEEVANI             Hospital A     👤   │
├──────────┬─────────────────────────────────┤
│ Dashboard│                                 │
│ Assistant│  Welcome back, Hospital A       │
│ Market   │                                 │
│ Monitor  │  Available equipment             │
│ Map      │  Active transactions             │
│ Activity │  Pending actions                 │
│ Inventory│  Network status                  │
│ Profile  │                                 │
└──────────┴─────────────────────────────────┘
```

No fake statistics.

If no transactions:

> No active transactions.

---

# 47. MCP Assistant

The primary interaction.

```text
You:
"Find a ventilator within 30 minutes."
```

MCP:

```text
Understanding request
       ↓
Searching network
       ↓
Checking compliance
       ↓
Calculating feasible routes
       ↓
Comparing options
```

Then:

```text
OPTION 1
Hospital B
Ventilator
ETA: 24 min
Rent: ₹...
Deposit: ₹...
Compliance: verified

[View route]

[Approve reservation]
```

---

# 48. Marketplace

This is the **discovery UI**.

Users can manually browse:

```text
Ventilator
Hospital B
Available: 2
₹X/hour
Deposit: ₹Y
Distance/ETA: X
Verified
```

But personalized questions such as:

> "Which is cheapest and fastest?"

should naturally push users toward MCP.

That distinction is excellent for the product:

```text
Marketplace = browse
MCP = reason
```

---

# 49. Monitor

Default:

```text
No current transactions.

Transactions involving your hospital
will appear here once a reservation is created.
```

When active:

```text
TRANSACTION #L-1024

Borrower → Hospital A
Lender   → Hospital B

Asset
Reservation
Blockchain
Payment
Dispatch
Delivery
Return
Settlement
```

Borrower sees its side.

Lender sees its side.

---

# 50. Map

Default:

```text
🗺️ No active route

A route map will appear when
SANJEEVANI calculates a route
for an active request.
```

When MCP requests GIS:

```text
MCP
 ↓
GIS
 ↓
route HTML / route payload
 ↓
Map tab
 ↓
embedded map
```

This is much better than showing a meaningless map all the time.

---

# 51. Activity

Immutable references:

```text
Loan requested
Reservation created
Payment initiated
Blockchain transaction submitted
Blockchain confirmed
Dispatch confirmed
Delivery confirmed
Return initiated
Settlement completed
```

The UI can link:

```text
Blockchain transaction
```

to a block explorer when using a public testnet.

---

# 52. Inventory

Hospital's private inventory.

```text
My Equipment

Oxygen Cylinder
Available: 3
Reserved: 1
Maintenance: 1

Ventilator
Available: 1
Reserved: 0
```

Other hospitals cannot access this private view.

---

# 53. Profile

```text
Hospital information
HFR verification
Wallet
Users
Registered equipment
Transactions
Payment configuration
Compliance
```

---

# 54. Complete SaaS user walkthrough

### Step 1

Visitor enters:

```text
SANJEEVANI
We care when even seconds count.
```

### Step 2

Sign up.

### Step 3

Create hospital organization.

### Step 4

Hospital identity is created.

### Step 5

Optional HFR verification/integration.

### Step 6

Hospital connects wallet.

### Step 7

Hospital registers equipment.

### Step 8

Equipment becomes:

```text
AVAILABLE
```

### Step 9

Hospital B joins.

### Step 10

Hospital B registers equipment.

### Step 11

Both appear in network discovery.

### Step 12

Hospital A asks:

> "I need an oxygen cylinder within 30 minutes."

### Step 13

MCP determines:

```text
authenticated organization
```

### Step 14

Inventory service:

```text
find available oxygen cylinders
```

### Step 15

Compliance:

```text
is asset eligible?
```

### Step 16

H3:

```text
prune unreachable/unlikely candidates
```

### Step 17

GIS:

```text
road route
ETA
traffic
```

### Step 18

MCP ranks:

```text
best feasible option
```

### Step 19

User receives proposal.

### Step 20

User approves.

### Step 21

PostgreSQL:

```text
AVAILABLE
       ↓
RESERVED_OFFCHAIN
```

### Step 22

Blockchain settlement begins asynchronously.

### Step 23

Payment begins.

### Step 24

Monitor updates.

### Step 25

Dispatch.

### Step 26

Delivery.

### Step 27

Loan:

```text
ACTIVE
```

### Step 28

Return.

### Step 29

Settlement.

### Step 30

Asset:

```text
AVAILABLE
```

### Step 31

Activity records the complete history.

---

# 55. Infrastructure

For the prototype:

```text
                         INTERNET
                            │
                            ▼
                    React / TypeScript
                            │
                            ▼
                       API Gateway
                            │
        ┌───────────────────┼────────────────────┐
        │                   │                    │
        ▼                   ▼                    ▼
   Auth Service        Core Service          MCP Service
        │                   │                    │
        │          ┌────────┼────────┐           │
        │          │        │        │           │
        │          ▼        ▼        ▼           ▼
        │       Inventory  Loan   Activity     Groq
        │
        ▼
   Supabase Auth
                            │
                            ▼
                    PostgreSQL/PostGIS
                            │
              ┌─────────────┼─────────────┐
              ▼             ▼             ▼
             GIS       Compliance     Blockchain
              │             │             │
             H3          mock signed     EVM
             OSRM        attestations    contract
                            │
                            ▼
                         Payment
                            │
                         Razorpay
```

---

# 56. Development architecture for your five-person team

Do not let five people edit everything.

Create clear ownership.

### Member 1 — Core / PostgreSQL

```text
database
schemas
migrations
organization
users
inventory
loans
reservations
activity
```

### Member 2 — GIS

```text
H3
PostGIS
OSRM
routing
candidate pruning
ETA
map response
```

### Member 3 — Blockchain

```text
smart contracts
wallet
deployment
events
transaction listener
blockchain adapter
```

### Member 4 — MCP / AI

```text
MCP server
tools
resources
prompts
Groq
orchestration
approval workflow
```

### Member 5 — Frontend/Auth/Payments

```text
React
authentication
dashboard
marketplace
monitor
activity
Razorpay adapter
```

You lead:

```text
architecture
API contracts
integration
CI/CD
security
PR review
main branch
```

---

# 57. Git strategy

Exactly as you proposed:

```text
main
│
├── feature/core-db
├── feature/gis
├── feature/blockchain
├── feature/mcp
└── feature/frontend
```

Nobody directly pushes to `main`.

Workflow:

```text
branch
 ↓
unit tests
 ↓
integration tests
 ↓
PR
 ↓
review
 ↓
merge
```

---

# 58. Every service needs an API contract BEFORE implementation

For every endpoint document:

```text
POST /reservations

Request
{
  asset_id,
  borrower_organization_id,
  duration
}

Response
{
  reservation_id,
  status,
  expires_at
}
```

And:

```text
Errors
401
403
404
409
422
500
```

This prevents the exact integration problems we encountered in the previous MVP.

---

# 59. Most important API boundaries

### Auth

```text
POST /auth/signup
POST /auth/login
POST /auth/logout
GET  /auth/me
```

### Organizations

```text
POST /organizations
GET /organizations/me
PATCH /organizations/me
```

### Inventory

```text
POST /equipment/types
POST /equipment/assets
GET  /equipment/assets
PATCH /equipment/assets/{id}
```

### Marketplace

```text
GET /marketplace
GET /marketplace/{asset_id}
```

### GIS

```text
POST /gis/candidates
POST /gis/route
POST /gis/best-option
```

### Compliance

```text
POST /compliance/verify
GET /compliance/{asset_id}
```

### MCP

```text
POST /mcp/chat
```

### Reservation

```text
POST /reservations
GET /reservations/{id}
POST /reservations/{id}/cancel
```

### Loan

```text
POST /loans
GET /loans/{id}
GET /loans
```

### Blockchain

```text
POST /blockchain/commit
GET /blockchain/transactions/{loan_id}
```

### Payment

```text
POST /payments/order
POST /payments/verify
POST /payments/webhook
```

### Activity

```text
GET /activity
```

---

# 60. System of record — this must be explicit

This is another architectural principle we should freeze.

### PostgreSQL

```text
Operational truth
```

### Blockchain

```text
Contractual / immutable transaction truth
```

### GIS

```text
Spatial computation
```

### MCP

```text
Decision/orchestration layer
```

### Razorpay

```text
Payment execution truth
```

### HFR

```text
External facility identity/verification source
```

That is clean.

---

# 61. What should NOT be stored on blockchain

Never put:

```text
patient information
medical records
passwords
full inventory
exact private hospital data
payment credentials
large GIS payloads
```

on-chain.

Instead:

```text
PostgreSQL
     │
     └── record
          │
          ▼
      SHA-256/hash
          │
          ▼
      blockchain
```

The chain can preserve proof that the agreed state existed.

---

# 62. Compliance microservice

For the prototype:

```text
Compliance Service
        │
        ├── HFR-like facility attestation
        ├── BMMP-like maintenance attestation
        └── calibration attestation
```

Each response contains:

```text
payload
issuer
timestamp
expiry
payload_hash
signature
```

Then SANJEEVANI verifies:

```text
signature
+
expiry
+
asset identity
```

This demonstrates the architecture without falsely claiming government connectivity.

---

# 63. Security architecture

Minimum:

```text
HTTPS
JWT
RBAC
organization-level authorization
PostgreSQL constraints
parameter validation
rate limiting
audit logs
secret management
wallet signing isolation
webhook signature verification
```

Most importantly:

> **The frontend must never be trusted to tell the backend which hospital the user belongs to.**

The backend obtains:

```text
authenticated user
      ↓
organization_id
      ↓
authorization
```

---

# 64. Blockchain security

Hospital private keys should never be stored as:

```text
private_key = "..."
```

in PostgreSQL.

For the MVP:

```text
MetaMask
```

can sign transactions.

Production:

```text
HSM / managed custody / secure signing service
```

depending on the governance model.

---

# 65. Business model

SANJEEVANI can become B2B SaaS.

## Tier 1 — Basic

```text
₹/month
```

Inventory management + network discovery.

## Tier 2 — Professional

```text
subscription
+
MCP
+
GIS optimization
+
transaction management
```

## Tier 3 — Enterprise

```text
custom
+
private network
+
hospital group integration
+
ABDM/HFR integration
+
analytics
+
compliance
+
SLA
```

Potential additional revenue:

```text
transaction fee
premium GIS
enterprise integrations
analytics
API access
network participation
```

But **do not invent a pricing figure yet**.

We need customer interviews and unit economics.

---

# 66. Network effect

This is one of SANJEEVANI's strongest business characteristics.

One hospital alone:

```text
limited value
```

Ten hospitals:

```text
more inventory
+
more demand
```

100 hospitals:

```text
much larger resource pool
```

Therefore:

```text
Hospital participation
        ↓
Network inventory
        ↓
Higher probability of successful match
        ↓
Higher hospital value
        ↓
More hospitals join
        ↓
Network becomes stronger
```

That's a genuine network effect.

---

# 67. Impact

Potential impact areas:

### Clinical

Reduce time spent searching for scarce equipment.

### Operational

Increase utilization of underused assets.

### Economic

Reduce unnecessary equipment purchases/rentals where sharing is feasible.

### Geographic

Connect facilities beyond their immediate administrative boundary.

### Trust

Provide an auditable transaction history between independent organizations.

### Digital infrastructure

Create a machine-readable resource-sharing layer on top of healthcare facilities.

---

# 68. But we must not claim clinical outcomes yet

We cannot say:

> "SANJEEVANI will save X lives."

We don't have evidence.

Instead:

> **SANJEEVANI is designed to reduce coordination and discovery latency for inter-hospital resource sharing.**

Then conduct experiments measuring:

```text
time-to-discovery
time-to-proposal
time-to-reservation
route ETA accuracy
reservation failure rate
equipment utilization
transaction completion rate
```

Those become scientifically measurable outcomes.

---

# 69. The right research evaluation

For the final project, compare:

### Baseline

```text
Manual hospital search
```

versus:

```text
SANJEEVANI
```

Measure:

```text
T1 = equipment discovery time
T2 = feasible hospital identification time
T3 = reservation time
T4 = transaction confirmation time
T5 = route ETA error
T6 = failed reservation rate
T7 = equipment utilization
```

Then demonstrate:

```text
manual workflow
        VS
SANJEEVANI workflow
```

That is much stronger than merely showing a blockchain transaction on a screen.

---

# 70. Future research

## Phase 1

Prototype:

```text
PostgreSQL
H3
OSRM
MCP
mock compliance
local EVM
mock payment
```

## Phase 2

Real integrations:

```text
HFR
real routing/traffic
Razorpay
production authentication
```

## Phase 3

Consortium:

```text
permissioned EVM
multiple institutional validators
```

## Phase 4

IoT:

```text
equipment sensors
     ↓
telemetry
     ↓
equipment health
```

## Phase 5

Predictive availability:

```text
historical demand
     ↓
forecast
     ↓
"Hospital B likely to have ventilator available tomorrow"
```

## Phase 6

Emergency corridors:

```text
hospital
 ↓
ambulance
 ↓
traffic
 ↓
equipment
 ↓
priority routing
```

---

# 71. The ultimate SANJEEVANI architecture

This is the diagram I would now put into the master design document:

```text
                              SANJEEVANI
                     "We care when even seconds count"
                                      │
                                      ▼
                             ┌────────────────┐
                             │   FRONTEND     │
                             │ React / TS     │
                             └───────┬────────┘
                                     │
                                     ▼
                           ┌─────────────────────┐
                           │ AUTHENTICATION      │
                           │ Supabase Auth       │
                           └─────────┬───────────┘
                                     │
                                     ▼
                         ┌────────────────────────┐
                         │ API / APPLICATION LAYER│
                         └───────────┬────────────┘
                                     │
              ┌──────────────────────┼──────────────────────┐
              │                      │                      │
              ▼                      ▼                      ▼
       ┌─────────────┐        ┌─────────────┐       ┌──────────────┐
       │ CORE SERVICE│        │ MCP SERVICE │       │ PAYMENT      │
       │             │        │             │       │ SERVICE      │
       └──────┬──────┘        └──────┬──────┘       └──────┬───────┘
              │                      │                      │
              │               ┌──────┼───────┐              ▼
              │               │      │       │          Razorpay
              │               ▼      ▼       ▼
              │             GIS  Compliance Blockchain
              │               │      │       │
              │               │      │       ▼
              │               │      │   Smart Contract
              │               │      │
              └───────────────┼──────┘
                              ▼
                    ┌────────────────────┐
                    │ PostgreSQL         │
                    │ + PostGIS          │
                    │                    │
                    │ Organizations      │
                    │ Users              │
                    │ Assets             │
                    │ Reservations       │
                    │ Loans              │
                    │ Payments           │
                    │ Activity           │
                    │ Compliance         │
                    └─────────┬──────────┘
                              │
                 ┌────────────┼────────────┐
                 ▼            ▼            ▼
                H3           OSRM      External APIs
                 │            │
                 └──────┬─────┘
                        ▼
                 FEASIBILITY ENGINE
                        │
                        ▼
                 MCP BEST OPTION
                        │
                        ▼
                  USER APPROVAL
                        │
             ┌──────────┴──────────┐
             ▼                     ▼
      OFF-CHAIN RESERVATION   BLOCKCHAIN
             │                COMMITMENT
             │                     │
             └──────────┬──────────┘
                        ▼
                    DISPATCH
                        │
                        ▼
                     DELIVERY
                        │
                        ▼
                      ACTIVE
                        │
                        ▼
                      RETURN
                        │
                        ▼
                    SETTLEMENT
                        │
                        ▼
                   AVAILABLE
```

---

# 72. The most important conceptual correction

After everything we've discussed, I would define SANJEEVANI in four layers:

```text
┌─────────────────────────────────────┐
│ 1. NETWORK                          │
│ Hospitals + verified resources      │
├─────────────────────────────────────┤
│ 2. INTELLIGENCE                     │
│ MCP + GIS + compliance              │
├─────────────────────────────────────┤
│ 3. OPERATIONS                       │
│ Reservation + dispatch + monitoring │
├─────────────────────────────────────┤
│ 4. TRUST                            │
│ Blockchain + payment settlement     │
└─────────────────────────────────────┘
```

And this is the sentence I would use when a judge asks:

### "So what exactly is SANJEEVANI?"

> **SANJEEVANI is a B2B SaaS resource-sharing network that transforms independent hospitals from isolated equipment inventories into a coordinated, trusted resource grid. Its MCP-based orchestration layer discovers and verifies available equipment, uses H3 and road-network intelligence to identify the fastest feasible source, reserves the resource immediately off-chain, and asynchronously records the inter-hospital contractual state on blockchain while conventional INR payment infrastructure handles monetary settlement.**

That is a **much stronger answer** than:

> "It's a blockchain-based healthcare platform."

---

# 73. And what makes it "first-of-its-kind"?

I would **not** say "the first in the world" or "the first in India." We do not have evidence sufficient to establish that.

Instead:

> **SANJEEVANI's proposed novelty is the integration of verified facility identity, cross-hospital resource discovery, AI orchestration, H3-based candidate pruning, road/traffic-aware feasibility, immediate off-chain reservation and blockchain-backed inter-organizational settlement into a single hospital resource-sharing workflow.**

That is defensible.

The distinction matters because India's existing systems already demonstrate equipment management, GIS, transfers and centralized inventory; ABDM already provides a verified facility registry. ([Ayushman Bharat Digital Mission][5])

**SANJEEVANI's innovation claim should therefore be about the orchestration and exchange layer, not about inventing each underlying technology.**

---

# 74. Final architecture decision — freeze this

If I were acting as your senior architect, I would now freeze the following:

| Component                   | SANJEEVANI decision                                    |
| --------------------------- | ------------------------------------------------------ |
| Product                     | B2B healthcare resource-sharing SaaS                   |
| Core problem                | Inter-hospital equipment discovery + feasible exchange |
| Database                    | PostgreSQL                                             |
| Spatial DB                  | PostGIS                                                |
| Spatial indexing            | H3                                                     |
| Routing MVP                 | OSRM + OpenStreetMap                                   |
| Production traffic          | Traffic-aware routing provider                         |
| AI                          | MCP + Groq                                             |
| MCP role                    | Orchestration, not database ownership                  |
| MCP tools                   | Small, typed, permission-controlled                    |
| MCP resources               | Authorized contextual data                             |
| MCP prompts                 | Reusable workflows                                     |
| Auth                        | Supabase Auth for prototype                            |
| Facility identity           | ABDM HFR integration/adapter                           |
| Compliance                  | Signed mock-attestation microservice                   |
| Reservation                 | PostgreSQL transactional optimistic lock               |
| Blockchain MVP              | Local Hardhat EVM                                      |
| Public demo                 | Sepolia if desired                                     |
| Production blockchain       | Permissioned EVM/consortium architecture               |
| Hospital wallet             | One primary wallet per organization initially          |
| Hospital = blockchain node? | **No**                                                 |
| Blockchain role             | contractual state, integrity, audit trail              |
| INR payment                 | Conventional payment infrastructure                    |
| Payment MVP                 | Mock provider                                          |
| Payment production          | Razorpay/UPI integration                               |
| UPI                         | Intent/QR; AutoPay where appropriate                   |
| Crypto payment              | **Not core**                                           |
| Patient data                | **Never on blockchain**                                |
| Frontend                    | React + TypeScript                                     |
| Backend                     | FastAPI/Python                                         |
| SaaS tenancy                | organization-based                                     |
| Private data                | organization-scoped                                    |
| Public network data         | controlled discovery                                   |
| Primary IDs                 | UUIDs                                                  |
| Blockchain tx hash          | unique external reference, not PK                      |
| Main branch                 | protected                                              |
| Development                 | feature branches + PR                                  |
| Testing                     | unit → integration → end-to-end                        |
| Prototype priority          | functionality over polish                              |

---

## The deepest architectural insight

The real SANJEEVANI is not:

```text
AI + GIS + Blockchain + PostgreSQL
```

That is just a technology stack.

The real system is:

```text
             FRAGMENTED CAPACITY
                     ↓
            VERIFIED NETWORK
                     ↓
           REAL-TIME DISCOVERY
                     ↓
           SPATIAL FEASIBILITY
                     ↓
             AI ORCHESTRATION
                     ↓
           INSTANT RESERVATION
                     ↓
          TRUSTED TRANSACTION
                     ↓
             PAYMENT + LOGISTICS
                     ↓
              AUDIT + SETTLEMENT
```

**That is the product.**

And the strongest scientific/product hypothesis for SANJEEVANI is now:

> **Can a trusted, AI-orchestrated inter-hospital resource-sharing network reduce the time and failure rate involved in locating and securing critical medical equipment compared with conventional fragmented coordination?**

That is measurable.

That is researchable.

That is commercially understandable.

And, importantly, **we can actually build and demonstrate it without pretending that every underlying component is novel.**

The next engineering step should therefore **not** be writing more code immediately. It should be freezing the **API contracts + PostgreSQL ER model + service boundaries + state machines** above. Once those four artifacts are locked, the five branches can be developed independently and merged without recreating the integration chaos we had in the MongoDB/Ganache MVP.

[1]: https://www.cdac.gov.in/index.aspx?id=product_details&productId=e-UpkaranEquipmentMaintenanceandManagementSystem%28EMMS%29&utm_source=chatgpt.com "Product Information"
[2]: https://www.sciencedirect.com/science/article/pii/S0166361520305248?utm_source=chatgpt.com "Blockchain in healthcare: A systematic literature review, synthesizing framework and future research agenda - ScienceDirect"
[3]: https://www.sciencedirect.com/science/article/pii/S1877050924002187?utm_source=chatgpt.com "Challenges and opportunities of digitalization in the healthcare supply chain: A literature review - ScienceDirect"
[4]: https://www.sciencedirect.com/org/science/article/pii/S2291969425000237?utm_source=chatgpt.com "Smart Contracts and Shared Platforms in Sustainable Health Care: Systematic Review - ScienceDirect"
[5]: https://abdm.gov.in/health-facilities?utm_source=chatgpt.com "NHA | Official website Ayushman Bharat Digital Mission"
[6]: https://www.cdac.in/index.aspx?id=product_details&productId=e-UpkaranEquipmentMaintenanceandManagementSystem%28EMMS%29&utm_source=chatgpt.com "Product Information"
[7]: https://pubmed.ncbi.nlm.nih.gov/36426330/?utm_source=chatgpt.com "Competence-Based Assessment of Biomedical Equipment Management and Maintenance System (e-Upkaran) Using Benefit Evaluation Framework."
[8]: https://www.postgis.net/?utm_source=chatgpt.com "PostGIS"
[9]: https://h3geo.org/docs/?utm_source=chatgpt.com "Introduction | H3"
[10]: https://developers.google.com/maps/documentation/routes/config_trade_offs?utm_source=chatgpt.com "Set the level of traffic data  |  Routes API  |  Google for Developers"
[11]: https://docs.mapbox.com/api/navigation/directions/?utm_source=chatgpt.com "Directions API | API Docs | Mapbox"
[12]: https://modelcontextprotocol.io/specification/2025-06-18/server/index?utm_source=chatgpt.com "Overview - Model Context Protocol"
[13]: https://modelcontextprotocol.io/specification/2025-06-18/server/tools?utm_source=chatgpt.com "Tools - Model Context Protocol"
[14]: https://razorpay.com/docs/payments/payment-methods/upi/?utm_source=chatgpt.com "Accept UPI Payments with Razorpay | Razorpay Docs"
[15]: https://razorpay.com/docs/payments/payment-gateway/s2s-integration/recurring-payments/upi/?preferred-country=US&utm_source=chatgpt.com "UPI Autopay | Razorpay Docs"
[16]: https://razorpay.com/pricing/?client_id=117944100.1781308802&session_id=1781308802&utm_source=chatgpt.com "Payment Gateway Charges - Simple & Transparent Pricing"
[17]: https://supabase.com/pricing?utm_source=chatgpt.com "Pricing & Fees | Supabase"
[18]: https://firebase.google.com/docs/auth?utm_source=chatgpt.com "Firebase Authentication"
