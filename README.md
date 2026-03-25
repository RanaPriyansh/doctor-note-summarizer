# AI Doctor Note Summarizer

[![GitHub](https://img.shields.io/badge/GitHub-000000?logo=github)](https://github.com/RanaPriyansh/doctor-note-summarizer)
[![License](https://img.shields.io/github/license/RanaPriyansh/doctor-note-summarizer)](https://github.com/RanaPriyansh/doctor-note-summarizer/blob/main/LICENSE)
[![Last commit](https://img.shields.io/github/last-commit/RanaPriyansh/doctor-note-summarizer)](https://github.com/RanaPriyansh/doctor-note-summarizer/commits/main)

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
Configure bundle ID: com.appfactory.doctornotesummarizer
Set RevenueCat product: AI Doctor Note Summarizer

## Revenue
- Freemium: 1 free generation
- Pro: $9/month
- Target: 100+ subscribers in first month = $900/mo
