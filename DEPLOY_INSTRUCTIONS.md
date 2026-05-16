# 🚀 LaptopRent Pro - Deploy Instructions

## Your Supabase is Already Connected ✅
URL: https://femckmuavhvxydcljodl.supabase.co
(Already in .env file — no setup needed)

## Deploy to Netlify (Free) - 3 Ways

---

### METHOD 1: Drag & Drop (Easiest - No account needed on GitHub)

1. Install Node.js from https://nodejs.org (if not installed)
2. Open terminal/command prompt in this project folder
3. Run:
   npm install
   npm run build
4. A "dist" folder will appear
5. Go to https://netlify.com → Sign up free
6. Drag the "dist" folder into Netlify drop zone
7. Your app is LIVE! ✅

---

### METHOD 2: Netlify CLI (One command deploy)

1. npm install
2. npm install -g netlify-cli
3. npm run build
4. netlify deploy --prod --dir=dist
5. Done ✅

---

### METHOD 3: GitHub → Netlify (Best for updates)

1. Push this folder to a GitHub repo
2. Go to netlify.com → New Site → Import from GitHub
3. Build command: npm run build
4. Publish directory: dist
5. Add environment variables:
   VITE_SUPABASE_URL = https://femckmuavhvxydcljodl.supabase.co
   VITE_SUPABASE_ANON_KEY = (copy from .env file)
6. Deploy ✅

---

## App URLs after deploy:
- Admin Panel: https://yoursite.netlify.app/admin
- User Portal: https://yoursite.netlify.app/user/login

## Login:
- Admin: admin@laptoprent.pro / admin123
