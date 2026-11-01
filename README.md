# CadenceIQ AI

> **Real-Time Executive Rhetorical Acoustics & Speech Performance Intelligence**

CadenceIQ AI is a high-precision speech analytics and rhetorical coaching platform designed for executives, founders, and competitive speakers. It captures real-time audio telemetry to evaluate vocal pacing (WPM), pitch stability, tonal modulation, and hesitation cadence.

---

## ðŸš€ Tech Stack & Core Technologies

Python 3.10+ Flask Groq LLM (LLaMA-3.1-8B) Web Audio API Chart.js Vercel

- **Python 3.10+ & Flask:** Microservice architecture powering acoustic analysis and LLM rhetorical feedback.
- **Groq LLM Engine:** Real-time conversational reasoning generating actionable speaking drills and rhetoric scores.
- **Web Audio API:** In-browser acoustic telemetry capturing raw decibel dynamics, pause durations, and frequency spectrums.
- **Interactive Visualization:** Dynamic Chart.js telemetry visualizing vocal stability, pitch curves, and filler-word density.
- **Serverless Cloud Ready:** Instant serverless deployment compatibility for Vercel.

---

## âœ¨ Key Features

- **Real-Time Cadence Tracking:** Analyzes spoken word velocity (words-per-minute) with optimal executive pacing bands.
- **Filler Word Detection:** Tracks verbal crutches ("um", "like", "actually", "basically") with live reduction prompts.
- **Acoustic Pitch & Tone Evaluation:** Identifies monotone patterns and advises on vocal dynamics and emphasis.
- **Speech Simulation Modes:** Mock interview panels, keynote stage rehearsal, and investor pitch telemetry.
- **Executive Speech Reports:** Exportable speech performance scorecards with targeted developmental drills.

---

## ðŸ› ï¸ Getting Started

### 1. Clone & Set Up Virtual Environment

`ash
git clone https://github.com/Rhythm2903/CadenceIQ-AI.git
cd CadenceIQ-AI

# Create and activate Python virtual environment
python -m venv .venv

# Windows
.venv\Scripts\activate

# macOS / Linux
source .venv/bin/activate
`

### 2. Install Dependencies

`ash
pip install -r requirements.txt
`

### 3. Configure Environment Variables

`ash
cp .env.example .env
`

Populate .env with your GROQ_API_KEY.

### 4. Run the Application

`ash
python -m flask run
`

---

## ðŸ” Environment Variables

Refer to [.env.example](.env.example) for required configuration keys.

---

## ðŸ“„ License

This project is open-source and available under the [MIT License](LICENSE).

---

## ðŸ‘¤ Author

Developed & Maintained by **Rhythm Agarwal** ([@Rhythm2903](https://github.com/Rhythm2903))