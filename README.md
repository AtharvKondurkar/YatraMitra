# YatraMitra

## Full-Stack Travel Planning Platform

YatraMitra is a full-stack travel planning platform designed to simplify trip planning by generating personalized travel plans based on destination, travel dates, interests, mood, travel pace, and budget.

The platform combines a React.js frontend, Node.js/Express.js backend, and Supabase for persistent data management to provide an end-to-end travel planning experience.

---

## Features

### Personalized Trip Planning
Generate travel plans based on:
- Destination
- Travel dates
- Interests
- Mood
- Travel pace
- Budget

### Traveler-Specific Planning
Supports different travel preferences and use cases, including:
- Pilgrims
- Families
- Young travelers

### Saved Trips
Save and manage planned trips for future reference.

### Booking Workflow
Provides a structured workflow for handling travel-related booking information.

### Maharashtra-Focused Travel
Designed around destinations and travel experiences across Maharashtra.

### Responsive Interface
Provides a responsive user interface across desktop and mobile screen sizes.

### Persistent Data Management
Uses Supabase for persistent application data and backend services.

### Full-Stack Architecture
React.js frontend communicates with a Node.js/Express.js backend through REST APIs.

---

## Technology Stack

| Layer | Technologies |
|---|---|
| Frontend | React.js, JavaScript, CSS |
| Backend | Node.js, Express.js |
| API | REST APIs |
| Database | Supabase |
| Frontend Deployment | Netlify |
| Backend Deployment | Render |
| Version Control | Git, GitHub |

---

## System Architecture

```text
┌─────────────────────────────┐
│         React.js            │
│      Frontend Application   │
└──────────────┬──────────────┘
               │
               │ REST API
               ▼
┌─────────────────────────────┐
│      Node.js + Express.js   │
│       Backend Services      │
└──────────────┬──────────────┘
               │
               │ Data Operations
               ▼
┌─────────────────────────────┐
│          Supabase           │
│    Database & Backend       │
└─────────────────────────────┘