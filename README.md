# Meeting Co-pilot

*Your documents, explained by AI. Anytime, anywhere.*

Meeting Co-pilot is a revolutionary platform that transforms how you present documents to clients. Upload your presentations or PDFs once, and our AI agent will explain them to your clients on your behalf - answering questions, highlighting key points, and providing visual references, all through an interactive voice and video experience.

## The Problem We Solve

As professionals, we often:
- Repeat the same presentations to different clients
- Spend valuable time explaining standard documents
- Need to be available for every client meeting
- Struggle to maintain consistency across presentations

**Meeting Co-pilot handles all this for you, giving you back your time while ensuring your clients receive consistent, high-quality explanations.**

## Key Features

- **AI-Powered Presentations**: Upload your PDF or PPT and our AI learns to explain it perfectly
- **Interactive Q&A**: Clients can ask questions and get immediate, contextual answers
- **Visual References**: AI shows relevant slides while explaining concepts
- **Simple Sharing**: Just share a link for clients to join the presentation session
- **No Downloads Required**: Works entirely in the browser
- **Always Available**: Your clients can schedule sessions at their convenience

## How It Works

1. **Upload** your presentation or PDF to our platform
2. **Ingestion**: System processes the document by extracting text and generating visual references
3. **Indexing**: Content is organized in a vector database for efficient semantic search
4. **Link Sharing**: You receive a unique link to share with clients
5. **Client Session**: Clients join a live session where our AI presents your document
6. **Interactive Q&A**: AI explains slides and answers questions using the indexed content

## Technology

Meeting Co-pilot is built using cutting-edge technology:

- **Next.js**: Creating a responsive, modern web interface
- **LiveKit**: Powering real-time voice and video communication
- **TypeScript**: Type-safe code for robust development
- **Tailwind CSS**: Utility-first styling approach

### Backend Services

Meeting Co-pilot connects to a powerful backend that provides:

- **RAG-Enabled Presentation**: Contextual understanding of your documents
- **Voice Interaction**: Natural language processing for spoken queries
- **Semantic Search**: Finding the most relevant content for questions
- **PDF/PowerPoint Processing**: Automatic extraction and preparation of documents
- **OpenAI Integration**: For embeddings, text generation, and speech synthesis
- **Deepgram**: For accurate speech recognition

*For details on setting up the backend services, please refer to the backend repository.*

## Getting Started

### For Document Owners

1. **Sign up** for a Meeting Co-pilot account
2. **Upload** your presentation or PDF
3. **Configure** your preferences (AI voice, presentation style)
4. **Share** your unique presentation link with clients
5. **Review** session analytics to improve your materials

### For Clients/Viewers

1. **Click** the shared link
2. **Join** the session (no account required)
3. **Listen** to the AI explanation
4. **Ask questions** at any time
5. **Request clarification** on specific slides or concepts

## Technical Implementation

This repository contains the frontend implementation of Meeting Co-pilot, built with:

- **Next.js**: React framework for the application
- **LiveKit**: Real-time voice and video communication
- **TypeScript**: Type-safe code for robust development
- **Tailwind CSS**: Utility-first styling approach

### Setup for Development

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/meeting-co-pilot.git
   cd meeting-co-pilot

2. Install dependencies:
   ```bash
   pnpm install

3. Set up environment variables (see .env.example)
   
4. Run the development server:
   ```bash
   pnpm run dev
Open http://localhost:3000 in your browser  

**Meeting Co-pilot** — Your documents, expertly explained, every time.  
For support or inquiries: work@omchauhan.in
