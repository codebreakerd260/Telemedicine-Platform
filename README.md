# 🏥 Telemedicine Platform – UI + UX Documentation

This document combines all **UI screens** and **UX flows**, with direct links to the implementation (`code.html`) and previews (`screen.png`).

---

## 📌 Core Screens

### 👤 Patient Flow

1. **Patient Onboarding Screen**

   - Multilingual login/signup.
   - [View Code](./Core%20Screens/Patient%20Flow%20Screens/patient_onboarding_screen/code.html) | ![Preview](./Core%20Screens/Patient%20Flow%20Screens/patient_onboarding_screen/screen.png)
   - **UX Notes**: Breadcrumbs for multi-step flow, error states on login, success toast after signup.

2. **Symptom Input & Triage Screen**

   - Enter symptoms, AI suggests specialization.
   - [View Code](./Core%20Screens/Patient%20Flow%20Screens/symptom_input_%26_triage_screen/code.html) | ![Preview](./Core%20Screens/Patient%20Flow%20Screens/symptom_input_%26_triage_screen/screen.png)
   - **UX Notes**: Loading indicators while triage runs, clear error messages.

3. **Doctor List Screen**

   - Filter/search doctors by specialization, fee, ratings.
   - [View Code](./Core%20Screens/Patient%20Flow%20Screens/doctor_list_screen/code.html) | ![Preview](./Core%20Screens/Patient%20Flow%20Screens/doctor_list_screen/screen.png)
   - **UX Notes**: Strong CTA (“Book Appointment”), consistent Navbar.

4. **Video Consultation Screen**

   - Video + chat for consultations.
   - [View Code](./Core%20Screens/Patient%20Flow%20Screens/video_consultation_screen/code.html) | ![Preview](./Core%20Screens/Patient%20Flow%20Screens/video_consultation_screen/screen.png)
   - **UX Notes**: Smooth transitions in/out of call, status indicators.

5. **Prescriptions & Health Records Screen**

   - Secure digital records + prescriptions.
   - [View Code](./Core%20Screens/Patient%20Flow%20Screens/prescriptions_%26_health_records_screen/code.html) | ![Preview](./Core%20Screens/Patient%20Flow%20Screens/prescriptions_%26_health_records_screen/screen.png)
   - **UX Notes**: Tabbed navigation (Prescriptions / Records), data persistence.

6. **Medicine Availability Lookup**

   - Pharmacy search + stock info.
   - [View Code](./Core%20Screens/Patient%20Flow%20Screens/medicine_availability_lookup/code.html) | ![Preview](./Core%20Screens/Patient%20Flow%20Screens/medicine_availability_lookup/screen.png)
   - **UX Notes**: Card components for medicines, clear error/success states.

---

### 👨‍⚕️ Doctor Flow

1. **Doctor Onboarding Screen**

   - Registration + specialization.
   - [View Code](./Core%20Screens/Doctor%20Flow%20Screens/doctor_onboarding_screen/code.html) | ![Preview](./Core%20Screens/Doctor%20Flow%20Screens/doctor_onboarding_screen/screen.png)
   - **UX Notes**: Guided form, validation feedback.

2. **Patient Request Dashboard**

   - Manage patient consultations.
   - [View Code](./Core%20Screens/Doctor%20Flow%20Screens/patient_request_dashboard/code.html) | ![Preview](./Core%20Screens/Doctor%20Flow%20Screens/patient_request_dashboard/screen.png)
   - **UX Notes**: Sidebar navigation, loading skeletons.

3. **Doctor Video Consult Interface**

   - Consult + take notes + prescribe.
   - [View Code](./Core%20Screens/Doctor%20Flow%20Screens/doctor_video_consult_interface/code.html) | ![Preview](./Core%20Screens/Doctor%20Flow%20Screens/doctor_video_consult_interface/screen.png)
   - **UX Notes**: Contextual buttons (“Issue Prescription”), success confirmation.

4. **Patient History View**

   - Review full patient history.
   - [View Code](./Core%20Screens/Doctor%20Flow%20Screens/doctor_patient_history_view/code.html) | ![Preview](./Core%20Screens/Doctor%20Flow%20Screens/doctor_patient_history_view/screen.png)
   - **UX Notes**: Collapsible sections, tabs.

---

### 🏥 Admin / Hospital Flow

1. **Admin Doctor Management**

   - Manage doctor profiles + permissions.
   - [View Code](./Core%20Screens/Admin%20-%20Hospital%20Flow%20Screens/admin_doctor_management_screen/code.html) | ![Preview](./Core%20Screens/Admin%20-%20Hospital%20Flow%20Screens/admin_doctor_management_screen/screen.png)
   - **UX Notes**: Confirm modals, audit logs.

2. **Medicine Stock Sync Dashboard**

   - Pharmacy integration & stock.
   - [View Code](./Core%20Screens/Admin%20-%20Hospital%20Flow%20Screens/medicine_stock_sync_dashboard/code.html) | ![Preview](./Core%20Screens/Admin%20-%20Hospital%20Flow%20Screens/medicine_stock_sync_dashboard/screen.png)
   - **UX Notes**: Clear error handling for sync failures.

3. **Reports Dashboard**

   - Usage + patient stats.
   - [View Code](./Core%20Screens/Admin%20-%20Hospital%20Flow%20Screens/reports_dashboard/code.html) | ![Preview](./Core%20Screens/Admin%20-%20Hospital%20Flow%20Screens/reports_dashboard/screen.png)
   - **UX Notes**: Charts, filters, export options.

---

## 🚀 Edge Enhancements

Organized by sets: integrations, microservices, advanced features — all linked with UX notes.

- you can click here to [see all screens](UI.md)

---

## 🔗 UX Glue

- **Navigation**

  - Navbar (patients), Sidebar (doctors/admins).
  - Breadcrumbs for multi-step flows.
  - Tabs for multi-section screens.

- **Reusable Components**

  - Navbar, Sidebar, Footer, Forms, Cards, Buttons, Modals, Language Switcher.

- **Micro-interactions**

  - Loading skeletons, error messages, success toasts.
  - Smooth animations for transitions.

- **Personalization**

  - Role-based dashboards (Patient, Doctor, Admin, Gov/NGO).
  - Persisted filters & language preferences.

---
