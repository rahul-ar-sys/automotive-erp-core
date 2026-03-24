# Vehicle Showroom Enterprise Resource Planning (ERP)

An enterprise-grade management solution designed to streamline automotive showroom operations, synchronize multi-branch data, and provide high-level financial intelligence.


## 🚀 Core Capabilities

### 🛡️ Enterprise Security & Access
* **Role-Based Authentication**: Granular access control for staff and administrators to ensure data integrity.
* **Session Management**: Secure server-side state handling for all administrative actions.

### 🚘 Intelligent Inventory Lifecycle
* **Status Tracking**: Real-time monitoring of vehicle states from "Intake" to "Booked" and "Delivered".
* **Detailed Specifications**: Comprehensive logging of models, variants, and registration data.

### 👥 Customer Relationship Management (CRM)
* **Lead Management**: Digital tracking of customer inquiries and contact profiles.
* **Transaction History**: Secure logging of payment modes (Cheque, Net-Banking, Finance) and unique booking identifiers.

### 📈 Financial & Operational Intelligence
* **Multi-Branch Analytics**: Comparative reporting on budget allocation vs. actual turnover across different geographic locations.
* **Automated Reporting**: Built-in engines for generating Profit & Loss statements and Sales-to-Service ratios.
* **Audit Logging**: System-generated activity logs to track administrative changes and maintain a transparent audit trail.

## 🛠️ Technical Architecture

* **Logic Layer**: PHP 7.x (Procedural & Functional modules).
* **Data Persistence**: MySQL (Relational schema optimized for ACID compliance).
* **Interface Layer**: Custom CSS3 UI framework with jQuery-enhanced asynchronous interactions.
* **Data Interop**: Support for advanced data formats including JSON, CSV, and Apache Parquet for large-scale reporting.

## ⚙️ Deployment & Configuration

1.  **Environment**: Optimized for LAMP/WAMP stacks.
2.  **Database Initialisation**:
    * Create a schema titled `vsms`.
    * Execute `db_bkp.sql` to initialize core entities (Branch, Staff, Vehicle, Customer).
3.  **Directory Mapping**: Ensure the `util/` directory is accessible for core functions and session handling.
4.  **Credentialing**: Default administrative access is provisioned via the `login_table` for initial setup.

## 📁 System Structure
* `BranchManagement/`: Financial oversight and performance analytics.
* `CustomerManagement/`: Booking engines and registration workflows.
* `ShowroomManagement/`: Inventory control and personnel administration.
* `util/`: Core utility functions, database connectors, and security protocols.
