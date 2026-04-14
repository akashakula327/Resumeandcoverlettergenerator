# AI Resume Builder

AI Resume Builder is a React + Vite application that generates a tailored cover letter, resume optimization suggestions, and a basic ATS analysis using AI.

## Project Overview

This app helps job seekers by taking the company name, experience level, job description, and existing resume content to produce:

- a professional cover letter customized to the target company and tone
- optimized resume content with achievement-focused bullet points
- keyword match analysis for the job description
- an ATS score estimate and improvement suggestions

## Key Features

- Clean responsive UI built with React and Bootstrap-style classes
- Structured AI response parsing and display
- Loading state and error handling for AI generation
- Custom CSS enhancements for modern form and result layout

## Project Structure

- `src/pages/Home.jsx` - main component and UI logic
- `src/App.css` - custom styles for hero, cards, buttons, and response layout
- `package.json` - dependencies, scripts, project metadata

## Installation

1. Clone or download the repository.
2. Install dependencies:

```bash
npm install
```

## Running the App

Start the development server with:

```bash
npm run dev
```

Then open the local Vite URL shown in the terminal.

## Usage

1. Enter the company name.
2. Choose your experience level and preferred cover letter tone.
3. Paste the job description.
4. Optionally paste your current resume content.
5. Click the generate button to get AI results.

## Notes

- The app currently uses a hard-coded Google Gemini API key in `src/pages/Home.jsx`. For production, move the key to a secure backend or environment variable.
- If the AI response format changes, the app now handles unexpected shapes and displays an error instead of crashing.

## Scripts

- `npm run dev` - start the Vite development server
- `npm run build` - create a production build
- `npm run preview` - preview the production build locally
- `npm run lint` - run ESLint checks

## License

This project can be reused for personal learning or development purposes.
