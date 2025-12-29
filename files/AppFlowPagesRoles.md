\# App Flow \+ Pages \+ Roles

\#\# User Roles  
MVP: Single role — Agent    
(No admin or multi-role yet)

\---

\#\# Pages Overview

\#\#\# Public Website  
1\. \*\*Home\*\*  
   \- Hero: “Never lose another real estate lead again.”  
   \- Sub: “AI answers missed calls instantly and qualifies leads for you.”  
   \- 3 Pillars visual blocks:  
       • Missed Call SMS Auto-Reply  
       • AI Voice Answering (Coming Soon)  
       • Website Chatbot (Phase 2\)  
   \- CTA: Start Free Trial / Book Demo

2\. \*\*Pricing\*\*  
   \- Simple tiers (MVP single plan recommended)  
   \- Feature checklist

3\. \*\*Contact/Demo\*\*  
   \- Contact form  
   \- Phone/email

\#\#\# App Dashboard (after login)  
1\. \*\*Login\*\*  
   \- Email/password via Supabase

2\. \*\*Leads Page\*\*  
   \- Table list of all leads  
   \- Columns: Name | Phone | Message Summary | Date  
   \- Click row → details page (optional Phase 2\)

3\. \*\*Account\*\*  
   \- View assigned number  
   \- Business name  
   \- Notification preferences

\#\#\# Internal/Hidden (Admin for onboarding only)  
\- \*\*Manual Setup Form\*\*  
  \- Assign Twilio number to agent  
  \- Set greeting template  
  \- Save to Supabase

\---

\#\# Lead Flow  
1\. Customer calls agent → missed call  
2\. Twilio triggers Webhook  
3\. AI sends SMS introduction  
4\. AI asks qualifiers:  
   \- Name?  
   \- What property/buy/sell?  
   \- Budget?  
   \- Timeline?  
5\. Lead stored in DB  
6\. Summary sent to agent SMS/email  
7\. Visible in lead dashboard

Success \= lead captured \+ agent notified

