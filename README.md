<div align="center">

<img src="https://bixyrentals.com/bixxxy-logo.png" alt="Bixxxy Logo" width="160" />

# Bixxxy

**A short-term rental platform.**

</div>

Bixxxy is a modern vacation and short-term rental platform designed to connect guests and travelers with fully furnished and serviced accommodations across the board.

Whether you're a guest searching for the perfect apartment, hotel, lodge, guest house, or resort — or a property owner managing listings and tracking bookings — Bixxxy delivers a seamless, transparent, and reliable experience built with both sides in mind.

---

## Overview

Bixxxy enables users to:

- Browse and discover a wide range of short-term rental properties
- Check real-time availability with color-coded calendars
- View detailed property and room overviews, including photos, amenities, and house rules
- See transparent price breakdowns covering base rates, service fees, taxes, and discounts
- Book rooms or units securely and make payments directly on the platform
- Use Google Maps integration for easy navigation and location awareness

The platform serves both **guests** and **property owners**, with dedicated interfaces for each and powerful admin tools for the Bixxxy team.

### Key Features

- **Real-time Availability** — Color-coded calendars showing booked, available, and pending dates across all properties
- **Secure Booking & Payments** — Integrated payment gateways for safe and reliable transactions
- **Transparent Pricing** — Clear breakdowns of nightly rates, service fees, cleaning fees, taxes, and applicable discounts
- **Property Management** — Landlord dashboards with analytics, booking tracking, transaction history, and listing management
- **Admin Control** — Full platform oversight including users, properties, bookings, disputes, and system settings
- **Responsive Design** — Optimized for desktop, tablet, and mobile

---

## Architecture

Bixxxy is modular by design, consisting of **5 main repositories** — 3 frontend apps and 2 backend servers — each with a clear and distinct responsibility.

---

### 1. Tenant Web App — *Bixxxy*

The core product. This is the main public-facing application where guests browse properties, search with filters, view listings, check real-time availability, make bookings, and complete payments. All the primary business logic flows through here.

![Bixxxy Tenant App](https://landlord.bixyrentals.com/tenant/vacation-listings-light.png)
*Browsing and booking short-term rentals on Bixxxy*

---

### 2. Landlord Web App — *Bixxxy Host*

The property owner portal. Landlords use this to manage their listings, update availability and pricing, monitor bookings in real time, view earnings analytics and revenue graphs, and get a full overview of their transaction history.

![Bixxxy Host — Landlord App](https://landlord.bixyrentals.com/landlord/dashboard-light.png)
*Landlord dashboard — analytics, bookings, and listing management*

---

### 3. Admin Web App — *Bixxxy Admin*

The internal management layer. This is the Bixxxy team's control center — built to oversee the entire platform with specialized dashboards, data tables, and management forms. It covers user management, property moderation, support, platform analytics, and system configuration.

![Bixxxy Admin App](https://bixyrentals.com/bixxxy-admin.png)
*Admin dashboard — platform-wide oversight and management*

---

### 4. Main Server

The primary API server powering both the Tenant and Landlord apps. Handles authentication, property data, real-time availability, bookings, payments, notifications, and all core business logic.

---

### 5. Admin Server

A separate, secure backend dedicated to admin-specific operations — including privileged actions, platform-level reporting, and internal tooling.

---

## Tech Stack

| Layer | Technologies |
|-------|-------------|
| **Frontend** | React, Vite, JavaScript, Tailwind CSS, shadcn/ui |
| **Backend** | NestJS, TypeScript |
| **Cloud** | Google Cloud Platform (GCP) |
| **Payments** | Pesapal, Stripe |
| **Maps** | Google Maps API |
| **CDN / Frontend Delivery** | Cloudflare |

The system runs on **two servers**: the main server handles the Tenant and Landlord apps, while a dedicated admin server handles the Admin app.

---

<br />

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)](https://nestjs.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)

<br />

[![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)](https://cloud.google.com/)
[![Google Maps](https://img.shields.io/badge/Google_Maps-34A853?style=for-the-badge&logo=googlemaps&logoColor=white)](https://developers.google.com/maps)
[![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white)](https://stripe.com/)
[![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)](https://www.cloudflare.com/)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge)](./LICENSE)

---

## Vision, Mission & Values

**Vision**  
To make short-term rentals accessible for everyone through Bixxxy.

**Mission**  
To work closely with guests and property owners to understand their needs and deliver a world-class platform that truly serves them.

**Our Values**  
As a growing startup, we operate collaboratively with a strong focus on design, engineering, innovation, and effective business models — ensuring we create the most reliable and accessible booking experience possible.

**Goal**  
To scale sustainably and achieve an annual average of over **1 million bookings within the next decade** across East Africa and the African continent.

---

## Contributing

This is a private organization repository. Contributions are managed internally by the Bixxxy engineering team. If you're part of the team, please refer to the contributing guidelines in your respective repository.

---

## License

Bixxxy is proprietary software. All rights reserved. Unauthorized use, reproduction, or distribution is strictly prohibited.

---

**Built with care and maximum effort**

[Website](https://bixxxy.com) · [Contact](mailto:info@bixxxy.com)
