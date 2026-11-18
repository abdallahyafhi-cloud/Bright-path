# Bright Path — Complete Grade 2 Prototype

## Run
Open `index.html` in a modern browser. No build step is required.

## Included
- Separate Adam and Eileen learner profiles
- English skill map based on the IXL Grade 2 English categories supplied in the conversation
- Starter Grade 2 Math strands
- Practice engine with multiple-choice questions, explanations, progress, and stars
- English US browser text-to-speech where available
- Listening practice
- Speaking practice using browser speech recognition where supported, plus typed fallback
- Weekly, midterm and final practice exam modes, scored out of 30
- Rewards, trophies, room decorations and parent dashboard
- Local browser storage and JSON progress export
- Responsive layout for desktop, tablet and mobile

## Important implementation notes
This is a complete self-contained front-end prototype, not a hosted production service.
Progress is stored locally in the browser/device. It is not synchronized across devices or users.
The included question bank is a starter bank to demonstrate the full learning workflow. It is NOT the promised 4,800-question four-month encyclopedia yet.
Math categories are starter strands pending the exact school/IXL Math skill list.
Browser speech voices and microphone speech recognition depend on browser, device, permissions and internet access. The speaking feedback is rule-of-thumb encouragement, not an AI language assessment.
The theme uses simple emoji placeholders rather than licensed Sonic/Kuromi artwork.

## Deploy to Vercel
1. Extract this ZIP.
2. Import the folder/repository into Vercel, or use the Vercel CLI from this folder.
3. Framework preset: Other.
4. Build command: leave blank.
5. Output directory: `.`

For a production version, add secure authentication, database sync, a larger curated non-repeating question bank, AI speech evaluation, and licensed character artwork.
