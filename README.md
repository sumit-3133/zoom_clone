# YOOM - Video Conferencing App

A modern, secure video conferencing application built with Next.js 14, Stream Video SDK, and Clerk Authentication. This project allows users to create, schedule, and join secure video meetings with high-quality audio and video.

![Project Banner](public/icons/logo.svg)

## 🚀 Tech Stack

- **Framework:** [Next.js 14](https://nextjs.org/) (App Router)
- **Language:** [TypeScript](https://www.typescriptlang.org/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Authentication:** [Clerk](https://clerk.com/)
- **Video SDK:** [GetStream.io](https://getstream.io/video/sdk/react/)
- **UI Components:** [shadcn/ui](https://ui.shadcn.com/)

## 🔋 Features

- **Authentication:** Secure sign-in/sign-up using Clerk (Google, GitHub, Email).
- **Instant Meetings:** Create a meeting room instantly and invite others.
- **Schedule Meetings:** Plan meetings for a future date and time.
- **Join via Link:** Seamlessly join meetings using a shared link.
- **Meeting Controls:** Toggle audio/video, manage participants, and change layouts (Grid/Speaker).
- **Personal Room:** A persistent meeting link for quick access.
- **Real-time Updates:** Low latency video and audio streaming.
- **Responsive Design:** Fully optimized for desktop and mobile devices.

## ⚙️ Environment Variables

To run this project, you will need to add the following environment variables to your `.env.local` file.

Get your keys from Clerk Dashboard and Stream Dashboard.

```env
# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_test_...
CLERK_SECRET_KEY=sk_test_...

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# Stream Video SDK
NEXT_PUBLIC_STREAM_API_KEY=...
STREAM_SECRET_KEY=...

# App Base URL
NEXT_PUBLIC_BASE_URL=http://localhost:3000
```

## 🏃‍♂️ Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/zoom-clone.git
   cd zoom-clone
   ```

2. **Install dependencies**

   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Run the development server**

   ```bash
   npm run dev
   ```

   Open http://localhost:3000 with your browser to see the result.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
