# System Architecture for Menopause Support App

## Technology Stack
- **Frontend:** React Native (Android and iOS mobile app)
- **Backend:** Node.js with Express
- **Database:** MongoDB
- **SMS Service:** Twilio for SMS updates and reminders
- **Hosting:** AWS EC2 and S3

## Component Communication
- Mobile app communicates with backend using HTTPS REST API.
- Data stored securely in MongoDB.
- Backend triggers SMS notifications through Twilio API.
- JWT-based authentication secures sessions.
- Offline data sync enabled on app to handle connectivity.

## Technical Feasibility
- Chosen tech stack supports scalability and low-end devices.
- SMS integration extends reach beyond smartphone users.
- Cloud infrastructure ensures reliability and data security.
- Modular architecture supports future feature expansion.
