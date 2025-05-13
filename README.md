# 📲 Doc_Tor – Government Document Guide App

> An intuitive Android application designed to help users **understand, access, and verify essential Indian government documents** — all in one place. Built using **Java + Android SDK**, with a clean UI and lightweight performance.

![Android](https://img.shields.io/badge/platform-Android-brightgreen)
![Java](https://img.shields.io/badge/language-Java-orange)
![Google Ads](https://img.shields.io/badge/integration-Google%20AdMob-yellow)


---

## 📌 About the App

Doc_Tor is a **centralized Android reference tool** that provides users with key information about common Indian government-issued documents such as:

- 🆔 Aadhaar Card  
- 🚗 Driving License  
- 🧾 Income Certificate  
- 🧒 Birth Certificate  
- ⚰️ Death Certificate  
- 📜 Caste Certificate  
- 🏠 Domicile Certificate

It helps users:
- Understand document formats
- Get guidance on application processes
- View requirements and eligibility
- Access links or embedded content for further help

---

## 🎯 Key Features

- 📑 One-click access to all major document guides
- 📱 Built using **native Android Java**
- 🎨 Lightweight UI with clean navigation
- 💵 Integrated with **Google AdMob** (AdView for monetization)
- ⚙️ Modular structure for adding more certificates

---

## 🛠 Tech Stack

| Component         | Technology                |
|------------------|---------------------------|
| Language          | Java                      |
| Platform          | Android (API 21+)         |
| IDE               | Android Studio            |
| Build System      | Gradle                    |
| Ads Integration   | Google Mobile Ads SDK     |
| UI Components     | XML Layouts               |

---

## 📂 App Structure

```plaintext
Doc_Tor/
├── app/src/main/java/com/karesantralis/doc_tor/
│   ├── AdharCard.java
│   ├── DrivingLicense.java
│   ├── BirthCertificate.java
│   ├── DeathCertificate.java
│   ├── IncomeCertificate.java
│   └── ... (other documents)
├── res/layout/
│   ├── activity_adhar_card.xml
│   ├── activity_driving_license.xml
│   └── ...
├── AndroidManifest.xml
