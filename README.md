# Patient Management System API 🏥

A robust, RESTful API built with **FastAPI** to manage patient records, featuring automated health metric calculations and persistent JSON storage.

## ✨ Features
* **Full CRUD Operations**: Create, Read, Update, and Delete patient profiles.
* **Automated BMI Logic**: Automatically calculates BMI and provides a health verdict (Underweight, Normal, Obese) using Pydantic computed fields.
* **Smart Sorting**: Sort patients dynamically by height, weight, or BMI.
* **Data Validation**: Strict type checking and validation for ages, heights, and weights.
* **Persistent Storage**: Records are maintained in a local `patients.json` database.

## 🛠️ Tech Stack
* **Framework**: [FastAPI](https://fastapi.tiangolo.com/)
* **Data Validation**: [Pydantic v2](https://docs.pydantic.dev/)
* **Language**: Python 3.10+

