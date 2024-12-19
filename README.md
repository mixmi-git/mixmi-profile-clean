# mixmi Profile

A customizable Web3 profile platform for creators, artists, and makers. Built with Next.js, TypeScript, and Tailwind CSS.

## Features

- 🎨 Customizable profile sections
- 🎵 Media embeds support:
  - YouTube videos
  - Spotify tracks and playlists
  - SoundCloud tracks and playlists
  - Apple Music albums and playlists
  - Mixcloud shows
  - Instagram Reels (as links)
  - TikTok (as links)
- 🛍️ Shop integration with Web3 features
- 🔗 Social links
- 💫 Interactive sticker
- 🖼️ Spotlight section for featured work
- 📱 Fully responsive design

## Tech Stack

- Next.js 14
- TypeScript
- Tailwind CSS
- shadcn/ui components
- Web3 Authentication

## Getting Started

1. Clone the repository
2. Install dependencies: `npm install`
3. Run the development server: `npm run dev`
4. Open [http://localhost:3000](http://localhost:3000)

## Project Structure

- `/app` - Next.js app directory and pages
- `/components` - Reusable React components
  - `/components/profile` - Profile-specific components
  - `/components/media` - Media embed components
  - `/components/ui` - UI components
- `/lib` - Utility functions and helpers
  - `mediaUtils.ts` - Media URL transformation utilities
  - `auth.ts` - Web3 authentication
- `/types` - TypeScript type definitions

## Features in Detail

### Media Support
- Automatic URL detection and transformation
- Responsive embeds
- Support for multiple formats and platforms

### Shop Integration
- Support for physical and digital products
- Token-gated content support
- Web3 marketplace features

### Profile Customization
- Editable sections
- Custom social links
- Interactive elements

## License

MIT License