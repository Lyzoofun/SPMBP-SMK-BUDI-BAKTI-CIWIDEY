# Product Requirement Document (PRD): PPDB Dashboard SMK Budi Bakti Ciwidey

## 1. Project Overview
A responsive web-based portal for the Student Admission Program (PPDB) of SMK Budi Bakti Ciwidey. The dashboard serves as a central hub for prospective students to access school information, explore academic programs, and initiate the registration process.

## 2. Target Audience
- **Prospective Students:** Primary users looking to register and learn about the school.
- **Parents/Guardians:** Secondary users seeking detailed school profiles and contact information.

## 3. Design System (Academic Horizon)
- **Visual Identity:** Professional, trustworthy, and modern academic aesthetic.
- **Color Palette:**
  - **Primary:** Deep Blue (#1e3a8a) - representing authority and stability.
  - **Secondary:** Blue Gradient (#1e3a8a to #1d4ed8) - used for the hero section.
  - **Accents:** Amber/Gold (#fbbf24) - used for highlights and buttons.
  - **Surface:** Light Blue-Grey (#f4f8fc) - background for readability.
- **Typography:** 'Poppins' (Sans-serif) for a modern, clean look across all headings and body text.
- **Components:** Rounded corners (20px for cards/banners), subtle shadows, and interactive hover states.

## 4. Key Features & Functionality

### 4.1. Navigation
- **Desktop Navbar:** Features school branding, a menu toggle, and a user profile dropdown.
- **Mobile Bottom Navigation:** Fixed bottom bar with quick access to Home, Profile, PPDB, News, and Contact.

### 4.2. Hero Section
- Dynamic welcome banner with school branding.
- Brief introductory text explaining the portal's purpose.

### 4.3. Feature Grid (8 Core Modules)
1. **Beranda:** Main landing information.
2. **Profil Sekolah:** History, vision, and success statistics.
3. **Kompetensi Keahlian:** Detailed information on DKV, BDP, and PPLG programs.
4. **Pendaftaran:** Interactive online registration form.
5. **Berita & Kegiatan:** Updates on school events and achievements.
6. **Galeri:** Visual documentation of campus facilities.
7. **Informasi PPDB:** Registration flows and requirements.
8. **Kontak & Lokasi:** WhatsApp integration and Google Maps location.

### 4.4. Modal System
- All feature modules open in a centralized, blurred-backdrop modal window to keep users on the dashboard without full page reloads.

### 4.5. Registration Form
- Fields for: Full Name, NISN, WhatsApp Number, and Major Selection.
- Integrated map trigger for address location.

## 5. Technical Specifications
- **Framework:** Vanilla HTML5, CSS3, and JavaScript.
- **Styling:** Custom CSS with a focus on responsiveness (Flexbox/Grid).
- **Interactivity:** DOM manipulation for modal handling and form submissions.
- **External Links:** WhatsApp API for direct communication and Google Maps for location services.

## 6. Future Enhancements
- User authentication and student login area.
- Document upload functionality for registration.
- Real-time admission status tracking.
