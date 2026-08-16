cd /d C:\Users\ADNAN\Desktop\fb\Ecoomerce

npm install
npx prisma generate
npx prisma db push
npx tsx scripts/seed-payments.ts
npx tsx scripts/seed.ts
npx tsx scripts/seed-international-payments.ts
npm pkg set scripts.dev="next dev -p 3000"

npm pkg set scripts.dev="next dev -p 3000"
npm pkg set scripts.start="next start -p 3000"
NODE_ENV=production bun .next/standalone/server.js 2>&1 | tee server.log
next dev -p 3000 2>&1 | tee dev.log

npx prisma studio


npm run dev

npx next dev -p 3000 > dev.log 2>&1

npm run build
npm start

http://localhost:3000




