# IH — MX Direction 2026 · Phone Prototype

Interactive phone-sized prototype for the Independent Health Member Experience 2026 redesign.

## Screens

1. **My Health Home** — Urgent care banner, appointments, medications with check-off, goals & tracking, and bottom tab navigation
2. **AI Chat Assistant** — Conversational interface with greeting, contextual quick-action chips (Renew Lisinopril, Ask about upcoming scan, Urgent Care), and message input
3. **Chat History** — Searchable list of conversations with In Progress / Closed sections and All Chats list

## Running Locally

Open `index.html` in any modern browser. No build step or dependencies required.

The prototype renders at iPhone 14/15 Pro dimensions (393×852) centered in a phone frame. On mobile viewports it goes full-screen.

## Interactions

- Tap **Urgent care banner** or **Get Care** tab → opens AI Chat
- Tap **hamburger menu** (☰) in Chat → opens Chat History
- Tap **×** in Chat → returns to Home
- Tap any chat in history or **New message** → opens Chat
- Check/uncheck **medication checkboxes**
- Tap **suggestion chips** for visual feedback
- Screen transitions animate with directional slide
