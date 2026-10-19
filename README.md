# 🌾 AgriScan: Early Detection of Crop Diseases and Pest Infestations

AgriScan is a simple mobile/web app prototype that helps farmers spot crop problems early. A farmer takes a photo of an affected leaf, and the app shows the likely disease or pest along with easy-to-follow treatment steps, in plain language.

**Live prototype:** https://vibrant-reveal-app.lovable.app

---

## The Problem

Many farmers notice crop damage only after it has spread, because expert advice is slow to reach them. Late detection means avoidable crop loss.

## Our Solution

AgriScan gives an instant first opinion so farmers can act early:

1. The farmer opens the app and takes a photo of one affected leaf in daylight (or picks one from the gallery).
2. The photo is checked using an existing, ready-made plant-disease recognition service.
3. The app shows the likely disease or pest in plain language, with simple treatment advice.
4. The farmer acts early and reduces crop loss.

## Key Features

- **Scan a leaf:** take a photo or choose one from the gallery.
- **Simple, icon-based interface** for users with low digital literacy.
- **Local language support** for regional languages.
- **Low data mode:** designed for rural networks (about 180 KB per scan, works on 2G).
- **Village outbreak map** to see nearby problems.
- **Scan history** to look back at earlier scans.
- **Farming tips** screen.

The prototype has four tabs: **Scan, Map, History, Tips**.

## Working Flow

```
Farmer opens app → Uploads leaf photo → Photo sent to disease-recognition API
→ Result and simple treatment shown → Farmer takes action early
```

## Technical Approach

| Part | Approach |
|------|----------|
| App interface | Built with an AI-assisted, no-code app builder |
| Disease detection | An existing, ready-to-use plant-disease recognition API (we do not train our own AI model) |
| Data storage | A simple cloud sheet (e.g. Google Sheets) to save scan history |
| Language support | Basic multi-language text display for regional languages |

### Methodology

- Start with common, well-documented crops in our region for the first version.
- Test the app with a small group of farmers and improve it based on feedback.
- Keep every screen simple: photo, wait, result, advice, with nothing extra.

## Project Status

This is an early **prototype** that demonstrates the idea and the user interface. Live disease detection through the recognition API and full data storage are planned next steps.

## Future Scope

- Connect the recognition API for real-time results.
- Add more crops and more regional languages.
- Make the outbreak map use real scan data from nearby villages.
- Test with real farmers and refine the app from their feedback.

## Team

- Sowjanya Balla
- Geethanjali Gorli
- Richita Kalyani
- Jaswitha Nerella
- Pinninti Akshitha Yadav
- Pardhavi Rongali

Team project by B.Tech CSE students, ANITS.
