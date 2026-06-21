# nexora-ai-assistant
# Nexora AI Assistant — Intelligent Business Assistant

A JARVIS-style AI business assistant built with n8n that manages leads, 
finances, and business targets through natural conversation — no manual 
spreadsheet work needed.

## What it does
- Answers business questions in natural language ("What are my pending payments?")
- Saves new leads directly to Google Sheets through conversation
- Logs income and expenses by just telling it what happened
- Reads and updates business targets on command
- Supports Hindi, English, and Hinglish — switches automatically
- Remembers last 10 messages for context-aware conversations

## Business problem it solves
Business owners lose hours every week manually updating CRMs and spreadsheets.
This assistant lets them manage their entire business by just sending a WhatsApp-
style message — the AI handles the rest.

## Tech stack
- n8n (workflow automation + AI agent)
- Groq API — LLaMA 3.3 70B (conversational AI)
- Google Sheets API (Finance Tracker + Lead Tracker + Targets)
- n8n AI Agent node with memory buffer
- 6 custom tools for read/write operations

## Capabilities
- Lead management — add, update, track pipeline
- Finance tracking — log income, expenses, payment status
- Target management — read and update business goals
- Daily priorities — AI suggests top 3 actions based on live data
- Multilingual — responds in whatever language you write in

## Built for
Nexora Marketing Agency — delivered as a real client project, June 2026

## Workflow file
Import `Nexora_Assistant.json` directly into n8n to use this workflow.
