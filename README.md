# 20 Questions (AI Edge Gallery Skill)

A lightweight, fully offline JavaScript skill for the Google AI Edge Gallery app, powered by Gemma 4. 

This skill allows you to play the classic game of 20 Questions with your local LLM. It features a dual-role system:
* **The LLM Guesses:** Think of a word, and the LLM will ask strategic Yes/No questions to narrow it down.
* **You Guess:** The LLM secretly generates a word and locks it into the webview's local storage to prevent hallucination or cheating mid-game.

## Folder Structure
To use this skill, ensure your files are organized exactly like this:

```text
20-questions/
├── SKILL.md
└── scripts/
    └── index.html
