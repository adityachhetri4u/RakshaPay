# RakshaPay  
AI-Powered Parametric Income Protection for Food Delivery Partners  

Guidewire DEVTrails 2026 | University Hackathon  

---

## Overview  
RakshaPay is an AI-driven parametric insurance platform designed to protect the income of food delivery gig workers such as Zomato and Swiggy partners.  

These workers rely entirely on daily orders, and any disruption like bad weather, platform outages, or civic restrictions directly impacts their earnings. RakshaPay solves this by providing automatic payouts based on real-world triggers, without requiring manual claims. :contentReference[oaicite:0]{index=0}  

---

## Problem Statement  

Food delivery workers operate without a financial safety net. Their income is completely dependent on successful deliveries.  

External factors such as:  
- Heavy rain, cyclones, and flooding  
- Extreme heat conditions  
- Pollution alerts  
- Curfews or area restrictions  
- Platform-side delivery suspensions  

can instantly reduce their income to zero. Currently, the entire financial loss is borne by the worker. :contentReference[oaicite:1]{index=1}  

---

## Solution  

RakshaPay introduces a parametric income insurance model where payouts are triggered automatically when predefined external conditions are met.  

Key features:  
- No claim filing required  
- Instant UPI payouts  
- AI-based dynamic premium calculation  
- Multi-layer fraud detection system  

---

## How It Works  

### Onboarding  
- Mobile number verification via OTP  
- Link delivery partner ID  
- Aadhaar eKYC via DigiLocker  
- UPI registration  
- Weekly plan selection  

The policy becomes active instantly after onboarding. :contentReference[oaicite:2]{index=2}  

---

### Workflow  

1. Worker subscribes to a weekly plan  
2. System continuously monitors external triggers  
3. Trigger is detected and validated  
4. AI verifies worker activity and location  
5. Payout is credited automatically  

---

## Parametric Triggers  

### Environmental Triggers  
- Heavy Rain / Flood  
- Extreme Heat  
- Severe Air Pollution (AQI > 400)  
- Cyclone / Storm  
- Fog / Thunderstorm alerts  

### Platform Triggers  
- App outage  
- Delivery zone suspension  
- Mass merchant closure  

### Traffic Triggers  
- Road blockage  
- Severe congestion  
- Waterlogging  

### Civic Triggers  
- Curfew or bandh  
- Processions or rallies  
- Area-wide power outage  

All triggers are verified using external data sources and require no manual claim process. :contentReference[oaicite:3]{index=3}  

---

## Pricing Model  

RakshaPay uses a weekly premium system aligned with gig workers’ earning cycles.  

### Formula  
Weekly Premium = Base Price × Risk Score × Earnings Factor  

- Base Price: ₹40  
- Risk Score: Based on location, forecast, and historical disruptions  
- Earnings Factor: Based on worker’s daily income  

Premiums are recalculated every week using AI models. :contentReference[oaicite:4]{index=4}  

---

## Coverage Plans  

| Plan     | Multiplier | Max Weekly Payout | Best For              |
|----------|-----------|------------------|----------------------|
| Flex     | 0.8×      | ₹800             | Part-time workers    |
| Standard | 1.0×      | ₹1500            | Full-time workers    |
| Pro      | 1.2×      | ₹2500            | High earners         |

---

## Payout Model  

Payout = Average Daily Income × Disruption Percentage × Coverage Multiplier  

Example:  
If a worker earns ₹800/day and faces a 50% disruption:  
Payout = ₹800 × 0.5 × 1.0 = ₹400  

---

## AI and Machine Learning  

### Risk Scoring Engine  
- Model: XGBoost / LightGBM  
- Inputs:  
  - Location risk  
  - Weather forecasts  
  - Seasonal trends  
  - Worker activity patterns  

---

### Fraud Detection  

Multi-layer verification using:  
- GPS data  
- Cell tower triangulation  
- IP geolocation  
- Motion sensor data  
- Platform activity logs  

Fraud scoring determines whether a claim is:  
- Auto-approved  
- Delayed for verification  
- Manually reviewed  

---

### Advanced Fraud Protection  

- Claim burst detection  
- Device fingerprint tracking  
- Syndicate detection using clustering (DBSCAN)  
- Historical behavior analysis  

---

## Platform Choice  

RakshaPay is built as a mobile-first Progressive Web App (PWA):  

- Works on low-end devices  
- Supports offline usage  
- Lightweight installation  
- Push notifications enabled  

---

## Tech Stack  

### Frontend  
- React (Vite)  
- Tailwind CSS  
- PWA with Workbox  

### Backend  
- Node.js + Express  
- PostgreSQL  
- Redis  
- Bull Queue  

### AI/ML  
- Python FastAPI  
- XGBoost / scikit-learn  
- Pandas  

### APIs  
- OpenWeatherMap  
- IMD  
- CPCB / OpenAQ  
- Google Maps  
- Razorpay  
- DigiLocker  

### Deployment  
- Docker  
- Render / Railway  
- GitHub Actions  

---

## Analytics Dashboard  

### Worker View  
- Weekly protected income  
- Active coverage status  
- Claim history  
- Risk forecast  

### Admin View  
- Live trigger monitoring  
- Claims tracking  
- Fraud detection insights  
- Loss ratio analytics  
- Risk heatmaps  

---

## Out of Scope  

RakshaPay only covers income loss. The following are excluded:  

- Health insurance  
- Accident coverage  
- Vehicle repair  
- Theft  
- Fuel expenses  

---

## Impact  

- Provides financial stability to gig workers  
- Reduces income uncertainty  
- Encourages safer working conditions  
- Enables scalable insurance for gig economy  

---

## Development Plan  

### Phase 1  
- Problem research  
- System design  
- Tech stack setup  

### Phase 2  
- Onboarding system  
- Policy creation  
- Trigger automation  
- Basic fraud detection  

### Phase 3  
- Advanced fraud detection  
- Instant payouts  
- Dashboards  
- Optimization  

---

## Vision  

To build a scalable, AI-powered financial safety net for gig workers, ensuring income protection during real-world disruptions.
