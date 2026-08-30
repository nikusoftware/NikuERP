# Niku ERP

**Niku ERP** is an Enterprise Resource Planning (ERP) solution designed to streamline business operations, automate workflows, and provide end-to-end visibility across your entire organization. Built on top of robust architecture and financial management principles, Niku ERP incorporates all core capabilities and enterprise-grade features inspired by **MixERP**.

---

## 🌟 Key Features & Functional Modules

### 🏦 1. Core Financials & Accounting
* **General Ledger (GL):** Multi-currency support, flexible chart of accounts, automated journal entries, and customizable financial periods.
* **Accounts Payable (AP) & Receivables (AR):** Managing vendor invoices, payment scheduling, customer invoicing, aging reports, and payment tracking.
* **Bank Reconciliation:** Multi-bank account management, electronic bank statement imports, and automated reconciliation rules.
* **Taxation Management:** Flexible tax rules, VAT/GST compliance, multi-jurisdiction tax configurations, and tax reporting.
* **Fixed Assets Management:** Asset tracking, multi-method depreciation calculation, asset write-offs, and transfers.
* **Financial Reporting:** Real-time generation of Balance Sheets, Profit & Loss Statements, Trial Balances, Cash Flow Statements, and custom financial ledgers.

### 📦 2. Inventory & Warehouse Management
* **Multi-Warehouse Support:** Manage stock across multiple locations, warehouses, bins, and racks seamlessly.
* **Stock Movements & Transfers:** Track inter-warehouse stock transfers, stock adjustments, and inventory write-offs.
* **Item Master & Variants:** Item category hierarchies, unit of measure (UOM) conversions, batch/lot tracking, and serial number tracking.
* **Reorder Level & Stock Valuation:** Automatic re-order level alerts, FIFO, LIFO, and Weighted Average stock valuation methods.
* **Barcode & Label Printing:** Integrated barcode creation and scanning support for fast inventory handling.

### 🛒 3. Sales & Order Management
* **Lead & Quotation Management:** Create and manage sales leads, generate quotations, and convert quotes into sales orders.
* **Sales Orders & Invoicing:** Complete order-to-cash lifecycle tracking, invoice generation, credit memos, and partial deliveries.
* **Point of Sale (POS):** Built-in web-based POS interface for retail environments with offline capabilities, register management, and barcode scanner integration.
* **Pricing & Discount Rules:** Flexible multi-tier pricing strategies, customer group discounts, volume discounts, and promotional offers.
* **Customer Relationship Management (CRM):** Customer history tracking, contact management, and interaction logs.

### 🛍️ 4. Purchasing & Procurement
* **Purchase Requisitions & Orders:** Create purchase requests, issue Purchase Orders (PO) to vendors, and manage PO approvals.
* **Goods Receipt Notes (GRN):** Track incoming shipments, match GRNs with purchase orders and vendor invoices (Three-Way Matching).
* **Vendor Management:** Vendor profiles, performance tracking, payment terms configuration, and credit management.
* **Purchase Returns:** Seamless handling of debit notes and vendor return authorizations.

### 👥 5. Human Resources & Payroll Management
* **Employee Information System (EIS):** Centralized repository for employee records, documents, contracts, and department structures.
* **Attendance & Leave Management:** Leave requests, approval workflows, holiday calendars, and shift management.
* **Payroll Processing:** Automated salary calculations, deductions, bonuses, tax withholdings, and pay stub generation.

### 🏢 6. Enterprise Administration & Security
* **Role-Based Access Control (RBAC):** Granular permission settings down to entity, module, and feature levels.
* **Multi-Company & Multi-Branch:** Multi-tenant architecture supporting multiple legal entities, divisions, and branches in a single instance.
* **Audit Trail & Logging:** Comprehensive system activity logs, transaction histories, and user audit trails.
* **Multi-Currency & Multi-Language:** Built-in localization support for international business operations.

### 🛠️ 7. Analytics, Reporting & Customization
* **Custom Report Builder:** Visual report designer for generating custom tabular and visual reports.
* **Interactive Dashboards:** Customizable real-time KPI widgets and executive summaries.
* **Extensible Architecture:** RESTful API support for integrations with third-party software (e-commerce, payment gateways, CRM).
* **Data Import/Export:** Export and import utilities supporting Excel, CSV, PDF, and JSON formats.

---

## 🚀 Getting Started

### Prerequisites
- Node.js / Python / .NET Core runtime (depending on deployment setup)
- PostgreSQL / SQL Server / MySQL Database Server

### Quick Installation
```bash
# Clone the Niku ERP repository
git clone [https://github.com/your-org/niku-erp.git](https://github.com/your-org/niku-erp.git)

# Navigate into project directory
cd niku-erp

# Install dependencies
npm install  # or pip install -r requirements.txt

# Run initial setup database migrations
npm run db:migrate

# Start the application server
npm start
