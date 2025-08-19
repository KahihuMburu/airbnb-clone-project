# airbnb-clone-project
An Airbnb‑style web app where users can browse properties, view details, authenticate, and complete bookings.

## 0) Project Initialization (Overview)
Goals
- Build a functional booking flow end‑to‑end (browse → details → book → confirm).
- Practice modern web app structure, teamwork, and documentation.
- Deploy a working preview (staging) and maintain production-ready practices.

## Tech Stack
- Frontend: HTML, CSS, JavaScript 
- Backend: Node.js + Express 
- Database: PostgreSQL (or similar RDBMS)
- Design Tools: Figma (UI/UX design and specs)
- Version Control: Git + GitHub

## 1) UI/UX Design Planning
### Design Goals
- Create an intuitive, low‑friction booking flow.
- Maintain visual consistency via a clear design system.
- Ensure fast loading and smooth interactions.
- Prioritize mobile‑first responsiveness and accessibility (WCAG).

### Key Features
- Property search and filtering.
- Detailed property viewing (gallery, amenities, reviews).
- Secure checkout process (simple flow), booking confirmation.
- User authentication; favorites (optional in Phase 1).

### Primary Pages
| Page | Description |
| --- | --- |
| **Property Listing View** | Grid of available properties with filters (e.g., location, price, rating). |
| **Listing Detailed View** | Complete property details with image gallery, amenities, reviews, calendar, and booking form. |
| **Simple Checkout View** | Streamlined payment and booking confirmation summary. |

### Why a User‑Friendly Design Matters
A clear, accessible interface reduces friction and errors, improves trust, and increases conversion rates. In a booking context, users must quickly compare options, understand pricing and availability, and complete payment confidently—small usability improvements can significantly impact bookings and customer satisfaction.

## 2) More UI/UX Design Planning (Figma Exploration)
> Use your Figma file to validate tokens and specs. Document the design properties below to keep the build consistent with the mockups.

### Color Styles
- **Primary:** `#FF5A5F`
- **Secondary:** `#008489`
- **Background:** `#FFFFFF`
- **Text (Primary):** `#222222`
- **Text (Secondary/Muted):** `#717171`

### Typography
- **Primary Font:** Circular (or Inter as fallback)
- **Body:** 16px, Medium (500), line-height ~1.5
- **Headings:** 24–32px, Bold (700)
- **Secondary Text:** 14px, Book/Regular (400)

### Why Identify Design Properties Early?
- Consistency: Shared tokens (colors, type, spacing) keep components cohesive across pages.
- Speed: Developers reference a single source of truth, reducing rework and review cycles.
- Quality: Early alignment prevents visual drift from the mockups and improves accessibility (contrast, size, spacing).

## 3) Project Roles and Responsibilities

- **Project Manager**: Oversees timeline and deliverables, coordinates with stakeholders, tracks risks and scope.
- **Product Owner**: Defines requirements, prioritizes features, manages the backlog, represents user needs.
- **Scrum Master**: Facilitates agile ceremonies, removes blockers, ensures continuous improvement.
- **Designers**: Create mockups, maintain design system/tokens, run UX reviews, specify responsive behaviors.
- **Frontend Developers**: Implement responsive UI components and pages, handle state management, integrate APIs, ensure accessibility.
- **Backend Developers**: Design and implement APIs, manage database schema and migrations, enforce business rules and security.
- **QA/Testers**: Write test plans and cases, run manual/e2e tests, file bugs, verify fixes.
- **DevOps Engineers**: Set up CI/CD, environments, observability, and deployment automation.

## 4) UI Component Patterns
Planned reusable components (document props and states as you build):

**Navbar**
  - Logo, search bar, user navigation (sign in/up, profile), responsive menu.
**Property Card**
  - Property image, price/night, location, rating, favorite button; responsive layout and skeleton loading.
**Footer**
  - Site links, company info, social links, copyright.





