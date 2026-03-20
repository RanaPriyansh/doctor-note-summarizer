# AI Doctor Note Summarizer

AI-powered doctor note summarizer for iOS.

## Features
- AI generation using Claude API
- Stripe subscription payments ($9/month)
- Freemium model: 1 free generation
- PDF export (coming soon)

## Setup
1. Copy `.env.example` to `.env` and fill in your API keys
2. Run: `pip install -r requirements.txt`
3. Run: `uvicorn main:app --reload`
4. Open http://localhost:8000/docs for API docs

## Deployment
Deploy to Vercel, Railway, or Heroku. Set all environment variables.

## App Store
iOS app template: iOS/DoctorNoteSummarizer/
Configure bundle ID: com.thielon.doctornotesummarizer
Set RevenueCat product: AI Doctor Note Summarizer

## Revenue
- Freemium: 1 free generation
- Pro: $9/month
- Target: 100+ subscribers in first month = $900/mo
