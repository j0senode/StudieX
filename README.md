# StudieX

An AI-powered study tool that transforms your notes and PDF documents into quizzes and flashcards instantly.
What it does
You paste your notes or upload a PDF, pick your settings, and StudieX generates a full quiz or flashcard deck from the content using AI. It handles everything from extraction to grading — no manual question writing needed.
Input methods

Paste text — drop in lecture notes, textbook excerpts, or any written material
Upload PDF — drag and drop a PDF and the app extracts all the text client-side before sending it to the AI. Works with any text-based PDF like lecture slides, papers, or textbooks.

Quiz mode
Generates multiple choice questions from your material. You go through them one at a time, select an answer, check it (the correct answer is revealed inline), then move to the next. At the end you get a scored results screen showing your percentage, a pass/fail grade, and a full breakdown of every question with your answer vs the correct one.
Flashcard mode
Generates front/back flashcard pairs. You flip each card with a click, navigate with prev/next, and jump to any card via dot indicators at the bottom.
Settings

Difficulty — Easy, Medium, or Hard controls how challenging the AI makes the questions
Count — slider to set how many questions or cards to generate (3–15)

Tech

Frontend — React, deployed on the web
Backend — Node.js / Express API hosted on Render
AI — Llama 3.3 70B via Groq for fast generation
PDF parsing — pdf.js running entirely in the browser, nothing is uploaded to a server
