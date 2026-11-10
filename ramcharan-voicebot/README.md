# Ramcharan Voice Bot – deploy in ~5 minutes (no coding)

1. Get a FREE API key: https://aistudio.google.com/apikey  (Google Gemini) – click "Create API key", copy it.
2. Put this folder on GitHub: create a new repo at github.com/new, click "uploading an existing file", drag in `index.html`, `package.json`, `README.md` and the `api` folder (with chat.js inside), then Commit.
3. Go to https://vercel.com, sign in with GitHub, click "Add New > Project", import the repo, then expand "Environment Variables":
     Name: GEMINI_API_KEY    Value: (paste your key)
   Click Deploy.
4. Open the URL Vercel gives you (like https://your-project.vercel.app). Test mic and typed questions in Chrome, in a private window.
   If Vercel shows a "Deployment Protection" login for visitors: Project > Settings > Deployment Protection > set to "Disabled" (or Standard Protection off for production), then redeploy.
5. Submit that URL. No key is ever visible to visitors.

Using Groq or OpenAI instead? Use GROQ_API_KEY or OPENAI_API_KEY as the variable name.

Using xAI Grok? Use XAI_API_KEY (get it at console.x.ai) and, if needed, add MODEL with a current model name from their console.
