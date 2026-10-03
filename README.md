# YatraMitra

## Full-Stack Travel Planning Platform

YatraMitra is a full-stack travel planning platform designed to simplify trip planning for destinations across Maharashtra. The application allows users to provide travel preferences such as destination, travel dates, interests, mood, travel pace, and budget, and uses these inputs to create a personalized travel planning experience.

The project combines a React.js frontend, Node.js/Express.js backend, and Supabase for persistent data management.

---

## Overview

Planning a trip often requires users to search across multiple sources for destinations, activities, travel options, and booking information.

YatraMitra brings key planning workflows into a single application by allowing users to:

- Enter detailed travel preferences
- Generate personalized travel plans
- Explore traveler-specific planning options
- Save trips for future reference
- Manage travel-related booking information
- Interact with a responsive web interface

The project demonstrates the implementation of a practical full-stack web application with frontend development, backend API development, database integration, and cloud deployment.

---

## Key Features

### Personalized Trip Planning

Users can provide multiple travel preferences, including:

- Destination
- Travel dates
- Interests
- Mood
- Travel pace
- Budget

These preferences are processed by the application's planning logic to create a travel experience aligned with the selected requirements.

### Traveler-Specific Planning

The application supports different travel scenarios and preferences, including:

- Pilgrimage travel
- Family trips
- Young traveler experiences
- General destination-based planning

### Saved Trips

Users can save planned trips and access them later without having to recreate their travel preferences.

### Booking Workflow

YatraMitra includes a structured booking workflow for handling travel-related booking information as part of the overall trip planning process.

### Maharashtra-Focused Travel

The platform focuses on destinations and travel experiences across Maharashtra, providing a focused regional travel use case.

### Responsive User Interface

The frontend is designed to provide a consistent experience across desktop and mobile screen sizes.

### Persistent Data Management

Supabase is used for persistent application data and backend services.

---

## Technology Stack

| Category | Technology |
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
                         User
                           |
                           v
              +------------------------+
              |        React.js        |
              |    Frontend Client     |
              +-----------+------------+
                          |
                          | HTTP / REST API
                          v
              +------------------------+
              |    Node.js + Express   |
              |    Backend Services    |
              +-----------+------------+
                          |
                          | Database Operations
                          v
              +------------------------+
              |       Supabase         |
              |   Persistent Storage   |
              +------------------------+