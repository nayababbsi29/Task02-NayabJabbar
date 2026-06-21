# Project 2: Chain-of-Thought (CoT) Logic Engine

## Goal
Force the AI to reason step-by-step through logic problems and catch its own mistakes before giving a final answer.

## What I Did
- Built a prompt that requires the AI to show its reasoning steps before the answer
- Added a self-correction step where the AI reviews its own logic
- Tested it against classic logic-trap problems that usually confuse LLMs

## Tests Performed
1. Bat and Ball problem (classic math trap) — Passed
2. Order of operations (15 - 5 × 2) — AI correctly caught a student's mistake
## What I Learned
Adding a self-correction step makes the AI much more reliable on logic problems where a quick first answer is usually wrong.   
   
