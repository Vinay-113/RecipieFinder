# Recipe Finder Application (Spoonacular)

This is a React (Vite) project for a Recipe Finder app integrated with the Spoonacular API.
It includes search, recipe cards, detail view, favorites (localStorage), and routing.

## How to use
1. Extract the ZIP.
2. Copy `.env.example` to `.env` and set your Spoonacular key:
   `VITE_SPOONACULAR_KEY=your_key_here`
3. Install dependencies:
   `npm install`
4. Run dev server:
   `npm run dev`
5. Build for production:
   `npm run build`

## Notes
- If you deploy to Vercel or Netlify, add `VITE_SPOONACULAR_KEY` as an environment variable.
- For production consider server-side proxy to hide the API key.
