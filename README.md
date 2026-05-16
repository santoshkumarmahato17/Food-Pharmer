# Food-Pharmer
AI-powered mobile app that scans packaged food labels to reveal what’s really inside. It extracts ingredients, decodes complex terms, checks misleading claims, and generates a transparency score. Combines OCR, knowledge graphs, and rule-based scoring to deliver clear, visual insights for smarter food choices in world 🌎.


🍎 FOOD PHARMAR

Know what’s really inside your food.

FOOD PHARMAR is an AI-powered mobile app that scans packaged food and breaks down what’s actually inside — no confusing labels, no marketing fluff. Just clear, simple insights so you can make smarter choices instantly.

🚀 What it does

Ever picked up something labeled “healthy” and wondered if it really is?

That’s exactly what this app helps with.

Just point your camera at a product, and it will:

📸 Scan ingredient labels in real time
🧠 Decode complex ingredients into simple language
⚠️ Flag hidden sugars, additives, and ultra-processed content
📊 Give a Transparency Score (0–100)
🔍 Detect misleading claims like “High Protein” or “No Added Sugar”
🍬 Show visual breakdowns (like teaspoons of sugar)
🔁 Suggest better alternatives
💡 Why this matters

In markets like India, food labels can be confusing — and sometimes misleading.

FOOD PHARMAR bridges the gap between:

🏷️ What brands say
vs
🧪 What’s actually inside

It brings the kind of analysis you see from health influencers… into your pocket.

🧠 How it works (simple version)
Scan → Extract → Understand → Score → Explain

Under the hood:

📷 OCR reads labels from images
🧬 Ingredient normalization maps chemical names to known substances
📊 Rule-based scoring evaluates food quality
🧠 Knowledge graph connects ingredients to health impact
🤖 AI explains everything in plain English
🏗️ Tech Stack

Frontend

Flutter (iOS + Android)
Camera + real-time scanning
AR-ready interface (future)

Backend

FastAPI (Python)
PostgreSQL + pgvector
OCR (ML Kit / PaddleOCR)

AI Layer

Multimodal AI (Gemini) for explanations
Rule-based scoring engine (deterministic)
Custom ingredient knowledge graph
🔁 Core Pipeline
User Scan
   ↓
Image Processing
   ↓
OCR (text extraction)
   ↓
Ingredient Parsing
   ↓
Normalization Engine
   ↓
Knowledge Graph Lookup
   ↓
Scoring Engine
   ↓
AI Explanation
   ↓
User Insights
📊 Example Output
🟠 Transparency Score: 38/100
⚠️ High sugar content
⚠️ Multiple additives detected
❌ “High Protein” claim is misleading
🍬 Equivalent to 6 teaspoons of sugar
🔄 Data Flywheel (gets smarter over time)
Users scan products
System analyzes ingredients
Users correct errors (if any)
Data improves
Future scans become more accurate
🛣️ Roadmap
Phase 1 (MVP)
Basic scanning + OCR
Ingredient decoding
Simple scoring system
Phase 2
Knowledge graph expansion
Claim verification
Healthier alternatives
Phase 3
Shareable insights (viral layer)
Product comparison
Phase 4
AR overlays
Personalized health insights
Wearable integration
⚠️ Important Note

This app is designed for education and transparency, not medical advice.

We don’t tell you what to eat —
we help you understand what you’re eating.

🧭 Vision

Think of FOOD PHARMAR as:

🧠 Google Maps for food truth

OCR = GPS
Knowledge Graph = Map
Scoring Engine = Route logic
AI = Voice assistant
🤝 Contributing

Got ideas? Found a bug? Want to improve the dataset?

Pull requests and suggestions are welcome.
