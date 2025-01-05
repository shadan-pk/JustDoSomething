# JustDoSomething

## Project Overview

JustDoSomething is a MERN application designed to reduce stress and anxiety by suggesting simple tasks for users to complete. By providing actionable prompts, the app eliminates decision fatigue and helps users focus on small, manageable actions. A streak system motivates users to maintain consistency in completing these tasks.

### Purpose
- Encourage users to engage in stress-relieving activities.
- Promote mindfulness and self-care through actionable tasks.
- Motivate users with a streak system.

### Features
1. Task Suggestions: Randomly suggest simple tasks like drinking water, walking, or visiting a nearby place.
2. Streak System: Track consecutive days of task completion.
3. User Accounts: Authentication and task history.
4. Notifications: Reminders to complete tasks.
5. Dashboard: Displays streaks, task history, and statistics.

## Tech Stack
- Frontend: React.js
- Backend: Node.js with Express.js
- Database: MongoDB
- Authentication: JWT
- Notifications: Firebase or OneSignal

## File Structure

### Backend
backend/
- config/db.js
- controllers/taskController.js
- controllers/userController.js
- models/Task.js
- models/User.js
- routes/taskRoutes.js
- routes/userRoutes.js
- middleware/authMiddleware.js
- utils/generateToken.js
- server.js

### Frontend
frontend/
- public/
- src/
  - components/TaskCard.js
  - components/StreakIndicator.js
  - pages/HomePage.js
  - pages/Dashboard.js
  - pages/LoginPage.js
  - pages/SignupPage.js
  - context/AuthContext.js
  - utils/api.js
  - App.js
  - index.js
- package.json

## How to Run

1. Clone the repository.
2. Install dependencies:
   - `cd backend && npm install`
   - `cd frontend && npm install`
3. Configure environment variables in `.env`.
4. Run the backend: `npm start`.
5. Run the frontend: `npm start`.

## License
This project is licensed under the MIT License.
