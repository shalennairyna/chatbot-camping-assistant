# AI Chatbot Assistant — Camping & Kayaking Center

A conversational AI assistant built for a camping and kayaking 
center. The bot helps guests with tour information, pricing, 
booking, and general questions — in multiple languages.

## Project Status
🚧 In progress — deployment to client website pending.

## What It Does
- Answers guest questions instantly and accurately
- Responds in the language of the user automatically
- Covers tours, pricing, booking, safety rules, and more
- Never invents information — falls back to the team if unsure
- Maintains a warm, friendly tone at all times

## Architecture
├── `system_prompt.md`    # Bot behavior, rules, tone, logic
└── `knowledge_base.md`   # Business data: tours, prices, rules

Note: API integration handled separately.

## Tech Stack
- Anthropic Claude API
- Markdown (knowledge base)
- Web widget (in progress)

## Tools Used
- Python (core script generated with AI assistance)
- VS Code

## Key Design Decisions
- Strict language detection — responds ONLY in user's language
- All answers based exclusively on knowledge base
- Fallback logic — redirects to team if data is missing
- Tone rules — warm, concise, no corporate jargon

## What I Learned
- How to structure a large system prompt for consistent behavior
- The importance of edge cases — small details matter a lot
- How to think like a business owner, not just a developer
- Prompt engineering is closer to writing than to coding

## Author
Iryna Shalenna
[LinkedIn](https://www.linkedin.com/in/iryna-shalenna)
