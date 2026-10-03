# Resourcify

## Smart Campus Resource Management Platform

Resourcify is a full-stack campus resource management platform designed to centralize the discovery, scheduling, and management of shared institutional resources such as classrooms, laboratories, equipment, auditoriums, and other campus spaces.

The platform provides structured workflows for resource discovery, booking, conflict detection, administrative approvals, user management, and booking oversight.

## Overview

Managing shared campus resources often involves spreadsheets, manual approvals, and scheduling conflicts.

Resourcify brings these workflows into a centralized web application where users can:

- Browse available campus resources
- Create and manage bookings
- Detect conflicting reservations
- Track booking status
- Manage resources through administrative workflows
- Review pending approvals
- Monitor booking activity
- Manage users and system settings
- Review audit records

The application is built using Next.js, TypeScript, Tailwind CSS, and Supabase.

## Key Features

### Resource Management

- Centralized resource catalog
- Resource availability tracking
- Classroom, laboratory, equipment, and shared-space management
- Administrative resource management

### Booking Management

- Create and manage resource bookings
- Conflict detection for overlapping reservations
- Booking status tracking
- Administrative approval workflows
- Booking history and oversight

### Role-Based Access

Administrative workflows provide controlled access to:

- Users
- Resources
- Bookings
- Pending approvals
- Conflicts
- Analytics
- Audit records
- System settings

### Authentication

Supabase Authentication is used for user authentication and session management.

### Admin Dashboard

The administrative interface provides dedicated sections for:

- Analytics
- Bookings
- Resources
- Pending approvals
- Conflict monitoring
- User management
- Audit records
- System settings

## Technology Stack

| Layer | Technology |
|---|---|
| Framework | Next.js 14 |
| Language | TypeScript |
| UI | React |
| Styling | Tailwind CSS |
| Authentication | Supabase Auth |
| Database | Supabase |
| API | Next.js API Routes |
| Deployment | Vercel |
| Version Control | Git, GitHub |

## Project Structure

```text
Resourcify/
│
├── src/
│   ├── app/
│   │   ├── admin/
│   │   ├── api/
│   │   ├── bookings/
│   │   ├── dashboard/
│   │   ├── login/
│   │   ├── profile/
│   │   └── resources/
│   │
│   ├── components/
│   └── lib/
│
├── supabase/
│   └── migrations/
│
├── .env.example
├── middleware.ts
├── next.config.mjs
├── package.json
├── tailwind.config.ts
└── tsconfig.json