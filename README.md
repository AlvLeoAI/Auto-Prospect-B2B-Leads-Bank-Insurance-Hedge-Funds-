# 🤖 Auto-Prospect B2B Leads: Bank | Insurance | Hedge Funds – Built with n8n

This workflow automatically scrapes, enriches, personalizes, and contacts B2B leads in the banking, insurance, and hedge fund sectors.

## 🚀 Use Case
Ideal for agencies or AI leadgen tools targeting financial institutions, this flow scrapes data, enriches it with emails, and sends custom messages via GPT-4o.

## 🔧 Tools & APIs Used
- [x] n8n
- [x] Apify (Google Maps)
- [x] AnyMailFinder (Email enrichment)
- [x] Perplexity (Company info scraping)
- [x] OpenAI (GPT-4o messaging)
- [x] Google Sheets (Lead tracking)
- [x] Gmail API (Cold Emailing)

## 🧠 Logic
- Webhook receives target city/country/types
- Splits into 3 flows: Banks, Insurance, Hedge Funds
- Scrapes Google Maps > enriches email > scrapes site info > generates email with GPT
- Sends via Gmail and logs in Google Sheets

## 📂 Download & Explore
- 📥 [JSON Workflow](https://github.com/AlvLeoAI/Auto-Prospect-B2B-Leads-Bank-Insurance-Hedge-Funds-/blob/main/JSON)
- 🖼️ Workflow Diagram (see below)

## 💡 Learnings
- How to modularize flows in n8n for scale
- Async API enrichments & fallbacks
- Crafting personalized AI sales messaging with GPT
