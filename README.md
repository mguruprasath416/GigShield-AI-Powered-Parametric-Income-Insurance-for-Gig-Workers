# GigShield — AI-Powered Parametric Income Insurance for Gig Workers

## What We're Building

A parametric insurance platform that protects **Zomato/Swiggy food delivery riders** from income loss caused by external disruptions like heavy rain, extreme heat, and city curfews.

When it rains heavily, the rider gets paid automatically — no claim form, no waiting.

---

## The Problem

Food delivery riders lose **20–30% of monthly income** during weather disruptions. They have no safety net. GigShield fixes that with a simple weekly plan.

---

## Our Persona

**Food delivery partners — Zomato & Swiggy riders**
- Earn ₹700–1200/day, paid weekly
- Work outdoors across urban zones
- No existing income protection

---

## How It Works

1. Rider pays ₹60/week to activate coverage
2. Our system monitors weather & disruption APIs every 5 minutes
3. When a trigger fires (e.g. heavy rain > 15mm/hr), a claim is auto-filed
4. Fraud checks run automatically
5. ₹800 is sent to the rider's account within 10 minutes — zero manual steps

---

## Parametric Triggers

| Event | Threshold | Source |
|---|---|---|
| Heavy rainfall | > 15 mm/hr | OpenWeatherMap API |
| Extreme heat | > 42°C | OpenWeatherMap API |
| Hazardous AQI | > 300 | OpenAQ API |
| City curfew / bandh | Zone flagged | Mock / News API |
| Platform outage | API errors > 80% | Simulated mock |

---

## Weekly Premium Model

- **Base price:** ₹49 – ₹79 / week
- AI adjusts price based on rider's zone risk, historical disruptions, and active hours
- **Coverage:** up to 2 lost workdays/week × average daily earnings (~₹800)

---

## AI/ML Plan

- **Dynamic premium calculation** — ML model (scikit-learn) personalises weekly price per zone
- **Risk profiling** — risk score assigned at onboarding based on zone data
- **Fraud detection** — GPS zone check, duplicate prevention, crowd validation
- **Predictive dashboard** — next-week disruption forecast for the insurer

---

## Tech Stack

| Layer | Tech |
|---|---|
| Frontend | React.js |
| Backend | Python / FastAPI |
| Database | PostgreSQL |
| ML | scikit-learn, pandas |
| Weather | OpenWeatherMap (free tier) |
| Payments | Razorpay (test mode) |
| Hosting | Render / Railway |

---

## Platform

**Web app** (mobile-responsive) — no install needed, works on any smartphone browser.

---

## Team

*(Add team member names)*

---

> Built for Guidewire DEVTrails 2026
