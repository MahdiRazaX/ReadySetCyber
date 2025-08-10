Ready. Set. Cyber. – Phishing Drill Game

An interactive, single-file HTML phishing simulation for ReadySetCyber — designed for Canadians of all skill levels, from first-timers to CISOs.
Built to run entirely in the browser (no server needed), fully self-contained, and mobile-friendly.

Features
	•	5 realistic Canadian phishing emails (Canada Post, CRA, AWS, Bell, RBC) + optional expert bonus (QR-code/script drop).
	•	Timer, scoring, accuracy tracking, and local leaderboard.
	•	Multilingual: English, French, plus starter packs for Urdu, Arabic, Tamil, Mandarin, Persian, Swahili, Punjabi, Filipino.
	•	Accessible (AODA-friendly) red/off-white palette, larger touch targets, reduced motion option.
	•	Mobile-optimized: swipeable email list, stacked layouts, full-width buttons on phones.
	•	100% self-contained — images can be inlined as data URLs for offline or single-file hosting.

How to Run (w3schools)
	1.	Open w3schools HTML Tryit Editor.
	2.	Clear all code in the editor.
	3.	Copy the full contents of the HTML file (ReadySetCyber.html) and paste into w3schools.
	4.	Click Run to test.

Customization
	•	Site Logo:
	•	Find const SITE_LOGO_DATA_URL = ""; in the script.
	•	Paste your logo’s data URL between the quotes.
	•	Brand Logos:
	•	Find const BRAND_ASSETS = { canada_post: null, cra: null, aws: null, bell: null, rbc: null };
	•	Replace null with a data URL for each brand’s logo.
	•	Translations:
	•	All UI strings are stored in the I18N object. Edit or expand as needed.
	•	Questions:
	•	Email scenarios live in the SCENARIOS array. Add/remove/edit objects to change game content.

Disclaimer

This simulation is entirely fictional.
All brand names, companies, and domains are used for educational purposes only.
No real emails are sent or received.
