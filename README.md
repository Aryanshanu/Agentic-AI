# Sahayak: AI Teaching Assistant for Multi-Grade Classrooms

**Sahayak** is an easy-to-use AI-powered tool made for teachers in classrooms where one teacher handles many grades at the same time. It helps teachers save time, manage lessons, and reach every student in their local language.

---

## Problems Teachers Face

- One teacher has to handle students from different grades together.
- Hard to make materials in local languages or fit for all grades.
- Not enough time to answer every student's question or prepare worksheets.
- Creating visuals or teaching aids takes too long.
- Writing or typing questions takes time.

---

## Sahayak Features

### 1. Hyper-Local Content Generation

- Teachers can ask for stories, explanations, or worksheets in any local language (like Marathi, Hindi, Telugu, etc.).
- Sahayak uses Gemini to create content that's simple and fits the local culture.
- Supports teacher requests in any language.

*Service used: Gemini 2.5 Pro (text generation and translation)*

---

### 2. Differentiated Worksheet Creation

- Teachers upload a photo of a textbook page.
- Sahayak makes worksheets or questions at different levels for each grade in the same class.
- Instantly get materials for all grades.

*Service used: Gemini 2.5 Pro (analyzing images and generating text)*

---

### 3. Instant Knowledge Base

- Teachers/students can ask questions like "Why is the sky blue?" in their own language.
- Sahayak gives clear, grade-level answers with easy examples or analogies.
- Uses recent conversation context to improve relevance.

*Services used: Firestore (stores the last 5 conversations for context), Gemini 2.0 Flash (generates grounded answers using RAG)*

---

### 4. Visual Aid Generation

- Teachers describe what they want (like, "Draw the water cycle").
- Sahayak creates simple SVG drawings or charts that can be quickly copied to the blackboard.

*Service used: Gemini 2.5 Pro (generates SVG graphics)*

---

### 5. Speech to Text

- Teachers can speak their questions instead of typing.
- Sahayak converts speech to text and handles multilingual queries for fast answers.

*Services used: Gemini 2.5 Pro (language support), Speech-to-Text (STT service)*

---

## Why Use Sahayak?

- Answers and materials in any language used by the teacher.
- Makes teaching easier for classes with mixed grades.
- Saves time by quickly creating stories, worksheets, visuals, and answers.
- Helps teachers explain tough concepts simply and clearly.

---

> **With Sahayak, every teacher gets powerful help to make sure every child in any grade and any language can learn and grow!**
