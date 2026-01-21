# Collective-Class-Note
AI system that merges multiple student notes into one clean, complete set of class notes.

Project Name: Collective Class Notes

Overview
This project explores a system where multiple students in the same class session submit their personal notes, and AI merges them into one high quality master set of notes. The goal is to reduce missed information, improve accuracy, and give every student a complete study resource.

Problem
Students often miss parts of lectures due to distractions, speed of instruction, or unclear explanations. Individual notes are incomplete and inconsistent. Shared documents become messy and hard to trust.

Solution
Each student submits their notes after class. The system groups overlapping content, removes duplicates, resolves gaps using multiple sources, and produces a clean structured final version for everyone.

Core Goals

* Accept multiple note submissions for a single class session
* Merge overlapping content intelligently
* Fill missing details using consensus across submissions
* Flag conflicts or low confidence sections instead of guessing
* Generate clean, readable output for studying
* Support exports like PDF and Markdown

MVP Scope

* Create class spaces and daily sessions
* Allow students to paste or upload notes
* Lock submissions when the session ends
* Generate a master note automatically
* Display contribution visibility
* Download final notes

Technical Direction

* Web frontend for submissions and viewing
* Backend API for storage and processing
* Database for users, sessions, and submissions
* AI pipeline for chunking, clustering, and merging
* Background jobs for processing

Why This Project
This project combines systems engineering, backend architecture, AI pipelines, automation, and real user value. It serves as a portfolio piece focused on reliability, scalability, and responsible AI usage.

Status
Planning phase. Architecture, data model, and MVP scope under active design.
