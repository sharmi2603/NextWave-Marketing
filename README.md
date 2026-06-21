# NextWave Marketing

NextWave Marketing is a modern digital marketing agency website designed to help businesses establish a strong online presence and achieve sustainable growth. The platform offers services such as SEO optimization, website development, social media marketing, branding, and performance advertising.

## Features

- Responsive and modern UI
- SEO Optimization Services
- Website Development Solutions
- Social Media Marketing
- Pricing Plans
- Contact Form
- Smooth Animations and Transitions
- Mobile-Friendly Design
- Fast Performance
- Built with React and TypeScript

## Tech Stack

- React
- TypeScript
- Vite
- Tailwind CSS
- Lucide React Icons
- Vercel (Deployment)

## Project Structure

```
├── .env.example                  # Template for environment variables              
├── firebase-applet-config.json   # Firebase client connection configurations
├── firestore.rules               # Security rules and access control for the Database
├── index.html                    # Main HTML entry point for the Frontend
├── metadata.json                 # Application metadata and metadata settings
├── package-lock.json             # Locked versions of project dependencies
├── package.json                  # Manifest file containing scripts and dependencies
├── tsconfig.json                 # TypeScript compiler configuration options
├── vite.config.ts                # Vite bundler config for development & building
│
├── assets/                       # Static files (images, icons, global styling resources)
│
└── src/                          # Project Application Source Code
    ├── components/               # Frontend UI View Components
    │   ├── BlogDetail.tsx        # View component for displaying detailed blog posts
    │   ├── Dashboard.tsx         # User/Admin portal view component
    │   └── LucideIcon.tsx        # Dynamic SVG icon loader component
    │
    ├── data/                     # Frontend App Data Storage
    │   └── initialData.ts        # Mock data, baseline values, and initial state data
    │
    ├── lib/                      # Core Shared Utilities & Services
    │   # (Houses core tools like Firebase SDK initialization scripts)
    │
    ├── App.tsx                   # Main React component, router, and layout shell
    ├── index.css                 # Global CSS rules, utility classes, and variable tokens
    ├── main.tsx                  # Application mount point (renders App.tsx to index.html)
    └── types.ts                  # TypeScript types and interfaces for strict type-checking

```

## Installation

Clone the repository:

```bash
git clone https://github.com/sharmi2603/nextwave-marketing.git
```

Navigate to the project directory:

```bash
cd nextwave-marketing
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open your browser and visit:

```
http://localhost:5173
```

## Build for Production

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```

## Deployment

This project is deployed using Vercel.

Deploy manually:

```bash
vercel --prod
```

## Services Offered

- Search Engine Optimization (SEO)
- Website Design and Development
- Social Media Marketing
- Content Marketing
- Google Ads Campaigns
- Branding and Identity Design
- Analytics and Performance Tracking

## Why Choose NextWave Marketing?

- Results-Driven Strategies
- Responsive and User-Friendly Designs
- Affordable Digital Solutions
- Data-Driven Marketing Approach
- Dedicated Support and Consultation
  
## Author

Developed by NextWave Marketing

## License

This project is licensed under the MIT License.
