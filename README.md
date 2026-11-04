# FundiLink

## Overview
FundiLink is a web application that helps customers find skilled local artisans (plumbers, electricians, tailors and more) on a map, book them and pay a deposit through mobile money. It gives artisans a simple way to be found and to manage their bookings.

## Problem Statement
Finding a trustworthy artisan nearby is harder than it should be:

- Customers rely on word of mouth and phone calls to find someone available.
- There is no easy way to see which providers are close to them.
- Bookings are agreed informally, so requests are forgotten or disputed.
- Artisans lose work because customers cannot find them or are unsure they will turn up.
- Deposits and payments are handled informally, with no clear record.

## Proposed Solution
FundiLink connects customers and artisans through one booking flow:

- Providers register, choose their skills and pin their location.
- Customers search a map for nearby providers and open their profiles.
- A customer sends a booking request, and the provider accepts or rejects it.
- The customer pays a deposit through Airtel Money, and the backend verifies the payment before the booking moves to paid.
- The provider marks the job as completed.
- Both sides are notified by email, and the provider also receives an SMS for new requests.

## Core Features
- User authentication for customers and providers
- Provider profiles with skills and location
- Map of nearby providers
- Booking requests and management
- Controlled booking status flow (requested, accepted, paid, completed)
- Mobile money deposit payments (Airtel Money)
- Email and SMS notifications

## Technology Stack
- React + TypeScript (Vite, Tailwind CSS)
- Node.js + Express + TypeScript
- PostgreSQL + Prisma
- Zod for input validation
- Leaflet + OpenStreetMap for maps
- Airtel Money API (sandbox or mock provider)
- Africa's Talking (SMS) and a transactional email provider
- Vercel and Railway for deployment

## Project Status
Planning and requirements definition.

> **Note:** Payments run in sandbox mode and no real money is handled.
