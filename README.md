# Misconception Lab — Next Founders 2026

Misconception Lab turns learning mistakes into testable hypotheses instead of treating every wrong answer as the same signal.

## Problem
A wrong answer can come from the wrong concept, a procedural mistake, missed constraints, or poor confidence calibration. Most study software treats all of these failures the same and responds with more generic practice.

## Product
The learner records the topic, suspected error cause, and confidence. A transparent evidence engine updates a misconception profile and recommends a next discriminating test designed to separate competing explanations.

## Startup model
Initial customer: independent tutors, tutoring centers, and small learning programs that need better diagnostic feedback without adopting a full LMS.

Revenue path:
- Free learner prototype
- Tutor plan: recurring subscription for saved learners, reports, and reusable diagnostic tests
- School/center plan: per-seat or cohort pricing
- Optional API/integration tier for learning platforms

The browser-only prototype keeps infrastructure costs low. A hosted version can scale by moving persistence to a managed backend while preserving the same inference interface.

See BUSINESS_MODEL.md for assumptions, pricing logic, unit economics, and go-to-market notes.

## Technical architecture
- HTML/CSS/JavaScript frontend
- Standalone transparent inference core in core.js
- Local browser persistence
- JSON export
- Deterministic Node.js tests
- Playwright end-to-end verification

## Run
Open index.html in a browser.

## Competition
Prepared for the Next Founders Hackathon 2026.
