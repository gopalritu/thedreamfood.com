THE DREAM FOOD - VERCEL STATIC DEPLOYMENT

This is a plain static HTML website. Keep index.html in the project root.

Vercel dashboard settings when importing this folder/repository:
- Framework Preset: Other
- Root Directory: ./ (project root)
- Build Command: leave empty
- Output Directory: leave empty (or . if the dashboard requires a value)
- Install Command: leave empty

Then redeploy.

CLI alternative:
1. Install Node.js if needed.
2. Open Terminal in this folder.
3. Run: npx vercel
4. Follow prompts, then run: npx vercel --prod
