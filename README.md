# 🏥 Sahali Animal Hospital Showcase

> *A modern, professional veterinary clinic website for Sahali Animal Hospital*

[![Status](https://img.shields.io/badge/Status-Live-brightgreen?style=for-the-badge)](https://sahalianimalhospital.ca)
[![React](https://img.shields.io/badge/React-18.3.1-blue?style=for-the-badge&logo=react&logoColor=white)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.8.3-blue?style=for-the-badge&logo=typescript&logoColor=white)](https://typescriptlang.org)
[![Vite](https://img.shields.io/badge/Vite-5.4.19-purple?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev)

<div align="center">

**[🚀 Live Demo](https://sahalianimalhospital.ca)**

</div>

---

## 📖 Overview

This website serves as the digital hub for Sahali Animal Hospital in Kamloops, British Columbia. It showcases their veterinary services, builds trust with clients through testimonials and educational content, and provides essential information about the clinic. 

The platform is designed to be highly responsive, user-friendly, and optimized for search engines, ensuring that pet owners can easily find information, book appointments, and contact the clinic.

> 🏥 **Developed for Sahali Animal Hospital** - Designed as the primary online platform for the clinic to enhance patient engagement and streamline communication.

### 🎯 What This Application Does

The platform is built to solve several core needs:
- **Service Showcase**: Displays comprehensive veterinary services including wellness exams, dental care, surgery, and exotic pet care.
- **Dynamic Blog System**: A Firebase-powered content management system for real-time blog updates and educational content.
- **Client Communication**: Secure forms for general inquiries and new client registrations, protected by Cloudflare Turnstile.
- **Trust Building**: Integration with Google Reviews and an interactive testimonial carousel.

---

## ✨ Key Features

<table>
<tr>
<td width="50%">

### Core Functionality
- 🏥 **Comprehensive Services**: Detailed pages for all veterinary offerings.
- 📝 **Dynamic Blog**: Markdown support with category filtering and related posts.
- 📧 **Secure Contact Forms**: Complex multi-section registration and quick messaging.
- ⭐ **Testimonials**: Auto-scrolling reviews and Google Reviews integration.

</td>
<td width="50%">

### Technical Highlights
- 🎨 **Professional Design**: Apple-inspired UI with premium Framer Motion animations.
- 📱 **Mobile Optimization**: Fully responsive layouts for all devices.
- 🔍 **SEO Ready**: Comprehensive metadata, structured JSON-LD data, and sitemap.
- 🚀 **Performance**: Optimized caching with TanStack React Query and Vercel edge delivery.

</td>
</tr>
</table>

### Supported Services

| Category | Description |
|----------|-------------|
| **Wellness & Exams** | Annual health checks and preventative care |
| **Dental Care** | Professional cleaning and oral surgery |
| **Diagnostics** | In-house laboratory and X-ray services |
| **Surgery** | Routine and specialized surgical procedures |
| **Exotic Pets** | Specialized care for rabbits, guinea pigs, lizards, and more |

---

## 🎨 Screenshots

<table>
<tr>
<td width="50%">

### Home Page Header
<!-- PLACEHOLDER: Add home page header screenshot here -->
![Home Page Header](placeholder-image-url)

</td>
<td width="50%">

### Services Grid
<!-- PLACEHOLDER: Add services grid screenshot here -->
![Services Grid](placeholder-image-url)

</td>
</tr>
</table>

### Contact and Registration Form
<!-- PLACEHOLDER: Add contact form screenshot here -->
![Contact Form](placeholder-image-url)

---

## 🔬 Architecture and Data Flow

### Application Structure

The application follows a modular architecture built on React and Vite:

```
1. Client Browser
2. React Application (Pages, Components, Hooks)
3. Service Layer (Firebase, EmailJS, Validation)
4. External Services (Firestore, EmailJS API, Cloudflare)
```

### Data Flow

#### Blog Data Management
- Content is stored in **Firebase Firestore**.
- **TanStack React Query** fetches, caches, and serves data to the UI.
- Background refetching ensures content remains fresh.

#### Secure Form Submission
- User fills out the interactive form.
- **Cloudflare Turnstile** verifies the user is human.
- **Zod** validates the schema on the client side.
- **EmailJS** securely routes the data to the clinic email inbox with reference numbers.

---

## 🛠 Technology Stack

### Frontend Architecture

| Technology | Purpose |
|------------|---------|
| **React 18** | UI component library with hooks architecture |
| **TypeScript** | Strict type safety across the entire codebase |
| **Vite** | Lightning fast build tool and development server |
| **Tailwind CSS** | Utility-first styling with custom theme configurations |
| **Framer Motion** | Advanced scroll-triggered animations and layout transitions |
| **shadcn/ui** | High-quality, accessible React component primitives |

### Backend and Integration

| Technology | Purpose |
|------------|---------|
| **Firebase** | Scalable NoSQL database (Firestore) for blog management |
| **EmailJS** | Serverless email delivery for client communications |
| **Cloudflare Turnstile** | Advanced bot protection without intrusive CAPTCHAs |
| **React Hook Form & Zod** | Complex form state management and strict validation |

### Infrastructure

| Service | Purpose |
|---------|---------|
| **Vercel** | Global edge network deployment and hosting |
| **Vercel Analytics** | Privacy-friendly web traffic analytics |

---

## 🔐 Security and Performance

### Security Measures
- **Content Security Policy**: Strict directives to prevent Cross-Site Scripting (XSS).
- **HTTP Security Headers**: Enforcement of HTTPS, clickjacking prevention, and MIME sniffing protection.
- **Bot Protection**: Invisible Turnstile verification for all form submissions.

### SEO Implementation
- **React Helmet Async**: Dynamic injection of meta tags and Open Graph data.
- **Structured Data**: JSON-LD schema markup for local veterinary business optimization.

---

## 🔒 Why is the Code Private?

This project is a custom commercial website developed specifically for Sahali Animal Hospital. The source code remains private to protect proprietary business logic, client data structures, and security implementations. However, this repository serves as a technical showcase to demonstrate the architectural decisions, design capabilities, and problem-solving skills involved in building a modern web platform.

---

## 👨‍💻 Author

**Deeparsh Singh**
- 🌐 [Portfolio](https://www.deeparshsingh.me)
- 💼 [LinkedIn](https://www.linkedin.com/in/deeparsh010/)
- 🐙 [GitHub](https://github.com/DeeparshSingh)

---

<div align="center">

**🏥 Sahali Animal Hospital - Modern Veterinary Web Experience**

Made with ❤️ for Sahali Animal Hospital

[🚀 Live Demo](https://sahalianimalhospital.ca)

</div>
