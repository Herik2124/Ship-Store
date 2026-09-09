# Ship Store

Ship Store is a web-based procurement and vendor-management system for general utility goods required on ships.

The system helps ships raise demands for essential items, receive quotations from multiple vendors, compare quotations, select a vendor, create an order, track delivery, and confirm receipt of goods.

## Project Information

- Project Code: AHM_2026_03
- Frontend: Oracle Redwood
- Backend: Oracle ADF
- Database: Oracle Database
- Source Control: GitHub

## Problem Statement

Ships require utility supplies such as cleaning materials, stationery, electrical items, maintenance supplies, safety items, basic tools, and pantry supplies.

Managing these requirements manually makes it difficult to compare vendor quotations, track orders, monitor deliveries, and ensure that supplies are received on time.

Ship Store centralizes this procurement process.

## User Roles

### Ship User

- Creates and submits utility-item demands
- Adds item details, quantities, required delivery date, location, and notes
- Views quotations received for a demand
- Tracks selected orders and delivery status
- Confirms receipt of delivered goods

### Vendor User

- Views available demands
- Submits quotations for demand items
- Provides item price, available quantity, expected delivery date, delivery charges, payment terms, and conditions
- Updates delivery progress

### Admin User

- Creates, updates, activates, and deactivates ships and vendors
- Monitors all demands, quotations, orders, and deliveries
- Selects the appropriate vendor after quotation comparison
- Views procurement, delivery, and vendor-performance reports

## Core Business Flow

```text
Ship creates demand
    ↓
Active vendors receive/view demand
    ↓
Vendors submit quotations
    ↓
User compares quotations
    ↓
User selects vendor
    ↓
Purchase order is created
    ↓
Vendor updates delivery status
    ↓
Ship confirms receipt
    ↓
Admin dashboard and reports are updated
