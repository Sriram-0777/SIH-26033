# Smart India Hackathon Workshop
# Date:
## Reference Number:
## Name:

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Farmers and FPOs sell through several intermediaries (commission agents, traders, wholesalers, retailers). Each layer adds a margin, so farmers get a small share of the final price while consumers pay far more. Farmers also lack price visibility, face unpredictable demand, and have little access to affordable logistics, which leads to distress sales and post-harvest losses.
Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution
A pre-booking digital marketplace connecting farmers/FPOs directly with consumers and bulk buyers.

1. How it works: Buyers pre-book produce before harvest at a fair-price band. Farmers get guaranteed demand, and buyers get locked prices.
2. How it addresses the problem: Removing intermediaries raises farmer income and lowers consumer prices. AI forecasting and pooled logistics cut waste and delivery costs.
3. Innovation and uniqueness:
   ◦ Pre-harvest booking, so farmers know their demand before they harvest
   ◦ Price Passport, which shows where each rupee goes compared with the mandi chain
   ◦ Locality group-buying that fills delivery trucks
   ◦ A fair-price floor (MSP or cost-plus)
   ◦ Voice and WhatsApp interface in regional languages
   ◦ FPO micro-hubs for grading, packing and pickup
## Technical Approach
1. Technologies:
   ◦ Frontend: React Native (mobile), React (web dashboard)
   ◦ Backend: FastAPI (Python), PostgreSQL, Redis
   ◦ AI/ML: Prophet/LSTM for price and demand forecasting, OR-Tools for route optimization
   ◦ Data: Agmarknet/data.gov.in (mandi prices), IMD or Open-Meteo (weather)
   ◦ Integrations: UPI payments, Google Maps API, WhatsApp/SMS alerts, speech-to-text for voice input
2. Methodology: Farmer registers and lists crop → AI forecast suggests price and timing → buyers or locality groups pre-book → orders are pooled by area → route optimizer plans pickups → FPO hub grades and packs → delivery → UPI payment → Price Passport generated. (Add the flow chart and prototype screenshots here
## Feasibility and Viability
1. Feasibility: It uses open mandi and weather data, widespread UPI and smartphone use, and existing FPO networks as the aggregation layer. The MVP can be built with standard open-source tools.
2. Challenges and risks:
   ◦ Low digital literacy among farmers
   ◦ Trust and quality disputes
   ◦ Perishable goods and last-mile cost
   ◦ Cold start (enough buyers and sellers)
   ◦ Price forecast errors
   3. Strategies:
   ◦ Voice-first, regional-language UI, with FPO agents onboarding farmers
   ◦ Quality grading, ratings and escrow-style payments
   ◦ Pilot in one district with 2 crops, then scale
   ◦ Pooled deliveries and hub-based pickups to cut costs
   ◦ Revenue from a small commission (2-3%) and logistics fees, so it stays sustainable without government subsidy
## Impact and Benefits
1. Target audience: Small and marginal farmers, FPOs, urban consumers, restaurants, retailers and institutional bulk buyers.
2. Benefits:
   ◦ Social: Higher farmer incomes, transparent pricing and more trust in the supply chain
   ◦ Economic: Lower consumer prices, less distress selling and a lower cost per delivery through pooling
   ◦ Environmental: Less food waste from demand-based harvesting, fewer empty delivery trips and a lower carbon footprint

## Research and References
* Agmarknet and data.gov.in (mandi price data)
* e-NAM (National Agriculture Market)
* Department of Consumer Affairs price monitoring data
* IMD / Open-Meteo (weather data)
* NITI Aayog and FAO reports on agri supply chain losses
* Prophet (Meta) and Google OR-Tools documentation
