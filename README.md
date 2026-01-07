# Invoice-to-Odoo Automation (UiPath RPA)

## 📌 Project Overview
This project is an **end-to-end Invoice Processing automation** built using **UiPath**, designed to extract data from PDF invoices and upload it into **Odoo ERP**.

The automation demonstrates a real-world RPA use case combining **Document Understanding**, **API integration**, and **ERP interaction**, implemented following **REFramework best practices**.

---

## 🎯 Business Use Case
Manual invoice processing is time-consuming and error-prone.  
This automation simulates how RPA can:
- Read invoice PDFs
- Extract and validate structured data
- Perform currency conversion
- Upload clean data into an ERP system

---

## ⚙️ Process Flow
1. Invoice PDF files are provided as input
2. UiPath Document Understanding extracts invoice data
3. Extracted data is validated
4. Exchange rate is retrieved using an external API
5. Invoice values are converted to the target currency
6. Final data is uploaded into **Odoo ERP**
7. Process completes with success or exception handling

---

## 🛠️ Technologies & Tools Used
- **UiPath Studio**
- **REFramework**
- **UiPath Document Understanding**
- **REST API Integration**
  - Exchange Rate API: https://exchangerate.host/
- **Odoo ERP**
- **PDF Invoice Processing**

---

## 📂 Input
- PDF invoices containing:
  - Invoice details (date, total, currency)
  - Line items (product, quantity, unit price)

---

## 📤 Output
- Invoice records successfully created in **Odoo ERP**
- Structured and validated invoice data
- Converted currency values based on real-time exchange rates

---

## 🧠 Key Features
- Modular and scalable REFramework design
- Document Understanding with structured extraction
- API integration for real-time data enrichment
- Error handling and logging
- Ready-to-extend for queues, emails, or storage buckets

---

## 📎 Notes
- This project is built for **learning and portfolio purposes**
- Invoice data and ERP environment are used for demonstration only

---

## 👤 Author
**Yousif Monsif**  
Junior RPA Developer (UiPath)

---

## 🔗 Repository
Feel free to explore the workflows, suggest improvements, or use this project as a reference for similar RPA use cases.
