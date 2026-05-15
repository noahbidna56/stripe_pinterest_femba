Stripe Agentic Board Checkout

One tap. Every item. One checkout.
Stripe Agentic Board Checkout lets Pinterest users convert any curated board into a completed multi-merchant purchase in a single session — with full price, merchant, and delivery transparency before a single charge is made.


What It Does
Pinterest users are the highest-intent shoppers on the internet — they curate exactly what they want to own. But the path from saved pin to completed purchase has always been broken: eight merchants, eight checkout flows, eight opportunities to abandon, and no way to see the total picture first.
Agentic Board Checkout closes that loop. An AI agent reads the board, matches every purchasable item to a verified merchant in Stripe's network, and surfaces a single unified approval screen showing item, merchant, price, and estimated delivery date — all at once. The user approves or removes items, confirms once, and Stripe handles every payment simultaneously via Shared Payment Tokens.

Key Features

🛒 One-tap multi-merchant checkout — Convert an entire Pinterest board into a purchase in one session, across any number of merchants, without visiting a single merchant site.
🤖 AI-powered item matching — Visual and semantic analysis identifies each pinned product and matches it to the closest live catalog item from a verified Stripe merchant at current prices.
👁️ Full transparency before commitment — The approval screen shows every item, price, merchant, and estimated delivery window before any CTA. Total cost is always visible.
🔐 Shared Payment Tokens — Your card number is never shared with any merchant. Stripe issues a scoped, per-merchant token for each transaction and processes everything invisibly underneath.
⚡ Unified order summary — One receipt, one email, covering every merchant and item — while individual merchant confirmation emails still go out per existing flows.


Tech Stack
LayerTechnologyFrontendReact 19 + Vite 8StylingTailwind CSS v4Animationscanvas-confettiLintingESLint 10 + react-hooks + react-refreshBuildVite (ES Modules)FontsDM Sans + DM Serif Display (Google Fonts)

Getting Started
Prerequisites

Node.js ≥ 18
npm ≥ 9

Install & Run
bash# Clone the repo
git clone <repo-url>
cd stripe-agentic-board

# Install dependencies
npm install

# Start dev server
npm run dev
The app will be available at http://localhost:5173.
Other Scripts
bashnpm run build     # Production build → dist/
npm run preview   # Preview the production build locally
npm run lint      # Run ESLint across all .js/.jsx files

User Journey
StepScreenWhat Happens1Pinterest board view"Buy My Board" button appears top-right2Loading stateAI agent scans board and matches items (P50 ≤1.8s)3Approval screenScrollable cards — item, merchant, price, delivery — with deselect toggles4ConfirmationStripe payment UI — saved method, biometric/PIN auth, one final tap5Order summaryUnified receipt + merchant confirmation emails

North Star Metric
Board-to-Purchase Conversion Rate — the percentage of "Buy My Board" sessions that result in at least one completed transaction.
90-Day Launch Targets
MetricTargetBoard-to-Purchase Conversion Rate≥ 15%Average Items per Completed Order≥ 4 itemsGross Payment Volume (agentic board)$50MAI Match Rate≥ 75%Dispute & Chargeback Rate≤ 0.6%Approval Screen Load Time (P95)≤ 4.0s

Team
MGMT 275 · Assignment 5 — Stripe Agentic Checkout Team Submission

License
Private — for course submission and demonstration purposes only.
