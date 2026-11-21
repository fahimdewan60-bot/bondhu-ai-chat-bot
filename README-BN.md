# Bondhu AI — মোবাইল ওয়েব অ্যাপ

এই সংস্করণে নির্বাচিত দ্বিতীয় Bondhu AI লোগো যুক্ত করা হয়েছে। মোবাইল-ফ্রেন্ডলি হোমস্ক্রিন, বাংলা চ্যাট UI, নতুন চ্যাট, সাজেশন, এবং সমর্থিত ব্রাউজারে বাংলা ভয়েস ইনপুট রয়েছে।

## চালাতে যা লাগবে
- Node.js 18 বা তার পরের সংস্করণ
- OpenAI API key (সার্ভারে গোপনভাবে রাখতে হবে)
- ইন্টারনেট সংযোগ

## চালুর ধাপ
1. ZIP Extract করো।
2. প্রজেক্ট ফোল্ডারে Terminal/Command Prompt খোলো।
3. `npm install` চালাও।
4. `.env.example` কপি করে `.env` নামে রাখো।
5. `.env` ফাইলে নিজের API key বসাও: `OPENAI_API_KEY=...`
6. `npm start` চালাও।
7. ব্রাউজারে `http://localhost:3000` খোলো।

## মোবাইলে যেকোনো জায়গা থেকে ব্যবহার
ওয়েবসাইটটি HTTPS hosting-এ deploy করতে হবে এবং hosting-এর Environment Variables/Secrets-এ `OPENAI_API_KEY` যোগ করতে হবে। API key কখনো HTML/JavaScript-এ বসাবে না। API ব্যবহারে খরচ হতে পারে—আগে usage ও billing limit দেখে নিও।

## বর্তমান সীমাবদ্ধতা
- এই ZIP হলো তৈরি করা ওয়েব অ্যাপের সোর্স প্রজেক্ট; এটি নিজে থেকে ইন্টারনেটে প্রকাশিত নয়।
- AI উত্তর পেতে সার্ভারে API key এবং hosting লাগবে।
- ভয়েস ইনপুট ব্রাউজারের Speech Recognition সমর্থনের ওপর নির্ভর করে।
- ছবি/ফাইল বিশ্লেষণ, ওয়েব সার্চ, অ্যাকাউন্ট, এবং স্থায়ী chat history এখনো যুক্ত করা হয়নি।
- Public launch-এর আগে authentication, rate limiting, privacy policy ও abuse protection যোগ করা দরকার।
