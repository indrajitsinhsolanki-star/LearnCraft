# LearnCraft
Give every teacher a co-teacher.
For India's 9.5 million teachers - The Next lecture made easy with LearnCraft - Your next lesson plan - is ready in 60 seconds.
LearnCraft — AI Lesson Co-pilot for India's Teachers

LearnCraft turns a 3-hour lesson prep into a 60-second conversation — so teachers can spend their time where it matters most: with their students.


🌐 Live Demo
→ Try LearnCraft live
No login. No install. Just describe your class and hit Generate.

The Problem
India has 9.5 million teachers. Most spend 2–3 hours every day on lesson planning — searching Google, copying from last year's notes, writing activities that don't match their classroom reality.
That's time stolen from actual teaching.
And most EdTech tools are built for students — not the people who teach them.

What LearnCraft Does
You tell LearnCraft:

What subject you're teaching
Which grade
How long the lesson is
What you want students to be able to do by the end
What your classroom actually looks like (40 students? chalk board only? rural Maharashtra?)

LearnCraft generates a complete, classroom-ready lesson plan in under 60 seconds — streamed live, structured in 8 sections, written in the language you teach in.

The 8-Section Lesson Plan
Every lesson plan LearnCraft generates includes:
#SectionWhat it is🎯Lesson ObjectiveOne crisp sentence: what students will do, not just "know"⚡HookA curiosity-first opening — no content delivery yet📖Teaching FlowNumbered beats with the best analogy + #1 misconception to address🤝Student ActivityPair/group work — instructions you can read aloud verbatim❓Discussion QuestionsEasy → Application → Creative/Opinion📊Exit Ticket3 questions with answer key — tells you what landed and what didn't🏠Extension TaskOne genuinely interesting optional homework (never "read pages X–Y")⚠️Teacher Watch-Outs3 real things that derail this specific lesson — and how to handle them

What Makes It Different
It's built for the Indian classroom — not a fantasy school.

Describe your classroom reality ("42 students, chalk board, no projector, rural Rajasthan") and every activity adapts to it
Works in 8 languages: English, Hindi, Hinglish, Tamil, Telugu, Kannada, Marathi, Bengali
Grade-aware pedagogy: play-based for Grades 1–5, inquiry for 6–8, exam-aware for 9–12
Subject personality: Science leads with phenomena, History leads with human stories, Languages lead with voice
Aligned with NCF 2023 principles — competency-based, activity-first, assessment-for-learning


Quick Start

Open the live demo
Click one of the quick-fill example pills to load a pre-filled scenario
Hit Generate My Lesson Plan
Watch it stream in real time — rendered into 8 clean sections
Copy to clipboard, or hit Regenerate for a fresh take

Keyboard shortcut: Ctrl + Enter to generate

Try These Examples
ExampleWhat it tests📐 Math — Fractions (Grade 5, English)Primary school, chalk board, concrete pedagogy🌿 Science — Photosynthesis (Grade 7, English)Middle school, inquiry-based, projector available📜 History — 1857 Revolt (Grade 9, English)High school, exam-aware, analytical✍️ English — Poetry (Grade 6, Hinglish)Code-switching output, mixed ability, emotional learning

Tech Stack
LayerToolFrontendVanilla HTML, CSS, JavaScript — zero dependenciesAI EngineClaude API (claude-sonnet-4)StreamingAnthropic Messages API with stream: trueHostingGitHub Pages / Netlify / VercelFontsPlayfair Display · DM Sans · Space Mono (Google Fonts)
No framework. No build step. No npm install. Open learncraft-demo.html in a browser and it works.

Prompt Architecture
The quality of LearnCraft's output comes from a carefully engineered three-layer prompt system:
System Prompt
└── Core pedagogy rules (NCF 2023, Bloom's Taxonomy, Indian classroom norms)

User Prompt
├── Teacher inputs (subject, grade, duration, goal, language, classroom)
├── Grade-band injection (automatically adapts for Gr 1–5 / 6–8 / 9–12)
└── Subject injection (Science / History / Language each get different philosophy)

Output Format
└── 8 emoji-anchored sections, timed, warm tone, language-aware
The same Claude model with a generic prompt gives generic output. The LearnCraft prompt architecture is the product.

Files
learncraft/
├── index.html              ← Main product demo (live app)
├── learncraft-brand.html   ← Brand identity (name, colours, typography, logo)
└── README.md               ← You are here

Roadmap
VersionFeatureStatusv1.0AI Lesson Plan Generator✅ Livev1.5NCF 2023 + NCERT curriculum mapping🔜 Nextv2.0Teacher memory & personalisation📅 Plannedv3.0School intelligence dashboard for HMs & DEOs🔭 Vision

Known Limitations (Honest Section)

API key is client-side — fine for demos, needs a backend proxy before public scale
No user accounts or saved lessons yet — coming in v2.0
Requires internet — offline mode planned for low-connectivity areas
Output quality depends on prompt specificity — vague learning goals get vaguer plans


Built At
This project was built at a 40-hour AI hackathon focused on social impact across education, climate, health, and productivity.
Challenge: Build an AI product that solves a real-world problem using Claude + no-code/low-code tools.
Our answer: Give India's 9.5 million teachers a co-pilot that turns lesson prep from a 3-hour Sunday evening into a 60-second Monday morning task.

About the Builder
Indrajitsinh Solanki
@indrajitsinhsolanki-star
Built with ☕, Claude, and a deep respect for teachers everywhere.

Powered By
Show Image
Show Image
Show Image

"Every teacher deserves a co-teacher. LearnCraft is that co-teacher."
