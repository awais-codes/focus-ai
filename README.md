# Focus AI - Chrome Extension

A smart Chrome extension that helps users maintain focus and improve productivity using AI-powered insights and focus modes.

## Features

- Real-time focus tracking and scoring
- Multiple focus modes (Deep Work, Research, Creative, Break)
- Productivity analytics and insights
- Distraction detection and gentle reminders
- Customizable work/break schedules

## Tech Stack

- React 18
- Vite
- Tailwind CSS
- Shadcn/UI
- Chrome Extension APIs
- Lucide Icons

## Prerequisites

- Node.js 18+
- npm
- Chrome browser

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/ai-focus-assistant.git
cd ai-focus-assistant
```

2. Install dependencies:

```bash
npm install
```

3. Install Shadcn/UI components:

```bash
npx shadcn-ui init
npx shadcn-ui add card button progress
```

4. Build the extension:

```bash
npm run build
```

5. Load in Chrome:

- Open Chrome
- Go to `chrome://extensions/`
- Enable Developer mode
- Click "Load unpacked"
- Select the `dist` folder

## Development

```bash
npm run dev
```

## Build

```bash
npm run build
```

## Project Structure

```
focus-ai/
├── src/
│   ├── components/
│   ├── main.jsx
│   └── App.jsx
├── public/
│   └── manifest.json
├── assets/
├── index.html
├── postcss.config.cjs
├── tailwind.config.cjs
├── tsconfig.json
├── tsconfig.node.json
└── vite.config.ts
```

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit changes
4. Push to branch
5. Open a Pull Request

## License

AGPL
