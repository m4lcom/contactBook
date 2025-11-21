# 📒 Contact Agenda

**Agenda** is a console application developed in **Python** that allows you to manage contacts for both persons and companies.  
It includes features to add, delete, and display contacts, with persistence in a text file.

---

## 🚀 Features
- Add, delete, and view contacts.
- Support for **Person** and **Company** types.
- Search contacts by last name, DNI, company name, or CUIT.
- Show all registered persons.
- Data persistence in `Data.txt`.

---

## 🛠 Tech Stack
- **Python 3**
- Standard libraries: `os`, `datetime`

---

## 📦 Installation
Clone the repository and navigate to the project folder:

```bash
git clone https://github.com/m4lcom/agenda.git
cd agenda
```

---

## ▶️ Usage
Run the main script:

```bash
python agenda.py
```

Follow the on‑screen menu to:

Add a new person or company.

Delete an existing contact.

Search and display contacts.

Show all persons stored in the agenda.

---

## 🧩 Main Classes
Agenda Handles the main menu, lists of contacts, and file persistence.

Contact Base class for contacts. Includes methods to add and delete contacts.

Person (Contact) Extends Contact. Stores last name, name, DNI, address, birth date. Includes method dia_nacimiento(fecha) to calculate the day of birth.

Company (Contact) Extends Contact. Stores name, CUIT, address, foundation date. Includes method cuando_nacio(fecha) to show the foundation date.

---

## 🔄 Data Storage
Contacts are saved in a plain text file Data.txt. Each line contains the contact type and its attributes, separated by commas.

Example:

Código
Type: Person, Last Name: Perez, Name: Juan, DNI: 12345678, Address: Main Street 123, Birth Date: 1990/05/10
Type: Company, Name: ACME Corp, CUIT: 30-12345678-9, Address: Evergreen Avenue 742, Foundation Date: 2000/01/01

---

## 🤝 Contributing
Fork the repo

Create a branch (feature/my-change)

Commit your changes

Open a Pull Request

---

## 📜 License
MIT License – see LICENSE.

---

## 📬 Contact
[Email](malcom.foca@gmail.com)

[Linkedin](https://linkedin.com/in/malcom-foca)
