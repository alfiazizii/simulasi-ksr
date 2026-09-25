# KSR IPS Pro CBT

KSR IPS Pro CBT is a single-page web application designed for junior high school students preparing for IPS (Social Sciences) competency exams. The app combines interactive lessons, a virtual tutor, and a CBT-style quiz simulation to help learners study efficiently and practice in a structured way.

## Purpose

This project aims to:

- Provide learning modules for four IPS subjects: Ekonomi, Sosiologi, Geografi, and Sejarah
- Support self-paced learning through organized study content
- Allow students to ask simple conceptual questions through a built-in chatbot
- Simulate a computerized test environment with scoring and review

## Features

- Home dashboard with quick access to major learning areas
- Subject-based learning modules for:
  - Ekonomi
  - Sosiologi
  - Geografi
  - Sejarah
- Chatbot assistant for IPS concepts and keyword-based explanations
- CBT simulation with:
  - timer
  - question navigation
  - marked doubtful answers
  - answer scoring with penalty rules
  - final score summary
  - per-subject diagnostic analysis
- Review screen with:
  - correct/incorrect answers
  - answer explanations
  - discussion of conceptual understanding
- Responsive layout for desktop and mobile devices

## Project Structure

This project is a front-end app built as a single HTML file containing:

- module data
- quiz data
- chatbot knowledge base
- UI components
- app logic
- React rendering code

## Technologies Used

- HTML
- JavaScript
- React
- ReactDOM
- Babel
- Tailwind CSS (used via class names in the HTML)

## Usage

1. Open the `index.html` file in a browser.
2. Use the navigation to access:
   - Home
   - Modul Kisi-Kisi
   - Tanya Guru
   - Simulasi CBT
3. Explore the study material by subject.
4. Ask questions in the chatbot using relevant IPS keywords.
5. Start the CBT simulation and complete the quiz.
6. Review results and study the explanations provided.

## Notes

- The app is intended as an educational prototype and demo.
- Quiz content and study material are static and embedded directly in the page.
- The chatbot uses keyword matching to return relevant responses, so it works best with plain topic-based questions.

## Recommended Setup

For best results:

- Use a modern browser such as Chrome, Edge, or Firefox
- Keep the app in a local folder and open `index.html` directly
- Ensure internet access is available if external libraries are loaded via CDN

## License

This project is intended for educational and personal use. Please check with the project owner before reusing it for commercial purposes.
