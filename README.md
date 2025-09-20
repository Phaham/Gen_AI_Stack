## GenAI Stack - No-Code Workflow Builder

GenAI Stack is a visual platform that enables users to create AI-powered document processing workflows without coding. It combines modern AI capabilities with an intuitive drag-and-drop interface for building automated document analysis pipelines.

### Key Features
- Visual Workflow Builder: Drag-and-drop interface for creating document processing workflows
- AI Document Processing: Supports PDF analysis with multiple AI models (OpenAI GPT-4, Google Gemini)
- Intelligent Search: Vector-based document retrieval using ChromaDB
- Real-time Collaboration: Multi-user workspace management
- Chat Interface: Natural language querying of processed documents

### Technology Stack
- Frontend: Next.js 14, TypeScript, Tailwind CSS, shadcn/ui
- Backend: FastAPI, Python 3.13, PostgreSQL, SQLAlchemy
- AI/ML: OpenAI GPT-4, Google Gemini, ChromaDB vector database
- Authentication: JWT-based secure authentication

### Quick Setup

Install dependencies:

```
### Backend
cd backend && python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```
```
### Frontend
cd frontend && pnpm install
Configure environment variables:
```

- Set up database connection (PostgreSQL)
- Add OpenAI and/or Google AI API keys


Run application:

```
### Backend (port 8000)
- python main_simple.py

### Frontend (port 3000)
pnpm dev
```

- Create an account and set up your workspace
- Upload documents (PDFs) for processing
- Build workflows using visual nodes and connectors
- Query documents through chat interface
- Export results and insights

### Project Highlights:

- Built with modern web technologies and best practices
- Supports multiple AI providers for flexibility
- Responsive design works on desktop and mobile
- Secure user authentication and data isolation
- Scalable architecture suitable for enterprise use