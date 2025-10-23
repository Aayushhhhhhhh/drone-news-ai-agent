# Drone News AI Agent – Daily Digest

**Candidate:** &lt;Aayush Sonawane &gt;  
**Phone:** &lt;+91 9373354125 &gt;  
**Email:** &lt; aayushsonawane01@gmail.com &gt;  
**GitHub:** https://github.com/Aayushhhhhhhh/drone-news-ai-agent  
**Availability:** Mon-Fri 10:00–17:00 IST  
**Preferred interview slots:**  
1. 10:30 – 11:30 AM IST  
2. 4:00 – 5:00 PM IST  

## What it does
- Runs daily at 09:00 IST (cron)  
- Fetches 5 latest drone/UAV/DGCA news from Google News RSS  
- Summarises each article with GPT-3.5-turbo  
- Builds social-ready HTML card (title, image, summary, hashtags, date)  
- E-mails one consolidated digest (Gmail) – **no personal social accounts used**

## Files
- `Drone_News_AI_Agent_&lt;YourName&gt;.json` → ready-to-import n8n workflow  
- `/screenshots` → UI proofs (workflow, e-mail sample, cron, OpenAI)

## How to re-run
1. Import JSON into any n8n instance.  
2. Add your OpenAI + Gmail OAuth2 credentials.  
3. Activate → next digest arrives automatically at 09:00 IST.
