# Clinic Companion — Lab 5

A two-page static website for an SMU Generative AI for Business course project. Includes a homepage, original About page, interactive Student Health Quick Guide, and access to the existing Chatling Clinic Companion chatbot.

## Two steps to finish the required integrations

1. **AI-generated video (required).** Generate a ~5-second video in an AI video tool such as Gemini, export it as MP4, rename it `clinic-companion.mp4`, and upload it into the `assets/` folder. The homepage already has a muted, autoplaying, looping, inline video player. Without the MP4, it displays a labeled placeholder. **The placeholder is not an AI-generated video and does not meet the video requirement.**
2. **Chatbot widget (recommended).** The site currently offers a chat panel that attempts to display your original Chatling share link and includes a direct-open fallback. For a reliable embedded chatbot, go to your Chatling project, find its **Add to Website / Embed** widget code, and paste that official script immediately before `</body>` in BOTH `index.html` and `about.html`. You can then remove or keep the existing chat panel. Verify the chatbot works on both published pages. Shared chatbot pages may refuse to appear inside iframes.

## Suggested AI video prompt

> Create a 5-second realistic, warm, professional promotional video for a school-health website called Clinic Companion. A bright modern elementary-school classroom: a teacher calmly reviews a tablet showing a simple abstract healthcare assistance interface, then looks reassured while a school nurse smiles in the background. Natural daylight, soft sage and teal palette, subtle camera movement, welcoming and trustworthy atmosphere. No readable text, no logos, no identifiable students, no medical procedures. Landscape 16:9.

## GitHub Pages steps

1. Sign in to GitHub and create a public repository such as `clinic-companion`.
2. Upload the **contents** of this folder to the root of your repository: `index.html`, `about.html`, `style.css`, `script.js`, and `assets/` (with the AI MP4 inside).
3. Choose **Settings → Pages → Build and deployment → Deploy from a branch → main → / (root) → Save**.
4. Once published, open `https://YOUR-USERNAME.github.io/clinic-companion/`. Test Home, About, Quick Guide, looping video, and the chatbot on both pages before submitting the URL in Canvas.

## Safety

This educational demo intentionally does not collect student information or diagnose. School policies, student-specific plans, and nurse directions take precedence. In an emergency, follow emergency procedures and call 911.
