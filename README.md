# PDF to Quiz

A Next.js web application that generates interactive quizzes from PDF documents. Upload a PDF, and the app will extract content and create quiz questions for you to test your knowledge or share with others.

## Features
- Upload PDF files and extract text
- Automatically generate quiz questions from PDF content
- Interactive quiz interface with scoring
- Modern UI built with Tailwind CSS
- Serverless API routes for quiz generation

## 🚀 Live Demo
This is the live demo, you can check it [here](https://aeriech-pdf-to-quiz.vercel.app/).

## Getting Started

### Prerequisites
- Node.js (v18 or newer recommended)
- pnpm (or npm/yarn)

### Installation
1. Clone the repository:
	```bash
	git clone https://github.com/Aeriech/pdf-to-quiz.git
	cd pdf-to-quiz
	```
2. Install dependencies:
	```bash
	pnpm install
	# or
	npm install
	```

### API Key Setup

To enable quiz generation, you need a Google Generative AI API key:

1. Go to [Google AI Studio API Keys](https://aistudio.google.com/api-keys).
2. Sign in and create a new API key.
3. Copy your API key.
4. Create a `.env` file in your project root (if it doesn't exist).
5. Add the following line to your `.env` file:
	```env
	GOOGLE_GENERATIVE_AI_API_KEY=your_api_key
	```
6. Replace `your_api_key` with your actual API key.

### Development
Start the development server:
```bash
pnpm dev
# or
npm run dev
```
Visit [http://localhost:3000](http://localhost:3000) to view the app.

### Build for Production
```bash
pnpm build
# or
npm run build
```

### Folder Structure
- `app/` — Next.js app directory (routes, pages, API)
- `components/` — UI and quiz components
- `lib/` — Utility functions and schemas

## Configuration
- Tailwind CSS for styling
- TypeScript for type safety
- Next.js API routes for backend logic

## License
This project is licensed under the MIT License.

---

Feel free to contribute or open issues for suggestions and bug reports!

