# 🪐 VibeQuest: Don't Panic Edition

**A text adventure game that teaches you how to *vibe code* using Google Antigravity.**

Inspired by *The Hitchhiker’s Guide to the Galaxy* and *Zork*, this game turns learning prompt engineering and agentic coding into an absurd, fun adventure.  
You are a fledgling vibe coder lost in the **Syntax Swamp**. Your goal: vibe with the **Antigravity Agent**, cross the bridge, launch your first mini-app, and reach **Production Planet**.

No install. No build step. Just pure vibes. 🚀

---

## 🎮 Play It Right Now

[▶️ Launch VibeQuest](https://rmathy-lang.github.io/vibequest-dont-panic/)

*(GitHub Pages – works on phone or desktop)*

---

## 🛠 How to Run Locally (30 seconds)

1. Clone the repo:
   ```bash
   git clone https://github.com/rmathy-lang/vibequest-dont-panic.git
   cd vibequest-dont-panic

2. Open the file:Double-click index.html
OR  
Run npx serve (or any static server)

That’s it. The entire game is one single HTML file with zero dependencies. What You’ll LearnHow to write ultra-specific natural-language prompts
Why details, constraints, and success criteria matter to agents
The real workflow used in Google Antigravity (and every other agentic tool)
How to iterate on AI-generated code like a pro

Each successful “vibe” gives you a mini-lesson + prompt tip.

 How to Deploy Your Own Copy (GitHub Pages)Fork this repo (or just copy the index.html)
Go to Settings → Pages
Set Source → Deploy from a branch
Branch: main
Folder: /(root)
Click Save

Your game will be live at:
https://YOUR-USERNAME.github.io/vibequest-dont-panic/

How to Add More Rooms & PuzzlesEverything lives in index.html (single file for maximum beginner-friendliness).Want to expand it? Just edit the rooms object in the JavaScript section:js

const rooms = {
  newRoomName: {
    title: "Your Room Title",
    desc: "Room description...",
    exits: { north: "anotherRoom" },
    vibes: {
      "your.*regex.*here": () => { /* magic happens */ }
    }
  }
}

We can keep vibing together to add:More puzzles
Real mini HTML apps inside the game
Sound effects / animations
Save system
Multiplayer vibe battles

 Built With Vibe CodingThis entire game was vibe-coded in one sitting using plain English + an AI agent.
Exactly what the game teaches you to do.Made with  for L&D teams and coding newbies everywhere. Contributing & FeedbackFound a bug? Want a new room? Just open an issue or PR.Or reply in the original thread and we’ll keep vibing the next feature together.Don’t panic. Just vibe.— Richard Mathy + Grok (your senior software engineer sidekick)

**Copy everything above** (including the ```markdown fences) and paste it into a new file called `README.md` in the root of your repo.

Then commit & push — GitHub will automatically show this beautiful readme on the repo homepage.

Want me to also give you a `CONTRIBUTING.md` or a list of the next 5 rooms/puzzles we can add next? Just say the word and we keep the vibes flowing! 🪐

Explain vibe coding techniques

Suggest next puzzle ideas

Revise README for clarity

Built With Vibe CodingThis entire game was vibe-coded in one sitting using plain English + an AI agent.
Exactly what the game teaches you to do.Made with  for L&D teams and coding newbies everywhere. Contributing & FeedbackFound a bug? Want a new room? Just open an issue or PR.Or reply in the original thread and we’ll keep vibing the next feature together.Don’t panic. Just vibe.— Richard Mathy + Grok (your senior software engineer sidekick)



