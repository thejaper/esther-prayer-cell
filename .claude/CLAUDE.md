# Esther Prayer Cell CRM - Project Guidelines

## Project Overview
- **Name**: Esther Prayer Cell CRM
- **Purpose**: Member & event management for Christian women's prayer group
- **Scope**: Frontend-first development (local storage), backend integration later
- **Budget**: Open source, local-first approach; evaluate cost-effective cloud solutions at launch

## Architecture & Tech Stack
- **Frontend**: HTML5, Vanilla JS, Tailwind CSS (CDN)
- **Data Storage**: Browser localStorage (temporary), JSON structure for backend migration
- **Design**: Blue color theme, professional & elegant, mobile-responsive
- **No external dependencies**: Keep it lightweight and self-contained

## Data Model (localStorage)
```
members: [{id, name, email, phone, joinDate, role, status, notes}]
events: [{id, title, date, time, location, type, attendees, description}]
attendance: [{eventId, memberId, status}]
```

## Developer Role
- Christian pastor perspective: understand community & spiritual context
- Top MNC engineer: scalable, maintainable code architecture
- CRM expert: best practices for member lifecycle management
- Budget-conscious: local-first, open-source, cost optimization for launch

## Current Phase
1. ✅ Frontend design (blue theme, responsive)
2. ✅ Local data persistence (localStorage)
3. 🔄 Enhanced UI/UX for prayer cell context
4. ⏳ Backend API design (Node.js/Python, when approved)
5. ⏳ Database migration (PostgreSQL/MySQL at launch)

## Design Principles
- **Color**: Blue primary theme (trust, spiritual, professional)
- **Tone**: Warm, community-focused, empowering for women's ministry
- **Performance**: Keep bundle small, fast load
- **Accessibility**: WCAG compliant for inclusivity

## Future Considerations
- Multi-location support (if other prayer cells expand)
- Mobile app version
- Integration with payment/giving system
- Email notifications for events
- Reporting & analytics for prayer metrics
