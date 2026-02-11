# Yash Portfolio

## Overview
A personal portfolio website for Yash Gupta, a developer from India. Built with React, Vite, TypeScript, Tailwind CSS, and shadcn/ui components.

## Recent Changes
- 2026-02-11: Migrated from Lovable to Replit environment. Updated Vite config to bind to port 5000 with all hosts allowed. Removed lovable-tagger dependency.

## Project Architecture
- **Frontend**: React 18 + TypeScript + Vite
- **Styling**: Tailwind CSS + shadcn/ui components
- **Routing**: react-router-dom v6
- **State**: @tanstack/react-query
- **Structure**:
  - `src/pages/` - Page components (Index, NotFound)
  - `src/components/` - Custom components (Sidebar, sections)
  - `src/components/ui/` - shadcn/ui components
  - `src/data/resumeData.ts` - Resume/portfolio data
  - `src/hooks/` - Custom hooks
  - `src/lib/` - Utilities

## User Preferences
- Dark theme portfolio (black background, white text)
- Minimal design with zero border radius
