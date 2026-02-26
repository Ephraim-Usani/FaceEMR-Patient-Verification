# FaceEMR — Patient Face Verification for Electronic Medical Records

> **Facial recognition module integrated into hospital EMR systems to eliminate patient identification errors in high-volume African hospitals**

[![Demo](https://img.shields.io/badge/▶%20Watch%20Demo-Google%20Drive-red)](https://drive.google.com/file/d/1TyRoM0jwDjZVKknvTwyO7iKNGDKREJut/view?usp=drive_link)
[![CPU Only](https://img.shields.io/badge/Deployment-CPU%20Only-orange)]()
[![Python](https://img.shields.io/badge/Python-3.8+-yellow)]()
[![EMR Integration](https://img.shields.io/badge/Integration-EMR%20System-green)]()

---

## The Clinical Problem

In high-volume hospitals across Africa, **patient misidentification is a serious and preventable safety risk**.

The core issue is simple: **many patients share the same name**.

In Nigeria and across Sub-Saharan Africa, common names like Emmanuel Okonkwo, Chukwuemeka Nwosu, or Fatima Mohammed appear hundreds of times across hospital patient registries. When a busy nurse or records officer retrieves a file by name search, there is a real risk of:

- Opening the wrong patient record
- Administering medication intended for another patient
- Filing X-ray or lab results in the wrong chart
- Performing procedures based on incorrect medical history

These are not hypothetical risks — they happen daily in under-resourced hospitals with paper-heavy or basic EMR systems.

**FaceEMR eliminates name-based confusion entirely.**

---

## What It Does

FaceEMR adds a facial recognition verification layer to any EMR system:

| Step | What Happens |
|------|-------------|
| **Registration** | Patient's face is captured and stored against their unique EMR record during first visit |
| **Verification** | On return visits, camera captures patient's face at the records desk |
| **Instant Match** | System matches face to the correct EMR record — regardless of name similarity |
| **Alert System** | Flags mismatches and prevents wrong record retrieval |
| **Fallback** | Manual override available for staff when needed |

**Result: The right file opens for the right patient, every time.**

---

## Why This Matters in Africa Specifically

- Common naming conventions across ethnic groups create high rates of name duplication
- Many patients do not carry formal ID documents
- Overcrowded hospitals process hundreds of patients daily under time pressure
- Basic EMR systems rely entirely on name and date-of-birth search
- A simple, camera-based verification system is practical and affordable

---

## Technical Approach

- **Face Detection:** Deep learning-based face detection pipeline
- **Recognition:** Face embedding comparison against stored patient profiles
- **Integration:** API-based integration with existing EMR systems
- **Hardware:** Standard webcam or Phone Camera — no specialized equipment required
- **Deployment:** CPU-only, runs on existing hospital computers
- **Privacy:** Face data stored locally within the hospital system — no cloud dependency

---
## Demo

[▶ Watch FaceEMR in action](https://drive.google.com/file/d/1TyRoM0jwDjZVKknvTwyO7iKNGDKREJut/view?usp=drive_link)

> The demo shows real-time fetal plane detection, auto-freeze, and automatic caliper placement for BPD, AC, and FL measurements.

## Privacy & Ethics

FaceEMR stores all biometric data locally within the hospital's own infrastructure. No patient data is transmitted externally. The system is designed to comply with Nigerian data protection regulations (NDPR) and can be adapted for other regulatory frameworks.

---

## Built By

**Ephraim Usani** — First-Class Radiographer & Clinical AI Engineer, Lagos, Nigeria

[LinkedIn](https://www.linkedin.com/in/ephraim-usani) | [GitHub](https://github.com/Ephraim-Usani)

> *"I saw this problem firsthand — a patient's X-ray filed in the wrong chart, a treatment decision made on incomplete history. I built FaceEMR because this problem is solvable with technology that already exists."*
