# Seedgen ERP - Enterprise Management System

A light, fast, enterprise-grade resource planning system engineered with PHP and the CodeIgniter framework. Seedgen ERP provides a unified platform to streamline organizational workflows, manage inventory/seed processing cycles, track financial logs, and oversee operational roles with minimal server overhead.

---

### 🚀 Core Features

*   **Modular Resource Tracking:** Comprehensive management modules designed to track production, raw materials, inventory state, and processing pipelines.
*   **Role-Based Access Control (RBAC):** Granular authorization and authentication layers separating administrative operations, inventory management, and view-only roles.
*   **Billing & Financial Reporting:** Integrated invoicing engines, ledger tracking, and automated transactional audit logs.
*   **Lightweight MVC Architecture:** Built on CodeIgniter's Model-View-Controller paradigm for high execution speed, fast page loads, and low footprint overhead.
*   **Dynamic Data Querying & Filters:** Filterable data tables for quick searching, record sorting, and generating CSV/PDF summary exports.

---

### 🛠️ Tech Stack & Architecture

| Layer | Technologies |
| :--- | :--- |
| **Backend Framework** | ![CodeIgniter](https://img.shields.io/badge/CodeIgniter-EF4223?style=flat-square&logo=codeigniter&logoColor=white) ![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white) |
| **Database Engine** | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) |
| **Frontend Layout** | HTML5, CSS3, JavaScript, jQuery, Bootstrap |
| **Environment Execution** | Apache Server (Xampp) |

---

### 💻 Local Installation & Setup Instructions

Follow these structured steps to deploy and run the application environment locally:

#### 1. Clone the Infrastructure
Clone the repository directly into your local web server's public directory (e.g., `C:\xampp\htdocs\` or `/var/www/html/`):
cd C:\xampp\htdocs
git clone [https://github.com/niralivachhani26/seedgen_erp_codeigniter.git](https://github.com/niralivachhani26/seedgen_erp_codeigniter.git)
cd seedgen_erp_codeigniter

#### 2. Create the Database
seedgen_erp_db

#### 3. Import the SQL Schema
#### 4. Configure Base URL Parameters
$config['base_url'] = 'http://localhost/seedgen_erp_codeigniter/';

#### 5. Configure Database Connections
(Open application/config/database.php and update your MySQL connection credentials:)

$db['default'] = array(

    'hostname' => 'localhost',
    
    'username' => 'root',
    
    'password' => '',
    
    'database' => 'seedgen_erp_db',
    
    'dbdriver' => 'mysqli',
    
);


#### 6. Launch the Local Application
http://localhost/seedgen_erp_codeigniter/
