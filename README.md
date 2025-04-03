# Salesforce CRM Enhancement for Sales Pipeline Management

## 📌 Project Overview
This project aims to enhance the **Sales Pipeline Management** process using **Salesforce CRM** by automating sales workflows, improving data tracking, and providing insightful analytics for better decision-making.

## 🚀 Features Implemented
- **Automated Follow-ups**: Apex triggers to create follow-up tasks during sales negotiations.
- **Custom Objects & Relationships**: Implemented ‘Deal’ and ‘Sales Meeting’ objects with appropriate relationships.
- **Dynamic Data Updates**: Apex trigger to auto-update ‘Total Deal Value’ on Account records.
- **Lightning Components (LWC)**: Interactive UI components for better sales tracking.
- **Dashboard & Reports**: Real-time insights into deals, follow-ups, and revenue metrics.

## 🛠 Technologies Used
- **Salesforce Development**: Apex, SOQL, SOSL
- **Lightning Web Components (LWC)**
- **Salesforce Admin Tools**: Flows, Process Builder, Validation Rules
- **Version Control**: Git & GitHub

## 📂 Project Structure
```
📦 salesforce-crm-enhancement
 ┣ 📂 lwc                # Lightning Web Components
 ┣ 📂 apex-triggers      # Apex triggers for automation
 ┣ 📂 dashboards         # Reports & dashboards
 ┣ 📜 README.md          # Project documentation
 ┗ 📜 config.json        # Salesforce metadata configurations
```

## 🏗 Installation & Setup
1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/salesforce-crm-enhancement.git
   ```
2. Authenticate and connect to your Salesforce org:
   ```bash
   sfdx force:auth:web:login
   ```
3. Push the source code to your Salesforce org:
   ```bash
   sfdx force:source:push
   ```
4. Assign the permission set (if required):
   ```bash
   sfdx force:user:permset:assign -n SalesPipelineManager
   ```

## 📢 How to Contribute
- Fork the repository.
- Create a feature branch (`git checkout -b feature-name`).
- Commit your changes and push (`git push origin feature-name`).
- Open a pull request for review.

## 📜 License
This project is open-source and available under the **MIT License**.

## 📧 Contact
For any queries, feel free to reach out:  
📩 Email: abhishekstoicism123@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/satya-abhishek-jakkula-473855210/)

