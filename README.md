# Clinic Companion — Lab 5

A two-page static website for an SMU Generative AI for Business course project. Includes a homepage, original About page, interactive Student Health Quick Guide, and access to the existing Chatling Clinic Companion chatbot.

## Video integrated

The Gemini-generated video has been included as `assets/clinic-companion.mp4`, trimmed from the uploaded 10-second original to approximately 5 seconds for the assignment. It is configured to play automatically, muted, inline and on a loop on the homepage. No separate upload or video setup is needed if you upload the entire website folder.

## Check Chatling before submitting

The site offers a chat panel that attempts to display your original Chatling share link and includes a direct-open fallback. **This is not a verified working website embed**: shared chatbot pages may refuse to appear inside iframes. For a reliable embedded chatbot, go to Chatling, obtain the official **Add to Website / Embed** widget code, and paste that script before `</body>` on BOTH `index.html` and `about.html`. Verify it works on both published pages.

## GitHub Pages steps

1. Sign in to GitHub and create a public repository such as `clinic-companion`.
2. Upload the **contents** of this folder to the root of your repository: `index.html`, `about.html`, `style.css`, `script.js`, and `assets/` (with the AI MP4 inside).
3. Choose **Settings → Pages → Build and deployment → Deploy from a branch → main → / (root) → Save**.
4. Once published, open `https://YOUR-USERNAME.github.io/clinic-companion/`. Test Home, About, Quick Guide, looping video, and the chatbot on both pages before submitting the URL in Canvas.

## Safety

This educational demo intentionally does not collect student information or diagnose. School policies, student-specific plans, and nurse directions take precedence. In an emergency, follow emergency procedures and call 911.
