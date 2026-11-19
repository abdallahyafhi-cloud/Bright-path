BRIGHT PATH – ADDITIVE UPGRADE

This upgrade preserves the existing Bright Path Grade 2 platform and adds:
- Mini lesson explanations and worked examples before each practice question.
- Interactive Word Detective and Math Sprint games.
- Story Library with read-aloud and browser speech-to-text retelling where supported.
- Character avatar selection per learner.
- Parent report print layout; choose “Save as PDF” in the browser print dialog.

Existing learner accounts, progress, daily practice flow, weekly 30-question / 30-minute exam, exam history, rewards, and parent dashboard code are retained.

IMPORTANT:
- Progress remains in this browser's localStorage as in the original prototype. Do not clear browser site data.
- Speech recognition depends on browser/device support and microphone permission.
- PDF export uses the browser Print dialog; select “Save as PDF”.
- The new HTML has passed JavaScript syntax validation (node --check), but must still be tested in the deployed browser environment.

DEPLOY:
Replace the existing index.html in the GitHub repository with the index.html in this package, commit the change, and wait for Vercel to redeploy. Do not upload the ZIP itself as the website entry point.
