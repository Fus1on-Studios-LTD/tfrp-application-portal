# The Flow Roleplay Community Portal

<div align="center">

<img src="https://panel.fus1on.live/attachments/69fd2f47592ce_TFRP.png" width="140" />

# Production-Ready Community Management Platform

Modern Discord-integrated recruitment, onboarding, staff management, interview tracking, analytics, and department operations platform built for The Flow RP Community.

[![Next.js](https://img.shields.io/badge/Next.js-16-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-Production-green?style=for-the-badge&logo=node.js)](https://nodejs.org/)
[![Prisma](https://img.shields.io/badge/Prisma-SQLite-blue?style=for-the-badge&logo=prisma)](https://www.prisma.io/)
[![Discord OAuth](https://img.shields.io/badge/Discord-OAuth2-5865F2?style=for-the-badge&logo=discord)](https://discord.com/developers/docs/topics/oauth2)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-UI-38BDF8?style=for-the-badge&logo=tailwindcss)](https://tailwindcss.com/)
[![Production Ready](https://img.shields.io/badge/Status-Production_Ready-00d084?style=for-the-badge)]()

</div>

---

# Overview

The Flow Roleplay Community Portal is a complete recruitment and department operations platform designed for modern FiveM roleplay communities.

Built with production deployment in mind, the portal integrates deeply with Discord and provides:

- Department applications
- Staff review systems
- Interview tracking
- Discord automation
- Department permissions
- Dynamic question management
- Audit logging
- Analytics
- Role synchronization
- Automated onboarding workflows

This platform was designed specifically for large-scale, structured roleplay communities requiring professional-grade recruitment infrastructure.

---

# Features

# Authentication & Discord Integration

- Discord OAuth2 authentication
- Automatic Discord guild joining
- Discord role synchronization
- Website role mapping
- Pending applicant role assignment
- Department role assignment automation
- Discord DM notifications
- Discord webhook logging
- Role-based dashboard visibility

---

# Department Application System

## Supported Departments

- Civilian Operations
- Sheriff's Office
- Police Department
- State Police
- Fire & EMS
- San Andreas Communications Department

## Application Features

- Dynamic configurable questions
- Department-specific question sets
- Text / textarea / select / radio / date question support
- Duplicate application prevention
- 14-day denial cooldown system
- Application status tracking
- Staff notes
- Notes edit history
- Department open/closed controls
- Applicant dashboard
- Secure applicant-only detail pages

---

# Staff Review System

- Full staff application review dashboard
- Search & filtering
- Department-specific access control
- Accept / deny workflows
- Discord automation logs
- Applicant review detail pages
- Staff audit logging
- Decision note tracking
- Staff action history

---

# Department Permission System

Granular permission control for department staff.

Supports:

- Review permissions
- Accept permissions
- Deny permissions
- Department-scoped access
- Discord-role based authorization

Examples:

| Role | Department | Permissions |
|---|---|---|
| Sheriff Command | sheriff | Review / Accept / Deny |
| Police Supervisors | police | Review / Accept |
| Communications Staff | communications | Review |

---

# Interview Management System

## Interview Scheduling

- Interview scheduling
- Discord DM interview notifications
- Location + notes support
- Interview audit logs
- Department-restricted visibility

## Interview Tracking

- Complete interview tracker
- Dynamic interview questions
- Interview answer storage
- Staff conducting logs
- Final verdict tracking
- Audio recording uploads
- Discord webhook logging
- Discord DM verdict notifications

## Final Verdict Support

- Moving Forward
- Not Moving Forward

Verdicts are displayed to:
- Staff
- Applicants
- Discord webhook logs

---

# Admin Panel

## Admin Features

- Question manager
- Interview question manager
- Department status manager
- Department permission manager
- Role mapping manager
- Audit log viewer
- Analytics dashboard
- Staff visibility controls

---

# Analytics & Logging

## Audit Logging

Tracks:
- Application decisions
- Interview scheduling
- Interview completion
- Discord role updates
- Discord DM delivery
- Staff actions
- Automation events

## Analytics Dashboard

- Application statistics
- Department analytics
- Acceptance rates
- Interview metrics
- Staff activity
- Discord automation monitoring

---

# Security Features

- Centralized security helper system
- Route protection
- Department-scoped authorization
- Applicant ownership validation
- Role-based dashboard rendering
- Secure server actions
- Secure API routes
- Maintenance mode
- Branded 404 / 500 pages
- Audit logging
- Automated backups

---

# Maintenance Mode

Built-in maintenance system with:

- Middleware protection
- Configurable maintenance messages
- Public-safe routes
- Branded maintenance page

---

# Production Infrastructure

## Stack

- Next.js 16
- React
- Prisma
- SQLite
- TailwindCSS
- Discord OAuth2
- PM2
- NGINX
- Ubuntu 24.04
