# Slack Clone fot Titan Exchange

Fully-featured Slack clone for Titan Exchange

## Prerequisites

Before you begin, make sure you have the following installed:

- Node.js (v14 or later)
- Bun (latest version) or you can use npm or what works for you
- Git

## Getting Started

Follow these steps to set up the project:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Titan-Cognitive/Titan_Exchange.git
   cd slack-clone
   ```

2. **Install Dependencies:**

   ```bash
   bun install
   bun install -g supabase-cli
   npm install @supabase/ssr @supabase/supabase-js --force
   bun add tailwindcss
   bun add eslint
   bun add react-hook-form zod @hookform/resolvers
   bun add next-themes
   bun add react-icons
   bun add @supabase/ssr @supabase/supabase-js
   bun add supabase@">=1.8.1" --dev
   bun add zustand
   bun add uploadthing @uploadthing/react
   bun add slugify uuid
   bun add shadcn-ui
   bunx --bun shadcn-ui init
   bunx --bun shadcn-ui add form
   bunx --bun shadcn-ui add input
   bunx --bun shadcn-ui add sonner
   bunx --bun shadcn-ui add avatar
   bunx --bun shadcn-ui add card
   bunx --bun shadcn-ui add separator
   bunx --bun shadcn-ui add popover
   bunx --bun shadcn-ui add dialog
   bunx --bun shadcn-ui add tabs
   bunx --bun shadcn-ui add progress
   bunx --bun shadcn-ui add collapsible  
   ```

3. **Set Up Environment Variables:**

   - Rename the `.env.example` file to `.env.local` and fill in the required environment variables.

   ```bash
   mv .env.example .env.local
   ```

4. **Run the Development Server:**

   ```bash
   bun run dev
   ```

   Your app should now be running on [http://localhost:3000](http://localhost:3000).

## Course Structure

Slack clone modules include:

- Setting up Next.js and TypeScript
- Configuring Supabase (RPC, Storage, SQL, Role Level Security)
- Styling with Tailwind CSS and Shadcn UI
- Implementing Authentication (Google Auth, GitHub Auth, Email Auth with Magic Link)
- Managing state with Zustand and React Hook Form
- Real-time communication with Socket.IO
- Handling file uploads with Uploadthing and Supbase Storage
- Advanced Next.js features and middleware

## Resources

### SQL Scripts

All SQL scripts used in this course can be found in the `sql.txt` file. These scripts will help you set up your database schema, functions, and other necessary configurations.

### Documentation Links

For detailed documentation and additional resources, refer to the `docs.tsx` file. This file contains links to various documentation pages for the libraries and tools.

### Environment Variables

Make sure to properly configure your environment variables by referring to the `.env.example` file. This file contains example values and instructions on what needs to be filled in.
---


