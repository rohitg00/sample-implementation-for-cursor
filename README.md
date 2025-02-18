# Netflix Recommendation App

A modern web application that helps users discover personalized movie and TV show recommendations based on their mood, preferences, and viewing history. Built with Next.js 14, TypeScript, Supabase, and TMDB API.

![Project Status](https://img.shields.io/badge/status-in_development-yellow)
![License](https://img.shields.io/badge/license-MIT-blue)
![Next.js Version](https://img.shields.io/badge/next.js-14.0-black)
![TypeScript](https://img.shields.io/badge/typescript-5.0-blue)

## 🎯 Features

- 🎭 Mood-based content recommendations
- 🎬 Personalized movie and TV show suggestions
- 📱 Responsive, mobile-first design
- 🔍 Advanced search with filters
- 📋 Personal watchlist management
- ⭐ Rating and review system
- 🌙 Dark/Light theme support
- 🔄 Real-time updates using Supabase
- 🎨 Modern UI with Shadcn UI components

## 🚀 Tech Stack

### Frontend
- Next.js 14 (App Router)
- TypeScript
- Tailwind CSS
- Shadcn UI
- React Hook Form
- Zod Validation

### Backend & Database
- Supabase (PostgreSQL)
- Row Level Security (RLS)
- Real-time subscriptions
- Edge Functions

### APIs & Integration
- TMDB API
- Supabase Auth
- Cloudinary (Image optimization)

### DevOps & Monitoring
- Vercel Deployment
- GitHub Actions CI/CD
- Error tracking with Sentry
- Performance monitoring

## 📋 Prerequisites

- Node.js 18.x or later
- npm or yarn
- Supabase account
- TMDB API key
- Git

## Implementation Guidelines

Our repository includes several core documentation files within the instructions folder that outline our sample implementations and best practices:

- **requirements.md**  
  Outlines the core features, user management, content discovery, and non-functional requirements to ensure we meet both functional and technical specifications.

- **techstack.md**  
  Details our technology stack for both frontend and backend, covering frameworks, libraries, and tools essential for a smooth development workflow.

- **status.md**  
  Provides a clear timeline and current project status, offering transparency on milestones, phases, and priorities throughout the development lifecycle.

- **.cursorrules**  
  Contains comprehensive guidelines on error handling, rate limiting, caching, performance optimization, testing, accessibility, security, and monitoring. These rules help ensure that API errors are handled gracefully, caching is implemented effectively, and all performance and security measures are in place.

By following these sample implementations, our project remains robust, scalable, and maintainable. The guidelines emphasize:
- **Error Handling:** Custom error types, error boundaries, and user-friendly messages.
- **Performance Optimization:** Effective caching strategies, image optimization, and robust monitoring of core web vitals.
- **Security and Accessibility:** Adherence to best practices in data protection, authentication, ARIA labels, and keyboard navigation.
- **Comprehensive Testing:** Unit, integration, and E2E tests to safeguard both functionality and user experience.

These documents serve as a blueprint, assisting every team member in maintaining a high standard of code quality and project management throughout our development process.
