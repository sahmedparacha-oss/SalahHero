🌙 SalahHero — Islamic Daily Habit Tracker

Pray. Learn. Grow. Be the Hero.

A free, beautiful, and fully offline-capable Islamic daily routine tracker for Muslim children and families worldwide. No app to install — just open the link, set up in 30 seconds, and start building Islamic habits.

✨ Live Demo
🔗 salahhero.netlify.app
Open on your phone → tap Add to Home Screen → it installs like a real app.

📱 Screenshots
OnboardingDaily TrackerPrayer TimesReports3-step family setup23 Islamic tasksGPS prayer timesDaily email reports

🌟 Features
👦 For Children

✅ 23 built-in daily tasks — all 5 prayers, Quran recitation, hygiene, study, health, sleep
✅ Emoji icons on every task — visual and engaging for kids
✅ Category filter — Prayer, Quran, Hygiene, Study, Health, Rest, Custom
✅ Progress ring — shows % completion throughout the day
✅ Appreciation banner — unlocks at 60%, 80%, and 100% with stars ⭐
✅ Custom tasks — add any personal habit to Morning, Daytime, or Evening
✅ Works offline — all data saves locally on the device

👨 For Parents

✅ Personal appreciation message — your own heartfelt words shown at 100% completion
✅ Real email reports via EmailJS — daily, weekly, or manual
✅ Auto midnight report — automatically sends when the day changes
✅ Report includes — tasks done, prayers completed, Quran log, missed tasks, appreciation message
✅ Edit any task — change name, time, category, emoji
✅ Parent name personalisation — messages addressed from you by name
✅ Reset all data — clean start for any new family

🕌 Prayer Times

✅ GPS-based prayer times — accurate for any city worldwide
✅ Manual city search — type any city name
✅ All 6 times — Fajr, Sunrise, Dhuhr, Asr, Maghrib, Isha in Arabic + English
✅ Powered by AlAdhan API — free, no key needed

⚙️ Settings & Customisation

✅ Full profile editing — child name, age, city, parent name, appreciation message
✅ 3-step onboarding — clean fresh setup for every new family
✅ Version-based auto-reset — change APP_VERSION to redistribute a clean file
✅ No hardcoded data — completely universal, works for any Muslim family worldwide


🚀 How to Use
Option 1 — Just open the link
Visit salahhero.netlify.app on any phone or browser.
Option 2 — Install as an app

Open the link in your phone browser
Android (Chrome): tap ⋮ menu → "Add to Home Screen"
iPhone (Safari): tap Share 📤 → "Add to Home Screen"
SalahHero appears on your home screen like a real app ✅

Option 3 — Run locally
bash# No build process needed — just open the HTML file
git clone https://github.com/yourusername/salahhero.git
cd salahhero
open index.html

📧 Email Reports Setup (EmailJS)
SalahHero uses EmailJS to send real email reports directly from the browser — no server needed.
To enable real email delivery:

Create a free account at emailjs.com (200 emails/month free)
Add Gmail as an Email Service → copy your Service ID
Create an Email Template with these variables:

{{to_email}} — parent's email address
{{parent_name}} — father/guardian name
{{child_name}} — child's name
{{report_text}} — full report content


Copy your Template ID and Public Key
Open index.html and update these 3 lines:

javascriptconst EJS_SERVICE  = 'your_service_id';
const EJS_TEMPLATE = 'your_template_id';
const EJS_KEY      = 'your_public_key';

🛠️ Tech Stack
TechnologyPurposePure HTML/CSS/JSNo framework, no build tools, no dependenciesGoogle FontsAmiri (Arabic/Islamic) + DM Sans (UI)localStorageAll data stored on device — fully privateAlAdhan APIFree GPS-based prayer timesNominatim APIReverse geocoding (GPS → city name)EmailJSEmail report delivery from browserNetlifyHosting and deployment

📂 Project Structure
salahhero/
│
└── index.html          # The entire app — single file
Yes, the entire app is one HTML file. No npm, no webpack, no frameworks. Just open and run.

🔧 Customisation
Change app version (force clean reset for all users)
javascriptconst APP_VERSION = '3.1';  // Change this number
Any user who opens the updated file gets a fresh onboarding screen automatically.
Add default tasks
Find the DEFAULT_TASKS array and add:
javascript{
  id:'your_task_id',
  name:'Your Task Name',
  time:'Time or when',
  emoji:'🎯',
  cat:'custom',   // prayer|quran|hygiene|study|health|rest|custom
  section:'morning'  // morning|daytime|evening
}
Change brand colours
css:root {
  --g1: #064e35;  /* Hero Green — primary */
  --g2: #0a6644;  /* Mid Green */
  --g3: #0f7a50;  /* Light Green */
  --gold: #fbbf24; /* Champion Gold */
}

🌍 Who is this for?
SalahHero is built for Muslim families worldwide who want to raise children with strong Islamic habits. It works for:

👦 Boys and girls aged 5–18
🇵🇰 Pakistan, 🇦🇪 UAE, 🇸🇦 Saudi Arabia, 🇬🇧 UK, 🇺🇸 USA, 🇲🇾 Malaysia — anywhere in the world
📱 Any phone — Android, iPhone, no app store needed
🌐 Any browser — Chrome, Safari, Firefox, Edge


🤝 Contributing
Contributions are welcome! If you have ideas for new features, Islamic content improvements, or language translations (Urdu, Arabic), please open an issue or submit a pull request.
Ideas welcome:

 Urdu / Arabic UI translation
 Streak tracking (7-day, 30-day badges)
 PWA manifest for automatic install prompt
 Ramadan special mode
 Multiple children profiles


📖 Islamic Principle

"The most beloved deeds to Allah are those done consistently, even if they are small."
— Prophet Muhammad ﷺ (Sahih Bukhari)

SalahHero is built on this principle — small daily habits, done consistently, that shape righteous young Muslims.

📄 License
MIT License — free to use, modify, and share. If you build something with this, please credit SalahHero and make dua for the team. 🤲

☎️ Contact
Built with ❤️ for Muslim families worldwide.
Pray. Learn. Grow. Be the Hero. 🌙

SalahHero — Islamic Habits for Champions
