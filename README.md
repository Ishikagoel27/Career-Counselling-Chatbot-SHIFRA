
# Career Counseling AI Assistant

An AI-powered career counseling platform that helps students and professionals explore suitable career paths based on their interests, strengths, and qualifications.

## Features

- Virtual AI Assistant (SHIFRA) for career guidance
- Career Assessment Tests
- Personalized Career Recommendations
- Resources and Help Center
- Interactive Chat Interface
- Real-time Aptitude Testing
- Industry Insights Database
- Skill Gap Analysis

## Tech Stack

### Frontend
- React with TypeScript for type safety
- Tailwind CSS for styling
- Tanstack Query for state management
- Shadcn UI components
- Vite for fast development

### Backend
- Express.js with Node.js
- TypeScript for better development experience
- Drizzle ORM for database operations
- PostgreSQL for data persistence

### AI/ML
- Google Gemini API for natural language processing
- Custom recommendation algorithms
- Real-time chat processing

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables:
   - Use Replit Secrets tool for secure configuration
   - Required variables: `GEMINI_API_KEY`, `DATABASE_URL`

4. Start the development server:
   ```bash
   npm run dev
   ```
5. Access the application at `http://localhost:5000`

## Project Structure

- `/client` - React frontend application
  - `/src/components` - Reusable UI components
  - `/src/pages` - Main application pages
  - `/src/hooks` - Custom React hooks
  - `/src/lib` - Utility functions and configurations

- `/server` - Express backend server
  - `/controllers` - Request handlers
  - `/services` - Business logic and external services
  - `/scripts` - Database seeds and utilities

- `/shared` - Shared types and schemas
- `/public` - Static assets

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm start` - Start production server
- `npm run check` - Type checking
- `npm run lint` - Lint code
- `npm run test` - Run tests

## Features in Detail

### Virtual Assistant
- AI-powered chatbot for career guidance
- Natural language processing for understanding user queries
- Personalized responses based on user profile

### Assessment System
- Comprehensive aptitude tests
- Skill evaluation modules
- Personal interest analysis
- Career path compatibility matching

### Career Resources
- Industry trends and insights
- Educational pathway recommendations
- Skill development resources
- Job market analysis

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a pull request

## License

This project is licensed under the MIT License.
