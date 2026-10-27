# StayTransit — Admin Console (Standalone)

Standalone, fully self-contained administration dashboard for StayTransit with unified styling, compact executive spacing, white header blocks, and integrated segmented controls.

## Included Pages (20 Screens)

- **index.html**: Live Tracking & Reservations Management
- **merchant_management.html**: Merchant Profiles & Approval Management
- **partner_agents.html**: Travel Agents & Broker Commission Management
- **partner_corporate.html**: Corporate B2B Accounts & Negotiated Credit Lines
- **locations.html**: Operational Airport Hubs & Metropolitan Zones
- **service_rules.html**: Vehicle Classifications & Chauffeur Service Tiers
- **amenities.html**: Fleet Amenities & Onboard Experience Categories
- **audit_trail.html**: System Security Logs & Change Ledger
- **support_messages.html**: Customer Support Tickets & Inquiries
- **coupon_codes.html**: Promotional Campaigns & Coupon Discount Codes
- **fees_management.html**: Platform Fees, Surcharges & Regional Taxes
- **domain_service_type.html**: Root Mobility Service Types & Sub-Types
- **domain_service_assets.html**: Fleet Vehicles, Asset Classes & Capacities
- **domain_sales_tax.html**: Regional Jurisdiction Tax Configurations
- **reports_management.html**: Settlement Statements & Financial Reconciliation
- **feedback_management.html**: Passenger Reviews & Chauffeur Ratings
- **system_settings.html**: Global Admin Thresholds, Timezones & Currencies
- **legal_privacy_policy.html**: Passenger & Enterprise Privacy Disclosures
- **legal_terms_conditions.html**: User Terms & Partner Service Agreements
- **legal_user_agreement.html**: Passenger Agreements & Chauffeur Charters

## Styling & Self-Containment

- `admin-styles.css`: Complete admin design system with white header blocks, segmented control styling, data table rules, badges, and toolbars.
- `styles.css`: Base design tokens, typography, root variables, and color palettes.

This directory is completely standalone and can be moved or deployed anywhere without external file dependencies.

## Running Locally

```bash
# Using Python
python -m http.server 3000

# Using Node.js
npx serve -l 3000 .
```
