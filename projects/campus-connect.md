# Campus Connect — AASTU Project Starter Documentation
A centralized directory for university events and a permanent digital archive for campus life at Addis Ababa Science and Technology University (AASTU).

---

# 1. One-Page Project Overview

## Project Name
Campus Connect (AASTU Edition)

## Vision
To become the definitive digital archive and event directory for AASTU — ensuring no student misses a workshop or seminar, while preserving the visual history of university life.

## The Problem
University life at AASTU is vibrant but digitally fragmented because information is scattered across:
- Telegram channels  
- Temporary Google Forms/Luma links  
- WhatsApp groups  
- Physical notice boards  
- Personal phone galleries  

This leads to:
- Missed events due to lost registration links  
- No central calendar for departmental activities  
- Loss of campus memories (photos/videos) after events end  
- Difficulty finding verified academic resources  
- Reliance on unreliable word-of-mouth for updates  

## Proposed Solution
A mobile-friendly web platform that acts as a curated aggregator:
- Event directory linking to external registration forms (Luma/Google Forms)  
- Permanent gallery for campus events and projects  
- Academic resources and calendar  
- Official announcements from clubs and administration  
- Department-specific filters for easy navigation  
- Verified links to prevent scams or expired forms  
- Profile system for students and club leaders  
- Administrative tools for content moderation  

## Target Users
- Students (primary)  
- Club leaders (content creators)  
- Campus administrators (verifiers)  
- Alumni (gallery viewers)  
- Prospective students (future)  

## Core Value Propositions
- Centralize all event links and campus information  
- Preserve campus history through a structured gallery  
- Provide essential academic and career tools  
- Improve communication between clubs and students  
- Foster a connected and documented campus community  

## Success Metrics (MVP)
- 300+ weekly active users  
- 100+ clicks per week to external event forms  
- 10+ event albums uploaded monthly  
- 5+ departments represented in the gallery  
- 50% of active clubs using the platform for announcements  

---

# 2. Feature List — MVP and Future Scope

## MVP Features

### Academic
- Academic Resources  
  Uploading, browsing, downloading notes, materials, and documents.

- Academic Calendar  
  Centralized date list for exams, midterms, holidays, deadlines.

- Resource Verification  
  Department representatives verify uploaded materials.

### Engagement
- Club Hub  
  Discover clubs, view descriptions, contacts, and upcoming activities.

- Events Page  
  List and explore campus events with external registration links.

- Campus Gallery  
  Structured photo albums organized by event, department, and year.

- Official Updates  
  Admin-only feed for critical announcements (no public confessions).

### Convenience
- Campus Map  
  Simple interactive map for buildings and facilities.

- Facility Information  
  Lab hours, library status, and location details.

### Career
- Jobs and Internships Board  
  Curated opportunities for students.

- Project Showcase  
  Students can display course or personal projects.

### Profile
- Name and Department  
- Batch/Section matching  
- Contributor Badge (for leaders)  
- Basic profile page  

### Administration
- Notifications  
  Administrators and clubs can push announcements.

- Link Verification  
  Admins approve external event links before publishing.

---

## Future Features

### Social & Engagement
- Yearbook Mode  
- Gallery (event reels and videos)  
- Alumni Connect  
- Department updates  

### Career
- Career Buddy Matching  
- Thesis Database  
- Alumni Mentorship  

### Academic
- Lab Equipment Booking  
- Peer Notes Rating  
- LMS Integration  

### Profile Enhancements
- Activity History  
- Event Attendance Record  
- Downloaded Resources Log  

### Integrations
- Local business partnerships and promotions  
- University LMS sync  

---

# 3. Screen Map / Wireframe Structure

## Home Screen
- Announcement bar  
- Quick-access cards: Events, Gallery, Resources  
- Latest Gallery Updates  
- This Week's Top Events  
- Campus map shortcut  

---

## Academic Module

### Resources
- Search  
- Categories (Department, Course)  
- Upload functionality (Verified)  
- Document list  

### Academic Calendar
- Monthly calendar view  
- Highlighted events, exams, and deadlines  
- Filters by department  

### Study Tools
- Resource sharing  
- Past exam papers  
- Lab manuals  

---

## Engagement Module

### Clubs
- Club directory  
- Club profile pages  
- Upcoming events  

### Events
- Full events list  
- Filters (Department, Type)  
- Event details with External Link (Luma/Forms)  

### Campus Gallery
- Album grid (Event based)  
- Categories: Department, Year, Type  
- Lightbox view for images  
- Upload interface (Leaders only)  

### Official Updates
- Admin announcements  
- Critical notices (Exam changes, Holidays)  
- No public posting (Read-only for students)  

---

## Convenience Module

### Campus Map
- Interactive pins  
- Building details  
- Department search  

### Facility Info
- Locations  
- Open hours  
- Contact details  

---

## Career Module

### Jobs and Internships
- Filterable listings  
- Job details page  

### Project Showcase
- Project gallery  
- Project detail pages  
- Tags for categories  

---

## Profile Module
- Name  
- Department  
- Batch/Section  
- Edit profile  
- Contributor Badge  
- Activity Log (future)  

---

# 4. Task Breakdown — Starter Backlog

## Backend Tasks
- Database schema design  
- Authentication system (University Email/ID)  
- User profile API  
- Events API (External Link storage)  
- Clubs API  
- Gallery API (Media storage & compression)  
- Resources API  
- Jobs API  
- Link Verification logic  
- Notifications API  
- Administrative endpoints  

---

## Frontend Tasks
- Global layout and navigation  
- Home page  
- Resources page  
- Academic calendar  
- Club hub  
- Events pages (Link handling)  
- Gallery pages (Grid & Lightbox)  
- Official Updates feed  
- Job listings page  
- Project showcase  
- Profile page  
- Login and registration pages  
- Design system (AASTU colors, typography, spacing)  

---

## UI/UX Design Tasks (Figma)
- Finalize palette and typography (AASTU Branding)  
- Home screen wireframes  
- Academic module wireframes  
- Gallery and Events UI  
- Profile pages  
- Form styles and upload layouts  

---

## Product Management Tasks
- Sprint planning  
- Prioritizing MVP features  
- Creating an API contract (Frontend–Backend)  
- Test cases for MVP  
- Weekly demo planning  
- Content Seeding Plan (Club onboarding)  

---

# 5. Recommended MVP Timeline

## Week 1
- Wireframes  
- Database schema  
- Backend setup  
- Cloud Storage Configuration  

## Week 2
- Home, Gallery, Resources  
- CRUD APIs for events (links) and gallery  

## Week 3
- Events Calendar  
- Clubs and External Links  
- Job listings  

## Week 4
- Profile mechanism  
- Notifications  
- Testing and deployment  
- Beta launch  

---

# Conclusion
This document provides a complete foundation for beginning development on Campus Connect.  
It includes the concept, scope, structure, initial wireframe outline, team tasks, and a realistic MVP timeline for a small development team.  
The focus remains on utility, archive, and event aggregation rather than social interaction.
