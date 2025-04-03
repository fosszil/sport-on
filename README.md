# SportOn

SportOn is a web app for the badminton community. Find players, discover and book courts, join tournaments, and share updates with other players.

## Features

- **Player profiles** — create an account, upload a profile photo, and browse players.
- **Tournaments** — create and manage tournaments, register to play, and filter by singles, doubles, or mixed doubles.
- **Court bookings** — search courts by name, location, or city and book a date and time slot.
- **Court details** — view photos, amenities, hourly prices, contact information, and maps.
- **Community** — share posts and images, reply to discussions, and see new posts and replies in realtime.
- **Personal dashboard** — view your profile, tournament registrations, and courts and tournaments you manage.

## Built with

Next.js, React, TypeScript, Tailwind CSS, and Supabase for authentication, database, image storage, and realtime updates.

## Getting started

You need Node.js, npm, and a Supabase project configured with the app's database tables and storage buckets.

1. Install dependencies:

   ```bash
   npm install
   ```

2. Create a `.env.local` file in the project root with your Supabase credentials:

   ```env
   NEXT_PUBLIC_SUPABASE_URL=https://your-project.supabase.co
   NEXT_PUBLIC_SUPABASE_ANON_KEY=your-anon-key
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

Open [localhost:3000](http://localhost:3000) in your browser. Restart the development server after changing environment variables.

To build and run for production:

```bash
npm run build
npm start
```
