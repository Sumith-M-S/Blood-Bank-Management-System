# 🩸 Blood Bank Management System

A web-based Blood Bank Management System built using **PHP, MySQL, CSS, and HTML**.  
It allows donors to register, users to request blood, and admins to manage blood inventory efficiently.

---

## 🚀 Features
- 🏥 **Admin Panel**: Manage donors, blood groups, and requests.  
- 🧑‍🤝‍🧑 **Donor Registration**: Add new blood donors with details.  
- 🔍 **Search Functionality**: Search for donors by blood group.  
- 📊 **Inventory Management**: Keep track of available blood.  
- 📩 **Request Blood**: Patients can request specific blood groups.  
- 📢 **Awareness Pages**: Encourage and spread information about blood donation.  

---

## 🛠 Tech Stack
- **Frontend**: HTML, CSS  
- **Backend**: PHP  
- **Database**: MySQL  

---

## 📂 Project Structure

flowchart TD
    A[Homepage] --> B[Donor Registration - donate_blood.php]
    A --> C[Request Blood - need_blood.php]
    A --> D[Search Blood Group - search_blood_group.php]
    A --> E[Why Donate Blood - why_donate_blood.php]
    A --> F[About Us - about_us.php]
    A --> G[Contact Us - contact_us.php]

    B --> H[Save Data - savedata.php]
    C --> I[Database - blood requests]
    D --> J[Database - donor records]

    subgraph Admin Panel
        K[Manage Donors]
        L[Manage Requests]
        M[View Inventory]
    end

    H --> Admin Panel
    I --> Admin Panel
    J --> Admin Panel


---



## ⚙️ Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Sumith-M-S/Blood-Bank-Management-System.git
