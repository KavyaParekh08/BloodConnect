🩸 BloodConnect

BloodConnect is a web application designed to connect blood donors, recipients, and hospitals in a simple, fast, and reliable way. The platform allows users to register as donors, request blood, and hospitals to manage availability — ensuring that critical blood requirements are met without delays.

🚀 Features

👤 User Authentication – Secure login/signup for donors and hospitals.

🩸 Blood Donation Requests – Request and fulfill blood requirements.

🏥 Hospital Dashboard – Hospitals can manage donors, requests, and availability.

📍 Nearby Donors & Hospitals – Locate donors and hospitals based on proximity.

🔔 Notifications & Alerts – Get notified for urgent blood requests.

📊 Data Tracking – Maintain records of past donations and requests.

🛠️ Tech Stack

Frontend: HTML, CSS, JavaScript

Backend: Supabase (Auth, Database, API),Python

Database: Supabase PostgreSQL

Hosting: GitHub Pages / Vercel / Netlify (your choice)
📥 Installation & Setup

Follow these steps to run BloodConnect locally:

1️⃣ Clone the Repository
git clone https://github.com/your-username/BloodConnect.git
cd BloodConnect

2️⃣ Setup Supabase

Create a free project on Supabase
.

Go to Project Settings → API and copy your:

Project URL

Anon (Public) API Key

Create a new file inside your project:

/assets/js/config.js


Add your credentials in it:

const SUPABASE_URL = "your-supabase-url";
const SUPABASE_KEY = "your-anon-key";
const supabase = supabase.createClient(SUPABASE_URL, SUPABASE_KEY);


⚠️ Important: Never expose these keys in a public repo. Add config.js to .gitignore before pushing.

3️⃣ Run Locally

Open index.html in your browser.

Or use a local server (recommended):

npx live-server


Then open http://localhost:8080
.

4️⃣ Deploy (Optional)

You can host the project on:

GitHub Pages

Netlify (netlify deploy)

Vercel (vercel deploy)

