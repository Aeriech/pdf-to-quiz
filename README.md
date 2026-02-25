# PDF to Quiz

A Next.js web application that generates interactive quizzes from PDF documents. Upload a PDF, and the app will extract content and create quiz questions for you to test your knowledge or share with others.

## Features
- Upload PDF files and extract text
- Automatically generate quiz questions from PDF content
- Interactive quiz interface with scoring
- Modern UI built with Tailwind CSS
- Serverless API routes for quiz generation

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

