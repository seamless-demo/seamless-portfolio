# Seamless Portfolio

A modern portfolio website built with Next.js, featuring a contact form that sends messages directly to your email.

## Features

- Modern, responsive design
- Animated sections using Framer Motion
- Contact form with email integration
- Portfolio gallery with filtering
- Dark theme optimized

## Tech Stack

- Next.js 15
- React 19
- TypeScript
- Tailwind CSS
- Framer Motion
- Nodemailer for email functionality

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/seamless-demo/seamless-portfolio.git
   cd seamless-portfolio
   ```

2. Install dependencies:
   ```bash
   pnpm install
   ```

3. Create a `.env.local` file in the root directory with your email credentials:
   ```
   EMAIL_USER=your-email@domain.com
   EMAIL_PASS=your-email-password
   ```

4. Run the development server:
   ```bash
   pnpm dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Email Configuration

The contact form uses Gmail SMTP for sending emails. To set this up:

1. Enable 2-Step Verification in your Google Account
2. Generate an App Password:
   - Go to Google Account Settings
   - Security → App passwords
   - Generate a new app password for this application
3. Use this app password in your `.env.local` file

## License

MIT License