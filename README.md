# FHD Tools — Next.js + PWA + RTL
واجهة عربية مستقلة مع API Route Handler وبنية Provider.

## تشغيل
npm install
npm run dev

## GitHub
git init
git add .
git commit -m "Initial FHD Tools"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/fhd-tools.git
git push -u origin main

## Vercel
Import the GitHub repository in Vercel. Next.js is detected automatically.
Add server-only environment variables if you connect an authorized external API.

## API
POST /api/jobs
{"url":"https://example.com/item"}

النسخة الحالية تجريبية. استبدل createJob في src/lib/api/provider.ts بمزود API مصرح به.

## PWA
manifest موجود في public/manifest.webmanifest. يمكن إضافة Service Worker للإنتاج حسب استراتيجية التخزين المؤقت المطلوبة.

هذه الواجهة ليست تابعة لـ Zefoy أو TikTok ولا تنفذ أتمتة أو تلاعباً غير مصرح به بمنصات اجتماعية.
