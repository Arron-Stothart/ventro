# Ventro

Ventro helps VCs scale their initial screening (inbound) process by creating AI versions of their investment team, allowing them to evaluate more founders through personalized pitch simulations. Each AI persona maintains the VC's unique investment thesis and communication style, complete with voice-matched responses powered by ElevenLabs. 

https://pitch.com/v/ventro-jy9mcx/782bb166-4ec9-46fe-8608-a327c6821d74


![ventro](https://github.com/user-attachments/assets/fee80678-5ed8-49a7-9701-d48426d629e6)


## Our Vision

The venture capital industry faces a critical inefficiency: VCs spend an enormous amount of time on initial screenings and managing inbound deals, taking away from their ability to focus on high-potential opportunities. Ventro solves this by combining several cutting-edge AI technologies:

- LLM-powered deck analysis with automatic CRM integration
- Voice replication using Eleven Labs' technology
- Automated note-taking and transcript analysis with Gemini
- Multilingual support for 24/7 founder engagement
- Real-time speech-to-video models for partner facial expressions (in development)

## Features

- 🎙️ Natural voice interactions powered by Eleven Labs AI
- 📝 Real-time transcription of founder responses
- 🔄 Customizable interview questions and knowledge bases
- 📊 Progress tracking and interview management
- 🎯 Focused evaluation of startup potential
- 🤝 Seamless CRM integration
- 🌍 Multilingual support
- 📈 Automated deck analysis

## Getting Started

### Prerequisites

- Node.js 18+ and npm
- An Eleven Labs API key (get one at [elevenlabs.io](https://elevenlabs.io))

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ventro.git
   cd ventro
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Copy the environment variables file and configure it:
   ```bash
   cp .env.example .env.local
   ```
   Edit `.env.local` and add your Eleven Labs API key.

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Tech Stack

- Next.js 14
- TypeScript
- Tailwind CSS
- Eleven Labs Conversation API
- Gemini API for transcript analysis
- Custom LLM models for deck analysis
- OpenAI for natural language processing
- MongoDB for data storage

## Our Approach

We believe that automation in VC isn't about replacing human judgment—it's about amplifying it. By handling initial screening and engagement automatically while maintaining each partner's authentic "voice" and investment philosophy, Ventro helps VCs focus their expertise where it matters most.

## Acknowledgments

- [Eleven Labs](https://elevenlabs.io) for their voice AI technology
- [Next.js](https://nextjs.org) for the React framework
- [Tailwind CSS](https://tailwindcss.com) for the utility-first CSS framework
- [OpenAI](https://openai.com) for language models
- [Google](https://deepmind.google/technologies/gemini/) for Gemini API
