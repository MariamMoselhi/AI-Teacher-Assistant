# AI-Powered Teacher Assistant

An intelligent educational platform that transforms heterogeneous learning resources into structured teaching materials using **Large Language Models (LLMs)**, **OCR**, and **modular AI workflows**.

The system automates the preparation of educational content by extracting knowledge from **PDFs, PowerPoint presentations, Word documents, websites, images, audio, and video**, then generating **lecture notes, professional presentation slides, quizzes, worksheets, summaries, teaching scripts, and research reports**.

Designed with a modular architecture, the project combines advanced content extraction, semantic reasoning, mathematical content preservation, image-aware lecture generation, and graph-based AI orchestration to provide a comprehensive AI assistant for educators.

---

# Features

- Multi-source educational content extraction
- PDF, DOCX, PPTX, Website, Audio, Video, and Image support
- AI-powered lecture generation
- Semantic image-to-section matching
- Mathematical equation and derivation preservation
- Automatic lecture PDF generation
- Advanced OCR pipeline for scanned documents and educational images
- Automatic generation of quizzes, summaries, worksheets, and teaching scripts
- AI-powered research assistant
- Graph-based workflow orchestration
- Modular and extensible architecture

---

# System Architecture

```text
                    Educational Resources
   ┌────────────────────────────────────────────────────┐
   │ PDF │ PPT │ DOCX │ Website │ Images │ Audio │ Video │
   └────────────────────────────────────────────────────┘
                           │
                           ▼
                 Content Extraction Layer
                           │
                           ▼
                OCR & Document Processing
                           │
                           ▼
              Unified Educational Knowledge
                           │
                           ▼
               AI Educational Processing Layer
          ┌──────────────────────────────────────┐
          │ Lecture Generator                    │
          │ Research Agent                       │
          │ Quiz Generator                       │
          │ Summary Generator                    │
          │ Worksheet Generator                  │
          │ Teaching Script Generator            │
          └──────────────────────────────────────┘
                           │
                           ▼
            Professional Educational Outputs
```

---

# Core Modules

## Content Extraction

Extracts educational content from multiple heterogeneous resources.

Supported formats include:

- PDF
- DOCX
- PPTX
- Websites
- Images
- Audio
- Video

Each extractor converts its source into clean textual information suitable for AI processing.

---

## OCR Engine

The OCR module goes beyond simple text recognition.

It includes:

- Image preprocessing
- Blob detection
- Region segmentation
- Layout analysis
- Frame detection
- Visual language model transcription

This enables accurate extraction from scanned lecture notes, screenshots, diagrams, and educational images.

---

## Lecture Generator

Automatically generates complete university-style lectures.

Pipeline:

1. Input Validation
2. Intelligent Content Extraction
3. Knowledge Merging
4. Lecture Structure Generation
5. Parsing & Normalization
6. Professional PDF Slide Generation

Generated lectures include:

- Title
- Learning Objectives
- Introduction
- Main Sections
- Mathematical Derivations
- Real-world Examples
- Common Misconceptions
- Summary
- Review Questions

---

## Research Agent

A dedicated AI agent responsible for research-oriented educational tasks.

Capabilities include:

- Structured reasoning
- Academic content generation
- Information synthesis
- Tool-assisted research workflows

---

## Educational Content Generators

Generate additional learning resources from the same extracted knowledge.

Supported outputs include:

- Lecture Notes
- Quizzes
- Worksheets
- Summaries
- Teaching Scripts

---

# Lecture Generation Pipeline

```text
User Educational Resources
            │
            ▼
      Input Validation
            │
            ▼
Intelligent Content Extraction
            │
            ▼
      Knowledge Merging
            │
            ▼
 Lecture Structure Generation
            │
            ▼
 Parsing & Normalization
            │
            ▼
 Professional PDF Generation
```

---

# Key Technologies

- Python
- Large Language Models (LLMs)
- OCR
- Prompt Engineering
- Graph-based AI Workflows
- Document Processing
- Mathematical Content Processing
- PDF Generation
- Image Processing
- Modular Software Architecture

---

# Project Structure

```text
Teacher_Assistant/
│
├── Extractors/
├── OCR/
├── LectureGenerator/
├── LectureAgent/
├── ResearchAgent/
├── Generators/
└── Utils/
```

---

# Project Goal

The goal of this project is to assist educators by automating the creation of high-quality educational materials.

Instead of manually preparing lectures from multiple educational resources, instructors can provide their learning materials, and the system automatically extracts relevant knowledge, organizes it into pedagogically structured content, and generates professional educational outputs ready for classroom use.

The modular design allows the platform to be easily extended with additional AI capabilities while maintaining scalability and maintainability.

---

# Highlights

- Multi-format educational resource support
- Intelligent knowledge extraction
- AI-generated university lectures
- Semantic image integration
- Mathematical equation preservation
- Advanced OCR pipeline
- Automated educational content generation
- Research assistant
- Professional PDF slide generation
- Modular AI architecture

---

# License

This project was developed as part of a **Graduation Project** and is intended for educational and research purposes.

---

> **Empowering educators through intelligent automation and AI-driven educational content generation.**
