# SeSPHR – A Methodology for Secure Sharing of Personal Health Records in the Cloud

**SeSPHR** is a secure, patient-centric platform for managing and sharing Personal Health Records (PHRs) in cloud environments. It ensures that only authorized users, such as healthcare professionals, family members, and insurance providers, can access sensitive health information, maintaining full data confidentiality and privacy through proxy re-encryption.



##  Project Purpose

The **Secure Sharing of Personal Health Records (SeSPHR)** project is designed to empower individuals to securely manage and share their electronic health records (PHRs) with authorized healthcare providers. It ensures the privacy, confidentiality, and integrity of sensitive health data in cloud environments.

This system facilitates:
- Secure, cloud-based access to personal health data  
- Better coordination between patients and healthcare professionals  
- Enhanced patient control over who can view or access their records  
- Confidential sharing and storage through strong security protocols  



## Project Scope

This project implements a digital platform for secure PHR sharing, supporting:

- **Strong Data Protection**  
  Advanced encryption and authentication to safeguard sensitive medical data from unauthorized access.

- **Role-Based Access Control**  
  Fine-grained access permissions are defined by the PHR owner (patient) to control who sees what.

- **Consent and Permission Management**  
  Patients can manage, grant, or revoke access to their records at any time.

- **Interoperability**  
  Standardized protocols and structured interfaces enable smooth data exchange between healthcare systems and providers.

- **Regulatory Compliance**  
  The system is designed with privacy principles in mind, aligning with healthcare data protection standards for the ethical and legal handling of records.

The platform focuses on both usability and security to support real-world healthcare collaboration while preserving individual privacy rights.

---

##  Key Features

- **Secure User Authentication** – Ensures that only registered and verified users can access PHR data.  
- **Granular Privacy Controls** – Allows PHR owners to define role-based and section-level access for different user categories.  
- **Strong Data Encryption** – Encrypts all health records before storage in the cloud.  
- **Audit Trail and Access Logs** – Logs every access and key operation for accountability.  
- **Interoperability and Integration** – Supports cloud deployment and browser-based access for diverse users.



## 🧩 System Modules

### 🔸 Cloud Server
Admin users securely log in and can perform actions such as:
- Authorize PHR Owners and PHR Users  
- View patient records and clinical reports  
- Manage login requests and access control tables  
- Monitor access logs and key operations  

### 🔸 View and Authorize Users
Admins can:
- View details of all registered users (username, email, address)  
- Grant or revoke user authorization  

### 🔸 PHR Owner
PHR Owners (patients) can:
- Register, log in, and view their profile  
- Add and manage patient health records  
- View key requests from users  
- View and manage clinical reports  

### 🔸 PHR User
PHR Users (e.g., doctors, family members) can:
- Register, log in, and view their profile  
- Request access keys to view clinical data  
- View access controls and granted reports  

## ✅ Getting Started

1. **Clone the Repository to Your Local Machine**

   ```bash
   git clone https://github.com/Bhupathi-Bhavana/SeSPHR-A-Methodology-for-Secure-Sharing-of-Personal-Health-Records-in-the-Cloud.git
   
2. **Set Up MySQL**
   
    - Open MySQL client
    - Create a new database (e.g., sesphr_db)
    - Import the provided Database.sql file located in the Database/ folder

3. **Deploy the Project Using Apache Tomcat**
   
    - Copy the project folder into the webapps/ directory of your Tomcat installation
    - Start the Tomcat server
    - Wait for the project to be deployed (usually accessible at: http://localhost:2020/SeSPHR)

4. **Access the Web Portal**
   
    - Open a browser and go to http://localhost:2020/SeSPHR
    - The login and registration interface should appear

6. **Register and Begin Using the System**

    - Choose to register either as a PHR Owner or a PHR User
    - PHR Owners (patients) can upload, manage, and share personal health records
    - PHR Users (e.g., doctors, family members) can request access to view clinical reports
    - After registration, log in with your credentials
    - Explore the user dashboard to securely manage and access health information according to your role
